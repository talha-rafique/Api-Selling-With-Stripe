## API with Stripe Metered Billing
This is the backed for APi selling with stripe payments for users account.

## Run it

- Create a metered billing product in Stripe
- Install Stripe CLI
- Add your testing Stripe secret key in the index.js

```bash
git clone 
npm i
node .
stripe listen --forward-to localhost:8080/webhook
```