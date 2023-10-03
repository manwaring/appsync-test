# Reproduces https://github.com/sid88in/serverless-appsync-plugin/issues/617

`main` branch has the v1 configurations, `v2-config` has the v2 configurations

Steps

- Clone repo
- Install dependencies with `npm ci`
- Deploy project with `npm run deploy`
- Make note of the Appsync API ID and URL in the AWS console
- Checkout the v2 config branch with `git checkout v2-config`
- Install dependencies with `npm ci`
- Deploy project with `npm run deploy`
- Note that the Appsync API ID and URL in the AWS console have changed
