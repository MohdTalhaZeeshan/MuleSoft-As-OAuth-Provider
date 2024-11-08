In postman  use Post method and  pass client_id , client_secret and client_name in headers then a client will be created and stored in object store.
use /token path to generate access token using Post method and pass client_id , client_secret and grant_type as "CLIENT_CREDENTILAS"-------> we get a token.
Validate the token by passing a method GET and ADD Authorization in headers as Bearer "token"-----> we will get client id.
