# All things Related to Enviroment Variables

### Here is what you need as enviroment variables for your api to run propaply

- PPOSTGRES_USERNAME
- POSTGRES_PASSWORD
- POSTGRES_HOST
- POSTGRES_DB
- AWS_BUCKET
- AWS_REGION
- AWS_PROFILE
- JWT_SECRET
- URL

### You need to set a `.env` file in your code locally or put them into the `elastic beanstalk enviroment properties` when the code is on the production server so you code work propoably.

![elastic beanstalk enviroment properties](./imgs/env1.png 'figure 1')

### or use a .sh file that will export them for you if you need when you call it.
