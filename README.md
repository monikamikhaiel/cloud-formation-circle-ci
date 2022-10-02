simple Cloud formation stack in order to test circle ci job 
aws cloudformation create-stack --stack-name simpleec2 --template-body file://main.yaml  --region=us-east-1
