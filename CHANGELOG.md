## 1.3.0

* Update to use forked solidus_frontend when needed.
* Add deprecation notice to README.
* Suggest setting a value for environment preference.
* Adopt CircleCI instead of Travis.
* Test suite improvements.
* Fix references to `Spree.t`.
* Extension maintenance.
* Remove 2.2 from CI (EOL).
* Fix Travis issue with Solidus old versions (Factory Bot gem).
* Remove versions past EOL from .travis.yml.
* Add Solidus 2.7 to .travis.yml.

## 1.2.0

## 1.1.0

## 1.0.0

* Upgrade braintree to 2.23.0 for bug fixes and fraud detection with deviceData.

## 0.2.0

* Add functionality around PayPal by adding a json or text field on credit card for storing extra data coming back from Braintree.
* Upgrade braintree to 2.14.0 for hosted field and teardown support.

## 0.1.5

* Use mapping to set cc_type conventionally.

## 0.1.3

* Add back in name validation on `CreditCard`.

## 0.1.2

* Upgrade braintree to 2.13.0-beta for the abiltiy to destroy/teardown.
* Fix bug related to using existing credit cards in admin.

## 0.1.1

* Get the client token and attach the dropin on page load to support the create
order flow in admin, also fixes clicking the new credit card radio quickly and
it attaching multiple dropins.

## 0.1.0

* First release.
