## SDK Quality
SDK includes 2 modules **Message** and **Balance** 
Balance and message modules has current and total balance, Arabic and English setting functions and all setting parameters are stored in iOS' native persistance. (Well written)
```
SendStatus
forgotPasswordType
changePasswordMobileNumber
balanceForUserWithAuthMobile
sendSMSforSenderName
sendSMSWKForSenderName
deleteMessageWithCredientialsMobileNumber
addSenderName
activeSenderName
checkSenderName
addAlphaSenderName
checkAlphaSenderMobileNumber
```
Every function has REST API call and is using the URLSession library(iOS Native SDK) for JSON POST, GET Request/Response management
The **Good** things I found in the SDK is that 
* URLSession library to call REST API
* Error Handling in every api calls response
* Comments in every codelines
## Comparison between Old and New SDK
## Working Result of New SDK
