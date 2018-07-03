# Running Terraforming on Docker

## Build

```
$ sudo docker build -t kazusato/terraforming:0.1.0 .
```

## Run

```
$ sudo docker run --rm \
 -e AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID \
 -e AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY \
 -e AWS_REGION=$AWS_REGION \
 kazusato/terraforming:0.1.0 \
 terraforming ec2
```

## References
- [dtan4/terraforming](https://github.com/dtan4/terraforming)

