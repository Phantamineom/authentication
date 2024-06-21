# authentication
# Endpoint
https://testing-harvestscan1.et.r.appspot.com/api

## Register

• URL
https://testing-harvestscan1.et.r.appspot.com/api/register

• Method
POST

• Request Body
email as string
password as string

• Response
{
"message": "Verification email sent! User created successfully!"
}


## Login
• URL
https://testing-harvestscan1.et.r.appspot.com/api/login

• Method
POST

• Request Body
email as string
password as string

• Response
{
 "message": "User logged in successfully",
 "userCredential": {…..}
}

## Logout
• URL
https://testing-harvestscan1.et.r.appspot.com/api/logout

• Method
POST

• Request Body
email as string

password as string

• Response
{
 "message": "User logged out successfully"
 }

## Reset Password
• URL
https://testing-harvestscan1.et.r.appspot.com/api/reset-password

• Method
POST

• Request Body
email as string
password as string

• Response
{
"message": "Password reset email sent successfully!"
}
