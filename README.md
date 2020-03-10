# packer build ami

# Packer Installation(for linux user):
- sudo apt-get update
- sudo apt-get install packer

# Packer validation:
- packer validate file_name.json

# Packer build ami:
- packer build \
    -var "aws_access_key=REDACTED" \
    -var "aws_secret_key=REDACTED" \
    -var "aws_region=us-east-1" \
    -var "aws_users=REDACTED" \
    ami.json

# hints:
Please remember to use double quote in command line for using environment paramters

# new component: codedeploy agent
