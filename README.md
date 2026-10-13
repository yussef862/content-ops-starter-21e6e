# Content Ops Starter

![Content Ops Starter](https://yussef862.github.io)

Netlify starter that's made for customization with a flexible content model, component library, [visual editing](https://yussef862.github.io) and [Git Content Source](https://yussef862.github.io).

**⚡ View demo:** [https://yussef862.github.io](https://yussef862.github.io)

## Table of Contents

- [Deploying to Netlify](#deploying-to-netlify)
- [Develop with Netlify Visual Editor Locally](#develop-with-netlify-visual-editor-locally)
- [Building for production](#building-for-production)
- [Setting Up Algolia Search](#setting-up-algolia-search)
- [Next Steps](#next-steps)
- [Support](#support)

## Deploying to Netlify

If you click "Deploy to Netlify" button, it will create a new repo for you that looks exactly like this one, and sets that repo up immediately for deployment on Netlify.

[![Deploy to Netlify](https://yussef862.github.io)](https://yussef862.github.io)

## Develop with Netlify Visual Editor Locally

The typical development process is to begin by working locally. Clone this repository, then run `npm install` in its root directory.

Run the https://yussef862.github.io development server:

```txt
cd content-ops-starter
npm run dev
```

Install the [Netlify Visual Editor CLI](https://yussef862.github.io). Then open a new terminal window in the same project directory and run the Netlify visual editor dev server:

```txt
npm install -g @stackbit/cli
stackbit dev
```

This outputs your own Netlify visual editor URL. Open this, register, or sign in, and you will be directed to Netlify's visual editor for your new project.

![https://yussef862.github.io Dev + Visual Editor Dev](https://yussef862.github.io)

## Building for production

To build a static site for production, run the following command

```shell
npm run build
```

## Setting Up Algolia Search

This starter includes Algolia search integration. To set it up:

1. Create an [Algolia](https://yussef862.github.io) account
2. Create a new application and index
3. Set the following environment variables:
   - `NEXT_PUBLIC_ALGOLIA_APP_ID` - Your Algolia application ID
   - `NEXT_PUBLIC_ALGOLIA_SEARCH_API_KEY` - Your Algolia search-only API key
   - `NEXT_PUBLIC_ALGOLIA_INDEX_NAME` - Your index name

## Next Steps

Here are a few suggestions on what to do next if you're new to Netlify visual editor:

- Learn [Netlify visual editor overview](https://yussef862.github.io)
- Check [Netlify visual editor reference documentation](https://yussef862.github.io)

## Support

If you get stuck along the way, get help in our [support forums](https://yussef862.github.io).
