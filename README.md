# Test Payments Card for Africa

A list of available test payment cards for various payment gateways. Please feel free to contribute cards for any payment gateways not currently listed here by making a pull request.

## Quick Link

- [Ravepay](#ravepay-flutterwave)
- [Paystack]()
- [Payu]()
- [Amplifypay]()
- [Voguepay]()

## Ravepay Flutterwave

Card type                         | Card Number                   | CVV       | Expiry      | PIN
:---------------------------------|:------------------------------|:----------|:------------|:---------
MasterCard PIN Authentication     | 5531 8866 5214 2950           | 564       | 09/32       | 3310
MasterCard PIN 2                  | 5438 8980 1456 0229           | 470       | 10/31       | 3310
Master 3D-Secure (VBSECURECODE)   | 5399 8383 8383 8381           | 564       | 10/31       | 3310
Visa 3D-Secure (VBSECURECODE)     | 4187 4274 1556 4246           | 828       | 09/32       | 3310
Visa 3D-Secure Authentication     | 4242 4242 4242 4242           | 812       | 01/31       | 3310
Address Verification(AVS) Card    | 4556052704172643              | 899       | 09/32       | 3310
Verve Card                        | 5061 4604 1012 0223 210       | 780       | 12/31       | 3310

#### Special test card case

Case type                              |  Card Number           | CVV       | Expiry
:--------------------------------------|:-----------------------|:----------|:------------
card Declined (Address Verification)   |  5143 0105 2233 9965   | 276       | 08/32 
Card Fraudulent                        |  5590 1317 4329 4314   | 887       | 11/32
Card Insufficient Funds                |  5258 5859 2266 6506   | 883       | 09/31
Pre-authorization Test Card            |  5377 2836 4507 7450   | 789       | 09/31
Do Not Honour                          |  5143010522339965      | 276       | 08/31
Invalid Transaction                    |  5551658157653822      | 276       | 08/31
Restricted Card, Retain Card           |  5551651630381384      | 276       | 08/31
Incorrect PIN                          |  5399834697894723      | 883       | 09/31
Verve - Card enrolment                 |  5531882884804517      | 564       | 10/32
Card Transaction Error                 |  5258589130149016      | 887       | 11/30

### Test Banks

Bank                            | Account number    
:------------------------------ |:---------------------



## Paystack
You can use the following test details to test different payment channels.

**OTP** : 12345

### Successful Test Cards

Case type                         | Card Number                   | CVV       | Expiry      | PIN
:---------------------------------|:------------------------------|:----------|:------------|:---------
No Validation                     | 4084084084084081              | 408       | 10/21       | null
PIN validation(reusable)          | 507850785078507812            | 081       | 10/21       | 1111
PIN + OTP validation(nonreusable) | 5060666666666666666           | 123       | 10/21       | 1234
PIN + Phone + OTP validation      | 507850785078507804            | 884       | 10/21       | 0000
Bank authorization Simulation     | 4084080000000409              | 000       | 10/31       | null

### Fail Test Cards

Case type           | Card Number                   | CVV       | Expiry      | PIN
:-------------------|:------------------------------|:----------|:------------|:---------
Declined            | 4084080000005408              | 001       | 10/21       | null
Token Not Generated | 507850785078507853            | 082       | 10/21       | 0000
500 error           | 5060660000000064              | 606       | 10/21       | null
Timeout error       | 506066506066506067            | 060       | 10/21       | null

### Test Banks Accounts

Bank                      | Account Number        | Birthday       | Code     
:-------------------------|:----------------------|:---------------|:---------
Zenith Bank(transaction)  | 0000000000            | 1999-10-14     | null 
First Bank of Nigeria(transfer) | 0000000000      | null           | 011

### Test Mobile Money

Network        | Number                
:--------------|:------------------
MTN            | 0551234987        
