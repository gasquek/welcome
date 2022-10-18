# Welcome
A non-code repo meant to act as documentation and introduction to GasqueK-Tech-Development


# Core Product
GasqueK's core technical products are the web-application services `admin.gasquen.se` and `gasquen.se`. 

![web](https://user-images.githubusercontent.com/42417723/196419892-7a835fa4-3285-4f99-96d4-b1049dc2c291.jpg)

## gasquen.se
Gasquen.se is our customer facing product. It is built using wordpress and uses the laravel-api backend under `admin.gasquen.se`. The site was developed by the consultant agency Sharpmind in 2018. Future development by the committée or 3rd parties can be found in the private repository. Wordpress management information can also be found in the private repository.

The service can be accessed at: <br>
https://gasquen.se/

For more technical information and security-sensitive information visit the repository: <br>
https://github.com/gasquek/core-web-product

## admin.gasquen.se
The admin page is primarely used by our staff and other parties involved in the operations of the nightclub. The admin page is used for booking the venue, ordering alcohol, and uploading marketing material. The admin product also serves the customer facing product `core-web-product` using a laravel based REST API.

You can visit the service at: <br>
https://admin.gasquen.se/

For more technical information and security-sensitive information visit the repository: <br>
https://github.com/gasquek/core-web-admin


# Data stack
GasqueK has a rather small datastack using Metabase, MySQL, Google Analytics, however, with great ambitions to extend these.

## Metabase
Metabase is our go to tool for business intelligence. Metabase is the easy, open-source way to help everyone to work with data like an analyst, even without SQL experience. You can read more about Metabaes [here](https://www.metabase.com/). We aim to have a data-driven organisation and operational mindset. Metabase is currently connected to two datasources `Gasquen.se` and `Google Analytics`.

Our Metabase service can be reached at: <br>
https://metabase.gasquen.se/

For more technical information and security-sensitive information visit the repository: <br>
https://github.com/gasquek/data-metabase

![Data](https://user-images.githubusercontent.com/42417723/196423317-f53142b8-33db-4461-8f3f-6a6719c83bad.jpg)

# Marketing Email
GasqueK uses MJML to produce beautiful HTML based marketing emails. These are used to create engaging content and information newsletters to our staff. Our current email service is open-source and is also very basic. It uses a SMTP connection with our email service prodvider Google and sends the html content to our staff. There are ideas to expand upon this.

For more technical information visit the repository: <br>
https://github.com/gasquek/email-marketing

![Email](https://user-images.githubusercontent.com/42417723/196423094-968285a6-6e9a-4d23-b495-0c452752a3f0.jpg)
