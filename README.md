```
export PCE_API_KEY=<YOUR_PCI_API_KEY>
aws cloudformation update-stack \
        --stack-name pce-ecs-fargate-example \
        --parameters ParameterKey=PceApiKey,ParameterValue=$PCE_API_KEY \
        --template-body file://pce-ecs-fargate-example.yaml
```
