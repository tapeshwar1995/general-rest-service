Testing echo:

Method: Post 

URL   : https://general-rest-service.herokuapp.com/echo

Payload:
 
{
    "message": "Test Message"
}
Testing echoSecure:

Method: Post 

URL   : https://general-rest-service.herokuapp.com/echoSecure

Authentication : Basic Auth, username : testU, password: testP

Payload:
 
{
    "message": "Test Message"
}
Testing pureEcho:

Method: Put/Get/Post/Delete 

URL   : https://general-rest-service.herokuapp.com/pureEcho?myparam=123

Payload:
{
    "message": "Test Message"
}
