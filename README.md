## Module Usage

```
module "http-instances" {
  instanceCount = 4
  ami = "ami-0726555fb5b46ab38"
}
```

## Available Variables 

```
instanceCount (number)
ami (string)
keypairs (string)
commonLabels (tuple)
commonTags (map)
```

## Available Outputs

```
publicIP - The public IP of the ec2 instance
arn - ARN of the instance
```
