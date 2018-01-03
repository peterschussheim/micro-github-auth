# micro-github-auth

[![Greenkeeper badge](https://badges.greenkeeper.io/peterschussheim/micro-github-auth.svg)](https://greenkeeper.io/)

## Usage

### Prerequisites

1. Setup an [application](https://github.com/settings/applications/new) to obtain a client ID and secret.
2. Decide on a deployment strategy, using `now` or your own server.

To deploy an instance of this service on Zeit's now cloud, **directly from this repo**, enter the following command in your terminal:

`$ now peterschussheim/micro-github-auth -e GH_CLIENT_ID=abc123 -e GH_CLIENT_SECRET=abc123 -e REDIRECT_URL=https://fsf.org`

Alternatively, to use your own server, you may store the required environment variables using a package such as [dotenv](https://github.com/motdotla/dotenv):

```
GH_CLIENT_ID="abc123"
GH_CLIENT_SECRET="abc123"
REDIRECT_URL="abc123"
GH_HOST="github.companyname.com"
```
