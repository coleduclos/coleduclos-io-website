# mobile-app-landing-page-template
GitHub template for creating a mobile app landing page

## AWS Infrastructure
### Build

```
make build
```

### Plan

```
make plan
```

### Deploy
```
make deploy
```

## HTML Code
### Build

```
make build
```

### Push

```
export APPLICATION_ID=coleduclosio
export ARTIFACT_S3_BUCKET=<INSERT_OPS_BUCKET>
make push
```

### Deploy

```
export APPLICATION_ID=coleduclosio
export ARTIFACT_S3_BUCKET=<INSERT_OPS_BUCKET>
export WEBSITE_S3_BUCKET=coleduclos.io
make deploy
```
