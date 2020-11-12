# udagram nanodegree "prjoect deployment

## Goal
Second Project of udacity nanodegree Cloud Devops Engineer 

### Installation

Deploy infrastructure

```sh
$ ./create.sh ope-uda-infra udagram_infra/infra.yml udagram_infra/infra_param.json
```

Deploy web application

```sh
$ ./create.sh ope-uda-app udagram_app/app.yml udagram_app/app_param.json
```

update web application

```sh
./update.sh ope-uda-app udagram_app/app.yml udagram_app/app_param.json
```