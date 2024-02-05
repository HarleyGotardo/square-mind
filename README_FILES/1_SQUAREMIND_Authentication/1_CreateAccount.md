- [Authentication](../MAIN_MD/2_SQUAREMIND_Authentication.md) > Create Account

<img src="https://github.com/HarleyGotardo/square-mind/assets/106173250/7225f6ca-0a77-4a0e-86c1-a874f541b187" alt="Create Account" width="300"/>

# Create Account
> This is used to register the user to an online database.



## Input:
  ● The user shall fill in the credential input.

## Process:
  ● The user shall enter his or her phone number or email address.
  ● The user shall tap the “Register” button.

## Output:
  ● The registration is filled and is submitted for verification.

______
>
# Data Dictionary
| Element ID | Element Text| Element Type | Data Type | Required? | Rules |
|------------|------------|------------|------------|------------|------------|
| RegistrationHeader | Register an Account for Mobile Inventory Management System Online Database | Header | Text |..|..|
| RegisteredCredential | ContactInfornation | Text | Text | Yes | Must be a legitimate mobile number or email address|
| VerificationCode | Verification Code | Text | Text | Yes | Must be 6 digits |
| UserPassword | Password | Password | Text | Yes | Hidden |
| InvalidCredentials | Invalid username and password. | Text |..|..| Hidden |
| RegistrationButton | Register | Button |..| Yes |..|
| LoginButton | Log in | Button |..| Yes |..|
