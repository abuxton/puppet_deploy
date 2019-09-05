
# puppet_deploy

This module is presented as a wrapper module for deploying puppet enterprise and various tools, it utilises a Puppet Bolt methodology of Task and Plans to enable deployment of Puppet and related products.


#### Table of Contents

- [puppet_deploy](#puppetdeploy)
      - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Setup](#setup)
    - [Setup Requirements **OPTIONAL**](#setup-requirements-optional)
    - [Beginning with puppet_deploy](#beginning-with-puppetdeploy)
  - [Usage](#usage)
  - [Limitations](#limitations)
  - [Development](#development)
    - [ToDO](#todo)

## Description

Deploy Puppet Open Source, Puppet Enterprise, Puppet agents, and other related products from one project.
Supported by spec tests and expande dto support Litmus execution. 

## Setup

### Setup Requirements **OPTIONAL**

* Puppet Bolt installed (their is always a Chicken where there is an egg)
* You may want the PDK to validate the module
* You will probably want bundler installed to extend the workflow. 

### Beginning with puppet_deploy

* invoke `bolt puppetfile install`
* invoke `bolt task show` or `bolt task show --modulepath=./modules/` (bolt.yaml is configured with a standard module path)
* invoke `bolt plan show` or `bolt plan show --modulepath=./modules/` (bolt.yaml is configured with a standard module path)

## Usage

Follow the bolt documentation for `bolt task` and or `bolt plan`


## Limitations

In the Limitations section, list any incompatibilities, known issues, or other warnings.

## Development

If you find, create or help with a project you consider may be useful for this collection feel free to create a pull request. 
if you want to add tasks, plans directly consider writing spec tests for the plans that can be executed with Litmus.

### ToDO

