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

<!-- Group End -->

---

<!-- TOC Start -->

### Common Table of Contents

|  No | Contents                                                                                                                                                             |
| --: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | [What is NextJS](#what-is-nextjs)                                                                                                                                    |
|   2 | [How do you create a new Next.js project?](#how-do-you-create-a-new-nextjs-project)                                                                                  |
|   3 | [What is the purpose of the `pages or app` directory in Next.js?](#what-is-the-purpose-of-the-pages-or-app-directory-in-nextjs)                                      |
|   4 | [What is file based routing in Next.js?](#what-is-file-based-routing-in-nextjs)                                                                                      |
|   5 | [What are the key features of Next.js?](#what-are-the-key-features-of-nextjs)                                                                                        |
|   6 | [What are the differences between Next.js and React.js](#what-are-the-differences-between-nextjs-and-reactjs)                                                        |
|   7 | [What is the difference between client-side and server-side rendering in Next.js?](#what-is-the-difference-between-client-side-and-server-side-rendering-in-nextjs)  |
|   8 | [What is the Link component in Next.js?](#what-is-the-link-component-in-nextjs)                                                                                      |
|   9 | [What is the useRouter hook in Next.js?](#what-is-the-userouter-hook-in-nextjs)                                                                                      |
|  10 | [What is the difference between push and replace in useRouter?](#what-is-the-difference-between-push-and-replace-in-userouter)                                       |
|  11 | [How do you navigate programmatically in Next.js?](#how-do-you-navigate-programmatically-in-nextjs)                                                                  |
|  12 | [How do you enable TypeScript in a Next.js project?](#how-do-you-enable-typescript-in-a-nextjs-project)                                                              |
|  13 | [How do you handle environment variables in Next.js?](#how-do-you-handle-environment-variables-in-nextjs)                                                            |
|  14 | [What is API Routes in Next.js?](#what-is-api-routes-in-nextjs)                                                                                                      |
|  15 | [What is the public folder in Next.js?](#what-is-the-public-folder-in-nextjs)                                                                                        |
|  16 | [What is dynamic import in Next.js?](#what-is-dynamic-import-in-nextjs)                                                                                              |
|  17 | [What is the default port for a Next.js app?](#what-is-the-default-port-for-a-nextjs-app)                                                                            |
|  18 | [How to change default port for a Next.js app?](#how-to-change-default-port-for-a-nextjs-app)                                                                        |
|  19 | [What is Fast Refresh in Next.js?](#what-is-fast-refresh-in-nextjs)                                                                                                  |
|  20 | [What is next.config.js?](#what-is-nextconfigjs)                                                                                                                     |
|  21 | [How do you add component-level CSS in Next.js?](#how-do-you-add-component-level-css-in-nextjs)                                                                      |
|  22 | [How do you add global CSS in Next.js?](#how-do-you-add-global-css-in-nextjs)                                                                                        |
|  23 | [How do you use Tailwind CSS in Next.js?](#how-do-you-use-tailwind-css-in-nextjs)                                                                                    |
|  24 | [What is server side rendering (SSR) in Next.js?](#what-is-server-side-rendering-ssr-in-nextjs)                                                                      |
|  25 | [What is static site generation (SSG) in Next.js?](#what-is-static-site-generation-ssg-in-nextjs)                                                                    |
|  26 | [What is the difference between static site generation and server side rendering?](#what-is-the-difference-between-static-site-generation-and-server-side-rendering) |
|  27 | [What is pre-rendering in Next.js?](#what-is-pre-rendering-in-nextjs)                                                                                                |
|  28 | [What is incremental static regeneration (ISR) in Next.js?](#what-is-incremental-static-regeneration-isr-in-nextjs)                                                  |
|  29 | [What is the Image component in Next.js?](#what-is-the-image-component-in-nextjs)                                                                                    |
|  30 | [How do you deploy a Next.js app to Vercel?](#how-do-you-deploy-a-nextjs-app-to-vercel)                                                                              |
|  31 | [How do you handle redirects in Next.js?](#how-do-you-handle-redirects-in-nextjs)                                                                                    |
|  32 | [What is the Head component in Next.js?](#what-is-the-head-component-in-nextjs)                                                                                      |
|  33 | [What is the next/head package used for?](#what-is-the-nexthead-package-used-for)                                                                                    |
|  34 | [How do you add custom headers in Next.js?](#how-do-you-add-custom-headers-in-nextjs)                                                                                |
|  35 | [What is the use of next export command?](#what-is-the-use-of-next-export-command)                                                                                   |
|  36 | [How do you optimize fonts in Next.js?](#how-do-you-optimize-fonts-in-nextjs)                                                                                        |
|  37 | [How do you enable custom fonts in Next.js?](#how-do-you-enable-custom-fonts-in-nextjs)                                                                              |
|  38 | [How do you configure Webpack in Next.js?](#how-do-you-configure-webpack-in-nextjs)                                                                                  |
|  39 | [How do you configure a custom Babel setup in Next.js?](#how-do-you-configure-a-custom-babel-setup-in-nextjs)                                                        |
|  40 | [What is the purpose of next-env.d.ts?](#what-is-the-purpose-of-next-envdts)                                                                                         |
|  41 | [What is the purpose of next-compose-plugins?](#what-is-the-purpose-of-next-compose-plugins)                                                                         |
|  42 | [How do you add polyfills in Next.js?](#how-do-you-add-polyfills-in-nextjs)                                                                                          |
|  43 | [What is static optimization in Next.js?](#what-is-static-optimization-in-nextjs)                                                                                    |
|  44 | [How do you handle internationalization (i18n) in Next.js?](#how-do-you-handle-internationalization-i18n-in-nextjs)                                                  |
|  45 | [What is React Strict Mode in Next.js?](#what-is-react-strict-mode-in-nextjs)                                                                                        |
|  46 | [What is a singleton router in Next.js?](#what-is-a-singleton-router-in-nextjs)                                                                                      |
|  47 | [What is next/script used for?](#what-is-nextscript-used-for)                                                                                                        |
|  48 | [What is middleware?](#what-is-middleware)                                                                                                                           |
|  49 | [What is a custom server in Next.js?](#what-is-a-custom-server-in-nextjs)                                                                                            |
|  50 | [How do you perform client-side data fetching in Next.js?](#how-do-you-perform-client-side-data-fetching-in-nextjs)                                                  |
|  51 | [How do you set up GraphQL in Next.js?](#how-do-you-set-up-graphql-in-nextjs)                                                                                        |
|  52 | [ How do you create API endpoints in Next.js?](#how-do-you-create-api-endpoints-in-nextjs)                                                                           |
|  53 | [What is the use of next-seo in Next.js?](#what-is-the-use-of-next-seo-in-nextjs)                                                                                    |
|  54 | [How do you handle routing in a Next.js app?](#how-do-you-handle-routing-in-a-nextjs-app)                                                                            |
|  55 | [How do you configure next-i18next in Next.js?](#how-do-you-configure-next-i18next-in-nextjs)                                                                        |
|  56 | [What is ssr: false in dynamic import?](#what-is-ssr-false-in-dynamic-import)                                                                                        |
|  57 | [How do you add Google Analytics to a Next.js project?](#how-do-you-add-google-analytics-to-a-nextjs-project)                                                        |
|  58 | [How do you add meta tags in Next.js?](#how-do-you-add-meta-tags-in-nextjs)                                                                                          |
|  59 | [How to add sitemap in nextjs app?](#how-to-add-sitemap-in-nextjs-app)                                                                                               |
|  60 | [How do you handle CORS in Next.js API routes?](#how-do-you-handle-cors-in-nextjs-api-routes)                                                                        |
|  61 | [How do you manage cookies in Next.js?](#how-do-you-manage-cookies-in-nextjs)                                                                                        |
|  62 | [What is the purpose of next/dynamic?](#what-is-the-purpose-of-nextdynamic)                                                                                          |
|  63 | [How to consider security in nextjs app router?](#how-to-consider-security-in-nextjs-app-router)                                                                     |
|  64 | [What is the useTranslation hook in Next.js?](#what-is-the-usetranslation-hook-in-nextjs)                                                                            |
|  65 | [What is AMP in Next.js?](#what-is-amp-in-nextjs)                                                                                                                    |
|  66 | [How do you enable AMP in Next.js?](#how-do-you-enable-amp-in-nextjs)                                                                                                |
|  67 | [What is the next/image component used for?](#what-is-the-nextimage-component-used-for)                                                                              |
|  68 | [What is the next/link component used for?](#what-is-the-nextlink-component-used-for)                                                                                |
|  69 | [What is the difference between pages and components directories?](#what-is-the-difference-between-pages-and-components-directories)                                 |
|  70 | [How do you handle static files in Next.js?](#how-do-you-handle-static-files-in-nextjs)                                                                              |
|  71 | [List some common performance optimization techniques in Next.js?](#list-some-common-performance-optimization-techniques-in-nextjs)                                  |
|  72 | [Mention some common security practices in Next.js?](#mention-some-common-security-practices-in-nextjs)                                                              |
|  73 | [Are there any limitations of Next.js?](#are-there-any-limitations-of-nextjs)                                                                                        |
|  74 | [Is Next.js suitable for large-scale applications?](#is-nextjs-suitable-for-large-scale-applications)                                                                |
|  75 | [How nextjs are full stack framework?](#how-nextjs-are-full-stack-framework)                                                                                         |
|  76 | [Prevent API routes from being accessed by the client?](#prevent-api-routes-from-being-accessed-by-the-client)                                                       |
|  77 | [JWT Token in Next.js?](#jwt-token-in-nextjs)                                                                                                                        |

### Pages Router Table of Contents

|  No | Contents                                                                                                                                            |
| --: | --------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | [What is the Pages Router in Next.js?](#what-is-the-pages-router-in-nextjs)                                                                         |
|   2 | [How do you create a route in the Pages Router?](#how-do-you-create-a-route-in-the-pages-router)                                                    |
|   3 | [How do you create a dynamic route in Next.js?](#how-do-you-create-a-dynamic-route-in-nextjs)                                                       |
|   4 | [What is catch all segment in Next.js?](#what-is-catch-all-segment-in-nextjs)                                                                       |
|   5 | [What is the \_app.js file in Next.js?](#what-is-the-_appjs-file-in-nextjs)                                                                         |
|   6 | [What is the \_document.js file in Next.js?](#what-is-the-_documentjs-file-in-nextjs)                                                               |
|   7 | [What is the difference between \_app.js and \_document.js?](#what-is-the-difference-between-_appjs-and-_documentjs)                                |
|   8 | [What is the \_error.js file in Next.js?](#what-is-the-_errorjs-file-in-nextjs)                                                                     |
|   9 | [How do you create a 404 page in Next.js?](#how-do-you-create-a-404-page-in-nextjs)                                                                 |
|  10 | [How do you fetch data in a Next.js page?](#how-do-you-fetch-data-in-a-nextjs-page)                                                                 |
|  11 | [What is getStaticProps?](#what-is-getstaticprops)                                                                                                  |
|  12 | [What is getServerSideProps?](#what-is-getserversideprops)                                                                                          |
|  13 | [What is the difference between getStaticProps and getServerSideProps?](#what-is-the-difference-between-getstaticprops-and-getserversideprops)      |
|  14 | [What is getStaticPaths?](#what-is-getstaticpaths)                                                                                                  |
|  15 | [What is fallback in getStaticPaths?](#what-is-fallback-in-getstaticpaths)                                                                          |
|  16 | [How do you handle API routes in Next.js?](#how-do-you-handle-api-routes-in-nextjs)                                                                 |
|  17 | [How you handle custom error pages in Next.js?](#how-do-you-handle-custom-error-pages-in-nextjs)                                                    |
|  18 | [Are there any limitations of the Pages Router](#are-there-any-limitations-of-the-pages-router)                                                     |
|  19 | [How do you handle authentication in Next.js with the Pages Router?](#how-do-you-handle-authentication-in-nextjs-with-the-pages-router)             |
|  20 | [How do you handle middleware in Next.js with the Pages Router?](#how-do-you-handle-middleware-in-nextjs-with-the-pages-router)                     |
|  21 | [How do you handle form submissions in Next.js with the Pages Router?](#how-do-you-handle-form-submissions-in-nextjs-with-the-pages-router)         |
|  22 | [Are there any performance optimizations available in the Pages Router?](#are-there-any-performance-optimizations-available-in-the-pages-router)    |
|  23 | [How do you handle internationalization in Next.js with the Pages Router?](#how-do-you-handle-internationalization-in-nextjs-with-the-pages-router) |
|  24 | [How do you handle seo in Next.js with the Pages Router?](#how-do-you-handle-seo-in-nextjs-with-the-pages-router)                                   |
|  25 | [How do you handle static assets in Next.js with the Pages Router?](#how-do-you-handle-static-assets-in-nextjs-with-the-pages-router)               |
|  26 | [How cache works in Next.js with the Pages Router?](#how-cache-works-in-nextjs-with-the-pages-router)                                               |
|  27 | [Cache revalidation in Next.js with the Pages Router?](#cache-revalidation-in-nextjs-with-the-pages-router)                                         |
|  28 | [Optimizing images in Next.js with the Pages Router?](#optimizing-images-in-nextjs-with-the-pages-router)                                           |
|  29 | [When to choose Pages Router over App Router in Next.js?](#when-to-choose-pages-router-over-app-router-in-nextjs)                                   |
|  30 | [When to choose App Router over Pages Router in Next.js?](#when-to-choose-app-router-over-pages-router-in-nextjs)                                   |

### App Router Table of Contents

|  No | Contents                                                                                                                                                                      |
| --: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | [What is the App Router in Next.js?](#what-is-the-app-router-in-nextjs)                                                                                                       |
|   2 | [How do you create a route in the App Router?](#how-do-you-create-a-route-in-the-app-router)                                                                                  |
|   3 | [How do you create a dynamic route with app router in Next.js?](#how-do-you-create-a-dynamic-route-with-app-router-in-nextjs)                                                 |
|   4 | [How do you create custom error pages in Next.js?](#how-do-you-create-custom-error-pages-in-nextjs)                                                                           |
|   5 | [How do you handle form submissions in Next.js?](#how-do-you-handle-form-submissions-in-nextjs)                                                                               |
|   6 | [How do you handle middleware in Next.js?](#how-do-you-handle-middleware-in-nextjs)                                                                                           |
|   7 | [How do you implement authentication in Next.js?](#how-do-you-implement-authentication-in-nextjs)                                                                             |
|   8 | [How to add authjs in nextjs app router?](#how-to-add-authjs-in-nextjs-app-router)                                                                                            |
|   9 | [How do you handle authentication tokens in Next.js?](#how-do-you-handle-authentication-tokens-in-nextjs)                                                                     |
|  10 | [How to add credentials in nextjs app router?](#how-to-add-credentials-in-nextjs-app-router)                                                                                  |
|  11 | [What is use server in Next.js?](#what-is-use-server-in-nextjs)                                                                                                               |
|  12 | [Difference between using & not using use server in Next.js?](#difference-between-using--not-using-use-server-in-nextjs)                                                      |
|  13 | [How do you handle API routes in Next.js?](#how-do-you-handle-api-routes-in-nextjs)                                                                                           |
|  14 | [How do middleware work in Next.js?](#how-do-middleware-work-in-nextjs)                                                                                                       |
|  15 | [What is form action in Next.js?](#what-is-form-action-in-nextjs)                                                                                                             |
|  16 | [How do you handle file uploads in Next.js?](#how-do-you-handle-file-uploads-in-nextjs)                                                                                       |
|  17 | [Mention some common use cases for the App Router in Next.js?](#mention-some-common-use-cases-for-the-app-router-in-nextjs)                                                   |
|  18 | [One of the main differences between the App Router and Pages Router?](#one-of-the-main-differences-between-the-app-router-and-the-pages-router-in-nextjs)                    |
|  19 | [What is the use of the `use client` directive in Next.js?](#what-is-the-use-of-the-use-client-directive-in-nextjs)                                                           |
|  20 | [Is it possible to use both App Router and Pages Router in the same Next.js project?](#is-it-possible-to-use-both-app-router-and-pages-router-in-the-same-nextjs-application) |
|  21 | [Are there any limitations of the App Router in Next.js?](#are-there-any-limitations-of-the-app-router-in-nextjs)                                                             |
|  22 | [Explain the concept of authorization in middleware & routes in Next.js?](#explain-the-concept-of-authorization-in-middleware--routes-in-nextjs)                              |
|  23 | [The difference between `use server` and `use client` in Next.js?](#the-difference-between-use-server-and-use-client-in-nextjs)                                               |
|  24 | [Understand the concept of server actions in Next.js?](#understand-the-concept-of-server-actions-in-nextjs)                                                                   |
|  25 | [Whats are the benifit of using server actions in Next.js?](#whats-are-the-benifit-of-using-server-actions-in-nextjs)                                                         |
|  26 | [Whats are the problem of using server actions in Next.js?](#whats-are-the-problem-of-using-server-actions-in-nextjs)                                                         |
|  27 | [Alternative options instead of server actions in Next.js?](#alternative-options-instead-of-server-actions-in-nextjs)                                                         |
|  28 | [Alternative solutions example of not using server actions in Next.js?](#alternative-solutions-example-of-not-using-server-actions-in-nextjs)                                 |
|  29 | [JWT Token in Next.js App Router?](#jwt-token-in-nextjs-app-router)                                                                                                           |
|  30 | [Context of JWT Token in Next.js App Router?](#context-of-jwt-token-in-nextjs-app-router)                                                                                     |
|  31 | [Is App Router better than Pages Router in Next.js?](#is-app-router-better-than-pages-router-in-nextjs)                                                                       |
|  32 | [How to handle global state management in Next.js with the App Router?](#how-to-handle-global-state-management-in-nextjs-with-the-app-router)                                 |
|  33 | [What is the fetch API in Next.js App Router?](#what-is-the-fetch-api-in-nextjs-app-router)                                                                                   |
|  34 | [How do you create route groups in the App Router?](#how-do-you-create-route-groups-in-the-app-router)                                                                        |
|  35 | [What are parallel routes in Next.js App Router?](#what-are-parallel-routes-in-nextjs-app-router)                                                                             |
|  36 | [How do you implement intercepting routes in App Router?](#how-do-you-implement-intercepting-routes-in-app-router)                                                            |
|  37 | [What is the loading.js file in App Router?](#what-is-the-loadingjs-file-in-app-router)                                                                                       |
|  38 | [How do you handle not-found pages in App Router?](#how-do-you-handle-not-found-pages-in-app-router)                                                                          |
|  39 | [What is the template.js file in App Router?](#what-is-the-templatejs-file-in-app-router)                                                                                     |
|  40 | [How do you implement nested layouts in App Router?](#how-do-you-implement-nested-layouts-in-app-router)                                                                      |
|  41 | [What are route handlers vs API routes in App Router?](#what-are-route-handlers-vs-api-routes-in-app-router)                                                                  |
|  42 | [How do you handle streaming and suspense in App Router?](#how-do-you-handle-streaming-and-suspense-in-app-router)                                                            |
|  43 | [What is React Server Components (RSC) in App Router?](#what-is-react-server-components-rsc-in-app-router)                                                                    |

<!-- TOC End -->

---

<!-- Question & Answers Start -->

### [Common](#common)

[:arrow_up: Back to Top](#groups)

1. ### What is NextJS?

   Next.js is a React framework for building full-stack web applications.

   [:arrow_up: Back to Top](#common-table-of-contents)

2. ### How do you create a new Next.js project?

   Using command

   > npx create-next-app@latest

   [:arrow_up: Back to Top](#common-table-of-contents)

3. ### What is the purpose of the `pages or app` directory in Next.js?

   It contains React components that are automatically routed based on their file name.

   [:arrow_up: Back to Top](#common-table-of-contents)

4. ### What is file based routing in Next.js?

   Routing based on the file structure in the `pages or app` directory.

   [:arrow_up: Back to Top](#common-table-of-contents)

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

   [:arrow_up: Back to Top](#common-table-of-contents)

6. ### What are the differences between Next.js and React.js

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

   [:arrow_up: Back to Top](#common-table-of-contents)

7. ### What is the difference between client-side and server-side rendering in Next.js?

   Client-side rendering (CSR) means that the browser fetches the JavaScript and renders the page on the client side, while server-side rendering (SSR) means that the server generates the HTML and sends it to the client.

   [:arrow_up: Back to Top](#common-table-of-contents)

8. ### What is the Link component in Next.js?

   A component for client side navigation between pages.

   ```jsx
   import Link from "next/link";

   <Link href="/">Home</Link>
   <Link href="/about">About</Link>
   ```

   [:arrow_up: Back to Top](#common-table-of-contents)

9. ### What is the useRouter hook in Next.js?

   A hook that allows access to the router object and perform navigation. The `useRouter` hook allows you to programmatically change routes inside **client** components.

   [:arrow_up: Back to Top](#common-table-of-contents)

10. ### What is the difference between push and replace in useRouter?

    The `push` method adds a new entry to the browser's history stack, while `replace` replaces the current entry in the history stack.

    ```jsx
    const router = useRouter();

    // Pushes a new route
    router.push("/new-route");

    // Replaces the current route
    router.replace("/new-route");
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

11. ### How do you navigate programmatically in Next.js?

    Using useRouter() hook.

    ```jsx
    const router = useRouter();

    function handleClick() {
      router.push(`/path`);
    }

    <button onClick={handleClick}>Go There</button>;
    ```

    ```jsx
    router.push(href: string, { scroll: boolean })
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

12. ### How do you enable TypeScript in a Next.js project?

    By adding a tsconfig.json file.

    [:arrow_up: Back to Top](#common-table-of-contents)

13. ### What is API Routes in Next.js?

    A feature to create API endpoints in the `pages/api` or `app/api` directory. It allow you to create custom request handlers for a given route using the Web Request and Response APIs.

    [:arrow_up: Back to Top](#common-table-of-contents)

14. ### What is the public folder in Next.js?

    A folder for static assets to be served from the root URL.

    ```
    public/
    ├── favicon.ico
    |── robots.txt
    |── images/
    |   └── profile.jpg
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

15. ### What is dynamic import in Next.js?

    A feature to load components or modules dynamically.

    ```jsx
    const ComponentA = dynamic(() => import("../components/A"));
    const ComponentB = dynamic(() => import("../components/B"));
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

16. ### How do you handle environment variables in Next.js?

    By adding them to .env.local and accessing via process.env.

    [:arrow_up: Back to Top](#common-table-of-contents)

17. ### What is the default port for a Next.js app?

    Port 3000.

    [:arrow_up: Back to Top](#common-table-of-contents)

18. ### How to change default port for a Next.js app?

    ```js
    "scripts": {
       "dev": "next dev -p 8080", // for dev
       "start": "next start -p 8080" // for prod
    },
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

19. ### What is Fast Refresh in Next.js?

    A feature for quick feedback when editing React components.

    [:arrow_up: Back to Top](#common-table-of-contents)

20. ### What is next.config.js?

    A configuration file to customize Next.js settings.

    ```ts
    // @ts-check

    /** @type {import('next').NextConfig} */
    const nextConfig = {
      /* config options here */
    };

    module.exports = nextConfig;
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

21. ### How do you add component-level CSS in Next.js?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

22. ### How do you add global CSS in Next.js?

    By importing CSS files in the \_app.js file.

    [:arrow_up: Back to Top](#common-table-of-contents)

23. ### How do you use Tailwind CSS in Next.js?

    By installing Tailwind CSS and configuring it in the next.config.js file.

    ```bash
    npm install tailwindcss postcss autoprefixer
    npx tailwindcss init -p
    ```

    Then, add the following to your `tailwind.config.js`:

    ```js
    module.exports = {
      content: [
        "./pages/**/*.{js,ts,jsx,tsx}",
        "./components/**/*.{js,ts,jsx,tsx}",
      ],
      theme: {
        extend: {},
      },
      plugins: [],
    };
    ```

    And import Tailwind CSS in your \_app.js:

    ```js
    import "tailwindcss/tailwind.css";
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

24. ### What is server side rendering (SSR) in Next.js?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

25. ### What is static site generation (SSG) in Next.js?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

26. ### What is the difference between static site generation and server side rendering?

    Static site generation (SSG) pre-renders at build time, server side rendering (SSR) pre-renders on each request.

    [:arrow_up: Back to Top](#common-table-of-contents)

27. ### What is pre-rendering in Next.js?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

28. ### What is incremental static regeneration (ISR) in Next.js?

    Incremental Static Regeneration is a technique in Next.js that allows you to update static pages at runtime without rebuilding the entire site.
    This feature introduces a seamless way to serve both static and dynamic content by revalidating and regenerating pages in the background.

    ```jsx
    export async function getStaticProps() {
      const res = await fetch("https://api.github.com/repos/vercel/next.js");
      const repo = await res.json();
      return { props: { repo }, revalidate: 1 };
    }
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

29. ### What is the Image component in Next.js?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

30. ### How do you deploy a Next.js app to Vercel?

    By connecting the git/github repository to Vercel and deploying it.

    [:arrow_up: Back to Top](#common-table-of-contents)

31. ### How do you handle redirects in Next.js?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

32. ### What is the Head component in Next.js?

    A component for modifying the of a page.

    ```jsx
    import Head from "next/head";

    <Head>
      <title>My page title</title>
      <meta name="viewport" content="initial-scale=1.0, width=device-width" />
    </Head>;
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

33. ### What is the next/head package used for?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

34. ### How do you add custom headers in Next.js?

    By configuring headers in next.config.js.

    [:arrow_up: Back to Top](#common-table-of-contents)

35. ### What is the use of next export command?

    To export a static version of the Next.js app.

    [:arrow_up: Back to Top](#common-table-of-contents)

36. ### How do you optimize fonts in Next.js?

    By using the built-in font optimization feature.

    [:arrow_up: Back to Top](#common-table-of-contents)

37. ### How do you enable custom fonts in Next.js?

    By using the next/font package to optimize and load custom fonts.

    ```js
    import { Inter } from "next/font/google";

    const inter = Inter({ subsets: ["latin"] });

    export default function Home() {
      return (
        <main className={inter.className}>
          <h1>Hello World!</h1>
        </main>
      );
    }
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

38. ### How do you configure Webpack in Next.js?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

39. ### How do you configure a custom Babel setup in Next.js?

    By adding a babel.config.js file.

    [:arrow_up: Back to Top](#common-table-of-contents)

40. ### What is the purpose of next-env.d.ts?

    A TypeScript declaration file for Next.js types.

    [:arrow_up: Back to Top](#common-table-of-contents)

41. ### What is the purpose of next-compose-plugins?

    To compose and apply multiple Next.js plugins.

    [:arrow_up: Back to Top](#common-table-of-contents)

42. ### How do you add polyfills in Next.js?

    By importing them in the \_app.js file or using next-polyfill.

    [:arrow_up: Back to Top](#common-table-of-contents)

43. ### What is static optimization in Next.js?

    A feature that automatically determines if a page can be statically generated.

    [:arrow_up: Back to Top](#common-table-of-contents)

44. ### How do you handle internationalization (i18n) in Next.js?

    By configuring i18n settings in next.config.js.

    ```js
    module.exports = {
      i18n: {
        locales: ["en", "fr"],
        defaultLocale: "en",
      },
    };
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

45. ### What is React Strict Mode in Next.js?

    A development mode only feature for highlighting potential problems in an application. It helps to identify unsafe lifecycles, legacy API usage, and a number of other features.

    ```js
    module.exports = {
      reactStrictMode: true,
    };
    ```

    **Note**: Since Next.js 13.5.1, Strict Mode is true by default with app router, so the above configuration is only necessary for pages. You can still disable Strict Mode by setting `reactStrictMode: false`.

    [:arrow_up: Back to Top](#common-table-of-contents)

46. ### What is a singleton router in Next.js?

    A single router instance accessible across the application.

    [:arrow_up: Back to Top](#common-table-of-contents)

47. ### What is next/script used for?

    The `next/script` component is used to load external scripts in a Next.js application. It provides features like loading scripts asynchronously, deferring execution, and controlling script loading behavior.

    ```jsx
    import Script from "next/script";

    export default function Page() {
      return (
        <>
          <Script src="https://example.com/script.js" strategy="lazyOnload" />
          <h1>Hello World!</h1>
        </>
      );
    }
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

48. ### What is middleware?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

49. ### What is a custom server in Next.js?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

50. ### How do you perform client-side data fetching in Next.js?

    Using `useEffect` and fetch or any other data fetching library like `axios`,`fetch` or `swr` by Next.js team.

    ```
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

    [:arrow_up: Back to Top](#common-table-of-contents)

51. ### How do you set up GraphQL in Next.js?

    By installing Apollo Client or any other GraphQL client and configuring it in the \_app.js file.

    ```bash
    npm install @apollo/client graphql
    yarn add @apollo/client graphql
    ```

    Then, set up Apollo Client in your \_app.js:

    ```js
    import {
      ApolloClient,
      InMemoryCache,
      ApolloProvider,
    } from "@apollo/client";

    const client = new ApolloClient({
      uri: "https://your-graphql-endpoint.com/graphql",
      cache: new InMemoryCache(),
    });

    function MyApp({ Component, pageProps }) {
      return (
        <ApolloProvider client={client}>
          <Component {...pageProps} />
        </ApolloProvider>
      );
    }

    export default MyApp;
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

52. ### How do you create API endpoints in Next.js?

    By adding files to the pages/api or app/api directory.

    [:arrow_up: Back to Top](#common-table-of-contents)

53. ### What is the use of next-seo in Next.js?

    next-seo is a plugin for managing SEO metadata in Next.js applications, making it easier to set and manage meta tags, Open Graph tags, and other SEO-related elements.

    ```jsx
    import { DefaultSeo } from "next-seo";

    function MyApp({ Component, pageProps }) {
      return (
        <>
          <DefaultSeo
            title="My Next.js App"
            description="A description of my Next.js app"
            openGraph={{
              type: "website",
              locale: "en_IE",
              url: "https://www.example.com/",
              site_name: "My Next.js App",
            }}
          />
          <Component {...pageProps} />
        </>
      );
    }

    export default MyApp;
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

54. ### How do you handle routing in a Next.js app?

    Using file-based routing in the pages or app directory.

    [:arrow_up: Back to Top](#common-table-of-contents)

55. ### How do you configure next-i18next in Next.js?

    By creating a next-i18next.config.js file and initializing it in the app.

    ```js
    // next-i18next.config.js
    module.exports = {
      i18n: {
        defaultLocale: "en",
        locales: ["en", "fr"],
      },
    };
    ```

    Then, initialize it in your app:

    ```jsx
    import { appWithTranslation } from "next-i18next";
    import nextI18NextConfig from "../next-i18next.config";

    function MyApp({ Component, pageProps }) {
      return <Component {...pageProps} />;
    }

    export default appWithTranslation(MyApp, nextI18NextConfig);
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

56. ### What is ssr: false in dynamic import?

    It disables server-side rendering for a dynamically imported component, ensuring it only loads on the client side.

    ```jsx
    import dynamic from "next/dynamic";

    const DynamicComponent = dynamic(() => import("../components/hello"), {
      ssr: false,
    });

    function Home() {
      return (
        <section>
          <Header />
          <DynamicComponent />
          <Footer />
        </section>
      );
    }

    export default Home;
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

57. ### How do you add Google Analytics to a Next.js project?

    By using the next/script component to load the Google Analytics script.

    ```jsx
    import Script from "next/script";

    export default function MyApp() {
      return (
        <>
          <Script
            src={`https://www.googletagmanager.com/gtag/js?id=YOUR_TRACKING_ID`}
            strategy="afterInteractive"
          />
          <Script id="google-analytics" strategy="afterInteractive">
            {`
              window.dataLayer = window.dataLayer || [];
              function gtag(){dataLayer.push(arguments);}
              gtag('js', new Date());
              gtag('config', 'YOUR_TRACKING_ID');
            `}
          </Script>
        </>
      );
    }
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

58. ### How do you add meta tags in Next.js?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

59. ### How to add sitemap in nextjs app?

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

    [:arrow_up: Back to Top](#common-table-of-contents)

60. ### How do you handle CORS in Next.js API routes?

    By setting appropriate headers in the API route response.

    ```js
    export default function handler(req, res) {
      res.setHeader("Access-Control-Allow-Origin", "*");
      res.setHeader("Access-Control-Allow-Methods", "GET, POST, PUT, DELETE");
      res.setHeader("Access-Control-Allow-Headers", "Content-Type");
      res.status(200).json({ message: "CORS enabled" });
    }
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

61. ### How do you manage cookies in Next.js?

    By using the cookie package or next-cookies to read and write cookies in API routes or server-side functions.

    ```js
    import Cookies from "cookies";

    export default function handler(req, res) {
      const cookies = new Cookies(req, res);
      cookies.set("token", "value", { httpOnly: true });
      res.status(200).json({ message: "Cookie set" });
    }
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

62. ### What is the purpose of next/dynamic?

    For dynamic importing of components with support for SSR.

    ```jsx
    import dynamic from "next/dynamic";

    // Client-side only component
    const DynamicComponentWithNoSSR = dynamic(
      () => import("../components/hello"),
      {
        ssr: false,
      }
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

    [:arrow_up: Back to Top](#common-table-of-contents)

63. ### How to consider security in nextjs app router?

    To consider security in Next.js app router, you can follow these best practices:

    - Use HTTPS for all requests to ensure data is encrypted in transit.
    - Implement authentication and authorization to protect sensitive routes.
    - Sanitize user input to prevent XSS attacks.
    - Use environment variables to store sensitive information like API keys.
    - Regularly update dependencies to patch known vulnerabilities.
    - Implement Content Security Policy (CSP) headers to mitigate XSS attacks.
    - Use secure cookies with the `HttpOnly` and `Secure` flags.

    [:arrow_up: Back to Top](#common-table-of-contents)

64. ### What is the useTranslation hook in Next.js?

    A hook provided by next-i18next for internationalization.

    [:arrow_up: Back to Top](#common-table-of-contents)

65. ### What is AMP in Next.js?

    A framework for creating fast, mobile-friendly pages.

    [:arrow_up: Back to Top](#common-table-of-contents)

66. ### How do you enable AMP in Next.js?

    By adding export const config = { amp: true } to a page.

    [:arrow_up: Back to Top](#common-table-of-contents)

67. ### What is the next/image component used for?

    For image optimization and responsive images.

    [:arrow_up: Back to Top](#common-table-of-contents)

68. ### What is the next/link component used for?

    For client-side navigation between pages.

    [:arrow_up: Back to Top](#common-table-of-contents)

69. ### What is the difference between pages and components directories?

    Pages are routes, components are reusable UI elements.

    [:arrow_up: Back to Top](#common-table-of-contents)

70. ### How do you handle static files in Next.js?

    By placing them in the `public` directory, which is served at the root URL.

    ```
    public/
    ├── images/
    │   └── logo.png
    └── favicon.ico
    ```

    You can access these files using `/images/logo.png` or `/favicon.ico`.

    [:arrow_up: Back to Top](#common-table-of-contents)

71. ### List some common performance optimization techniques in Next.js.

    - Use static generation (SSG) for pages that can be pre-rendered.
    - Implement incremental static regeneration (ISR) for dynamic content.
    - Use the next/image component for optimized images.
    - Enable code splitting and tree shaking.
    - Use dynamic imports for large components.
    - Optimize CSS with CSS modules or styled-components.
    - Leverage caching strategies for API routes.

    [:arrow_up: Back to Top](#common-table-of-contents)

72. ### Mention some common security practices in Next.js.

    - Use HTTPS for secure communication.
    - Implement authentication and authorization.
    - Sanitize user input to prevent XSS attacks.
    - Use environment variables for sensitive data.
    - Regularly update dependencies to patch vulnerabilities.
    - Implement Content Security Policy (CSP) headers.
    - Use secure cookies with `HttpOnly` and `Secure` flags.

    [:arrow_up: Back to Top](#common-table-of-contents)

73. ### Are there any limitations of Next.js?

    - Limited support for non-React libraries.
    - Requires a Node.js server for server-side rendering.
    - Some features may not be compatible with static site generation.
    - Learning curve for developers new to React or Next.js.

    [:arrow_up: Back to Top](#common-table-of-contents)

74. ### Is Next.js suitable for large-scale applications?

    Yes, Next.js is suitable for large-scale applications due to its features like server-side rendering, static site generation, and API routes. It also supports code splitting, dynamic imports, and incremental static regeneration, which help in managing large codebases efficiently.

    [:arrow_up: Back to Top](#common-table-of-contents)

75. ### How nextjs are full stack framework?

    Next.js is considered a full-stack framework because it allows developers to build both the frontend and backend of web applications within a single codebase. It provides features like server-side rendering, static site generation, API routes, and database integration, enabling the development of complete web applications without needing separate frameworks for the frontend and backend.

    [:arrow_up: Back to Top](#common-table-of-contents)

76. ### Prevent API routes from being accessed by the client?

    To prevent API routes from being accessed by the client, you can implement authentication and authorization checks in your API route handlers. This ensures that only authenticated users can access the API endpoints.

    ```js
    export default function handler(req, res) {
      const token = req.headers.authorization;

      if (!token || !isValidToken(token)) {
        return res.status(401).json({ error: "Unauthorized" });
      }

      // Handle the request
      res.status(200).json({ message: "Success" });
    }
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

77. ### JWT Token in Next.js?

    JSON Web Tokens (JWT) can be used in Next.js for authentication and authorization. You can create a JWT token upon user login and store it in a cookie or local storage. Then, you can verify the token in API routes or server-side functions to authenticate users.

    ```js
    import jwt from "jsonwebtoken";

    // Create a JWT token
    const token = jwt.sign({ userId: user.id }, process.env.JWT_SECRET, {
      expiresIn: "1h",
    });

    // Verify the JWT token
    jwt.verify(token, process.env.JWT_SECRET, (err, decoded) => {
      if (err) {
        return res.status(401).json({ error: "Invalid token" });
      }
      // Proceed with authenticated user
    });
    ```

    [:arrow_up: Back to Top](#common-table-of-contents)

78. ### How do you handle global styles in the App Router?

    By creating a `globals.css` file in the `app` directory and importing it in the `_app.js` file.

    ```css
    /* app/globals.css */
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
        "Helvetica Neue", Arial, sans-serif;
    }
    ```

    Then import it in your `_app.js`:

    ```jsx
    // app/_app.js
    import "../globals.css";

    export default function MyApp({ Component, pageProps }) {
      return <Component {...pageProps} />;
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

### [Pages Router](#pages-router)

[:arrow_up: Back to Top](#groups)

1. ### What is the Pages Router in Next.js?

   The Pages Router is a file-based routing system in Next.js that automatically creates routes based on the file structure inside the `pages` directory.

   [:arrow_up: Back to Top](#pages-router-table-of-contents)

2. ### How do you create a route in the Pages Router?

   In Next.js pages router, you create routes by adding files to the `pages` directory:

   - `pages/index.js` - the homepage (/)
   - `pages/about.js` - the about page (/about)
   - `pages/blog/index.js` - the blog index page (/blog)
   - `pages/blog/[slug].js` - dynamic blog posts (/blog/:slug)

   [:arrow_up: Back to Top](#pages-router-table-of-contents)

3. ### How do you create a dynamic route in Next.js?

   In the pages directory, you can add bracket syntax to create dynamic routes:

   ```jsx
    pages/posts/[id].js → /posts/1, /posts/2, etc.
    pages/[username]/settings.js → /foo/settings, /bar/settings, etc.
    pages/post/[...all].js → /post/2020/id/title, etc.

   ```

   [:arrow_up: Back to Top](#pages-router-table-of-contents)

4. ### What is catch all segment in Next.js?

   A catch-all segment allows you to match multiple segments in a dynamic route. It is defined using `[[...param]]` syntax.

   This allows you to create routes that can match multiple segments, such as `/docs/nextjs`, `/docs/react`, etc.

   ```jsx
   // pages/docs/[[...slug]].js
   export default function Docs({ params }) {
     return <div>Docs: {params.slug.join("/")}</div>;
   }
   ```

   [:arrow_up: Back to Top](#pages-router-table-of-contents)

5. ### What is the \_app.js file in Next.js?

   A special file for initializing pages. It's used for layout, state, or custom error handling.

   [:arrow_up: Back to Top](#pages-router-table-of-contents)

6. ### What is the \_document.js file in Next.js?

   A custom document for augmenting the application's HTML and body tags.

   [:arrow_up: Back to Top](#pages-router-table-of-contents)

7. ### What is the difference between \_app.js and \_document.js?

   \_app.js is for page initialization, \_document.js is for custom document structure.

   [:arrow_up: Back to Top](#pages-router-table-of-contents)

8. ### What is the \_error.js file in Next.js?

   The `_error.js` file is used to create a custom error page for handling errors such as 404 and 500 in Next.js applications.

   [:arrow_up: Back to Top](#pages-router-table-of-contents)

9. ### How do you create a 404 page in Next.js?

   By adding a `pages/404.js` file.

   [:arrow_up: Back to Top](#pages-router-table-of-contents)

10. ### How do you fetch data in a Next.js page?

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

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

11. ### What is getStaticProps?

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

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

12. ### What is getServerSideProps?

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

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

13. ### What is the difference between getStaticProps and getServerSideProps?

    getStaticProps runs at build time, getServerSideProps runs on each request.

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

14. ### What is getStaticPaths?

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

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

15. ### What is fallback in getStaticPaths?

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

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

16. ### How do you handle API routes in Next.js?

    By creating files in the `pages/api` directory, which will be treated as API endpoints.

    ```jsx
    // pages/api/hello.js
    export default function handler(req, res) {
      res.status(200).json({ name: "John Doe" });
    }
    ```

    You can access this API route at `/api/hello`.

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

17. ### How do you handle custom error pages in Next.js?

    By creating a `_error.js` file in the `pages` directory.

    ```jsx
    // pages/_error.js
    export default function Error({ statusCode }) {
      return (
        <p>
          {statusCode
            ? `An error ${statusCode} occurred on server`
            : "An error occurred on client"}
        </p>
      );
    }
    ```

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

18. ### Are there any limitations of the Pages Router?

    Yes, the Pages Router has some limitations compared to the App Router, such as:

    - Limited support for nested routes and layouts.
    - Less flexibility in handling server components.
    - No support for React Server Components.

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

19. ### How do you handle authentication in Next.js with the Pages Router?

    By using libraries like `next-auth` or implementing custom authentication logic in API routes.

    ```jsx
    // pages/api/auth/[...nextauth].js
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
    });
    ```

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

20. ### How do you handle middleware in Next.js with the Pages Router?

    By creating a custom server or using API routes to implement middleware logic.

    ```js
    // pages/api/middleware.js
    export default function middleware(req, res, next) {
      // Custom middleware logic
      if (req.headers.authorization) {
        next(); // Proceed to the next handler
      } else {
        res.status(401).json({ error: "Unauthorized" });
      }
    }
    ```

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

21. ### How do you handle form submissions in Next.js with the Pages Router?

    By using client-side form handling or API routes for server-side handling.

    ```jsx
    // pages/contact.js
    export default function Contact() {
      const handleSubmit = async (e) => {
        e.preventDefault();
        const formData = new FormData(e.target);
        const response = await fetch("/api/contact", {
          method: "POST",
          body: formData,
        });
        if (response.ok) {
          alert("Form submitted successfully!");
        } else {
          alert("Error submitting form.");
        }
      };

      return (
        <form onSubmit={handleSubmit}>
          <input name="name" type="text" placeholder="Name" required />
          <input name="email" type="email" placeholder="Email" required />
          <button type="submit">Submit</button>
        </form>
      );
    }
    ```

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

22. ### Are there any performance optimizations available in the Pages Router?

    Yes, you can use features like static generation (SSG), server-side rendering (SSR), and incremental static regeneration (ISR) to optimize performance in the Pages Router.

    - **Static Generation (SSG)**: Pre-render pages at build time.
    - **Server-Side Rendering (SSR)**: Render pages on each request.
    - **Incremental Static Regeneration (ISR)**: Update static pages after the build.

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

23. ### How do you handle internationalization in Next.js with the Pages Router?

    By using the `next-i18next` library or the built-in internationalization features in Next.js.

    ```js
    // next.config.js
    module.exports = {
      i18n: {
        locales: ["en", "fr"],
        defaultLocale: "en",
      },
    };
    ```

    Then, you can use the `useTranslation` hook from `next-i18next` to handle translations in your components.

    ```jsx
    import { useTranslation } from "next-i18next";

    export default function Home() {
      const { t } = useTranslation("common");
      return <h1>{t("welcome")}</h1>;
    }
    ```

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

24. ### How do you handle SEO in Next.js with the Pages Router?

    By using the `next/head` component to manage meta tags and other SEO-related elements.

    ```jsx
    import Head from "next/head";

    export default function Home() {
      return (
        <>
          <Head>
            <title>My Next.js App</title>
            <meta
              name="description"
              content="A description of my Next.js app"
            />
          </Head>
          <h1>Welcome to My Next.js App</h1>
        </>
      );
    }
    ```

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

25. ### How do you handle static assets in Next.js with the Pages Router?

    By placing static assets in the `public` directory, which is served at the root URL.

    ```
    public/
    ├── images/
    │   └── logo.png
    └── favicon.ico
    ```

    You can access these files using `/images/logo.png` or `/favicon.ico`.

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

26. ### How cache works in Next.js with the Pages Router?

    Next.js uses a built-in caching mechanism for static assets and API routes. You can also implement custom caching strategies using HTTP headers or libraries like `next-cache`.

    - **Static Assets**: Cached by default with a long cache lifetime.
    - **API Routes**: Can be cached using HTTP headers like `Cache-Control`.

    ```js
    export default function handler(req, res) {
      res.setHeader("Cache-Control", "public, max-age=3600, immutable");
      res.status(200).json({ message: "Cached response" });
    }
    ```

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

27. ### Cache revalidation in Next.js with the Pages Router?

    Cache revalidation can be handled using the `revalidate` option in `getStaticProps` or by setting appropriate HTTP headers in API routes.

    - **Using `revalidate`**: Automatically revalidates static pages after a specified time.

    ```jsx
    export async function getStaticProps() {
      const res = await fetch("https://api.example.com/data");
      const data = await res.json();

      return {
        props: { data },
        revalidate: 10, // Revalidate every 10 seconds
      };
    }
    ```

    - **Using HTTP Headers**: Set cache control headers in API routes.

    ```js
    export default function handler(req, res) {
      res.setHeader("Cache-Control", "s-maxage=10, stale-while-revalidate");
      res.status(200).json({ message: "Revalidated response" });
    }
    ```

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

28. ### Optimizing images in Next.js with the Pages Router?

    By using the `next/image` component, which automatically optimizes images for performance.

    ```jsx
    import Image from "next/image";

    export default function Home() {
      return (
        <div>
          <h1>My Next.js App</h1>
          <Image
            src="/images/logo.png"
            alt="Logo"
            width={500}
            height={300}
            quality={75}
          />
        </div>
      );
    }
    ```

    The `next/image` component provides features like lazy loading, responsive images, and automatic format selection.

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

29. ### When to choose Pages Router over App Router in Next.js?

    You might choose the Pages Router over the App Router in the following scenarios:

    - When you need a simple file-based routing system without complex nested routes.
    - When you prefer the traditional Next.js routing approach.
    - When your application does not require advanced features like server components or layouts.

    The Pages Router is suitable for smaller applications or when you want to leverage existing knowledge of Next.js routing.

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

30. ### When to choose App Router over Pages Router in Next.js?

    You might choose the App Router over the Pages Router in the following scenarios:

    - When you need advanced routing capabilities, such as nested routes and layouts.
    - When you want to leverage React Server Components for better performance and flexibility.
    - When your application requires more complex data fetching strategies.

    The App Router is suitable for larger applications or when you want to take advantage of the latest features in Next.js 13.

    [:arrow_up: Back to Top](#pages-router-table-of-contents)

### [App Router](#app-router)

[:arrow_up: Back to Top](#groups)

1. ### What is the App Router in Next.js?

   The App Router is a new routing system introduced in Next.js 13 that allows for more flexible and powerful routing capabilities, including nested routes, layouts, and server components.

   [:arrow_up: Back to Top](#app-router-table-of-contents)

2. ### How do you create a route in the App Router?

   In the App Router, you create routes by adding files to the `app` directory. Each file corresponds to a route, and you can create nested routes by creating subdirectories.

   ```
   app/
   ├── page.js          // Home page
   ├── about/
   │   └── page.js      // About page
   └── blog/
       ├── page.js      // Blog index page
       └── [slug]/
           └── page.js  // Dynamic blog post page
   ```

   [:arrow_up: Back to Top](#app-router-table-of-contents)

3. ### How do you create a dynamic route with app router in Next.js?

   In the App Router, you create dynamic routes by using square brackets in the file name. For example, to create a dynamic blog post route, you would create a file named `[slug]/page.js` inside the `blog` directory.

   ```
   app/
   └── blog/
       └── [slug]/
           └── page.js  // Dynamic blog post page
   ```

   [:arrow_up: Back to Top](#app-router-table-of-contents)

4. ### How do you create custom error pages in Next.js?

   By creating error.js files in app directory.

   ```jsx
   // app/error.js
   export default function ErrorPage() {
     return <h1>Custom Error Page</h1>;
   }
   ```

   [:arrow_up: Back to Top](#app-router-table-of-contents)

5. ### How do you handle form submissions in Next.js?

   Using client-side form handling or API routes for server-side handling.

   [:arrow_up: Back to Top](#app-router-table-of-contents)

6. ### How do you handle middleware in Next.js?

   By creating a middleware.js file in the app directory.

   [:arrow_up: Back to Top](#app-router-table-of-contents)

7. ### How do you implement authentication in Next.js?

   Using next-auth or a custom authentication solution.

   [:arrow_up: Back to Top](#app-router-table-of-contents)

8. ### How to add authjs in nextjs app router?

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

   [:arrow_up: Back to Top](#app-router-table-of-contents)

9. ### How do you handle authentication tokens in Next.js?

   By using cookies or local storage to store authentication tokens.

   ```js
   // Example of setting a token in a cookie
   import Cookies from "js-cookie";

   function setToken(token) {
     Cookies.set("authToken", token, { expires: 7 }); // Expires in 7 days
   }

   function getToken() {
     return Cookies.get("authToken");
   }
   ```

   [:arrow_up: Back to Top](#app-router-table-of-contents)

10. ### How to add credentials in nextjs app router?

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

    [:arrow_up: Back to Top](#app-router-table-of-contents)

11. ### What is use server in Next.js?

    The `use server` directive is used to indicate that a function should be executed on the server side. It allows you to write server-side logic in a component or function that can be called from the client side.

    ```jsx
    "use server";

    export async function myServerFunction() {
      // Server-side logic here
      return "Hello from the server!";
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

12. ### Difference between using & not using use server in Next.js?

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

    [:arrow_up: Back to Top](#app-router-table-of-contents)

13. ### How do you handle API routes in Next.js?

    By creating files in the `app/api` directory, where each file corresponds to an API endpoint.

    ```jsx
    // app/api/hello/route.js
    export async function GET(request) {
      return new Response("Hello, World!");
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

14. ### How do middleware work in Next.js?

    Middleware in Next.js allows you to run code before a request is completed. You can use it to modify the request or response, redirect users, or perform authentication checks.

    ```js
    // app/middleware.js
    import { NextResponse } from "next/server";
    export function middleware(request) {
      // Perform some logic here
      if (request.nextUrl.pathname === "/") {
        return NextResponse.redirect(new URL("/home", request.url));
      }
      return NextResponse.next();
    }
    ```

    You can also specify which paths the middleware should apply to:

    ```js
    // app/middleware.js
    export const config = {
      matcher: ["/about/:path*", "/blog/:path*"],
    };
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

15. ### What is form action in Next.js?

    The `formAction` is a special attribute used in Next.js to define the action URL for a form submission. It allows you to specify a server-side function that will handle the form submission.

    ```jsx
    // app/form-example/page.js
    "use server";

    export async function handleSubmit(formData) {
      const name = formData.get("name");
      console.log("Form submitted with name:", name);
      return { success: true };
    }

    export default function FormExample() {
      return (
        <form action={handleSubmit}>
          <input type="text" name="name" />
          <button type="submit">Submit</button>
        </form>
      );
    }
    ```

    In this example, when the form is submitted, the `handleSubmit` function will be called on the server side with the form data.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

16. ### How do you handle file uploads in Next.js?

    By using the `formData` API in a server action to handle file uploads.

    ```jsx
    // app/upload/page.js
    "use server";

    export async function handleUpload(formData) {
      const file = formData.get("file");
      // Process the file (e.g., save it to a storage service)
      console.log("File uploaded:", file.name);
      return { success: true };
    }

    export default function UploadPage() {
      return (
        <form action={handleUpload} encType="multipart/form-data">
          <input type="file" name="file" />
          <button type="submit">Upload</button>
        </form>
      );
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

17. ### Mention some common use cases for the App Router in Next.js.

    - Creating nested routes with layouts.
    - Implementing server-side rendering for dynamic content.
    - Handling API routes for backend functionality.
    - Managing authentication and authorization flows.
    - Building complex applications with shared layouts and components.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

18. ### One of the main differences between the App Router and Pages Router in Next.js?

    The App Router allows for nested routes, layouts, and server components, while the Pages Router uses a flat file structure for routing and does not support nested routes or layouts.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

19. ### What is the use of the `use client` directive in Next.js?

    The `use client` directive is used to indicate that a component should be rendered on the client side. It allows you to write client-side logic in a component that can be executed in the browser.

    ```jsx
    "use client";

    export default function ClientComponent() {
      return <div>This component is rendered on the client side.</div>;
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

20. ### Is it possible to use both App Router and Pages Router in the same Next.js project?

    Yes, it is possible to use both App Router and Pages Router in the same Next.js project. You can have the `app` directory for the App Router and the `pages` directory for the Pages Router, allowing you to take advantage of both routing systems.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

21. ### Are there any limitations of the App Router in Next.js?

    Yes, some limitations of the App Router include:

    - It is only available in Next.js 13 and later versions.
    - It may not support all features available in the Pages Router.
    - Some third-party libraries may not be compatible with the App Router.
    - Many features from the Pages Router, such as `getStaticProps` and `getServerSideProps`, are not available in the App Router.
    - The App Router is still evolving, and some features may change or be added in future releases.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

22. ### Explain the concept of authorization in middleware & routes in Next.js.

    Authorization in middleware and routes in Next.js involves checking if a user has the necessary permissions to access a specific route or perform an action. This can be done by verifying user roles, permissions, or tokens in the middleware function before allowing access to the route.

    ```js
    // app/middleware.js
    import { NextResponse } from "next/server";

    export function middleware(request) {
      const token = request.cookies.get("authToken");

      if (!token) {
        return NextResponse.redirect(new URL("/login", request.url));
      }

      // Additional authorization logic can go here

      return NextResponse.next();
    }

    export const config = {
      matcher: ["/protected/:path*"], // Apply middleware to protected routes
    };
    ```

    In this example, the middleware checks for an authentication token in the cookies. If the token is not present, it redirects the user to the login page. If the token is valid, it allows access to the protected routes.

    ```js
    // app/api/protected/route.js
    import { NextResponse } from "next/server";
    import jwt from "jsonwebtoken";
    export async function GET(request) {
      const token = request.cookies.get("authToken");

      if (!token) {
        return NextResponse.json({ error: "Unauthorized" }, { status: 401 });
      }

      try {
        const decoded = jwt.verify(token, process.env.JWT_SECRET);
        // Handle the request for authorized users
        return NextResponse.json({
          message: "Protected data",
          userId: decoded.userId,
        });
      } catch (error) {
        return NextResponse.json({ error: "Invalid token" }, { status: 401 });
      }
    }
    ```

    In this example, the API route checks for the authentication token in the request cookies. If the token is not present, it returns a 401 Unauthorized response. If the token is valid, it returns the protected data.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

23. ### The difference between `use server` and `use client` in Next.js?

    - **`use server`**: Indicates that the function should be executed on the server side. It allows you to write server-side logic that can be called from the client side.

    - **`use client`**: Indicates that the component should be rendered on the client side. It allows you to write client-side logic that can be executed in the browser.

    ```jsx
    // Example of use server
    "use server";

    export async function fetchData() {
      const response = await fetch("https://api.example.com/data");
      const data = await response.json();
      return data;
    }

    // Example of use client
    ("use client");

    export default function ClientComponent() {
      return <div>This component is rendered on the client side.</div>;
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

24. ### Understand the concept of server actions in Next.js.

    Server actions in Next.js allow you to define functions that can be executed on the server side when a form is submitted or an action is triggered. These functions can handle data processing, database interactions, or any server-side logic.

    ```jsx
    // app/actions/submitForm.js
    "use server";

    export async function submitForm(formData) {
      const name = formData.get("name");
      console.log("Form submitted with name:", name);
      return { success: true };
    }
    ```

    You can then use this action in a form:

    ```jsx
    // app/form/page.js
    import { submitForm } from "../actions/submitForm";

    export default function FormPage() {
      return (
        <form action={submitForm}>
          <input type="text" name="name" />
          <button type="submit">Submit</button>
        </form>
      );
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

25. ### Whats are the benifit of using server actions in Next.js?

    - **Performance**: Server actions allow you to offload heavy computations or data processing to the server, reducing the load on the client.
    - **Security**: Sensitive operations can be performed on the server, preventing exposure of sensitive data or logic to the client.
    - **Simplified Data Fetching**: You can fetch data directly in server actions without needing to manage client-side state or effects.
    - **Reduced Client Bundle Size**: By moving logic to the server, you can reduce the amount of JavaScript sent to the client, improving load times.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

26. ### What's are the problem of using server actions in Next.js?

    - **Latency**: Server actions can introduce latency since they require a round trip to the server, which may not be ideal for real-time interactions.
    - **Complexity**: Managing server actions can add complexity to your application, especially if you have many actions or need to handle different states.
    - **Limited Client-Side Interactivity**: Since server actions are executed on the server, they may not provide the same level of interactivity as client-side functions.
    - **Debugging Challenges**: Debugging server actions can be more challenging compared to client-side code, as you may not have access to browser developer tools.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

27. ### Alternative options instead of server actions in Next.js?

    - **API Routes**: You can create API routes to handle server-side logic and data fetching, which can be called from the client side.
    - **Client-Side Fetching**: Use client-side data fetching methods like `useEffect` or libraries like SWR or React Query to manage data on the client side.
    - **Static Site Generation (SSG)**: Use SSG for pages that can be pre-rendered at build time, reducing the need for server actions.
    - **Server-Side Rendering (SSR)**: Use SSR for dynamic pages that require server-side data fetching on each request.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

28. ### Alternative solutions example of not using server actions in Next.js?

    Instead of using server actions, you can use API routes to handle form submissions or data processing. Here's an example:

    ```jsx
    // app/api/submitForm/route.js
    export async function POST(request) {
      const formData = await request.formData();
      const name = formData.get("name");
      console.log("Form submitted with name:", name);
      return new Response(JSON.stringify({ success: true }), {
        status: 200,
        headers: { "Content-Type": "application/json" },
      });
    }
    ```

    You can then call this API route from a client-side component:

    ```jsx
    // app/form/page.js
    export default function FormPage() {
      const handleSubmit = async (event) => {
        event.preventDefault();
        const formData = new FormData(event.target);
        const response = await fetch("/api/submitForm", {
          method: "POST",
          body: formData,
        });
        const result = await response.json();
        console.log(result);
      };

      return (
        <form onSubmit={handleSubmit}>
          <input type="text" name="name" />
          <button type="submit">Submit</button>
        </form>
      );
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

29. ### JWT Token in Next.js App Router?

    JSON Web Tokens (JWT) can be used in the Next.js App Router for authentication and authorization. You can create a JWT token upon user login and store it in a cookie or local storage. Then, you can verify the token in API routes or server-side functions to authenticate users.

    ```js
    import jwt from "jsonwebtoken";

    // Create a JWT token
    const token = jwt.sign({ userId: user.id }, process.env.JWT_SECRET, {
      expiresIn: "1h",
    });

    // Verify the JWT token
    jwt.verify(token, process.env.JWT_SECRET, (err, decoded) => {
      if (err) {
        return res.status(401).json({ error: "Invalid token" });
      }
      // Proceed with authenticated user
    });
    ```

    Using it on application:

    ```jsx
    // app/api/auth/route.js
    import { NextResponse } from "next/server";
    import jwt from "jsonwebtoken";
    export async function POST(request) {
      const { token } = await request.json();
      try {
        const decoded = jwt.verify(token, process.env.JWT_SECRET);
        return NextResponse.json({ userId: decoded.userId });
      } catch (error) {
        return NextResponse.json({ error: "Invalid token" }, { status: 401 });
      }
    }
    ```

    You can also use JWT tokens for protecting API routes:

    ```js
    // app/api/protected/route.js
    import { NextResponse } from "next/server";
    import jwt from "jsonwebtoken";
    export async function GET(request) {
      const token = request.cookies.get("authToken");

      if (!token) {
        return NextResponse.json({ error: "Unauthorized" }, { status: 401 });
      }

      try {
        const decoded = jwt.verify(token, process.env.JWT_SECRET);
        // Handle the request for authorized users
        return NextResponse.json({
          message: "Protected data",
          userId: decoded.userId,
        });
      } catch (error) {
        return NextResponse.json({ error: "Invalid token" }, { status: 401 });
      }
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

30. ### Context of JWT Token in Next.js App Router?

    The context of using JWT tokens in the Next.js App Router is primarily for authentication and authorization purposes. JWT tokens allow you to securely transmit user information between the client and server, enabling you to verify user identity and permissions without needing to store session data on the server.

    This approach is particularly useful for stateless applications where you want to maintain user sessions without relying on server-side session storage.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

31. ### Is App Router better than Pages Router in Next.js?

    The App Router offers more flexibility and features compared to the Pages Router, such as nested routes, layouts, and server components. It is designed for building complex applications with shared layouts and components.

    However, the choice between App Router and Pages Router depends on your specific use case. If you need simple routing without nested routes or layouts, the Pages Router may be sufficient.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

32. ### How to handle global state management in Next.js with the App Router?

    You can handle global state management in Next.js with the App Router using libraries like Redux, Zustand, or React Context API. These libraries allow you to create a global store that can be accessed from any component in your application.

    - **Using React Context API**:

    ```jsx
    // app/context/GlobalState.js
    import { createContext, useContext, useState } from "react";

    const GlobalStateContext = createContext();

    export function GlobalStateProvider({ children }) {
      const [state, setState] = useState({ user: null });

      return (
        <GlobalStateContext.Provider value={{ state, setState }}>
          {children}
        </GlobalStateContext.Provider>
      );
    }

    export function useGlobalState() {
      return useContext(GlobalStateContext);
    }
    ```

    Then wrap your application with the `GlobalStateProvider`:

    ```jsx
    // app/layout.js
    import { GlobalStateProvider } from "./context/GlobalState";

    export default function RootLayout({ children }) {
      return (
        <html lang="en">
          <body>
            <GlobalStateProvider>{children}</GlobalStateProvider>
          </body>
        </html>
      );
    }
    ```

    Now you can access the global state in any component using the `useGlobalState` hook.

    ```jsx
    // app/page.js
    import { useGlobalState } from "./context/GlobalState";

    export default function HomePage() {
      const { state, setState } = useGlobalState();

      return (
        <div>
          <h1>Welcome, {state.user ? state.user.name : "Guest"}</h1>
          <button onClick={() => setState({ user: { name: "John Doe" } })}>
            Log In
          </button>
        </div>
      );
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

33. ### What is the fetch API in Next.js App Router?

    In the Next.js App Router, you can use the `fetch` API to make HTTP requests to external APIs or your own API routes. The `fetch` function is available globally in both server and client components.

    - **Example of using fetch in a server component**:

    ```jsx
    // app/api/data/route.js
    export async function GET() {
      const response = await fetch("https://api.example.com/data");
      const data = await response.json();
      return new Response(JSON.stringify(data), {
        headers: { "Content-Type": "application/json" },
      });
    }
    ```

    - **Example of using fetch in a client component**:

    ```jsx
    // app/page.js
    import { useEffect, useState } from "react";

    export default function HomePage() {
      const [data, setData] = useState(null);

      useEffect(() => {
        async function fetchData() {
          const response = await fetch("/api/data");
          const result = await response.json();
          setData(result);
        }
        fetchData();
      }, []);

      return (
        <div>
          <h1>Data from API</h1>
          <pre>{JSON.stringify(data, null, 2)}</pre>
        </div>
      );
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

34. ### How do you create route groups in the App Router?

    Route groups allow you to organize routes without affecting the URL structure. You create them by wrapping folder names in parentheses `()`.

    ```
    app/
    ├── (marketing)/
    │   ├── about/
    │   │   └── page.js     // /about
    │   └── contact/
    │       └── page.js     // /contact
    ├── (shop)/
    │   ├── products/
    │   │   └── page.js     // /products
    │   └── cart/
    │       └── page.js     // /cart
    └── layout.js           // Shared layout
    ```

    Route groups are useful for organizing code, creating different layouts for different sections, or conditionally including layouts.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

35. ### What are parallel routes in Next.js App Router?

    Parallel routes allow you to render multiple pages simultaneously in the same layout. They are defined using slots with the `@` convention.

    ```
    app/
    ├── layout.js
    ├── page.js
    ├── @analytics/
    │   └── page.js
    └── @team/
        └── page.js
    ```

    ```jsx
    // app/layout.js
    export default function Layout({ children, analytics, team }) {
      return (
        <div>
          <div>{children}</div>
          <div>{analytics}</div>
          <div>{team}</div>
        </div>
      );
    }
    ```

    This allows you to render independent pages that can load at different speeds and handle their own loading and error states.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

36. ### How do you implement intercepting routes in App Router?

    Intercepting routes allow you to load a route from another part of your application while keeping the context of the current page, similar to modals.

    ```
    app/
    ├── feed/
    │   └── page.js
    ├── photo/
    │   └── [id]/
    │       └── page.js
    └── @modal/
        └── (..)photo/
            └── [id]/
                └── page.js
    ```

    The `(..)` convention indicates that you want to intercept routes at the same level. Intercepting routes use conventions like:

    - `(.)` - match segments on the same level
    - `(..)` - match segments one level above
    - `(..)(..)` - match segments two levels above
    - `(...)` - match segments from the root app directory

    [:arrow_up: Back to Top](#app-router-table-of-contents)

37. ### What is the loading.js file in App Router?

    The `loading.js` file creates loading UI that shows instantly while route segments are loading. It automatically wraps the page and its children in a React Suspense boundary.

    ```jsx
    // app/dashboard/loading.js
    export default function Loading() {
      return (
        <div className="loading">
          <p>Loading dashboard...</p>
          <div className="spinner"></div>
        </div>
      );
    }
    ```

    ```
    app/
    ├── dashboard/
    │   ├── loading.js      // Loading UI for dashboard
    │   ├── page.js
    │   └── settings/
    │       ├── loading.js  // Loading UI for settings
    │       └── page.js
    ```

    The loading UI will be shown immediately on navigation and can be nested for granular loading states.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

38. ### How do you handle not-found pages in App Router?

    You can create custom not-found pages using the `not-found.js` file. This file defines UI to render when the `notFound()` function is thrown within a route segment.

    ```jsx
    // app/not-found.js
    import Link from "next/link";

    export default function NotFound() {
      return (
        <div>
          <h2>Not Found</h2>
          <p>Could not find requested resource</p>
          <Link href="/">Return Home</Link>
        </div>
      );
    }
    ```

    You can also trigger the not-found page programmatically:

    ```jsx
    // app/page.js
    import { notFound } from "next/navigation";

    export default function Page({ params }) {
      const post = getPost(params.id);

      if (!post) {
        notFound();
      }

      return <div>{post.title}</div>;
    }
    ```

    [:arrow_up: Back to Top](#app-router-table-of-contents)

39. ### What is the template.js file in App Router?

    The `template.js` file is similar to `layout.js` but creates a new instance for each of its children on navigation. This means state is not preserved and effects are re-synchronized.

    ```jsx
    // app/template.js
    export default function Template({ children }) {
      return <div className="template-wrapper">{children}</div>;
    }
    ```

    Key differences from layout:

    - **Layout**: State is preserved, DOM elements are not re-created
    - **Template**: New instance on navigation, DOM elements are re-created

    Templates are useful when you need:

    - CSS/JS animations on route changes
    - Features that rely on `useEffect` and `useState`
    - To change the default browser behavior

    [:arrow_up: Back to Top](#app-router-table-of-contents)

40. ### How do you implement nested layouts in App Router?

    Nested layouts are implemented by creating `layout.js` files in different route segments. Layouts are nested automatically based on the folder structure.

    ```
    app/
    ├── layout.js           // Root layout
    ├── page.js             // Home page
    └── dashboard/
        ├── layout.js       // Dashboard layout
        ├── page.js         // Dashboard page
        └── settings/
            ├── layout.js   // Settings layout
            └── page.js     // Settings page
    ```

    ```jsx
    // app/layout.js (Root Layout)
    export default function RootLayout({ children }) {
      return (
        <html lang="en">
          <body>
            <nav>Global Navigation</nav>
            {children}
          </body>
        </html>
      );
    }

    // app/dashboard/layout.js
    export default function DashboardLayout({ children }) {
      return (
        <div className="dashboard">
          <aside>Dashboard Sidebar</aside>
          <main>{children}</main>
        </div>
      );
    }
    ```

    When visiting `/dashboard/settings`, all three layouts (root, dashboard, settings) will be rendered in a nested structure.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

41. ### What are route handlers vs API routes in App Router?

    In the App Router, API routes are now called "Route Handlers" and use the `route.js` file convention instead of the pages-based approach.

    **Pages Router (API Routes)**:

    ```
    pages/api/users.js
    ```

    **App Router (Route Handlers)**:

    ```
    app/api/users/route.js
    ```

    ```jsx
    // app/api/users/route.js
    export async function GET(request) {
      const users = await getUsers();
      return Response.json(users);
    }

    export async function POST(request) {
      const data = await request.json();
      const user = await createUser(data);
      return Response.json(user, { status: 201 });
    }

    export async function PUT(request) {
      const data = await request.json();
      const user = await updateUser(data);
      return Response.json(user);
    }

    export async function DELETE(request) {
      await deleteUser(request.nextUrl.searchParams.get("id"));
      return new Response(null, { status: 204 });
    }
    ```

    Route handlers support all HTTP methods and provide better TypeScript support and Web APIs compatibility.

    [:arrow_up: Back to Top](#app-router-table-of-contents)

42. ### How do you handle streaming and suspense in App Router?

    The App Router has built-in support for streaming and React Suspense, allowing you to progressively render and stream UI to the client.

    ```jsx
    // app/page.js
    import { Suspense } from "react";

    async function UserProfile({ userId }) {
      const user = await getUserData(userId); // This can be slow
      return <div>Welcome, {user.name}!</div>;
    }

    async function UserPosts({ userId }) {
      const posts = await getUserPosts(userId); // This can also be slow
      return (
        <div>
          {posts.map((post) => (
            <div key={post.id}>{post.title}</div>
          ))}
        </div>
      );
    }

    export default function Page({ params }) {
      return (
        <div>
          <h1>User Dashboard</h1>
          <Suspense fallback={<div>Loading profile...</div>}>
            <UserProfile userId={params.id} />
          </Suspense>
          <Suspense fallback={<div>Loading posts...</div>}>
            <UserPosts userId={params.id} />
          </Suspense>
        </div>
      );
    }
    ```

    Benefits of streaming:

    - Faster initial page load
    - Better perceived performance
    - Progressive enhancement
    - SEO-friendly as search engines can index content as it streams

    [:arrow_up: Back to Top](#app-router-table-of-contents)

43. ### What is React Server Components (RSC) in App Router?

    React Server Components (RSC) are a new React feature that allows components to be rendered on the server. In the App Router, components are Server Components by default.

    **Server Components** (default):

    ```jsx
    // app/page.js - This is a Server Component
    async function ServerComponent() {
      const data = await fetch("https://api.example.com/data");
      const result = await data.json();

      return (
        <div>
          <h1>Server Rendered Data</h1>
          <p>{result.message}</p>
        </div>
      );
    }
    ```

    **Client Components** (opt-in with "use client"):

    ```jsx
    // app/components/ClientComponent.js
    "use client";

    import { useState } from "react";

    export default function ClientComponent() {
      const [count, setCount] = useState(0);

      return (
        <button onClick={() => setCount(count + 1)}>Count: {count}</button>
      );
    }
    ```

    **Benefits of Server Components**:

    - Direct access to server-side resources (databases, file system)
    - No JavaScript bundle sent to client
    - Improved performance and SEO
    - Automatic code splitting

    **When to use Client Components**:

    - Interactive features (event handlers, state)
    - Browser-only APIs (localStorage, geolocation)
    - React hooks (useState, useEffect)

    [:arrow_up: Back to Top](#app-router-table-of-contents)
