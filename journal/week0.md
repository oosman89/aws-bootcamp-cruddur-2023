# Week 0 — Billing and Architecture
https://lucid.app/lucidchart/61982fa7-1b15-4c28-9e7b-c803c4f39507/edit?viewport_loc=-211%2C-16%2C3012%2C1311%2C0_0&invitationId=inv_f0c1fdd1-423c-4c01-9e5c-a5d2d0ed3327

https://lucid.app/lucidchart/a90487fe-bb11-4e4c-99ec-ce158b3d1550/edit?viewport_loc=64%2C74%2C1264%2C604%2C0_0&invitationId=inv_2716d185-dfaf-4c6c-8467-0bad669d4699


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
