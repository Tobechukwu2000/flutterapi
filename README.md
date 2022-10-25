This Library Enables Easy Integration of Standard Flutterwave API into a python project New or Existing. It contains functions to initiate and Verify Transaction(s).

INSTALLATION:

To install the package via pip use:
* pip install flwave

FUNCTIONS IN LIBRARY:

1. create_tranaction
2. verify_transaction
3. make_refund
4. transaction_details

HOW TO USE:
1. To Initiate a transaction: * from flwave import flwaveapi
 
2. To Verfify A Transaction  Using Transaction Reference: * from flwaveapi import verify_transaction

3. To Verify a Transaction using Transaction ID: * from flwaveapi import verfify_transaction

4. To Create Refund for a transaction: from flwaveapi import make_refund

5. To get transaction details (Single or Multiple): from flwaveapi import transaction_details 


for more info visit Flutterwave official API Docs: https://developer.flutterwave.com 

The repository for this code is hosted on https://github.com/josh2297/ feel free to reach out to the creator for pull request and other possible questions regarding the use of this library.

Note: This is an open source project and is licensed using the MIT-style licensing standard.

The Output of each Function above is a python dictionary.This dictionary should be parsed to retrieve needed information.

