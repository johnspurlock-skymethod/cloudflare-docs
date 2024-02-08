---
_build:
  publishResources: false
  render: never
  list: never
---

To create a new Cloudflare account:

1. [Sign up](https://dash.cloudflare.com/sign-up) on the Cloudflare dashboard.

2. To secure your account, enable [two-factor authentication](/fundamentals/setup/account/account-security/2fa/).

3. If you have a Cloudflare contact (Enterprise only), ask them to set up your account as a multi-user organization. Account members will need:
    - [**Access** permissions](/cloudflare-one/roles-permissions/) to read or edit applications and Access policies.
    - [**Gateway** permissions](/cloudflare-one/roles-permissions/) to read or edit Gateway policies.
    - [**PII** permissions](/cloudflare-one/roles-permissions/#cloudflare-zero-trust-pii) to view user information in Gateway activity logs.

## Best practices

{{<render file="_create-account-best-practices.md" productFolder="fundamentals">}}