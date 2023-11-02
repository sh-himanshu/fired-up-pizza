# Fired Up Pizza

eCommerce website for pizza ordering, complete with seamless and secure payments through PayPal's API integration.

<p align="center">
<a href=https://github.com/sh-himanshu/fired-up-pizza target="_blank">
<img src='./public/pizza.png' width="100%" alt="Banner" />
</a>
</p>

<p align="center">
<img src="https://img.shields.io/github/contributors/sh-himanshu/fired-up-pizza" alt="GitHub contributors" />
<img src="https://img.shields.io/github/discussions/sh-himanshu/fired-up-pizza" alt="GitHub discussions" />
<img src="https://img.shields.io/github/issues/sh-himanshu/fired-up-pizza" alt="GitHub issues" />
<img src="https://img.shields.io/github/issues-pr/sh-himanshu/fired-up-pizza" alt="GitHub pull request" />
</p>

## 🔍 Table of Contents

- [Fired Up Pizza](#fired-up-pizza)
  - [🔍 Table of Contents](#-table-of-contents)
  - [💻 Stack](#-stack)
  - [📝 Project Summary](#-project-summary)
  - [⚙️ Setting Up](#️-setting-up)
      - [Your Environment Variable](#your-environment-variable)
  - [🚀 Run Locally](#-run-locally)
  - [🙌 Contributors](#-contributors)
  - [📄 License](#-license)

## 💻 Stack

- [react](https://reactjs.org/): JavaScript library for building user interfaces.
- [react-redux](https://react-redux.js.org/): Official React bindings for Redux, a predictable state container for JavaScript apps.
- [redux](https://redux.js.org/): A predictable state container for JavaScript apps.
- [axios](https://axios-http.com/): Promise-based HTTP client for the browser and Node.js.
- [next](https://nextjs.org/): React framework for server-rendered applications.
- [mongoose](https://mongoosejs.com/): Object Data Modeling (ODM) library for MongoDB and Node.js.
- [cookie](https://www.npmjs.com/package/cookie): HTTP cookie parsing and serialization for Node.js.
- [paypal/react-paypal-js](https://github.com/paypal/react-paypal-js): React components for integrating PayPal into your app.

## 📝 Project Summary

- [components](components): Contains reusable UI components used throughout the project.
- [models](models): Defines data models and handles data manipulation logic.
- [pages](pages): Contains top-level pages of the application.
- [pages/admin](pages/admin): Handles administrative functionality and user management.
- [pages/api](pages/api): Contains API endpoints for server-side communication.
- [pages/api/orders](pages/api/orders): Manages orders-related API functionality.
- [pages/api/products](pages/api/products): Manages products-related API functionality.
- [pages/orders](pages/orders): Handles order-related functionality and views.
- [pages/product](pages/product): Handles product-related functionality and views.
- [redux](redux): Contains Redux actions, reducers, and store configuration.

## ⚙️ Setting Up

#### Your Environment Variable

```
MONGO_URL = string
ADMIN_USERNAME = string
ADMIN_PASSWORD = string
TOKEN = string
```

## 🚀 Run Locally

1.Clone the fired-up-pizza repository:

```sh
git clone https://github.com/sh-himanshu/fired-up-pizza
```

2.Install the dependencies with one of the package managers listed below:

```bash
yarn install
```

3.Start the development mode:

```bash
yarn dev
```

## 🙌 Contributors

<table style="border:1px solid #404040;text-align:center;width:100%">
<tr><td style="width:14.29%;border:1px solid #404040;">
        <a href="https://github.com/sh-himanshu" spellcheck="false">
          <img src="https://avatars.githubusercontent.com/u/88159798?v=4?s=100" width="100px;" alt="sh-himanshu"/>
          <br />
          <b>sh-himanshu</b>
        </a>
        <br />
        <a href="https://github.com/sh-himanshu/fired-up-pizza/commits?author=sh-himanshu" title="Contributions" spellcheck="false">
          2 contributions
        </a>
      </td></table>

## 📄 License

[**Add Your License**](https://choosealicense.com)
