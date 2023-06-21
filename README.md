## API with Stripe Metered Billing
This is the backed for APi selling with stripe payments for users account.

## Run it

- need to create products in stripe and then connect stripe via Stripe CLi
- Install Stripe CLI and connect
- Add testing Stripe secret key in the index.js

# To Run
```bash
git clone 
npm i
node .
stripe listen --forward-to localhost:8080/webhook
```