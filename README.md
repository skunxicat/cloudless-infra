# cloudless-infra

> Foundation module for cloudless infrastructure. Standardizes the boring stuff so you focus on the unique parts.

Provides consistent labeling, naming conventions, and environment context for all cloudless modules.

## Quick Start

```bash
# Bootstrap into existing project
curl -sL https://raw.githubusercontent.com/ql4b/cloudless-infra/main/bootstrap | bash
```

or 

```
# specify project name and directory
curl -sL https://raw.githubusercontent.com/ql4b/cloudless-infra/main/bootstrap | bash -s my-project infra
```

```bash

export PATH="$(pwd):$PATH"
tf init 
tf apply --auto-approve

tf output -json env | jq 

```

## Manual Setup 

```
# setup environment variables
cp .env.example .env

# edit variables in .env

```

## tf wrapper

```
# add . to the $PATH
export PATH="$(pwd):$PATH"

# check tf is in the $PATH
which tf

tf varsion

```

## tf init 

```
tf init
```

## outputs

```
tf apply --auto-approve
tf output -json env | jq 

```
