
![Logo](https://i.postimg.cc/9Q0y8PtC/White-and-Black-Minimalist-Elegant-Boutique-Logo-cropped.png)


# FLWAVE LIBRARY

This Library Enables Easy Integration of Standard Flutterwave API into a python project New or Existing. It contains functions to initiate and Verify Transaction(s).

## Installation

To install the package via pip use:

```bash
  pip install flwave
```
    
## Usage/Examples
1. To Initiate a transaction:

```javascript
from flwave import flwaveapi
```

2. To Verfify A Transaction Using Transaction Reference:

```javascript
from flwaveapi import verify_transaction
```

3. To Verify a Transaction using Transaction ID:

```javascript
from flwaveapi import verfify_transaction
```

4. To Create Refund for a transaction:

```javascript
from flwaveapi import make_refund
```

5. To get transaction details (Single or Multiple):

```javascript
from flwaveapi import transaction_details
```





## LIBRARY FUNCTIONS

| Funtion |Required Arguments     | Description                |
| :-------- | :------- | :------------------------- |
| `create_transaction` | key`string`, amount`float`, e-mail`string`, redirect_url`string`, url`string`|This function makes a POST request to flutterwave payment API and returns a unique payment link.
| `verify_transaction`|  key`string` |This function makes a GET request to flutterwave verify Transaction API and returns a Dict Containing Details of Transaction. |
| `make_refund` | key`string`, txn_id`int` |  This function makes a POST request to make a refund in a disputed Transaction.|
| `transaction_details` |key`string` | This function makes a GET request to flutterwave and returns a Dict Containing Details of Transaction. |


The Output of each Function above is a python dictionary.This dictionary should be parsed to retrieve needed information.
## Contributing

Contributions are always welcome!

Please feel free to reach out to the creator for pull request and other possible questions regarding the use of this library.


## Documentation
For more info visit Flutterwave official API Docs: 

[Documentation](https://developer.flutterwave.com)


## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)


## Appendix

PYPI Link: https://pypi.org/project/flwave/



