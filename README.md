#Dokternet x Botika
Collaboration between Dokternet and Botika

##API Documentation
###https://documenter.getpostman.com/view/2648013/SVfTN6wa

##API List
- Menampilkan semua medical center
  - [**API Documentation**](https://documenter.getpostman.com/view/2648013/SVfTN6wa?version=latest#be632b2b-2f57-44da-b27d-7e32d3cac2a2)
  - [_API Response_](https://api.myjson.com/bins/eapyz)
- Menampilkan klinik yang tersedia pada medical center
  - [**API Documentation**](https://documenter.getpostman.com/view/2648013/SVfTN6wa?version=latest#e950ada0-1104-47c4-af1d-6cd866bb0df1)
  - [_API Response_](https://api.myjson.com/bins/xy0xn)
- Menampilkan dokter yang tersedia pada medical center
  - [**API Documentation**](https://documenter.getpostman.com/view/2648013/SVfTN6wa?version=latest#bb412466-5caf-4bea-9dd0-ba0111606120)
  - [_API Response_](https://api.myjson.com/bins/14hsl7)
- Menampilkan asuransi yang tersedia pada medical center
  - [**API Documentation**](https://documenter.getpostman.com/view/2648013/SVfTN6wa?version=latest#29fdb744-eea9-4771-ac8b-5cbc95d18146)
  - [_API Response_](https://api.myjson.com/bins/zsgwr)
- Menampilkan dokter yang tersedia pada klinik
  - [**API Documentation**](https://documenter.getpostman.com/view/2648013/SVfTN6wa?version=latest#8025bd8d-5d7c-436f-857f-ef0b4cba2cb0)
  - [_API Response_](https://api.myjson.com/bins/oh8ez)
  
##Miscellaneous
###Common Error
- Application ID not found
```javascript
{
    "status": "error",
    "code": 401,
    "message": "Application id is not found"
}
```
- Master Key not found (Combination between App ID and Master Key mismatch)
```javascript
{
    "status": "error",
    "code": 401,
    "message": "Master key is not found"
}
```