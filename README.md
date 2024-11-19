## NextJS Interview Questions & Answers

:rocket: This repository aimed to contains 500 nextjs interview questions & answers with exmample.

---

<!-- TOC Start -->

### Table of Contents

|  No | Contents                                                                                                                                                            |
| --: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | [What is NextJS](#what-is-nextjs)                                                                                                                                   |
|   2 | [How do you create a new Next.js project?](#how-do-you-create-a-new-nextjs-project)                                                                                 |
|   3 | [What is the purpose of the `pages or app` directory in Next.js?](#what-is-the-purpose-of-the-`pages-or-app`-directory-in-nextjs)                                                     |
|   4 | [What is file-based routing in Next.js?](#what-is-file-based-routing-in-nextjs)                                                                                     |
|   5 | [How do you create a dynamic route in Next.js?](#how-do-you-create-a-dynamic-route-in-nextjs)                                                                       |
|   6 | [What is getStaticProps?](#what-is-getstaticprops)                                                                                                                  |
|   7 | [What is getServerSideProps?](#what-is-getserversideprops)                                                                                                          |
|   8 | [What is getStaticPaths?](#what-is-getstaticpaths)                                                                                                                  |
|   9 | [What is the difference between getStaticProps and getServerSideProps?](#what-is-the-difference-between-getstaticprops-and-getserversideprops)                      |
|  10 | [What is the Link component in Next.js?](#what-is-the-link-component-in-nextjs)                                                                                     |
|  11 | [What is the useRouter hook in Next.js?](#what-is-the-userouter-hook-in-nextjs)                                                                                     |
|  12 | [How do you navigate programmatically in Next.js?](#how-do-you-navigate-programmatically-in-nextjs)                                                                 |
|  13 | [What is the \_app.js file in Next.js?](#what-is-the-_appjs-file-in-nextjs)                                                                                         |
|  14 | [What is the \_document.js file in Next.js?](#what-is-the-_documentjs-file-in-nextjs)                                                                               |
|  15 | [How do you add global CSS in Next.js?](#how-do-you-add-global-css-in-nextjs)                                                                                       |
|  16 | [How do you add component-level CSS in Next.js?](#how-do-you-add-component-level-css-in-nextjs)                                                                     |
|  17 | [What is static site generation (SSG) in Next.js?](#what-is-static-site-generation-ssg-in-nextjs)                                                                   |
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

1. ### What is NextJS

   Next.js is a React framework for building full-stack web applications.

   [:arrow_up: Back to Top](#table-of-contents)

2. ### How do you create a new Next.js project?

   Using command

   > npx create-next-app

   [:arrow_up: Back to Top](#table-of-contents)

3. ### What is the purpose of the `pages or app` directory in Next.js?

   It contains React components that are automatically routed based on their file name.

   [:arrow_up: Back to Top](#table-of-contents)
5. ### How many ways we can manage routing of application with Next.js?
   We can manage or create routing of application in 2 ways currently.
   - Pages Router
   - App Router (Support from v13)
   
   [:arrow_up: Back to Top](#table-of-contents)

7. ### What is file-based routing in Next.js?

   Routing based on the file structure in the pages directory.

   [:arrow_up: Back to Top](#table-of-contents)

8. ### How do you create a dynamic route in Next.js?

   By using square brackets in the filename

   > blogs/[id].js.

   > blogs/[id]/index.js

   [:arrow_up: Back to Top](#table-of-contents)

9. ### What is getStaticProps?

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

10. ### What is getServerSideProps?

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

11. ### What is getStaticPaths?

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

11. ### What is the difference between getStaticProps and getServerSideProps?

   getStaticProps fetches data at build time, while getServerSideProps fetches data on each request.

   [:arrow_up: Back to Top](#table-of-contents)

11. ### What is the Link component in Next.js?

    A component for client-side navigation between pages.

    ```jsx
    import Link from 'next/link'

    <Link href="/">Home</Link>
    <Link href="/about">About</Link>
    ```

    [:arrow_up: Back to Top](#table-of-contents)

12. ### What is the useRouter hook in Next.js?

    A hook that allows access to the router object and perform navigation.

    [:arrow_up: Back to Top](#table-of-contents)

13. ### How do you navigate programmatically in Next.js?

    Using useRouter() hook.

    ```jsx
    const router = userRouter();

    function handleClick() {
      router.push(`/path`);
    }

    <button onClick={handleClick}>Go There</button>;
    ```

    [:arrow_up: Back to Top](#table-of-contents)

14. ### What is the \_app.js file in Next.js?

    A custom App component that initializes pages and can add global styles or layout components.

    [:arrow_up: Back to Top](#table-of-contents)

15. ### What is the \_document.js file in Next.js?

    A custom Document component that allows customization of the HTML document structure.

    [:arrow_up: Back to Top](#table-of-contents)

16. ### How do you add global CSS in Next.js?

    By importing the CSS file in \_app.js.

    [:arrow_up: Back to Top](#table-of-contents)

17. ### How do you add component-level CSS in Next.js?

    Using CSS modules with a .module.css file extension.

    [:arrow_up: Back to Top](#table-of-contents)

18. ### What is static site generation (SSG) in Next.js?

    Pre-rendering pages at build time.

    [:arrow_up: Back to Top](#table-of-contents)

19. ### What is server-side rendering (SSR) in Next.js?

    Rendering pages on each request.

    [:arrow_up: Back to Top](#table-of-contents)

20. ### What is incremental static regeneration (ISR) in Next.js?

    Re-generating static pages at runtime as traffic comes in.

    [:arrow_up: Back to Top](#table-of-contents)

21. ### What is the Image component in Next.js?

    A component that optimizes images for faster loading.

    [:arrow_up: Back to Top](#table-of-contents)

22. ### What is next.config.js?

    A configuration file to customize Next.js settings.

    [:arrow_up: Back to Top](#table-of-contents)

23. ### How do you enable TypeScript in a Next.js project?

    By adding a tsconfig.json file.

    [:arrow_up: Back to Top](#table-of-contents)

24. ### What is API Routes in Next.js?

    A feature to create API endpoints in the pages/api directory.

    [:arrow_up: Back to Top](#table-of-contents)

25. ### How do you deploy a Next.js app to Vercel?

    By connecting the repository to Vercel and deploying it.

    [:arrow_up: Back to Top](#table-of-contents)

26. ### What is pre-rendering in Next.js?

    Generating HTML for pages in advance, instead of on each request.

    [:arrow_up: Back to Top](#table-of-contents)

27. ### What is the difference between static generation and server-side rendering?

    Static generation pre-renders at build time, SSR pre-renders on each request.

    [:arrow_up: Back to Top](#table-of-contents)

28. ### How do you handle redirects in Next.js?

    By configuring redirects in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

29. ### What is the Head component in Next.js?

    A component for modifying the of a page.

    [:arrow_up: Back to Top](#table-of-contents)

30. ### How do you fetch data in a Next.js page?

    Using getStaticProps or getServerSideProps.

    [:arrow_up: Back to Top](#table-of-contents)

31. ### What is dynamic import in Next.js?

    A feature to load components or modules dynamically.

    [:arrow_up: Back to Top](#table-of-contents)

32. ### How do you handle environment variables in Next.js?

    By adding them to .env.local and accessing via process.env.

    [:arrow_up: Back to Top](#table-of-contents)

33. ### What is fallback in getStaticPaths?

    Determines how to handle missing paths, with true, false, or ‘blocking’.

    [:arrow_up: Back to Top](#table-of-contents)

34. ### What is a custom server in Next.js?

    A way to customize the server-side behavior, e.g., with Express.

    [:arrow_up: Back to Top](#table-of-contents)

35. ### What is the next/head package used for?

    To manage the document head for meta tags, title, etc.

    [:arrow_up: Back to Top](#table-of-contents)

36. ### How do you create a 404 page in Next.js?

    By adding a 404.js file in the pages directory.

    [:arrow_up: Back to Top](#table-of-contents)

37. ### What is the use of next export command?

    To export a static version of the Next.js app.

    [:arrow_up: Back to Top](#table-of-contents)

38. ### How do you optimize fonts in Next.js?

    By using the built-in font optimization feature.

    [:arrow_up: Back to Top](#table-of-contents)

39. ### What is the default port for a Next.js app?

    Port 3000.

    [:arrow_up: Back to Top](#table-of-contents)

40. ### How do you add custom headers in Next.js?

    By configuring headers in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

41. ### What is Fast Refresh in Next.js?

    A feature for quick feedback when editing React components.

    [:arrow_up: Back to Top](#table-of-contents)

42. ### What is the public folder in Next.js?

    A folder for static assets served from the root URL.

    [:arrow_up: Back to Top](#table-of-contents)

43. ### How do you configure a custom Babel setup in Next.js?

    By adding a babel.config.js file.

    [:arrow_up: Back to Top](#table-of-contents)

44. ### How do you handle internationalization (i18n) in Next.js?

    By configuring i18n settings in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

45. ### What is React Strict Mode in Next.js?

    A development mode that highlights potential problems in an application.

    [:arrow_up: Back to Top](#table-of-contents)

46. ### What is a singleton router in Next.js?

    A single router instance accessible across the application.

    [:arrow_up: Back to Top](#table-of-contents)

47. ### What is the useTranslation hook in Next.js?

    A hook for handling translations when using i18n.

    [:arrow_up: Back to Top](#table-of-contents)

48. ### How do you create custom error pages in Next.js?

    By adding \_error.js in the pages directory.

    [:arrow_up: Back to Top](#table-of-contents)

49. ### What is AMP in Next.js?

    Accelerated Mobile Pages, a framework for fast-loading mobile pages.

    [:arrow_up: Back to Top](#table-of-contents)

50. ### How do you enable AMP in Next.js?

    By adding amp attribute to a page component.

    [:arrow_up: Back to Top](#table-of-contents)

51. ### What is the next/image component used for?

    To optimize and serve images in a Next.js application.

    [:arrow_up: Back to Top](#table-of-contents)

52. ### What is the next/link component used for?

    For client-side navigation between pages.

    [:arrow_up: Back to Top](#table-of-contents)

53. ### What is the difference between pages and components directories?

    pages contains routable components, components contains reusable UI components.

    [:arrow_up: Back to Top](#table-of-contents)

54. ### How do you handle middleware in Next.js?

    Using middleware functions in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

55. ### How do you add polyfills in Next.js?

    By customizing the webpack configuration in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

56. ### What is the difference between client-side and server-side rendering in next.js?

    Client-side rendering happens in the browser, server-side rendering happens on the server.

    [:arrow_up: Back to Top](#table-of-contents)

57. ### What is static optimization in Next.js?

    Automatically determining if a page can be statically generated.

    [:arrow_up: Back to Top](#table-of-contents)

58. ### How do you fetch data on the client-side in Next.js?

    Using useEffect and fetch or other data fetching libraries.

    [:arrow_up: Back to Top](#table-of-contents)

59. ### How do you implement authentication in Next.js?

    Using libraries like NextAuth.js or custom authentication logic.

    [:arrow_up: Back to Top](#table-of-contents)

60. ### What is the difference between \_app.js and \_document.js?

    \_app.js is for global components, \_document.js is for modifying the HTML document structure.

    [:arrow_up: Back to Top](#table-of-contents)

61. ### How do you create API endpoints in Next.js?

    By adding files to the pages/api directory.

    [:arrow_up: Back to Top](#table-of-contents)

62. ### What is ISR in Next.js?

    Incremental Static Regeneration, updating static pages after build without redeploying.

    [:arrow_up: Back to Top](#table-of-contents)

63. ### How do you configure Webpack in Next.js?

    By extending the Webpack configuration in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

64. ### What is the purpose of next-env.d.ts?

    It provides type definitions for TypeScript support in Next.js.

    [:arrow_up: Back to Top](#table-of-contents)

65. ### How do you handle routing in a Next.js app?

    Using the file-based routing system in the pages directory.

    [:arrow_up: Back to Top](#table-of-contents)

66. ### What is the purpose of next/dynamic?

    To enable dynamic imports and code splitting.

    [:arrow_up: Back to Top](#table-of-contents)

67. ### How do you add meta tags in Next.js?

    Using the Head component from next/head.

    [:arrow_up: Back to Top](#table-of-contents)

68. ### What is the purpose of next-compose-plugins?

    To compose multiple plugins in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

69. ### How do you handle form submissions in Next.js?

    Using client-side form handling or API routes for server-side handling.

    [:arrow_up: Back to Top](#table-of-contents)

70. ### How do you set up Redux in a Next.js project?

    By creating a Redux store and integrating it with \_app.js.

    [:arrow_up: Back to Top](#table-of-contents)

71. ### What is the purpose of next/router?

    To handle routing and navigation within a Next.js app.

    [:arrow_up: Back to Top](#table-of-contents)

72. ### How do you use CSS-in-JS with Next.js?

    Using libraries like styled-components or Emotion.

    [:arrow_up: Back to Top](#table-of-contents)

73. ### How do you handle redirects in Next.js?

    By adding a redirects property in next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

74. ### How do you use Sass in a Next.js project?

    By installing sass and importing .scss files in your components.

    [:arrow_up: Back to Top](#table-of-contents)

75. ### What is the basePath option in Next.js?

    It allows you to specify a base path for the application.

    [:arrow_up: Back to Top](#table-of-contents)

76. ### How do you customize the 500 error page in Next.js?

    By creating a 500.js file in the pages directory.

    [:arrow_up: Back to Top](#table-of-contents)

77. ### What is the trailingSlash option in Next.js?

    It configures whether to include a trailing slash in the URLs.

    [:arrow_up: Back to Top](#table-of-contents)

78. ### What is the difference between push and replace in useRouter?

    push adds a new entry in the history stack, replace replaces the current entry.

    [:arrow_up: Back to Top](#table-of-contents)

79. ### What is ssr: false in dynamic import?

    It disables server-side rendering for the dynamically imported component.

    [:arrow_up: Back to Top](#table-of-contents)

80. ### How do you configure PWA in Next.js?

    By using plugins like next-pwa and configuring next.config.js.

    [:arrow_up: Back to Top](#table-of-contents)

81. ### How do you add Google Analytics to a Next.js project?

    By including the Google Analytics script in \_app.js or \_document.js.

    [:arrow_up: Back to Top](#table-of-contents)

82. ### What is the purpose of middleware in Next.js?

    To run code before a request is completed.

    [:arrow_up: Back to Top](#table-of-contents)

83. ### How do you use Apollo Client with Next.js?

    By setting up Apollo Provider in \_app.js and creating a client.

    [:arrow_up: Back to Top](#table-of-contents)

84. ### What is the publicRuntimeConfig in Next.js?

    Configuration exposed to the browser.

    [:arrow_up: Back to Top](#table-of-contents)

85. ### What is the serverRuntimeConfig in Next.js?

    Configuration only available on the server side.

    [:arrow_up: Back to Top](#table-of-contents)

86. ### What is the purpose of \_error.js in Next.js?

    To customize the error page for HTTP errors.

    [:arrow_up: Back to Top](#table-of-contents)

87. ### How do you perform client-side data fetching in Next.js?

    Using useEffect and fetch or any other data-fetching library.

    [:arrow_up: Back to Top](#table-of-contents)

88. ### What is the use of next-seo in Next.js?

    To manage SEO metadata in a Next.js application.

    [:arrow_up: Back to Top](#table-of-contents)

89. ### How do you use Tailwind CSS in Next.js?

    By installing tailwindcss and configuring it with PostCSS.

    [:arrow_up: Back to Top](#table-of-contents)

90. ### How do you configure next-i18next in Next.js?

    By installing next-i18next and setting up the configuration in next.config. js.

    [:arrow_up: Back to Top](#table-of-contents)

91. ### What is next/script used for?

    To optimize loading third-party scripts.

    [:arrow_up: Back to Top](#table-of-contents)

92. ### How do you enable custom fonts in Next.js?

    By using the next/font package or including fonts in the public directory.

    [:arrow_up: Back to Top](#table-of-contents)

93. ### How do you set up GraphQL in Next.js?

    By using Apollo Client or another GraphQL client.

    [:arrow_up: Back to Top](#table-of-contents)

94. ### What is swcMinify in next.config.js?

    It enables the use of the SWC compiler for minification.

    [:arrow_up: Back to Top](#table-of-contents)

95. ### What is the use of next-compose-plugins?

    To enable composition of multiple plugins in Next.js configuration.

    [:arrow_up: Back to Top](#table-of-contents)

96. ### What is a hybrid application in Next.js?

    An application that uses both static generation and server-side rendering.

    [:arrow_up: Back to Top](#table-of-contents)

97. ### How do you handle CORS in Next.js API routes?

    By setting headers in the API route handlers.

    [:arrow_up: Back to Top](#table-of-contents)

98. ### What is the purpose of rewrites in next.config.js?

    To map an incoming request path to a different destination path.

    [:arrow_up: Back to Top](#table-of-contents)

99. ### How do you manage cookies in Next.js?

    Using libraries like cookie or js-cookie to set and retrieve cookies.

    [:arrow_up: Back to Top](#table-of-contents)

100. ### How do you handle authentication tokens in Next.js?

    By storing tokens in cookies or local storage and sending them with requests.

    [:arrow_up: Back to Top](#table-of-contents)

101. ### What is next-pwa used for?

     To configure and enable Progressive Web App features in Next.js.

     [:arrow_up: Back to Top](#table-of-contents)

102. ### What is the next-sitemap package used for?

     To generate sitemaps for a Next.js application.

     [:arrow_up: Back to Top](#table-of-contents)

<!-- Question & Answers End -->
