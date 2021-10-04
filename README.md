# Howto

First replace these variables:
```JS
const mongoUser = '<username>';
const mongoDbName = '<databasename>';
const mongoPass = '<password>';
const mongodbCluster = '<clustername>';
```

Second set your AWS profile in `serverless.yaml` corresponding your `~/.aws` settings

```YAML
provider:
  profile: <set-your-aws-profile>
```

Third execute `npm install` to download all dependencies. 

Last execute `serverless deploy` in the `crash-service-test` directory.