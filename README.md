# Azure Web App - Node.js Example

This is a basic Node.js app using Express, ready to deploy to Azure Web App.

## Running Locally

```sh
npm install
npm start
```

Visit http://localhost:3000

## Deploying to Azure Web App

1. Push this code to your Azure Web App repository.
2. Azure will automatically run `npm install` and `npm start`.
3. Your app will be available at your Azure Web App URL.

The server listens on the port provided by the `PORT` environment variable, as required by Azure.
