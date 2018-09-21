# AWS CodeBuild Project CloudWatch Logs<a name="aws-properties-codebuild-project-cloudwatchlogs"></a>

`CloudWatchLogs` is a property of the [AWS::CodeBuild::Project](aws-resource-codebuild-project.md) resource that specifies settings for CloudWatch Logs generated by an AWS CodeBuild build\.

## Syntax<a name="aws-properties-codebuild-project-cloudwatchlogs-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-codebuild-project-cloudwatchlogs-syntax.json"></a>

```
{
  "[Status](#cfn-codebuild-project-cloudwatchlogs-status)" : String,
  "[GroupName](#cfn-codebuild-project-cloudwatchlogs-groupname)" : String,
  "[StreamName](#cfn-codebuild-project-cloudwatchlogs-streamname)" : String
}
```

### YAML<a name="aws-properties-codebuild-project-cloudwatchlogs-syntax.yaml"></a>

```
[Status](#cfn-codebuild-project-cloudwatchlogs-status):  String
[GroupName](#cfn-codebuild-project-cloudwatchlogs-groupname):  String
[StreamName](#cfn-codebuild-project-cloudwatchlogs-streamname):  String
```

## Properties<a name="aws-properties-codebuild-project-cloudwatchlogs-properties"></a>

`Status`  <a name="cfn-codebuild-project-cloudwatchlogs-status"></a>
The current status of the CloudWatch Logs for a build project\. Valid values are:  
+ `ENABLED`: CloudWatch Logs are enabled for this build project\.
+ `DISABLED`: CloudWatch Logs are not enabled for this build project\.
*Required*: Yes  
*Type*: String  
*Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt)

`GroupName`  <a name="cfn-codebuild-project-cloudwatchlogs-groupname"></a>
 The group name of the CloudWatch Logs\.   
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt)

`StreamName`  <a name="cfn-codebuild-project-cloudwatchlogs-streamname"></a>
 The prefix of the stream name of the CloudWatch Logs\.   
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt)

## See Also<a name="aws-properties-codebuild-project-cloudwatchlogs-seealso"></a>
+ [ CloudWatchLogsConfig](https://docs.aws.amazon.com/codebuild/latest/APIReference/API_CloudWatchLogsConfig.html) in the *AWS CodeBuild API Reference*