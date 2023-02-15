# Week 0 — Billing and Architecture

<img width="589" alt="Screen Shot 2023-02-15 at 19 22 56" src="https://user-images.githubusercontent.com/116604457/219131671-86e772dd-645d-4dd2-a877-8734f6aaafab.png">

<img width="568" alt="Screen Shot 2023-02-15 at 19 22 31" src="https://user-images.githubusercontent.com/116604457/219131794-99280740-e86b-41b2-8543-77023cc60632.png">


{
  "alarmName": "Crudalarm",
  "alarmType": "MetricAlarm",
  "timestamp": "2023-02-11T19:59:37.163Z",
  "historyItemType": "ConfigurationUpdate",
  "historySummary": "Alarm \"Crudalarm\" created",
  "historyData": {
    "version": "1.0",
    "type": "Create",
    "createdAlarm": {
      "alarmName": "Crudalarm",
      "alarmDescription": "",
      "alarmArn": "arn:aws:cloudwatch:us-east-1:596384998295:alarm:Crudalarm",
      "alarmConfigurationUpdatedTimestamp": "2023-02-11T19:59:37.162+0000",
      "namespace": "AWS/Billing",
      "metricName": "EstimatedCharges",
      "statistic": "Maximum",
      "period": 21600,
      "dimensions": [
        {
          "value": "USD",
          "name": "Currency"
        }
      ],
      "threshold": 20,
      "comparisonOperator": "GreaterThanThreshold",
      "evaluationPeriods": 1,
      "datapointsToAlarm": 1,
      "treatMissingData": "missing",
      "stateValue": "INSUFFICIENT_DATA",
      "stateUpdatedTimestamp": "2023-02-11T19:59:37.162+0000",
      "actionsEnabled": true,
      "alarmActions": [],
      "insufficientDataActions": [],
      "okactions": []
    }
  }
}
