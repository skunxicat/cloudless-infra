# cloudless-infra

> Foundation module for cloudless infrastructure. Standardizes the boring stuff so you focus on the unique parts.

Provides consistent labeling, naming conventions, and environment context for all cloudless modules.

## setup 

```
# setup environment variables
cp .env.example .env

# edit variables in .env

```

## tf wrapper

```
# add . to the $PATH
export PATH="$(realpath .):$PATH"

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