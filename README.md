# example-klotho

- https://klo.dev/
- https://klo.dev/docs/

## Deploy

```shell
# Compile
$ klotho . --app my-first-app --provider aws

# Deploy (by Pulumi)
$ cd compiled/
$ npm i
$ pulumi config set aws:region ap-northeast-1
$ pulumi up
```

## Destroy

```shell
$ cd compiled/
$ pulumi down
```
