# KNYC site

Microsite for Kaggle NYC. Allows visitors to invite themselves to slack and 
provides links to resources.
It is a standard node.js, express site with [Pug](https://pugjs.org/) templates.

[original readme](https://github.com/outsideris/slack-invite-automation)

## Installation

1. npm install
1. `cp .env.template .env` and fill in the SLACK_TOKEN by getting the oauth token. See https://github.com/outsideris/slack-invite-automation/pull/125/files
1. npm start

Open localhost:3000 in a browser to see the main page.

## Testing

You can use the curl provided in `send-invite.sh` to test the invites are sending.

## Logging in

`ssh -i <pem file> ubuntu@52.6.145.255`
Note elastic ip may change in the future
