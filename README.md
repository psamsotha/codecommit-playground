## AWS Elastic Beanstalk Java SE with Jersey

### Directions

1. Go to AWS management console and go to Elastic Beanstalk.
2. Create an Application using the Java 8 SE platform. Use the sample
   application.
3. Install the EB CLI.
4. With the EB CLI, run `eb init` to initialize the application locally.
   Follow the instructions.
5. Run `eb create` to create an environment.
6. When the environment is created, you should be able to access the api
   at `<url>/api/hello`.
   
For more detailed explanation, see the [AWS docs][docs]



[docs]: https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/java-se-platform.html