# ThiccStatus Discord

The ThiccStatus Discord client is a Python module, available on PyPi (PIP)! This module provides an easy status/uptime monitoring connection from your [Discord.py](https://discordpy.readthedocs.io/en/stable/) bot to [ThiccStatus](https://isthicc.dev/)!

## Current state of Discord.py

We are aware of the current state of Discord.py, though, we are hopeful for it's continued maintenance, whether official or not. 

This project will not be abandoned due to the state of Discord.py

## Installation 

You can install the ThiccStatus Discord.py module with 

`pip install thiccstatus`

## Setup

Once you have the ThiccStatus Discord.py module installed load the module with: 

```python
bot.load_extension('thiccstatus')
```

## How to use

*Work in progress!*

## Prerequisites

- An IsThicc API Token(attainable [here](https://isthicc.dev/dash/api))
- A ThiccStatus status page  
- Your API token and Status page domain saved in environmental variables(view below)

### Environmental variables

| Key  | Value | Example |
| ------------- | ------------- | ------------- |
| THICCSTATUS_API_TOKEN  | Your ThiccStatus API token | 3e8ed76e-6f1f-40ca-bd03-177196454934 |
| THICCSTATUS_DOMAIN  | Domain of your ThiccStatus status page | testing.thiccstat.us |
