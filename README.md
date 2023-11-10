# Nuvolaris LLM Plugin

## Install

This is a [nuv](https://github.com/nuvolaris/nuv) plugin to setup and manage an LLM provider for Nuvolaris.

To use, install [nuv](https://nuvolaris.github.io/nuvolaris/3.0.0/installation/download.html) and clone the plugin for development:

```
git clone https://github.com/nuvolaris/olaris-llm
```

Then you have a `nuv llm` subcommand (if you run from the parent folder)

## Use

Setup a few convenience aliases

```
alias nlg="nuv llm gcp"
alias nlu="nuv llm util"
alias nlt="nuv llm tgi"
```

## Prerequisites

You need:
- the gcloud command 
- a gcloud account,
- billing and authorizations set up
- a default project 
- vm with a public hostname to connect from

## Manage a Cloud VM with GPU

```
nlg create
nlg destroy

nlg start
nlg enter
nlg stop
```

## Build tgi

```
nlt build 
```
