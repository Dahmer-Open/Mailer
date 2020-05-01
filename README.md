# Dahmer's Open Mailer

Dahmer's Open Mailer is an example mailing service using NodeJS and Node-Mailer. Currently only supports gmail. 📧

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

In order for Dahmer's Open Mailer to work properly, you cannot have any sort of 2 factor auth configured on the email used to sent the email.

> You currently need to disable some security in the sender's account in order to be
> able to send emails.
>
> Go to https://myaccount.google.com/u/2/lesssecureapps?pageId=none, make sure you are
> on the right account and allow unsafe apps. If you use Google Suite, you need to
> allow your domain's users to allow unsafe apps first by following these instructions: 
> https://support.google.com/a/answer/6260879?hl=en under Manage access to less secure
> apps.
>
> This will remain true until the 1.0.0 version.


### Installing

A step by step series of examples that tell you how to get a development env running.

1. Install the dependencies by running `npm i`;
2. If your project doesn't have a `.env` file yet at its root, create it. This file will contain the authentication credentials for your email and will not be pushed to your repository.
3. Add the `DO_MAILER_EMAIL` and `DO_MAILER_PASSWORD` variables with your email credentials.

## Running the tests

To run the tests, ensure that the `DO_MAILER_TEST_RECIPIENT` is set in the `.env` file and run `npm run test`, you should receive an email.

## Built With

* [NodeJS](https://nodejs.org/en/) - JavaScript runtime built on Chrome's V8 JavaScript engine.
* [NodeMailer](https://nodemailer.com/about/) - a module for Node.js applications to allow easy as cake email sending.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/DominicF96/DO_Mailer/tags). 

## Authors

* **Dominic Fournier** - *Initial work*

See also the list of [contributors](https://github.com/DominicF96/DO_Mailer/graphs/contributors) who participated in this project.

## License

This project is licensed under the GNUv3.0 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to Esterling Accime for his very useful [video tutorial on Nodemailer](https://www.youtube.com/watch?v=Va9UKGs1bwI).



