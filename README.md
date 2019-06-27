# opg-document-conversion-lambda
OPG Document Conversion Lambda: Managed by opg-org-infra &amp; Terraform

## Requirements

* AWS CLI already configured with Administrator permission
* [Python 3 installed](https://www.python.org/downloads/)
* [Docker installed](https://www.docker.com/community-edition)

## Setup process

### Local development

**Invoking function locally using a local sample payload**

```bash
sam local invoke HelloWorldFunction --event event.json
```

```bash
python3 -m virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
```g


