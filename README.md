# dynamo

A plugin to open the DynamoDB table page on AWS console with interactive selector.

## Requirements

- [fzf](https://github.com/junegunn/fzf)

## Installation

```bash
curl -LO https://raw.githubusercontent.com/RossyWhite/dynamo/v0.0.1/dynamo
chmod u+x dynamo
mv dynamo /usr/local/bin
```

## Usage

```bash
$ dynamo --help

Usage: dynamo [OPTIONS...]
OPTIONS:
  -h, --help      Show help for 'dynamo'
  --profile       string   Use a specific profile from your credential file.
  --region        string   The region to use. Overrides config/env settings.
Examples:
  dynamo my-dynamodb --profile development --region ap-northeast-1
```
