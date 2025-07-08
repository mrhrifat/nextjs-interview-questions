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

|  No | Contents                                                                                                                                                        |
| --: | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | [What is NextJS](#what-is-nextjs)                                                                                                                               |
|   2 | [How do you create a new Next.js project?](#how-do-you-create-a-new-nextjs-project)                                                                             |
|   3 | [What is the purpose of the `pages or app` directory in Next.js?](#what-is-the-purpose-of-the-pages-or-app-directory-in-nextjs)                                 |
|   4 | [What is file based routing in Next.js?](#what-is-file-based-routing-in-nextjs)                                                                                 |
|   5 | [What do you create route at pages based routing in Next.js?](#what-do-you-create-route-at-pages-based-routing-in-nextjs)                                       |
|   6 | [How do you create a dynamic route in Next.js?](#how-do-you-create-a-dynamic-route-in-nextjs)                                                                   |
|   7 | [What are the key features of Next.js?](#what-are-the-key-features-of-nextjs)                                                                                   |
|   8 | [What are the Differences Between Next.js and React.js](#what-are-the-differences-between-nextjs-and-reactjs)                                                   |
|   9 | [What is Incremental Side Rendering?](#what-is-incremental-side-rendering)                                                                                      |
|  10 | [What is getStaticProps?](#what-is-getstaticprops)                                                                                                              |
|  11 | [What is getServerSideProps?](#what-is-getserversideprops)                                                                                                      |
|  12 | [What is getStaticPaths?](#what-is-getstaticpaths)                                                                                                              |
|  13 | [What is the difference between getStaticProps and getServerSideProps?](#what-is-the-difference-between-getstaticprops-and-getserversideprops)                  |
|  14 | [What is the Link component in Next.js?](#what-is-the-link-component-in-nextjs)                                                                                 |
|  15 | [What is the useRouter hook in Next.js?](#what-is-the-userouter-hook-in-nextjs)                                                                                 |
|  16 | [How do you navigate programmatically in Next.js?](#how-do-you-navigate-programmatically-in-nextjs)                                                             |
|  17 | [What is middleware?](#what-is-middleware)                                                                                                                      |
|  18 | [How do you add component-level CSS in Next.js?](#how-do-you-add-component-level-css-in-nextjs)                                                                 |
|  19 | [What is static site generation (SSG) in Next.js?](#what-is-static-site-generation-ssg-in-nextjs)                                                               |
|  20 | [What is server-side rendering (SSR) in Next.js?](#what-is-server-side-rendering-ssr-in-nextjs)                                                                 |
|  21 | [What is incremental static regeneration (ISR) in Next.js?](#what-is-incremental-static-regeneration-isr-in-nextjs)                                             |
|  22 | [What is the Image component in Next.js?](#what-is-the-image-component-in-nextjs)                                                                               |
|  23 | [What is next.config.js?](#what-is-nextconfigjs)                                                                                                                |
|  24 | [How do you enable TypeScript in a Next.js project?](#how-do-you-enable-typescript-in-a-nextjs-project)                                                         |
|  25 | [What is API Routes in Next.js?](#what-is-api-routes-in-nextjs)                                                                                                 |
|  26 | [How do you deploy a Next.js app to Vercel?](#how-do-you-deploy-a-nextjs-app-to-vercel)                                                                         |
|  27 | [What is pre-rendering in Next.js?](#what-is-pre-rendering-in-nextjs)                                                                                           |
|  28 | [How to add authjs in nextjs app router?](#how-to-add-authjs-in-nextjs-app-router)                                                                              |
|  29 | [How to add credentials in nextjs app router?](#how-to-add-credentials-in-nextjs-app-router)                                                                    |
|  30 | [What is the difference between static site generation and server side rendering?](#what-is-the-difference-between-static-generation-and-server-side-rendering) |
|  31 | [How to add sitemap in nextjs app router?](#how-to-add-sitemap-in-nextjs-app-router)                                                                            |
|  32 | [How to consider security in nextjs app router?](#how-to-consider-security-in-nextjs-app-router)                                                                |
|  33 | [How do you handle redirects in Next.js?](#how-do-you-handle-redirects-in-nextjs)                                                                               |
|  34 | [What is use server in Next.js?](#what-is-use-server-in-nextjs)                                                                                                 |
|  35 | [Difference between using & not using use server in Next.js?](#difference-between-using--not-using-use-server-in-nextjs)                                        |
|  36 | [What is the Head component in Next.js?](#what-is-the-head-component-in-nextjs)                                                                                 |
|  37 | [What is the public folder in Next.js?](#what-is-the-public-folder-in-nextjs)                                                                                   |
|  38 | [How do you fetch data in a Next.js page?](#how-do-you-fetch-data-in-a-nextjs-page)                                                                             |
|  39 | [What is dynamic import in Next.js?](#what-is-dynamic-import-in-nextjs)                                                                                         |
|  40 | [How do you handle environment variables in Next.js?](#how-do-you-handle-environment-variables-in-nextjs)                                                       |
|  41 | [What is fallback in getStaticPaths?](#what-is-fallback-in-getstaticpaths)                                                                                      |
|  42 | [What is a custom server in Next.js?](#what-is-a-custom-server-in-nextjs)                                                                                       |
|  43 | [What is the next/head package used for?](#what-is-the-nexthead-package-used-for)                                                                               |
|  44 | [What is the use of next export command?](#what-is-the-use-of-next-export-command)                                                                              |
|  45 | [How do you optimize fonts in Next.js?](#how-do-you-optimize-fonts-in-nextjs)                                                                                   |
|  46 | [What is the default port for a Next.js app?](#what-is-the-default-port-for-a-nextjs-app)                                                                       |
|  47 | [How to change default port for a Next.js app?](#how-to-change-default-port-for-a-nextjs-app)                                                                   |
|  48 | [How do you add custom headers in Next.js?](#how-do-you-add-custom-headers-in-nextjs)                                                                           |
|  49 | [What is Fast Refresh in Next.js?](#what-is-fast-refresh-in-nextjs)                                                                                             |
|  50 | [How do you configure a custom Babel setup in Next.js?](#how-do-you-configure-a-custom-babel-setup-in-nextjs)                                                   |
|  51 | [How do you handle internationalization (i18n) in Next.js?](#how-do-you-handle-internationalization-i18n-in-nextjs)                                             |
|  52 | [What is React Strict Mode in Next.js?](#what-is-react-strict-mode-in-nextjs)                                                                                   |
|  53 | [What is a singleton router in Next.js?](#what-is-a-singleton-router-in-nextjs)                                                                                 |
|  54 | [How do you perform client-side data fetching in Next.js?](#how-do-you-perform-client-side-data-fetching-in-nextjs)                                             |
|  55 | [What is the use of next-seo in Next.js?](#what-is-the-use-of-next-seo-in-nextjs)                                                                               |
|  56 | [How do you use Tailwind CSS in Next.js?](#how-do-you-use-tailwind-css-in-nextjs)                                                                               |
|  57 | [How do you configure next-i18next in Next.js?](#how-do-you-configure-next-i18next-in-nextjs)                                                                   |
|  58 | [What is next/script used for?](#what-is-nextscript-used-for)                                                                                                   |
|  59 | [How do you enable custom fonts in Next.js?](#how-do-you-enable-custom-fonts-in-nextjs)                                                                         |
|  60 | [How do you set up GraphQL in Next.js?](#how-do-you-set-up-graphql-in-nextjs)                                                                                   |
|  61 | [What is swcMinify in next.config.js?](#what-is-swcminify-in-nextconfigjs)                                                                                      |
|  62 | [What is the use of next-compose-plugins?](#what-is-the-use-of-next-compose-plugins)                                                                            |
|  63 | [What is a hybrid application in Next.js?](#what-is-a-hybrid-application-in-nextjs)                                                                             |
|  64 | [What is the trailingSlash option in Next.js?](#what-is-the-trailingslash-option-in-nextjs)                                                                     |
|  65 | [What is the difference between push and replace in useRouter?](#what-is-the-difference-between-push-and-replace-in-userouter)                                  |
|  66 | [What is ssr: false in dynamic import?](#what-is-ssr-false-in-dynamic-import)                                                                                   |
|  67 | [How do you configure PWA in Next.js?](#how-do-you-configure-pwa-in-nextjs)                                                                                     |
|  68 | [How do you add Google Analytics to a Next.js project?](#how-do-you-add-google-analytics-to-a-nextjs-project)                                                   |
|  69 | [What is the purpose of middleware in Next.js?](#what-is-the-purpose-of-middleware-in-nextjs)                                                                   |
|  70 | [How do you use Apollo Client with Next.js?](#how-do-you-use-apollo-client-with-nextjs)                                                                         |
|  71 | [What is the publicRuntimeConfig in Next.js?](#what-is-the-publicruntimeconfig-in-nextjs)                                                                       |
|  72 | [What is the serverRuntimeConfig in Next.js?](#what-is-the-serverruntimeconfig-in-nextjs)                                                                       |
|  73 | [What is the purpose of \_error.js in Next.js?](#what-is-the-purpose-of-_errorjs-in-nextjs)                                                                     |
|  74 | [How do you perform client-side data fetching in Next.js?](#how-do-you-perform-client-side-data-fetching-in-nextjs)                                             |
|  75 | [What is the use of next-seo in Next.js?](#what-is-the-use-of-next-seo-in-nextjs)                                                                               |
|  76 | [How do you use Tailwind CSS in Next.js?](#how-do-you-use-tailwind-css-in-nextjs)                                                                               |
|  77 | [How do you configure next-i18next in Next.js?](#how-do-you-configure-next-i18next-in-nextjs)                                                                   |
|  78 | [What is next/script used for?](#what-is-nextscript-used-for)                                                                                                   |
|  79 | [How do you enable custom fonts in Next.js?](#how-do-you-enable-custom-fonts-in-nextjs)                                                                         |
|  80 | [How do you set up GraphQL in Next.js?](#how-do-you-set-up-graphql-in-nextjs)                                                                                   |
|  81 | [What is swcMinify in next.config.js?](#what-is-swcminify-in-nextconfigjs)                                                                                      |
|  82 | [What is the use of next-compose-plugins?](#what-is-the-use-of-next-compose-plugins)                                                                            |
|  83 | [What is a hybrid application in Next.js?](#what-is-a-hybrid-application-in-nextjs)                                                                             |
|  84 | [How do you handle CORS in Next.js API routes?](#how-do-you-handle-cors-in-nextjs-api-routes)                                                                   |
|  85 | [What is the purpose of rewrites in next.config.js?](#what-is-the-purpose-of-rewrites-in-nextconfigjs)                                                          |
|  86 | [How do you manage cookies in Next.js?](#how-do-you-manage-cookies-in-nextjs)                                                                                   |
|  87 | [How do you handle authentication tokens in Next.js?](#how-do-you-handle-authentication-tokens-in-nextjs)                                                       |
|  88 | [What is next-pwa used for?](#what-is-next-pwa-used-for)                                                                                                        |
|  89 | [What is the next-sitemap package used for?](#what-is-the-next-sitemap-package-used-for)                                                                        |
|  90 | [What is the \_app.js file in Next.js?](#what-is-the-_appjs-file-in-nextjs)                                                                                     |
|  91 | [What is the \_document.js file in Next.js?](#what-is-the-_documentjs-file-in-nextjs)                                                                           |
|  92 | [How do you add global CSS in Next.js?](#how-do-you-add-global-css-in-nextjs)                                                                                   |
|  93 | [What is the useTranslation hook in Next.js?](#what-is-the-usetranslation-hook-in-nextjs)                                                                       |
|  94 | [How do you create custom error pages in Next.js?](#how-do-you-create-custom-error-pages-in-nextjs)                                                             |
|  95 | [What is AMP in Next.js?](#what-is-amp-in-nextjs)                                                                                                               |
|  96 | [How do you enable AMP in Next.js?](#how-do-you-enable-amp-in-nextjs)                                                                                           |
|  97 | [What is the next/image component used for?](#what-is-the-nextimage-component-used-for)                                                                         |
|  98 | [What is the next/link component used for?](#what-is-the-nextlink-component-used-for)                                                                           |
|  99 | [What is the difference between pages and components directories?](#what-is-the-difference-between-pages-and-components-directories)                            |
| 100 | [How do you handle middleware in Next.js?](#how-do-you-handle-middleware-in-nextjs)                                                                             |
| 101 | [How do you add polyfills in Next.js?](#how-do-you-add-polyfills-in-nextjs)                                                                                     |

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
   | Code Splitting     | Automatically splits code into smaller bundles, loading only what's needed for a specific page.                 | Requires manual code splitting or use of lazy loading to optimize performance.                         |
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
   import Link from "next/link";

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

22. ### How to add authjs in nextjs app router?

    To add authjs in nextjs app router, you can use the `next-auth` package. First, install it:

    ```bash
    npm install next-auth
    ```

    Then, create a file named `[...nextauth].js` in the `app/api/auth` directory and configure your authentication providers.

    ```js
    import NextAuth from "next-auth";
    import Providers from "next-auth/providers";

    export default NextAuth({
      providers: [
        Providers.Google({
          clientId: process.env.GOOGLE_CLIENT_ID,
          clientSecret: process.env.GOOGLE_CLIENT_SECRET,
        }),
      ],
      // Add more configuration options as needed
      callbacks: {
        async session(session, user) {
          // Add custom session properties here
          return session;
        },
      },
      pages: {
        signIn: "/auth/signin", // Custom sign-in page
        error: "/auth/error", // Error page
      },
      secret: process.env.NEXTAUTH_SECRET, // Required for JWT encryption
      session: {
        jwt: true, // Use JWT for session management
      },
      jwt: {
        secret: process.env.NEXTAUTH_JWT_SECRET, // Required for JWT encryption
      },
      events: {
        signIn: async (message) => {
          // Custom logic after sign-in
          console.log("User signed in:", message);
        },
      },
      debug: process.env.NODE_ENV === "development", // Enable debug mode in development
      theme: {
        colorScheme: "light", // Change to "dark" for dark mode
        brandColor: "#0000FF", // Custom brand color
        logo: "/logo.png", // Custom logo URL
      },
      pages: {
        signIn: "/auth/signin", // Custom sign-in page
        signOut: "/auth/signout", // Custom sign-out page
        error: "/auth/error", // Error page
        verifyRequest: "/auth/verify-request", // Verification request page
        newUser: null, // Will disable the new account creation screen
      },
    });
    ```

    [:arrow_up: Back to Top](#table-of-contents)

23. ### How to add credentials in nextjs app router?

    To add credentials in Next.js app router, you can use the `next-auth` package with the Credentials provider. First, install it:

    ```bash
    npm install next-auth
    ```

    Then, create a file named `[...nextauth].js` in the `app/api/auth` directory and configure your credentials provider.

    ```js
    import NextAuth from "next-auth";
    import CredentialsProvider from "next-auth/providers/credentials";

    export default NextAuth({
      providers: [
        CredentialsProvider({
          name: "Credentials",
          credentials: {
            username: { label: "Username", type: "text" },
            password: { label: "Password", type: "password" },
          },
          async authorize(credentials) {
            // Add your own logic to validate credentials here
            const user = { id: 1, name: "John Doe" }; // Example user

            if (
              credentials.username === "admin" &&
              credentials.password === "password"
            ) {
              return user; // Return user object if credentials are valid
            } else {
              return null; // Return null if credentials are invalid
            }
          },
        }),
      ],
      pages: {
        signIn: "/auth/signin", // Custom sign-in page
      },
      callbacks: {
        async session(session, user) {
          session.user = user; // Add user object to session
          return session;
        },
      },
      secret: process.env.NEXTAUTH_SECRET, // Required for JWT encryption
      session: {
        jwt: true, // Use JWT for session management
      },
      jwt: {
        secret: process.env.NEXTAUTH_JWT_SECRET, // Required for JWT encryption
      },
    });
    ```

    [:arrow_up: Back to Top](#table-of-contents)

24. ### What is the difference between static site generation and server side rendering?

    Static site generation (SSG) pre-renders at build time, server side rendering (SSR) pre-renders on each request.

    [:arrow_up: Back to Top](#table-of-contents)

25. ### How to add sitemap in nextjs app router?

    To add a sitemap in Next.js app router, you can use the `next-sitemap` package. First, install it:

    ```bash
    npm install next-sitemap
    ```

    Then, create a `next-sitemap.config.js` file in the root of your project and configure your sitemap options.

    ```js
    /** @type {import('next-sitemap').IConfig} */
    module.exports = {
      siteUrl: process.env.SITE_URL || "https://example.com",
      generateRobotsTxt: true, // (optional)
      changefreq: "daily", // (optional)
      priority: 0.7, // (optional)
      sitemapSize: 7000, // (optional)
      exclude: ["/404", "/500"], // (optional)
      robotsTxtOptions: {
        policies: [
          { userAgent: "*", allow: "/" },
          { userAgent: "Googlebot", disallow: "/private" },
        ],
      },
    };
    ```

    Finally, run the following command to generate the sitemap:

    ```bash
    npx next-sitemap
    ```

    This will create a `sitemap.xml` file in the `public` directory of your Next.js app.

    [:arrow_up: Back to Top](#table-of-contents)

26. ### How to consider security in nextjs app router?

    To consider security in Next.js app router, you can follow these best practices:

    - Use HTTPS for all requests to ensure data is encrypted in transit.
    - Implement authentication and authorization to protect sensitive routes.
    - Sanitize user input to prevent XSS attacks.
    - Use environment variables to store sensitive information like API keys.
    - Regularly update dependencies to patch known vulnerabilities.
    - Implement Content Security Policy (CSP) headers to mitigate XSS attacks.
    - Use secure cookies with the `HttpOnly` and `Secure` flags.

    [:arrow_up: Back to Top](#table-of-contents)

27. ### How do you handle redirects in Next.js?

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

28. ### What is use server in Next.js?

    The `use server` directive is used to indicate that a function should be executed on the server side. It allows you to write server-side logic in a component or function that can be called from the client side.

    ```jsx
    "use server";

    export async function myServerFunction() {
      // Server-side logic here
      return "Hello from the server!";
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

29. ### Difference between using & not using use server in Next.js?

    **Using `use server`**: The function is executed on the server side, allowing access to server-side resources and APIs. It can be used to perform operations that require server-side logic, such as database queries or API calls.

    **Not using `use server`**: The function is executed on the client side, meaning it cannot access server-side resources directly. It can only perform operations that are available in the client environment, such as manipulating the DOM or making client-side API calls.

    - **Example with `use server`**:

      ```jsx
      "use server";
      export async function fetchData() {
        const response = await fetch("https://api.example.com/data");
        const data = await response.json();
        return data;
      }
      ```

    - **Example without `use server`**:

      ```jsx
      export async function fetchData() {
        const response = await fetch("https://api.example.com/data");
        const data = await response.json();
        return data;
      }
      ```

    - Example with `use server` In Component:

      ```jsx
        import { fetchData } from "./path/to/your/file";

        export default function MyComponent() {
          const data = await fetchData(); // This will run on the server side
          return <div>{data}</div>;
        }
      ```

    - Example without `use server` In Component:

      ```jsx
      import { fetchData } from "./path/to/your/file";
      export default function MyComponent() {
        const data = fetchData(); // This will run on the client side
        return <div>{data}</div>;
      }
      ```

    [:arrow_up: Back to Top](#table-of-contents)

30. ### What is the Head component in Next.js?

    A component for modifying the of a page.

    ```jsx
    import Head from "next/head";

    <Head>
      <title>My page title</title>
      <meta name="viewport" content="initial-scale=1.0, width=device-width" />
    </Head>;
    ```

    [:arrow_up: Back to Top](#table-of-contents)

31. ### What is the public folder in Next.js?

    A folder for static assets to be served from the root URL.

    ```
    public/
    ├── favicon.ico
    |── robots.txt
    |── images/
    |   └── profile.jpg
    ```

    [:arrow_up: Back to Top](#table-of-contents)

32. ### How do you fetch data in a Next.js page?

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

33. ### What is dynamic import in Next.js?

    A feature to load components or modules dynamically.

    ```jsx
    const ComponentA = dynamic(() => import("../components/A"));
    const ComponentB = dynamic(() => import("../components/B"));
    ```

    [:arrow_up: Back to Top](#table-of-contents)

34. ### How do you handle environment variables in Next.js?

    By adding them to .env.local and accessing via process.env.

    [:arrow_up: Back to Top](#table-of-contents)

35. ### What is fallback in getStaticPaths?

    Determines how to handle missing paths, with true, false, or 'blocking'.

    ```jsx
    export async function getStaticPaths() {
      const paths = await getAllPostIds();
      return {
        paths,
        fallback: true, // this will enable fallback for all paths which are not generated at build time
      };
    }
    ```

    ```jsx
    export async function getStaticPaths() {
      const paths = await getAllPostIds();
      return {
        paths,
        fallback: false, // this will return 404 for all paths which are not generated at build time
      };
    }
    ```

    ```jsx
    export async function getStaticPaths() {
      const paths = await getAllPostIds();
      return {
        paths,
        fallback: "blocking", // this will return a static page for all paths which are not generated at build time
      };
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

36. ### What is a custom server in Next.js?

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

37. ### What is the next/head package used for?

    To manage the document head for meta tags, title,description, og etc.

    ```jsx
    import Head from "next/head";

    export default function Home() {
      return (
        <div>
          <Head>
            <title>My page title</title>
            <meta name="description" content="My description" />
          </Head>
          <h1>Hello World!</h1>
        </div>
      );
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

38. ### What is the use of next export command?

    To export a static version of the Next.js app.

    [:arrow_up: Back to Top](#table-of-contents)

39. ### How do you optimize fonts in Next.js?

    By using the built-in font optimization feature.

    [:arrow_up: Back to Top](#table-of-contents)

40. ### What is the default port for a Next.js app?

    Port 3000.

    [:arrow_up: Back to Top](#table-of-contents)

41. ### How to change default port for a Next.js app?

    ```js
    "scripts": {
       "dev": "next dev -p 8080", // for dev
       "start": "next start -p 8080" // for prod
    },
    ```

    [:arrow_up: Back to Top](#table-of-contents)

42. ### How do you add custom headers in Next.js?

    By configuring headers in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

43. ### What is Fast Refresh in Next.js?

    A feature for quick feedback when editing React components.

    [:arrow_up: Back to Top](#table-of-contents)

44. ### How do you configure a custom Babel setup in Next.js?

    By adding a babel.config.js file.

    [:arrow_up: Back to Top](#table-of-contents)

45. ### How do you handle internationalization (i18n) in Next.js?

    By configuring i18n settings in next.config.js.

    ```js
    module.exports = {
      i18n: {
        locales: ["en", "fr"],
        defaultLocale: "en",
      },
    };
    ```

    [:arrow_up: Back to Top](#table-of-contents)

46. ### What is React Strict Mode in Next.js?

    A development mode only feature for highlighting potential problems in an application. It helps to identify unsafe lifecycles, legacy API usage, and a number of other features.

    ```js
    module.exports = {
      reactStrictMode: true,
    };
    ```

    **Note**: Since Next.js 13.5.1, Strict Mode is true by default with app router, so the above configuration is only necessary for pages. You can still disable Strict Mode by setting `reactStrictMode: false`.

    [:arrow_up: Back to Top](#table-of-contents)

47. ### What is a singleton router in Next.js?

    A single router instance accessible across the application.

    [:arrow_up: Back to Top](#table-of-contents)

48. ### How do you perform client-side data fetching in Next.js?

    Using `useEffect` and fetch or any other data fetching library like `axios`,`fetch` or `swr` by Next.js team.

    ```
    import { useEffect, useState } from "react";

    export default function Page() {
      const [data, setData] = useState(null);

      useEffect(() => {
        fetch("https://api.github.com/repos/vercel/next.js")
          .then((res) => res.json())
          .then((data) => setData(data));
      }, []);

      return <p>{data ? data.stargazers_count : "Loading..."}</p>;
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

### [Pages Router](#pages-router)

[:arrow_up: Back to Top](#groups)

50. ### What do you create route at pages based routing in Next.js?

    In Next.js pages router, you create routes by adding files to the `pages` directory:

    - `pages/index.js` - the homepage (/)
    - `pages/about.js` - the about page (/about)
    - `pages/blog/index.js` - the blog index page (/blog)
    - `pages/blog/[slug].js` - dynamic blog posts (/blog/:slug)

    [:arrow_up: Back to Top](#table-of-contents)

51. ### How do you create a dynamic route in Next.js?

    In the pages directory, you can add bracket syntax to create dynamic routes:

    ```jsx
     pages/posts/[id].js → /posts/1, /posts/2, etc.
     pages/[username]/settings.js → /foo/settings, /bar/settings, etc.
     pages/post/[...all].js → /post/2020/id/title, etc.

    ```

    [:arrow_up: Back to Top](#table-of-contents)

52. ### What is the \_app.js file in Next.js?

    A special file for initializing pages. It's used for layout, state, or custom error handling.

    [:arrow_up: Back to Top](#table-of-contents)

53. ### What is the \_error.js file in Next.js?

    The `_error.js` file is used to create a custom error page for handling errors such as 404 and 500 in Next.js applications.

    [:arrow_up: Back to Top](#table-of-contents)

54. ### What is the \_document.js file in Next.js?

    A custom document for augmenting the application's HTML and body tags.

    [:arrow_up: Back to Top](#table-of-contents)

55. ### How do you create a 404 page in Next.js?

    By adding a `pages/404.js` file.

    [:arrow_up: Back to Top](#table-of-contents)

56. ### What is the difference between getStaticProps and getServerSideProps?

    getStaticProps runs at build time, getServerSideProps runs on each request.

    [:arrow_up: Back to Top](#table-of-contents)

57. ### What is getStaticProps?

    A function that runs at build time to fetch data for a page.

    ```jsx
    export async function getStaticProps(context) {
      const res = await fetch(`https://...`);
      const data = await res.json();

      if (!data) {
        return {
          notFound: true,
        };
      }

      return {
        props: { data }, // will be passed to the page component as props
      };
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

58. ### What is getServerSideProps?

    A function that runs on each request to fetch data for a page.

    ```jsx
    export async function getServerSideProps(context) {
      const res = await fetch(`https://...`);
      const data = await res.json();

      if (!data) {
        return {
          notFound: true,
        };
      }

      return {
        props: { data }, // will be passed to the page component as props
      };
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

59. ### What is getStaticPaths?

    A function that specifies dynamic routes to pre-render based on data.

    ```jsx
    export async function getStaticPaths() {
      const res = await fetch("https://.../posts");
      const posts = await res.json();

      // Get the paths we want to pre-render based on posts
      const paths = posts.map((post) => ({
        params: { id: post.id },
      }));

      // We'll pre-render only these paths at build time.
      // { fallback: false } means other routes should 404.
      return { paths, fallback: false };
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

60. ### How do you add global CSS in Next.js?

    By importing CSS files in the \_app.js file.

    [:arrow_up: Back to Top](#table-of-contents)

### [App Router](#app-router)

[:arrow_up: Back to Top](#groups)

61. ### What is the useTranslation hook in Next.js?

    A hook provided by next-i18next for internationalization.

    [:arrow_up: Back to Top](#table-of-contents)

62. ### How do you create custom error pages in Next.js?

    By creating error.js files in app directory.

    [:arrow_up: Back to Top](#table-of-contents)

63. ### What is AMP in Next.js?

    A framework for creating fast, mobile-friendly pages.

    [:arrow_up: Back to Top](#table-of-contents)

64. ### How do you enable AMP in Next.js?

    By adding export const config = { amp: true } to a page.

    [:arrow_up: Back to Top](#table-of-contents)

65. ### What is the next/image component used for?

    For image optimization and responsive images.

    [:arrow_up: Back to Top](#table-of-contents)

66. ### What is the next/link component used for?

    For client-side navigation between pages.

    [:arrow_up: Back to Top](#table-of-contents)

67. ### What is the difference between pages and components directories?

    Pages are routes, components are reusable UI elements.

    [:arrow_up: Back to Top](#table-of-contents)

68. ### How do you handle middleware in Next.js?

    By creating a middleware.js file in the app directory.

    [:arrow_up: Back to Top](#table-of-contents)

### [Others](#others)

[:arrow_up: Back to Top](#groups)

67. ### How do you add polyfills in Next.js?

    By importing them in the \_app.js file or using next-polyfill.

    [:arrow_up: Back to Top](#table-of-contents)

68. ### What is the difference between client-side and server-side rendering in Next.js?

    Client-side rendering happens in the browser, server-side rendering happens on the server.

    [:arrow_up: Back to Top](#table-of-contents)

69. ### What is static optimization in Next.js?

    A feature that automatically determines if a page can be statically generated.

    [:arrow_up: Back to Top](#table-of-contents)

70. ### How do you fetch data on the client-side in Next.js?

    Using React hooks like useState and useEffect with fetch.

    ```jsx
    import { useState, useEffect } from "react";

    function Profile() {
      const [data, setData] = useState(null);
      const [isLoading, setLoading] = useState(true);

      useEffect(() => {
        fetch("/api/profile")
          .then((res) => res.json())
          .then((data) => {
            setData(data);
            setLoading(false);
          });
      }, []);

      if (isLoading) return <p>Loading...</p>;
      if (!data) return <p>No profile data</p>;

      return (
        <div>
          <h1>{data.name}</h1>
          <p>{data.bio}</p>
        </div>
      );
    }
    ```

    [:arrow_up: Back to Top](#table-of-contents)

71. ### How do you implement authentication in Next.js?

    Using next-auth or a custom authentication solution.

    [:arrow_up: Back to Top](#table-of-contents)

72. ### What is the difference between \_app.js and \_document.js?

    \_app.js is for page initialization, \_document.js is for custom document structure.

    [:arrow_up: Back to Top](#table-of-contents)

73. ### How do you create API endpoints in Next.js?

    By adding files to the pages/api or app/api directory.

    [:arrow_up: Back to Top](#table-of-contents)

74. ### What is ISR in Next.js?

    Incremental Static Regeneration, for updating static pages after deployment.

    [:arrow_up: Back to Top](#table-of-contents)

75. ### How do you configure Webpack in Next.js?

    By adding a custom webpack configuration in next.config.js.

    ```js
    module.exports = {
      webpack: (
        config,
        { buildId, dev, isServer, defaultLoaders, webpack }
      ) => {
        // Note: we provide webpack above so you should not `require` it
        // Perform customizations to webpack config
        config.plugins.push(new webpack.IgnorePlugin(/\/__tests__\//));

        // Important: return the modified config
        return config;
      },
    };
    ```

    [:arrow_up: Back to Top](#table-of-contents)

76. ### What is the purpose of next-env.d.ts?

    A TypeScript declaration file for Next.js types.

    [:arrow_up: Back to Top](#table-of-contents)

77. ### How do you handle routing in a Next.js app?

    Using file-based routing in the pages or app directory.

    [:arrow_up: Back to Top](#table-of-contents)

78. ### What is the purpose of next/dynamic?

    For dynamic importing of components with support for SSR.

    ```jsx
    import dynamic from "next/dynamic";

    // Client-side only component
    const DynamicComponentWithNoSSR = dynamic(
      () => import("../components/hello"),
      { ssr: false }
    );

    function Home() {
      return (
        <div>
          <Header />
          <DynamicComponentWithNoSSR />
          <Footer />
        </div>
      );
    }

    export default Home;
    ```

    [:arrow_up: Back to Top](#table-of-contents)

79. ### How do you add meta tags in Next.js?

    Using the Head component from next/head.

    ```jsx
    import Head from "next/head";

    function IndexPage() {
      return (
        <div>
          <Head>
            <title>My page title</title>
            <meta
              name="viewport"
              content="initial-scale=1.0, width=device-width"
            />
            <meta property="og:title" content="My page title" key="title" />
          </Head>
          <p>Hello world!</p>
        </div>
      );
    }

    export default IndexPage;
    ```

    [:arrow_up: Back to Top](#table-of-contents)

80. ### What is the purpose of next-compose-plugins?

    To compose and apply multiple Next.js plugins.

    [:arrow_up: Back to Top](#table-of-contents)

81. ### How do you handle form submissions in Next.js?


    Using client-side form handling or API routes for server-side handling.

    [:arrow_up: Back to Top](#table-of-contents)

<!-- Continue with the remaining questions -->
