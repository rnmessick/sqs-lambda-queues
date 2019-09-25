# sqs-lambda-queues

<!-- Received assistance on building readme by Nick Paro -->
![Image of cloudwatch metric](https://github.com/rnmessick/sqs-lambda-queues/blob/master/src/main/resources/cloudwatchMetrics.JPG)
![Image of all queues added to triggers](https://github.com/rnmessick/sqs-lambda-queues/blob/master/src/main/resources/sqsReceiverAllQueuesTriggers.JPG)
![receiver lambda function](https://github.com/rnmessick/sqs-lambda-queues/blob/master/src/main/resources/sqsReceiverLamdaSuccess.JPG)

### Run Instructions
- clone or fork https://github.com/rnmessick/sqs-queues

- add .env
  - REACT_APP_AWS_ACCESS_KEY_ID={ your aws id }
  - REACT_APP_AWS_SECRET_ACCESS_KEY={ your aws secret key }
- To start the front end:
  - `npm start` on the logger-react-queueA application.
  - `npm start` on the logger-react-queueB application.
  - `npm start` on the logger-react-queueC application.

### Collaboration / Resources

- @Bombibear
- Sapana Poudel
- Nhu Trinh
- Joachen Busch
- Brandon Hurrington
- Nick Paro
- Travis Cox
- Jack Kinne
- Marisha Hoza
- Chris Coulon
- Matt Stuhring
- Melfi Perez
- Padmapriva Ganapathi
- [AWS SQS Docs](https://docs.aws.amazon.com/sdk-for-java/v1/developer-guide/examples-sqs-message-queues.html)
- [AWS SQS Example Code](https://github.com/awsdocs/aws-doc-sdk-examples/blob/master/java/example_code/sqs/src/main/java/aws/example/sqs/UsingQueues.java)

- [AWS SQS Lambda Sample Code](https://docs.aws.amazon.com/lambda/latest/dg/with-sqs-create-package.html)
