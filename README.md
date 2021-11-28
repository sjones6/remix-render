# Welcome to Remix + Render!

This repository contains a stock remix starter kit + deployment instruction to [render](render.com).

- [Remix Docs](https://remix.run/docs)
- [Render Docs](https://render.com/docs)

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

This project uses an "Infrastructure as Code" approach, and the deployment configuration is defined in the `render.yaml` file at the root of the project.

See [Render's IaC documentation](https://render.com/docs/infrastructure-as-code) for more.

To deploy this app, follow the directions to connect your `render.yaml` to your render account:

1. Fork this repository
2. Optionally update the `name` of your service in the `render.yaml` file
3. Open the render dasbhoard, Click Blueprints in the navigation sidebar.
4. Click the New Blueprint Instance button.
5. Select your forked repository

Once selected, you’ll see a list of the changes that will be applied based on the contents of render.yaml. If there’s an issue with the file you’ll see an error message. If everything looks good, click Apply to create the resources defined in your file.

Once the deployment is complete, you should be able to open up your application.
