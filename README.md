## NextJS Interview Questions & Answers

:rocket: This repository aimed to contains 500 nextjs interview questions & answers with exmample.

---

<!-- Group Start -->

### Groups

|  No | Contents                      |
| --: | ----------------------------- |
|   1 | [Common](#common)             |
|   2 | [Pages Router](#pages-router) |
|   3 | [App Router](#app-router)     |
|   4 | [Others](#others)             |

<!-- Group End -->

---

<!-- TOC Start -->

### Table of Contents

|  No | Contents                                                                                                                                                            |
| --: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | [What is NextJS](#what-is-nextjs)                                                                                                                                   |
|   2 | [How do you create a new Next.js project?](#how-do-you-create-a-new-nextjs-project)                                                                                 |
|   3 | [What is the purpose of the `pages or app` directory in Next.js?](#what-is-the-purpose-of-the-pages-or-app-directory-in-nextjs)                                     |
|   4 | [What is file based routing in Next.js?](#what-is-file-based-routing-in-nextjs)                                                                                     |
|   5 | [What do you create route at pages based routing in Next.js?](#what-do-you-create-route-at-pages-based-routing-in-nextjs)                                           |
|   7 | [How do you create a dynamic route in Next.js?](#how-do-you-create-a-dynamic-route-in-nextjs)                                                                       |
|   8 | [What are the key features of Next.js?](#what-are-the-key-features-of-nextjs)                                                                                       |
|   9 | [What are the Differences Between Next.js and React.js](#what-are-the-differences-between-nextjs-and-reactjs)                                                       |
|  10 | [What is getStaticProps?](#what-is-getstaticprops)                                                                                                                  |
|  11 | [What is getServerSideProps?](#what-is-getserversideprops)                                                                                                          |
|  12 | [What is getStaticPaths?](#what-is-getstaticpaths)                                                                                                                  |
|  13 | [What is the difference between getStaticProps and getServerSideProps?](#what-is-the-difference-between-getstaticprops-and-getserversideprops)                      |
|  14 | [What is the Link component in Next.js?](#what-is-the-link-component-in-nextjs)                                                                                     |
|  15 | [What is the useRouter hook in Next.js?](#what-is-the-userouter-hook-in-nextjs)                                                                                     |
|  12 | [How do you navigate programmatically in Next.js?](#how-do-you-navigate-programmatically-in-nextjs)                                                                 |
|  13 | [What is the \_app.js file in Next.js?](#what-is-the-_appjs-file-in-nextjs)                                                                                         |
|  14 | [What is the \_document.js file in Next.js?](#what-is-the-_documentjs-file-in-nextjs)                                                                               |
|  15 | [How do you add global CSS in Next.js?](#how-do-you-add-global-css-in-nextjs)                                                                                       |
|  16 | [How do you add component-level CSS in Next.js?](#how-do-you-add-component-level-css-in-nextjs)                                                                     |
|  17 | [What is static site generation (SSG) in Next.js?](#what-is-static-site-generation-ssg-in-nextjs)                                                                   |
|  18 | [What is middleware?](#what-is-middleware)                                                                                                                          |
|  18 | [What is server-side rendering (SSR) in Next.js?](#what-is-server-side-rendering-ssr-in-nextjs)                                                                     |
|  19 | [What is incremental static regeneration (ISR) in Next.js?](#what-is-incremental-static-regeneration-isr-in-nextjs)                                                 |
|  20 | [What is the Image component in Next.js?](#what-is-the-image-component-in-nextjs)                                                                                   |
|  21 | [What is next.config.js?](#what-is-nextconfigjs)                                                                                                                    |
|  22 | [How do you enable TypeScript in a Next.js project?](#how-do-you-enable-typescript-in-a-nextjs-project)                                                             |
|  23 | [What is API Routes in Next.js?](#what-is-api-routes-in-nextjs)                                                                                                     |
|  24 | [How do you deploy a Next.js app to Vercel?](#how-do-you-deploy-a-nextjs-app-to-vercel)                                                                             |
|  25 | [What is pre-rendering in Next.js?](#what-is-pre-rendering-in-nextjs)                                                                                               |
|  26 | [What is the difference between static generation and server-side rendering?](#what-is-the-difference-between-static-generation-and-server-side-rendering)          |
|  27 | [How do you handle redirects in Next.js?](#how-do-you-handle-redirects-in-nextjs)                                                                                   |
|  28 | [What is the Head component in Next.js?](#what-is-the-head-component-in-nextjs)                                                                                     |
|  29 | [How do you fetch data in a Next.js page?](#how-do-you-fetch-data-in-a-nextjs-page)                                                                                 |
|  30 | [What is dynamic import in Next.js?](#what-is-dynamic-import-in-nextjs)                                                                                             |
|  31 | [How do you handle environment variables in Next.js?](#how-do-you-handle-environment-variables-in-nextjs)                                                           |
|  32 | [What is fallback in getStaticPaths?](#what-is-fallback-in-getstaticpaths)                                                                                          |
|  33 | [What is a custom server in Next.js?](#what-is-a-custom-server-in-nextjs)                                                                                           |
|  34 | [What is the next/head package used for?](#what-is-the-nexthead-package-used-for)                                                                                   |
|  35 | [How do you create a 404 page in Next.js?](#how-do-you-create-a-404-page-in-nextjs)                                                                                 |
|  36 | [What is the use of next export command?](#what-is-the-use-of-next-export-command)                                                                                  |
|  37 | [How do you optimize fonts in Next.js?](#how-do-you-optimize-fonts-in-nextjs)                                                                                       |
|  38 | [What is the default port for a Next.js app?](#what-is-the-default-port-for-a-nextjs-app)                                                                           |
|  39 | [How do you add custom headers in Next.js?](#how-do-you-add-custom-headers-in-nextjs)                                                                               |
|  40 | [What is Fast Refresh in Next.js?](#what-is-fast-refresh-in-nextjs)                                                                                                 |
|  41 | [What is the public folder in Next.js?](#what-is-the-public-folder-in-nextjs)                                                                                       |
|  42 | [How do you configure a custom Babel setup in Next.js?](#how-do-you-configure-a-custom-babel-setup-in-nextjs)                                                       |
|  43 | [How do you handle internationalization (i18n) in Next.js?](#how-do-you-handle-internationalization-i18n-in-nextjs)                                                 |
|  44 | [What is React Strict Mode in Next.js?](#what-is-react-strict-mode-in-nextjs)                                                                                       |
|  45 | [What is a singleton router in Next.js?](#what-is-a-singleton-router-in-nextjs)                                                                                     |
|  46 | [What is the useTranslation hook in Next.js?](#what-is-the-usetranslation-hook-in-nextjs)                                                                           |
|  47 | [How do you create custom error pages in Next.js?](#how-do-you-create-custom-error-pages-in-nextjs)                                                                 |
|  48 | [What is AMP in Next.js?](#what-is-amp-in-nextjs)                                                                                                                   |
|  49 | [How do you enable AMP in Next.js?](#how-do-you-enable-amp-in-nextjs)                                                                                               |
|  50 | [What is the next/image component used for?](#what-is-the-nextimage-component-used-for)                                                                             |
|  51 | [What is the next/link component used for?](#what-is-the-nextlink-component-used-for)                                                                               |
|  52 | [What is the difference between pages and components directories?](#what-is-the-difference-between-pages-and-components-directories)                                |
|  53 | [How do you handle middleware in Next.js?](#how-do-you-handle-middleware-in-nextjs)                                                                                 |
|  54 | [How do you add polyfills in Next.js?](#how-do-you-add-polyfills-in-nextjs)                                                                                         |
|  55 | [What is the difference between client-side and server-side rendering in Next.js?](#what-is-the-difference-between-client-side-and-server-side-rendering-in-nextjs) |
|  56 | [What is static optimization in Next.js?](#what-is-static-optimization-in-nextjs)                                                                                   |
|  57 | [How do you fetch data on the client-side in Next.js?](#how-do-you-fetch-data-on-the-client-side-in-nextjs)                                                         |
|  58 | [How do you implement authentication in Next.js?](#how-do-you-implement-authentication-in-nextjs)                                                                   |
|  59 | [What is the difference between \_app.js and \_document.js?](#what-is-the-difference-between-_appjs-and-_documentjs)                                                |
|  60 | [How do you create API endpoints in Next.js?](#how-do-you-create-api-endpoints-in-nextjs)                                                                           |
|  61 | [What is ISR in Next.js?](#what-is-isr-in-nextjs)                                                                                                                   |
|  62 | [How do you configure Webpack in Next.js?](#how-do-you-configure-webpack-in-nextjs)                                                                                 |
|  63 | [What is the purpose of next-env.d.ts?](#what-is-the-purpose-of-next-envdts)                                                                                        |
|  64 | [How do you handle routing in a Next.js app?](#how-do-you-handle-routing-in-a-nextjs-app)                                                                           |
|  65 | [What is the purpose of next/dynamic?](#what-is-the-purpose-of-nextdynamic)                                                                                         |
|  66 | [How do you add meta tags in Next.js?](#how-do-you-add-meta-tags-in-nextjs)                                                                                         |
|  67 | [What is the purpose of next-compose-plugins?](#what-is-the-purpose-of-next-compose-plugins)                                                                        |
|  68 | [How do you handle form submissions in Next.js?](#how-do-you-handle-form-submissions-in-nextjs)                                                                     |
|  69 | [How do you set up Redux in a Next.js project?](#how-do-you-set-up-redux-in-a-nextjs-project)                                                                       |
|  70 | [What is the purpose of next/router?](#what-is-the-purpose-of-nextrouter)                                                                                           |
|  71 | [How do you use CSS-in-JS with Next.js?](#how-do-you-use-css-in-js-with-nextjs)                                                                                     |
|  72 | [How do you handle redirects in Next.js?](#how-do-you-handle-redirects-in-nextjs-1)                                                                                 |
|  73 | [How do you use Sass in a Next.js project?](#how-do-you-use-sass-in-a-nextjs-project)                                                                               |
|  74 | [What is the basePath option in Next.js?](#what-is-the-basepath-option-in-nextjs)                                                                                   |
|  75 | [How do you customize the 500 error page in Next.js?](#how-do-you-customize-the-500-error-page-in-nextjs)                                                           |
|  76 | [What is the trailingSlash option in Next.js?](#what-is-the-trailingslash-option-in-nextjs)                                                                         |
|  77 | [What is the difference between push and replace in useRouter?](#what-is-the-difference-between-push-and-replace-in-userouter)                                      |
|  78 | [What is ssr: false in dynamic import?](#what-is-ssr-false-in-dynamic-import)                                                                                       |
|  79 | [How do you configure PWA in Next.js?](#how-do-you-configure-pwa-in-nextjs)                                                                                         |
|  80 | [How do you add Google Analytics to a Next.js project?](#how-do-you-add-google-analytics-to-a-nextjs-project)                                                       |
|  81 | [What is the purpose of middleware in Next.js?](#what-is-the-purpose-of-middleware-in-nextjs)                                                                       |
|  82 | [How do you use Apollo Client with Next.js?](#how-do-you-use-apollo-client-with-nextjs)                                                                             |
|  83 | [What is the publicRuntimeConfig in Next.js?](#what-is-the-publicruntimeconfig-in-nextjs)                                                                           |
|  84 | [What is the serverRuntimeConfig in Next.js?](#what-is-the-serverruntimeconfig-in-nextjs)                                                                           |
|  85 | [What is the purpose of \_error.js in Next.js?](#what-is-the-purpose-of-_errorjs-in-nextjs)                                                                         |
|  86 | [How do you perform client-side data fetching in Next.js?](#how-do-you-perform-client-side-data-fetching-in-nextjs)                                                 |
|  87 | [What is the use of next-seo in Next.js?](#what-is-the-use-of-next-seo-in-nextjs)                                                                                   |
|  88 | [How do you use Tailwind CSS in Next.js?](#how-do-you-use-tailwind-css-in-nextjs)                                                                                   |
|  89 | [How do you configure next-i18next in Next.js?](#how-do-you-configure-next-i18next-in-nextjs)                                                                       |
|  90 | [What is next/script used for?](#what-is-nextscript-used-for)                                                                                                       |
|  91 | [How do you enable custom fonts in Next.js?](#how-do-you-enable-custom-fonts-in-nextjs)                                                                             |
|  92 | [How do you set up GraphQL in Next.js?](#how-do-you-set-up-graphql-in-nextjs)                                                                                       |
|  93 | [What is swcMinify in next.config.js?](#what-is-swcminify-in-nextconfigjs)                                                                                          |
|  94 | [What is the use of next-compose-plugins?](#what-is-the-use-of-next-compose-plugins)                                                                                |
|  95 | [What is a hybrid application in Next.js?](#what-is-a-hybrid-application-in-nextjs)                                                                                 |
|  96 | [How do you handle CORS in Next.js API routes?](#how-do-you-handle-cors-in-nextjs-api-routes)                                                                       |
|  97 | [What is the purpose of rewrites in next.config.js?](#what-is-the-purpose-of-rewrites-in-nextconfigjs)                                                              |
|  98 | [How do you manage cookies in Next.js?](#how-do-you-manage-cookies-in-nextjs)                                                                                       |
|  99 | [How do you handle authentication tokens in Next.js?](#how-do-you-handle-authentication-tokens-in-nextjs)                                                           |
| 100 | [What is next-pwa used for?](#what-is-next-pwa-used-for)                                                                                                            |
| 101 | [What is the next-sitemap package used for?](#what-is-the-next-sitemap-package-used-for)                                                                            |

<!-- TOC End -->

---

<!-- Question & Answers Start -->

### [Common](#common)

[:arrow_up: Back to Top](#groups)

1. ### What is NextJS?

   Next.js is a React framework for building full-stack web applications.

   [:arrow_up: Back to Top](#table-of-contents)

2. ### How do you create a new Next.js project?

   Using command

   > npx create-next-app@latest

   [:arrow_up: Back to Top](#table-of-contents)

3. ### What is the purpose of the `pages or app` directory in Next.js?

   It contains React components that are automatically routed based on their file name.

   [:arrow_up: Back to Top](#table-of-contents)

4. ### What is file based routing in Next.js?

   Routing based on the file structure in the `pages or app` directory.

   [:arrow_up: Back to Top](#table-of-contents)

5. ### What are the key features of Next.js?

   - Server Side Rendering (SSR): Next.js allows rendering React components on the server before sending them to the client, improving performance and SEO.
   - Static Site Generation (SSG): It pre-renders pages at build time, useful for blogs or e-commerce sites.
   - API Routes: You can build a backend using API routes in the same codebase without needing an external server.
   - File Based Routing: Next.js automatically creates routes based on the file structure inside the pages directory.
   - Client Side Rendering (CSR): Like React, Next.js also supports traditional client-side rendering.
   - Incremental Side Rendering:
   - Image Optimization: Built-in image optimization capabilities that reduce image sizes and enhance loading times.
   - Automatic Code Splitting: Next.js splits the code into smaller bundles, which are loaded only when required, improving performance.
   - TypeScript Support: Native support for TypeScript, enabling strict typing and better developer experience.
   - Incremental Static Regeneration (ISR): Pages can be statically generated at runtime and updated incrementally.
   - Fast Refresh: Provides an instant feedback loop while coding, similar to React's hot reloading.

   [:arrow_up: Back to Top](#table-of-contents)

6. ### What are the Differences Between Next.js and React.js?

   | Feature            | Next.js                                                                                                         | React.js                                                                                               |
   | ------------------ | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
   | Rendering          | Supports Server-Side Rendering (SSR), Static Site Generation (SSG), and Client-Side Rendering (CSR).            | Only supports Client-Side Rendering (CSR) by default.                                                  |
   | Routing            | Built-in file-based routing system. Automatically generates routes based on the folder structure.               | No built-in routing. Requires libraries like React Router.                                             |
   | SEO                | Excellent for SEO as it supports SSR and SSG, allowing pre-rendered content to be indexed by search engines.    | Limited SEO capabilities due to client-side rendering. Additional work is needed for SEO optimization. |
   | Performance        | Faster initial page load due to SSR, automatic code splitting, and static generation.                           | May have slower page loads for large apps since everything is rendered on the client.                  |
   | Configuration      | Minimal configuration required. Comes with SSR, SSG, and routing out of the box.                                | Requires manual setup for SSR, routing, and other advanced features.                                   |
   | Learning Curve     | Slightly steeper due to built-in advanced features like SSR, SSG, and API routes.                               | Easier to learn initially, but requires additional tools for SSR and routing.                          |
   | API Routes         | Built-in API routes that can handle backend logic within the same project.                                      | No support for API routes; requires external tools for backend development.                            |
   | Code Splitting     | Automatically splits code into smaller bundles, loading only what’s needed for a specific page.                 | Requires manual code splitting or use of lazy loading to optimize performance.                         |
   | Deployment         | Optimized for easy deployment on platforms like Vercel (creators of Next.js) and supports serverless functions. | Deployment typically requires additional configuration for optimized hosting and SSR.                  |
   | Image Optimization | Has a built-in Image component for automatic image resizing and optimization.                                   | Does not provide image optimization; developers need third-party libraries for that.                   |

   [:arrow_up: Back to Top](#table-of-contents)

7. ### What is Incremental Side Rendering?

   Incremental Static Regeneration is a technique in Next.js that allows you to update static pages at runtime without rebuilding the entire site.
   This feature introduces a seamless way to serve both static and dynamic content by revalidating and regenerating pages in the background.

   [:arrow_up: Back to Top](#table-of-contents)

8. ### What is the Link component in Next.js?

   A component for client side navigation between pages.

   ```jsx
   import Link from 'next/link'

   <Link href="/">Home</Link>
   <Link href="/about">About</Link>
   ```

   [:arrow_up: Back to Top](#table-of-contents)

9. ### What is the useRouter hook in Next.js?

   A hook that allows access to the router object and perform navigation. The `useRouter` hook allows you to programmatically change routes inside **client** components.

   [:arrow_up: Back to Top](#table-of-contents)

10. ### How do you navigate programmatically in Next.js?

    Using useRouter() hook.

    ```jsx
    const router = userRouter();

    function handleClick() {
      router.push(`/path`);
    }

    <button onClick={handleClick}>Go There</button>;
    ```

    ```jsx
    router.push(href: string, { scroll: boolean })
    ```

    [:arrow_up: Back to Top](#table-of-contents)

11. ### What is middleware?

    Middleware allows you to run code before a request is completed. Then, based on the incoming request, you can modify the response by rewriting, redirecting, modifying the request or response headers or responding directly.

    ```js
    import { NextResponse } from "next/server";

    // This function can be marked `async` if using `await` inside
    export function middleware(request) {
      return NextResponse.redirect(new URL("/home", request.url));
    }

    // See "Matching Paths" below to learn more
    export const config = {
      matcher: "/about/:path*",
    };
    ```

    [:arrow_up: Back to Top](#table-of-contents)

12. ### How do you add component-level CSS in Next.js?

    Using CSS modules with a `.module.css` file extension.

    ```
    // styles.module.css
    .example {
      color: red;
    }

    // Component.js
    import styles from './styles.module.css';

    export default function Component() {
      return <div className={styles.example}>Hello World!</div>;
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

13. ### What is static site generation (SSG) in Next.js?

    Pre-rendering pages at build time. If a page uses Static Generation, the page HTML is generated at build time.

    ```jsx
    export async function getStaticProps() {
      const res = await fetch("https://api.github.com/repos/vercel/next.js");
      const repo = await res.json();
      return { props: { repo } };
    }

    export default function Page({ repo }) {
      return <p>{repo.stargazers_count} Stars</p>;
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

14. ### What is server side rendering (SSR) in Next.js?

    Rendering pages on each request. If a page uses Server-side Rendering, the page HTML is generated on each request.

    ```jsx
    export async function getServerSideProps() {
      const res = await fetch("https://api.github.com/repos/vercel/next.js");
      const repo = await res.json();
      return { props: { repo } };
    }

    export default function Page({ repo }) {
      return <p>{repo.stargazers_count} Stars</p>;
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

15. ### What is incremental static regeneration (ISR) in Next.js?

    Re-generating static pages at runtime as traffic comes in.

    ```jsx
    export async function getStaticProps() {
      const res = await fetch("https://api.github.com/repos/vercel/next.js");
      const repo = await res.json();
      return { props: { repo }, revalidate: 1 };
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

16. ### What is the Image component in Next.js?

    A component that optimizes images for faster loading.

    ```jsx
    export default function Page() {
      return (
        <Image
          src={profilePic}
          alt="Picture of the author"
          // width={500} automatically provided
          // height={500} automatically provided
          // blurDataURL="data:..." automatically provided
          // placeholder="blur" // Optional blur-up while loading
        />
      );
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

17. ### What is next.config.js?

    A configuration file to customize Next.js settings.

    ```ts
    // @ts-check

    /** @type {import('next').NextConfig} */
    const nextConfig = {
      /* config options here */
    };

    module.exports = nextConfig;
    ```

    [:arrow_up: Back to Top](#table-of-contents)

18. ### How do you enable TypeScript in a Next.js project?

    By adding a tsconfig.json file.

    [:arrow_up: Back to Top](#table-of-contents)

19. ### What is API Routes in Next.js?

    A feature to create API endpoints in the `pages/api` or `app/api` directory. It allow you to create custom request handlers for a given route using the Web Request and Response APIs.

    [:arrow_up: Back to Top](#table-of-contents)

20. ### How do you deploy a Next.js app to Vercel?

    By connecting the git/github repository to Vercel and deploying it.

    [:arrow_up: Back to Top](#table-of-contents)

21. ### What is pre-rendering in Next.js?

    Generating HTML for pages in advance, instead of on each request.

    ```jsx
    export async function getStaticProps() {
      const res = await fetch("https://api.github.com/repos/vercel/next.js");
      const repo = await res.json();
      return { props: { repo } };
    }

    export default function Page({ repo }) {
      return <p>{repo.stargazers_count} Stars</p>;
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

22. ### What is the difference between static site generation and server side rendering?

    Static site generation (SSG) pre-renders at build time, server side rendering (SSR) pre-renders on each request.

    [:arrow_up: Back to Top](#table-of-contents)

23. ### How do you handle redirects in Next.js?

    There are a few ways you can handle redirects in Next.js. One of them is by configuring redirects in next.config.js.

    ```js
    module.exports = {
      async redirects() {
        return [
          {
            source: "/about",
            destination: "/about-us",
            permanent: true,
          },
        ];
      },
    };
    ```

    [:arrow_up: Back to Top](#table-of-contents)

24. ### What is the Head component in Next.js?

    A component for modifying the of a page.

    ```
    import Head from 'next/head'

    <Head>
      <title>My page title</title>
      <meta name="viewport" content="initial-scale=1.0, width=device-width" />
    </Head>
    ```

    [:arrow_up: Back to Top](#table-of-contents)

25. ### What is the public folder in Next.js?

    A folder for static assets to be served from the root URL.

    ```
    public/
    ├── favicon.ico
    |── robots.txt
    |── images/
    |   └── profile.jpg
    ```

    [:arrow_up: Back to Top](#table-of-contents)

26. ### How do you fetch data in a Next.js page?

    Using getStaticProps or getServerSideProps in server side.

    ```jsx
    // getStaticProps
    export async function getStaticProps() {
      const res = await fetch("https://api.github.com/repos/vercel/next.js");
      const repo = await res.json();
      return { props: { repo } };
    }

    export default function Page({ repo }) {
      return repo.stargazers_count;
    }
    ```

    ```jsx
    // getServerSideProps
    export async function getServerSideProps() {
      // Fetch data from external API
      const res = await fetch("https://api.github.com/repos/vercel/next.js");
      const repo = await res.json();
      // Pass data to the page via props
      return { props: { repo } };
    }

    export default function Page({ repo }) {
      return (
        <main>
          <p>{repo.stargazers_count}</p>
        </main>
      );
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

27. ### What is dynamic import in Next.js?

    A feature to load components or modules dynamically.

    ```jsx
    const ComponentA = dynamic(() => import("../components/A"));
    const ComponentB = dynamic(() => import("../components/B"));
    ```

    [:arrow_up: Back to Top](#table-of-contents)

28. ### How do you handle environment variables in Next.js?

    By adding them to .env.local and accessing via process.env.

    [:arrow_up: Back to Top](#table-of-contents)

29. ### What is fallback in getStaticPaths?

    Determines how to handle missing paths, with true, false, or ‘blocking’.

    [:arrow_up: Back to Top](#table-of-contents)

30. ### What is a custom server in Next.js?

    A way to customize the server-side behavior, e.g., with Express.

    ```js
    import { createServer } from "http";
    import { parse } from "url";
    import next from "next";

    const port = parseInt(process.env.PORT || "3000", 10);
    const dev = process.env.NODE_ENV !== "production";
    const app = next({ dev });
    const handle = app.getRequestHandler();

    app.prepare().then(() => {
      createServer((req, res) => {
        const parsedUrl = parse(req.url, true);
        handle(req, res, parsedUrl);
      }).listen(port);

      console.log(
        `> Server listening at http://localhost:${port} as ${
          dev ? "development" : process.env.NODE_ENV
        }`
      );
    });
    ```

    [:arrow_up: Back to Top](#table-of-contents)

31. ### What is the next/head package used for?

    To manage the document head for meta tags, title,description, og etc.

    [:arrow_up: Back to Top](#table-of-contents)

32. ### What is the use of next export command?

    To export a static version of the Next.js app.

    [:arrow_up: Back to Top](#table-of-contents)

33. ### How do you optimize fonts in Next.js?

    By using the built-in font optimization feature.

    [:arrow_up: Back to Top](#table-of-contents)

34. ### What is the default port for a Next.js app?

    Port 3000.

    [:arrow_up: Back to Top](#table-of-contents)

35. ### How do you add custom headers in Next.js?

    By configuring headers in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

36. ### What is Fast Refresh in Next.js?

    A feature for quick feedback when editing React components.

    [:arrow_up: Back to Top](#table-of-contents)

37. ### How do you configure a custom Babel setup in Next.js?

    By adding a babel.config.js file.

    [:arrow_up: Back to Top](#table-of-contents)

38. ### How do you handle internationalization (i18n) in Next.js?

    By configuring i18n settings in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

39. ### What is React Strict Mode in Next.js?

    A development mode only feature for highlighting potential problems in an application. It helps to identify unsafe lifecycles, legacy API usage, and a number of other features.

    ```js
    module.exports = {
      reactStrictMode: true,
    };
    ```

    **Note**: Since Next.js 13.5.1, Strict Mode is true by default with app router, so the above configuration is only necessary for pages. You can still disable Strict Mode by setting `reactStrictMode: false`.

    [:arrow_up: Back to Top](#table-of-contents)

40. ### What is a singleton router in Next.js?

    A single router instance accessible across the application.

    [:arrow_up: Back to Top](#table-of-contents)

41. ### How do you perform client-side data fetching in Next.js?

    Using `useEffect` and fetch or any other data fetching library like `axios`,`fetch` or `swr` by Next.js team.

    [:arrow_up: Back to Top](#table-of-contents)

42. ### What is the use of next-seo in Next.js?

    To manage SEO metadata in a Next.js application.

    [:arrow_up: Back to Top](#table-of-contents)

43. ### How do you use Tailwind CSS in Next.js?

    By installing tailwindcss and configuring it with PostCSS.

    [:arrow_up: Back to Top](#table-of-contents)

44. ### How do you configure next-i18next in Next.js?

    By installing next-i18next and setting up the configuration in next.config. js.

    [:arrow_up: Back to Top](#table-of-contents)

45. ### What is next/script used for?

    To optimize loading third-party scripts.

    ```jsx
    import Script from "next/script";

    export default function Dashboard() {
      return (
        <>
          <Script src="https://example.com/script.js" />
        </>
      );
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

46. ### How do you enable custom fonts in Next.js?

    By using the next/font package or including fonts in the public directory.

    ```jsx
    import localFont from "next/font/local";

    // Font files can be colocated inside of `app`
    const myFont = localFont({
      src: "./my-font.woff2",
      display: "swap",
    });

    export default function RootLayout({ children }) {
      return (
        <html lang="en" className={myFont.className}>
          <body>{children}</body>
        </html>
      );
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

47. ### How do you set up GraphQL in Next.js?

    By using Apollo Client or another GraphQL client.

    [:arrow_up: Back to Top](#table-of-contents)

48. ### What is swcMinify in next.config.js?

    It enables the use of the SWC compiler for minification.

    [:arrow_up: Back to Top](#table-of-contents)

49. ### What is the use of next-compose-plugins?

    To enable composition of multiple plugins in Next.js configuration.

    [:arrow_up: Back to Top](#table-of-contents)

50. ### What is a hybrid application in Next.js?

    An application that uses both static generation and server side rendering.

    [:arrow_up: Back to Top](#table-of-contents)

51. ### What is the trailingSlash option in Next.js?

    It configures whether to include a trailing slash in the URLs.

    ```js
    module.exports = {
      trailingSlash: true,
    };
    ```

    [:arrow_up: Back to Top](#table-of-contents)

52. ### What is the difference between push and replace in useRouter?

    `push` adds a new entry in the history stack, `replace` replaces the current entry.

    [:arrow_up: Back to Top](#table-of-contents)

53. ### What is `ssr: false` in dynamic import?

    It disabled server-side rendering for the dynamically imported component.

    ```jsx
    const ComponentC = dynamic(() => import("../components/C"), { ssr: false });
    ```

    **Note**: ssr: false option will only work for client components, move it into client components ensure the client code-splitting working properly.

    [:arrow_up: Back to Top](#table-of-contents)

54. ### How do you configure PWA in Next.js?

    By using plugins like next-pwa and configuring next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

55. ### How do you add Google Analytics to a Next.js project?

    By including the Google Analytics script in \_app.js or \_document.js.

    ```jsx
    import { GoogleAnalytics } from "@next/third-parties/google";

    export default function RootLayout({ children }) {
      return (
        <html lang="en">
          <body>{children}</body>
          <GoogleAnalytics gaId="G-XYZ" />
        </html>
      );
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

56. ### What is the purpose of middleware in Next.js?

    To run code before a request is completed.

    [:arrow_up: Back to Top](#table-of-contents)

57. ### How do you use Apollo Client with Next.js?

    By setting up Apollo Provider in \_app.js and creating a client.

    [:arrow_up: Back to Top](#table-of-contents)

58. ### What is the publicRuntimeConfig in Next.js?

    Configuration exposed to the browser.

    [:arrow_up: Back to Top](#table-of-contents)

### Pages Router

[:arrow_up: Back to Top](#groups)

1. ### What do you create route at pages based routing in Next.js?

   Create a directory into pages directory & create index file.

   ```
        pages/index.jsx // /

        pages/blog/index.jsx // /blog



   ```

   [:arrow_up: Back to Top](#table-of-contents)

2. ### How do you create a dynamic route in Next.js?

   By using square brackets in the filename

   ```
        pages/blogs/[id].js.pages // /blogs/1, /blogs/2, /blogs/...

        blogs/[id]/index.js // /blogs/1, /blogs/2, /blogs/...

        app/products[id]/page.jsx // /products/1, /products/2, /products/...

        pages/[...products]/index.js // (products/1, products/2, products/...)

        pages/[[...products]]/index.js // (products, products/1, products/2, products/...)
   ```

   [:arrow_up: Back to Top](#table-of-contents)

3. ### What is the \_app.js file in Next.js?

   A custom App component that initializes pages and can add global styles or layout components.

   [:arrow_up: Back to Top](#table-of-contents)

4. ### What is the \_document.js file in Next.js?

   A custom Document component that allows customization of the HTML document structure.

   [:arrow_up: Back to Top](#table-of-contents)

5. ### How do you create a 404 page in Next.js?

   By adding a 404.js file in the pages directory.

   [:arrow_up: Back to Top](#table-of-contents)

6. ### What is the difference between getStaticProps and getServerSideProps?

   getStaticProps fetches data at build time, while getServerSideProps fetches data on each request.

   [:arrow_up: Back to Top](#table-of-contents)

7. ### What is getStaticProps?

   A function used for static site generation to fetch data at build time.

   ```jsx
   export async function getStaticProps() {
     const res = await fetch("https://api.github.com/repos/vercel/next.js");
     const repo = await res.json();
     return { props: { repo } };
   }

   export default function Page({ repo }) {
     return repo.stargazers_count;
   }
   ```

   [:arrow_up: Back to Top](#table-of-contents)

8. ### What is getServerSideProps?

   A function used for server-side rendering to fetch data on each request.

   ```jsx
   export async function getServerSideProps() {
     // Fetch data from external API
     const res = await fetch("https://api.github.com/repos/vercel/next.js");
     const repo = await res.json();
     // Pass data to the page via props
     return { props: { repo } };
   }

   export default function Page({ repo }) {
     return (
       <main>
         <p>{repo.stargazers_count}</p>
       </main>
     );
   }
   ```

   [:arrow_up: Back to Top](#table-of-contents)

9. ### What is getStaticPaths?

   A function used with getStaticProps to specify dynamic routes to be pre-rendered.

   ```jsx
   export async function getStaticPaths() {
     return {
       paths: [
         {
           params: {
             name: "next.js",
           },
         },
       ],
     };
   }

   export async function getStaticProps() {
     const res = await fetch("https://api.github.com/repos/vercel/next.js");
     const repo = await res.json();
     return { props: { repo } };
   }

   export default function Page({ repo }) {
     return repo.stargazers_count;
   }
   ```

   [:arrow_up: Back to Top](#table-of-contents)

10. ### How do you add global CSS in Next.js?

    By importing the CSS file in \_app.js.

    [:arrow_up: Back to Top](#table-of-contents)

11. ### What is the useTranslation hook in Next.js?

    A hook for handling translations when using i18n.

    [:arrow_up: Back to Top](#table-of-contents)

12. ### How do you create custom error pages in Next.js?

    By adding \_error.js in the pages directory.

    [:arrow_up: Back to Top](#table-of-contents)

13. ### What is AMP in Next.js?

    Accelerated Mobile Pages, a framework for fast-loading mobile pages.

    [:arrow_up: Back to Top](#table-of-contents)

14. ### How do you enable AMP in Next.js?

    By adding amp attribute to a page component.

    [:arrow_up: Back to Top](#table-of-contents)

15. ### What is the next/image component used for?

    To optimize and serve images in a Next.js application.

    [:arrow_up: Back to Top](#table-of-contents)

16. ### What is the next/link component used for?

    For client-side navigation between pages.

    [:arrow_up: Back to Top](#table-of-contents)

17. ### What is the difference between pages and components directories?

    pages contains routable components, components contains reusable UI components.

    [:arrow_up: Back to Top](#table-of-contents)

18. ### How do you handle middleware in Next.js?

    Using middleware functions in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

19. ### How do you add polyfills in Next.js?

    By customizing the webpack configuration in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

20. ### What is the difference between client-side and server-side rendering in next.js?

    Client-side rendering happens in the browser, server-side rendering happens on the server.

    [:arrow_up: Back to Top](#table-of-contents)

21. ### What is static optimization in Next.js?

    Automatically determining if a page can be statically generated.

    [:arrow_up: Back to Top](#table-of-contents)

22. ### How do you fetch data on the client-side in Next.js?

    Using useEffect and fetch or other data fetching libraries.

    ```jsx
    "use client";

    import { useState, useEffect } from "react";

    export function Posts() {
      const [posts, setPosts] = useState(null);

      useEffect(() => {
        async function fetchPosts() {
          const res = await fetch("https://api.vercel.app/blog");
          const data = await res.json();
          setPosts(data);
        }
        fetchPosts();
      }, []);

      if (!posts) return <div>Loading...</div>;

      return (
        <ul>
          {posts.map((post) => (
            <li key={post.id}>{post.title}</li>
          ))}
        </ul>
      );
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

23. ### How do you implement authentication in Next.js?

    Using libraries like AuthJS, JWT or custom authentication logic.

    [:arrow_up: Back to Top](#table-of-contents)

24. ### What is the difference between \_app.js and \_document.js?

    \_app.js is for global components,

    \_document.js is for modifying the HTML document structure.

    [:arrow_up: Back to Top](#table-of-contents)

25. ### How do you create API endpoints in Next.js?

    By adding files to the `pages/api` or `app/api` directory.

    [:arrow_up: Back to Top](#table-of-contents)

26. ### What is ISR in Next.js?

    Incremental Static Regeneration, updating static pages after build without redeploying.

    [:arrow_up: Back to Top](#table-of-contents)

27. ### How do you configure Webpack in Next.js?

    By extending the Webpack configuration in next.config.js.

    ```js
    module.exports = {
      webpack: (
        config,
        { buildId, dev, isServer, defaultLoaders, nextRuntime, webpack }
      ) => {
        // Important: return the modified config
        return config;
      },
    };
    ```

    [:arrow_up: Back to Top](#table-of-contents)

28. ### What is the purpose of next-env.d.ts?

    It provides type definitions for TypeScript support in Next.js.

    [:arrow_up: Back to Top](#table-of-contents)

29. ### How do you handle routing in a Next.js app?

    Using the file-based routing system in the pages directory.

    [:arrow_up: Back to Top](#table-of-contents)

30. ### What is the purpose of next/dynamic?

    To enable dynamic imports and code splitting.

    ```jsx
    "use client";

    import { useState } from "react";
    import dynamic from "next/dynamic";

    // Client Components:
    const ComponentA = dynamic(() => import("../components/A"));
    const ComponentB = dynamic(() => import("../components/B"));
    const ComponentC = dynamic(() => import("../components/C"), { ssr: false });

    export default function ClientComponentExample() {
      const [showMore, setShowMore] = useState(false);

      return (
        <div>
          {/* Load immediately, but in a separate client bundle */}
          <ComponentA />

          {/* Load on demand, only when/if the condition is met */}
          {showMore && <ComponentB />}
          <button onClick={() => setShowMore(!showMore)}>Toggle</button>

          {/* Load only on the client side */}
          <ComponentC />
        </div>
      );
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

31. ### How do you add meta tags in Next.js?

    Using the Head component from next/head.

    ```jsx
    export const metadata = {
      title: "NextJS",
      description: "A React Framework for building full-stack web applications",
    };

    export default function Page() {}
    ```

    [:arrow_up: Back to Top](#table-of-contents)

32. ### What is the purpose of next-compose-plugins?

    To compose multiple plugins in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

33. ### How do you handle form submissions in Next.js?

    Using client-side form handling or API routes for server-side handling.

    [:arrow_up: Back to Top](#table-of-contents)

34. ### How do you set up Redux in a Next.js project?

    By creating a Redux store and integrating it with \_app.js.

    [:arrow_up: Back to Top](#table-of-contents)

35. ### What is the purpose of next/router?

    To handle routing and navigation within a Next.js app.

    [:arrow_up: Back to Top](#table-of-contents)

36. ### How do you use CSS-in-JS with Next.js?

    Using libraries like styled-components or Emotion.

    [:arrow_up: Back to Top](#table-of-contents)

37. ### How do you use Sass in a Next.js project?

    By installing sass and importing .scss files in your components.

    > next.config.js

    ```js
    import type { NextConfig } from "next";

    const nextConfig: NextConfig = {
      sassOptions: {
        implementation: "sass-embedded",
      },
    };

    export default nextConfig;
    ```

    > app/variables.module.scss

    ```scss
    $primary-color: #64ff00;

    :export {
      primaryColor: $primary-color;
    }
    ```

    > app/page.jsx

    ```jsx
    import variables from "./variables.module.scss";

    export default function Page() {
      return <h1 style={{ color: variables.primaryColor }}>Hello, Next.js!</h1>;
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

38. ### What is the basePath option in Next.js?

    It allows you to specify a base path for the application.

    [:arrow_up: Back to Top](#table-of-contents)

39. ### How do you customize the 500 error page in Next.js?

    By creating a 500.js file in the pages directory.

    ```jsx
    export default function Custom500() {
      return <h1>500 - Server-side error occurred</h1>;
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

40. ### What is the serverRuntimeConfig in Next.js?

    Configuration only available on the server side.

    [:arrow_up: Back to Top](#table-of-contents)

41. ### What is the purpose of \_error.js in Next.js?

    To customize the error page for HTTP errors.

    [:arrow_up: Back to Top](#table-of-contents)

### App Router

[:arrow_up: Back to Top](#groups)

1. ### What do you create route at app based routing in Next.js?

   Create a directory into app directory & create page file.

   ```
       app/page.jsx // /

       app/blog/page.jsx // /blog

   ```

   [:arrow_up: Back to Top](#table-of-contents)

2. ### How do you handle CORS in Next.js API routes?

   By setting headers in the API route handlers.

   [:arrow_up: Back to Top](#table-of-contents)

3. ### What is the purpose of rewrites in next.config.js?

   To map an incoming request path to a different destination path.

   [:arrow_up: Back to Top](#table-of-contents)

4. ### How do you manage cookies in Next.js?

   Using libraries like cookie or js-cookie to set and retrieve cookies.

   [:arrow_up: Back to Top](#table-of-content

5. ### What is next-pwa used for?

   To configure and enable Progressive Web App features in Next.js.

   [:arrow_up: Back to Top](#table-of-contents)

6. ### What is the next-sitemap package used for?

   To generate sitemaps for a Next.js application.

   [:arrow_up: Back to Top](#table-of-contents)

### Others

[:arrow_up: Back to Top](#groups)

<!-- Question & Answers End -->
