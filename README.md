payfriend
===========

PayFriend Payment Methods

To run this simple express application, clone, npm install, npm run, visit at [http://localhost:8000](http://localhost:8000)

## Functionalities

### Login

- Success: Any entry (or blank fields) will result in a successful login
- Failure: Using email address `fail@fail.com` will result in failed login

### Add credit card

- Success: Any entry (or blank fields) will result in success
- Failure: Using credit card number `1001001` will result in failure

_Note: there is an experimentation of roughly 50% where the credit card type dropdown will or won't be present_

### Add bank account

- Success: Any entry (or blank fields) will result in success
- Failure: Using bank account number `1001001` will result in failure
