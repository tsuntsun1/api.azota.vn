#api.azota.vn/api/Auth/
- The auth system itself using JWT instead of Bearer for authentication. 
- Password is stored as Base64? i'm not sure

#api.azota.vn/api/Auth/SaveLastActivity
- Unknown..maybe for checking user's last activity like changing profile picture,etc....

#api.azota.vn/api/Auth/Login
- Login data (sent from client) : phone (string), password (string) [Example: phone: 0123456789, password: 123456789] *all plaintext lol*

#api.azota.vn/api/Auth/GetSchoolInfo
- Getting school information

#api.azota.vn/api/Auth/Info
- Same as auth/Login but this time the avatar get filled with user's avatar/
