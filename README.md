# Lucra Content Ops Starter

## Develop with Netlify Visual Editor Locally

[![Netlify Status](https://api.netlify.com/api/v1/badges/3cbc77aa-a173-45ae-bb86-b0e5fe300134/deploy-status)](https://app.netlify.com/sites/lucrabudgeting/deploys)

The typical development process is to begin by working locally. Clone this repository, then run `npm install` in its root directory.

Run the Next.js development server:

```txt
npm run dev
```

Install the [Netlify Visual Editor CLI](https://www.npmjs.com/package/@stackbit/cli). Then open a new terminal window in the same project directory and run the Netlify visual editor dev server:

```txt
npm install -g @stackbit/cli
npm run editor
```

This outputs your own Netlify visual editor URL. Open this, register, or sign in, and you will be directed to Netlify's visual editor for your new project.

![Next.js Dev + Visual Editor Dev](https://assets.stackbit.com/docs/next-dev-stackbit-dev.png)

## Building for production

To build a static site for production, run the following command

```shell
npm run build
```

## Next Steps

Here are a few suggestions on what to do next if you're new to Netlify visual editor:

- Learn [how Netlify visual editor works](https://docs.netlify.com/create/concepts/how-create-works/)
- Check [Netlify visual editor reference documentation](https://visual-editor-reference.netlify.com/)

## Support

If you get stuck along the way, get help in our [support forums](https://answers.netlify.com/).
