## NextJS

[**NEXTJS LEARN DOCS**](https://nextjs.org/learn/excel/typescript)

> To run dev use: 
`npm run dev`

> To build use: 
`npm run build`

The best way to deploy your web app is as a static HTML app, if that's possible. With a static app, you can use a fast and efficient web server like NGINX or a cost-effective static hosting service like ZEIT now or GitHub pages.

But not every app can be deployed as a static app. If your app needs to generate dynamic pages at the runtime, you can't deploy it as a static app.

If you can categorize your app as a static app, you can build it with Next.js. Next.js 3.0 comes with a feature that allows you to export an app into a set of HTML pages.

> To export HTML content on a directory called 'out' use
`npm run export`

> To test the exported app, install this NPM module globally:
`npm install -g serve`

> Then go to 'out' and use:
`serve -p 8080`

ZEIT Now is the most simple and scalable way to deploy your application to production:

> `npm install -g now`

> Then, run the following command in the root directory of your app:
`now`
