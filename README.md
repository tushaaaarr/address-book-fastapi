# find-my-food

Live demo --  https://myaddress-book.herokuapp.com/

Swagger doc --  https://myaddress-book.herokuapp.com/docs


After Cloning project Follow below steps


run the following commands (on project base directory) 
```
pip install -r requirements.txt
```


Run the following command to start Fastapi Project locally
```
uvicorn main:app --reload
```



```
User Section--
1) See all registered users (/view-all_users)

2) Add new user(/add-user/)

parameters = 
{
"email":"tusharspatil808@gmai.com",
"password":1234
 }


Address Section--

1)View all addresses (/user/{user_id}/view-addresses/).

2)View one address used (/user/view-address/{address_id})
 
3)Create new address (/user/{user_id}/create-addresse/) 

parameters = 
              {
              "address":"city name, pincode",
              "coordinates":"Latitude : 16.4020402, Longitude: 74.3842372",
               }

4)Update address ("/user/update-address/{address_id})
parameters = 
              {
              "address":"city name, pincode",
              "coordinates":"Latitude : 16.4020402, Longitude: 74.3842372",
               }

5)Delete address (/user/delete-addresse/{address_id})
```
