# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- EB CLI to be able to interacte with elastic beanstalk easily

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.
```

### Installation And Configurations

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. [DB Properties](docs/dbprop.md)
1. In AWS, provision a s3 bucket for hosting the uploaded files. [S3 Buckets Properties](docs/s3prop.md)
1. Export the ENV variables. [ENV Setup](docs/env.md)
1. In AWS, Create a user using IAM service to react with the cli tooles. [IAM User](docs/iam.md)
1. config your Elastic beanstalk. [EB Configuration](docs/ebconfig.md)
1. config your circleci pipeline. [Circleci Pipeline Configuration](docs/circleci.md)
1. From the root of the repo, Their is a main `package.json` file with scripts that is used for the `circleci` config file to run all the tasks needed for deployment, so if you need to test it just call `npm run <name of the script>`

## Application Diagram for Deployment and Communication flow

![Diagram](docs/imgs/digram.png 'figure 1')

## How to Deploy

Just Go to the main directory and after all the installations steps run `npm run deploy`.

## Application Links

- [FrontEnd link](http://front-bucket-28342289234.s3-website-us-east-1.amazonaws.com/)
- [Backed link](http://udagram-api-dev22222.us-east-1.elasticbeanstalk.com/)

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
