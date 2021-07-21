# sejutahati
Jalankan docker file : docker-compose up -d

Register
======================
URL : POST http://54.252.184.154:5000/register
BODY : 
{
    "username":"paijo",
    "password":"paijo123"
}

Login : 
======================
URL : POST http://54.252.184.154:5000/login
BODY : 
{
    "username":"paijo",
    "password":"paijo123"
}

Get User :
=====================
URL : GET http://54.252.184.154:5000/getuser
HEADER : 
	KEY : Authorization
	Value : Bearer token
BODY :
{
    "username":"paijo",
    "password":"paijo123"
}

Update : 
=====================
URL : PATCH http://54.252.184.154:5000/update-user/id
HEADER : 
	KEY : Authorization
	Value : Bearer token
BODY :
{
    "username":"paijo123",
    "password":"paijo123"
}


Delete:
==================== 
URL : DELETE http://54.252.184.154:5000/delete-user/id
HEADER : 
	KEY : Authorization
	Value : Bearer token
BODY : 
{
    "username":"paijo123",
    "password":"paijo123"
}
