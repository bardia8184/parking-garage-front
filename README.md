# Scenario
We are building an application to manage a parking garage customers. The app is accessed from a web browser and runs as a single page application. Each customer is able to request entering the parking garage, and receive a ticket. The customer is then charged for parking based on the length of their stay. The customer is not allowed to leave the parking before a successful payment.
This API has the following capabilities:
1.	Each customer is able to request entry to the parking garage at the time of arrival. If there is space available, the app issues a ticket to the customer.
2.	The customer is able to pay their ticket based on the length of their stay (options: 1hr ($3), 3hr ($4.5), 6hr ($6.75), or ALL DAY ($10.12)
3.	When the customer is on their way out of the garage, the app checks that if the ticket is paid. If not, denies their exit.
4.	If the parking garage is full, the app denies entry.
5.	App allows each customer to register in case the lot is full and maintain a queue of customers, sends a message (email or otherwise) to notify if there is a free spot when one becomes available.


## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
