# Inventory Manager

A web app to track and manage inventory for homes, kitchens and small shops. Built with React, TypeScript, Vite, Tailwind CSS and Firebase.

## Features

- Store and manage product data such as quantities and expiration dates
- Highlight products that are close to expiring
- Email and password authentication via Firebase Auth
- Product data stored in Firestore

## Tech stack

- React 18 + TypeScript
- Vite
- Tailwind CSS
- Firebase (Auth and Firestore)
- ESLint and Prettier

## Getting started

```bash
git clone https://github.com/SethSaDev/inventory-manager-web.git
cd inventory-manager-web
yarn
cp .env.example .env   # then fill in your Firebase config
yarn dev
```

Open http://localhost:3000 in your browser.

Other scripts: `yarn build`, `yarn preview`, `yarn lint`, `yarn pretty`.

## Credits and license

Based on [xSallus/my-inventory-front](https://github.com/xSallus/my-inventory-front) by Salomao Souza, released under the MIT License. See [LICENSE.md](LICENSE.md).
