# AWS Tor Layer

This is Tor Layer for AWS Lambda.

Downloadable (& executable) tor package can be found [here](https://gitweb.torproject.org/tor.git).


## Deployment

Tor layer can be uploaded using [serverless framework](https://www.serverless.com/). Exec below:

```shell
$ sls deploy [options]

Options
  --profile <profile>  AWS IAM profile.
```

Or, manually upload `context-amazon-linux-2.zip` as lambda layer.

The path of tor file is `/opt/bin/tor`.