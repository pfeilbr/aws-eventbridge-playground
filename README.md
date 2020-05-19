# aws-eventbridge-playground

learn [AWS EventBridge](https://aws.amazon.com/eventbridge/)

```sh
# put events on default event bus
aws events put-events --entries file://sample-events/my-custom-app-events.json
```

## Resources

* <https://github.com/jbesw/s3-to-lambda/blob/master/eventbridge/README.md> - examples using `AWS::Events::Rule` in SAM to map event sources to targets (e.g. lambda, kinesis, etc.)