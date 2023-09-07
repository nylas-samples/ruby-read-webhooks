# ruby-read-webhooks

This sample will show you to read webhooks using the Nylas Ruby SDK.

## Setup

You need a web server capable of running Ruby code. [Koyeb](https://www.koyeb.com/) is a great option.

### System dependencies

Handled by the web server.

### Gather environment variables

You'll need to create the following environment values:

```text
V3_TOKEN
BASE_URL
GRANT_ID
CALENDAR_ID
CLIENT_SECRET
```

### Install dependencies

Everything is on the Gemfile file, but here they are:

```bash
nylas / 6.0.0.beta.1
sinatra / 3.1.0
sinatra-contrib / 3.1.0
rack / 2.2.8
puma / 6.3.1
```

# Compilation

Clone this repo and use it as the source for your web server compilation

## Usage

Run the generated web page.

If successful, you will start to see all your incoming webhooks
