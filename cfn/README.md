#to launch cfn stack
aws cloudformation create-stack \
--stack-name lexchatbot \
--template-body file://infra.yaml \
--capabilities CAPABILITY_NAMED_IAM


#to delete the stack
aws cloudformation delete-stack \
--stack-name lexchatbot