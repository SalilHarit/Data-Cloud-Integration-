# THIS FILE TELLS ABOUT KNOWN ERRORS OF THE CLOUD SYSTEM IMPLEMENTATION 

1. do not use testing tools like postman and insomnia which transform the request payload in url encoded form format as the apply preflight modifications which result in errors since the request payload is quite unique its growing gradually difficult to test it 
