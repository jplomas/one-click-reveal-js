# one-click-reveal-js

Netlify '1-click' deploy: [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/jplomas/one-click-reveal-js)
Vercel '1-click' deploy: [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fjplomas%2Fone-click-reveal-js&output-directory=build%2F)

## Use

Click one of the buttons above!  A free-tier [Netlify](https://netlify.com) or [Vercel](https://vercel.com/) account is all you need to deploy a reveal.js site in under 60 seconds 🚀

## Editing

Look in ``src/index.html`` in the repository cloned during the deploy.  Committing changes to this file will re-deploy your site.

The actual slides are all [Markdown](https://www.markdownguide.org/basic-syntax/).

Change the theme by adjusting the variables in ``src/styles.scss``

## Demo

Demo deploy at [https://musical-baklava-399414.netlify.app/](https://musical-baklava-399414.netlify.app/)

## Advanced use

```npm run serve```

-> runs a dev server, defaulting to [http://localhost:1234](http://localhost:1234)

```npm run build```

-> builds a build/ folder to deploy at your hosting service of choice.
