# [Adyen Checkout](https://docs.adyen.com/checkout) integration demo

This repository includes examples of PCI-compliant UI integrations for online payments with Adyen. Within this demo app, we've created a simplified version of an e-commerce website, complete with commented code to highlight key features and concepts of Adyen's API. Check out the underlying code to see how you can integrate Adyen to give your shoppers the option to pay with their preferred payment methods, all in a seamless checkout experience.

## Integrations

**Java with Spark Java** demos of the following client-side integrations are available in this repository:

* [Drop-in](https://docs.adyen.com/checkout/drop-in-web)
* [Component](https://docs.adyen.com/checkout/components-web)
  * ACH
  * Alipay
  * Boleto
  * Card
  * Dotpay
  * Giropay
  * iDEAL
  * Klarna
  * Sofort
  

## Requirements - TODO

* Java 1.8
* Gradle

## Installation - TODO

1. Clone this repo
2. ...
 
## Usage - TODO

1. Update the config file `config.ini` with your [API key](https://docs.adyen.com/user-management/how-to-get-the-api-key), [Origin Key](https://docs.adyen.com/user-management/how-to-get-an-origin-key), and merchant account name like below:
    ```
    merchant_account = TestMerchantAccount
    checkout_apikey = SampleAPIKey
    origin_key = SampleOriginKey
    ```
2. Make sure your (venv) is activated by running `source ./venv/bin/activate` from your projects root.
3. Run `./start.sh` to:
    * Initialize the required environment variables. This step is necessary every time you re-activate your (venv)
    * Run flask 
3. Visit [http://localhost:8080](http://localhost:8080) and select an integration type!

## Contributing

We commit all our new features directly into our GitHub repository. Feel free to request or suggest new features or code changes yourself as well!!

## License

MIT license. For more information, see the **LICENSE** file in the root directory