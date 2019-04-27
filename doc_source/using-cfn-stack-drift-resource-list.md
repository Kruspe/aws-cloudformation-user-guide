# Resources that Support Drift Detection<a name="using-cfn-stack-drift-resource-list"></a>

The following resource types support drift detection\.


| Service | Resource | 
| --- | --- | 
| API Gateway |  [AWS::ApiGateway::Authorizer](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-apigateway-authorizer.html) [AWSCloudFormation/latest/UserGuide/aws\-resource\-apigateway\-deployment\.html](https://docs.aws.amazon.com/aws-resource-apigateway-deployment) [AWS::ApiGateway::Method](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-apigateway-method.html) [AWS::ApiGateway::Model](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-apigateway-model.html) [AWS::ApiGateway::Resource](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-apigateway-resource.html) [AWS::ApiGateway::RestApi](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-apigateway-restapi.html) [AWS::ApiGateway::RequestValidator](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-apigateway-requestvalidator.html) [AWS::ApiGateway::Stage](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-apigateway-stage.html)  | 
| Auto Scaling |  [AWS::AutoScaling::AutoScalingGroup](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-as-group.html) [AWS::AutoScaling::LaunchConfiguration](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-as-launchconfig.html) [AWS::AutoScaling::LifecycleHook](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-as-lifecyclehook.html) [AWS::AutoScaling::ScalingPolicy](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-as-policy.html) [AWS::AutoScaling::ScheduledAction](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-as-scheduledaction.html)  | 
| CloudTrail |  [AWS::CloudTrail::Trail](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-cloudtrail-trail.html)  | 
| CloudWatch |  [AWS::CloudWatch::Alarm](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-cw-alarm.html) [AWS::Events::Rule](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-events-rule.html) [AWS::Logs::LogGroup](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-logs-loggroup.html) [AWS::Logs::MetricFilter](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-logs-metricfilter.html) [AWS::Logs::SubscriptionFilter](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-logs-subscriptionfilter.html)  | 
| DynamoDB |  [AWS::DynamoDB::Table](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-dynamodb-table.html)  | 
| Amazon EC2 |  [AWS::EC2::EIP](aws-properties-ec2-eip.md) [AWS::EC2::Instance](aws-properties-ec2-instance.md) [AWS::EC2::InternetGateway](aws-resource-ec2-internetgateway.md) [AWS::EC2::NatGateway](aws-resource-ec2-natgateway.md) [AWS::EC2::NetworkAcl](aws-resource-ec2-network-acl.md) [AWS::EC2::NetworkInterface](aws-resource-ec2-network-interface.md) [AWS::EC2::RouteTable](aws-resource-ec2-route-table.md) [AWS::EC2::SecurityGroup](aws-properties-ec2-security-group.md) [AWS::EC2::Subnet](aws-resource-ec2-subnet.md) [AWS::EC2::Volume](aws-properties-ec2-ebs-volume.md) [AWS::EC2::VPC](aws-resource-ec2-vpc.md)  | 
| Amazon ECS |  [AWS::ECS::Cluster](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ecs-cluster.html) [AWS::ECS::Service](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ecs-service.html) [AWS::ECS::TaskDefinition](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ecs-taskdefinition.html)  | 
| Elastic Load Balancing |  [AWS::ElasticLoadBalancing::LoadBalancer](https://docs.aws.amazon.com/aws-properties-ec2-elb) [AWS::ElasticLoadBalancingV2::Listener](aws-resource-elasticloadbalancingv2-listener.md) [AWS::ElasticLoadBalancingV2::ListenerRule](aws-resource-elasticloadbalancingv2-listenerrule.md) [AWS::ElasticLoadBalancingV2::LoadBalancer](aws-resource-elasticloadbalancingv2-loadbalancer.md)  | 
| IAM |  [AWS::IAM::Group](aws-properties-iam-group.md) [AWS::IAM::InstanceProfile](aws-resource-iam-instanceprofile.md) [AWS::IAM::ManagedPolicy](aws-resource-iam-managedpolicy.md) [AWS::IAM::Role](aws-resource-iam-role.md) [AWS::IAM::User](aws-properties-iam-user.md)  | 
| AWS IoT |  [AWS::IoT::Thing](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-iot-thing.html)  | 
| Lambda |  [AWS::Lambda::Alias](aws-resource-lambda-alias.md) [AWS::Lambda::Function](aws-resource-lambda-function.md) [AWS::Lambda::Version](aws-resource-lambda-version.md)  | 
| Amazon RDS |  [AWS::RDS::DBCluster](aws-resource-rds-dbcluster.md) [AWS::RDS::DBInstance](aws-properties-rds-database-instance.md)  | 
| Route 53 |  [AWS::Route53::HostedZone](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-route53-hostedzone.html)  | 
| Amazon S3 |  [AWS::S3::Bucket](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-s3-bucket.html)  | 
| Amazon SNS |  [AWS::SNS::Topic](aws-properties-sns-topic.md)  | 
| Amazon SQS |  [AWS::SQS::Queue](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-sqs-queues.html)  | 