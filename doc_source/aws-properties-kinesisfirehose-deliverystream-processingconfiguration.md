# Amazon Kinesis Data Firehose DeliveryStream ProcessingConfiguration<a name="aws-properties-kinesisfirehose-deliverystream-processingconfiguration"></a>

The `ProcessingConfiguration` property configures data processing for an Amazon Kinesis Data Firehose delivery stream\.

`ProcessingConfiguration` is a property of the [ElasticsearchDestinationConfiguration](aws-properties-kinesisfirehose-deliverystream-elasticsearchdestinationconfiguration.md), [ExtendedS3DestinationConfiguration](aws-properties-kinesisfirehose-deliverystream-extendeds3destinationconfiguration.md), [RedshiftDestinationConfiguration](aws-properties-kinesisfirehose-deliverystream-redshiftdestinationconfiguration.md), and [SplunkDestinationConfiguration](aws-properties-kinesisfirehose-deliverystream-splunkdestinationconfiguration.md) property types\. 

## Syntax<a name="aws-properties-kinesisfirehose-deliverystream-processingconfiguration-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-kinesisfirehose-deliverystream-processingconfiguration-syntax.json"></a>

```
{
  "[Enabled](#cfn-kinesisfirehose-deliverystream-processingconfiguration-enabled)" : Boolean,
  "[Processors](#cfn-kinesisfirehose-deliverystream-processingconfiguration-processors)" : [ [*Processor*](aws-properties-kinesisfirehose-deliverystream-processor.md), ... ]
}
```

### YAML<a name="aws-properties-kinesisfirehose-deliverystream-processingconfiguration-syntax.yaml"></a>

```
  [Enabled](#cfn-kinesisfirehose-deliverystream-processingconfiguration-enabled): Boolean
  [Processors](#cfn-kinesisfirehose-deliverystream-processingconfiguration-processors): 
    - [*Processor*](aws-properties-kinesisfirehose-deliverystream-processor.md)
```

## Properties<a name="aws-properties-kinesisfirehose-deliverystream-processingconfiguration-properties"></a>

`Enabled`  <a name="cfn-kinesisfirehose-deliverystream-processingconfiguration-enabled"></a>
Indicates whether data processing is enabled \(`true`\) or disabled \(`false`\)\.  
 *Required*: No  
*Type*: Boolean  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`Processors`  <a name="cfn-kinesisfirehose-deliverystream-processingconfiguration-processors"></a>
The data processors\.  
 *Required*: Yes  
 *Type*: List of [Processor](aws-properties-kinesisfirehose-deliverystream-processor.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 