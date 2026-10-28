# Skybound Flight Reservations

A responsive, frontend-only flight reservation demo built with React, JavaScript, HTML, CSS, Bootstrap, and Vite.

## Run locally

```sh
npm install
npm run dev
```

Create a production build with `npm run build`, or run the project linter with `npm run lint`.

## Features

- Search sample flights by origin, destination, date, trip type, and traveler count.
- Choose Indian domestic or international airports; domestic India fares display in INR and routes involving other countries display in USD.
- Sort flight results and continue to traveler details and a checkout with UPI, net banking, QR-code, and card demo options.
- View a confirmation and saved reservations from **My bookings**.
- Open **Help** for answers about searching, demo checkout, and locally saved bookings.
- Keep booking data in browser `localStorage` under `skybound-bookings`.
- Navigate Explore, flight results, checkout, confirmation, bookings, and Help with browser-addressable hash routes. The current search can be refreshed in the same tab.

Flight schedules and fares are sample data and are not live exchange-rate conversions. Checkout is a UI demo only: no payment gateway, UPI app, or bank is connected, no payment is processed, and payment details are not saved. The generated QR code contains a demo order reference only; it cannot be used to transfer money. Do not enter real payment details.
