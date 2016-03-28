# pyinstagram
Pyinstagram is small python program that allows you to upload photo to Instagram.

#Module
```
import pyinstagram
with pyinstagram.client('username', 'password') as client:
    client.upload('xyz.jpg', '#tag')
```
    
***Disclaimer: Pyinstagram uses private API of Instagram, there is no guaranty that this library will work in the future. Instagram may not like that you use private API.***
    
    
