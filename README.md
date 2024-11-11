## NextJS Interview Questions & Answers

:rocket: This repository aimed to contains 500 nextjs interview questions & answers with exmample.

---

<!-- TOC Start -->

### Table of Contents

| No | Content |
|----:|------------|
| 1 | [What is NextJS](#what-is-nextjs) |
| 2 | [How do you create a new Next.js project?](#how-do-you-create-a-new-nextjs-project) |
| 3 | [What is the purpose of the pages directory in Next.js?](#what-is-the-purpose-of-the-pages-directory-in-nextjs) |
| 4 | [What is file-based routing in Next.js?](#what-is-file-based-routing-in-nextjs) |
| 5 | [How do you create a dynamic route in Next.js?](#how-do-you-create-a-dynamic-route-in-nextjs) |
| 6 | [What is getStaticProps?](#what-is-getstaticprops) |
| 7 | [What is getServerSideProps?](#what-is-getserversideprops) |
| 8 | [What is getStaticPaths?](#what-is-getstaticpaths) |
| 9 | [What is the difference between getStaticProps and getServerSideProps?](#what-is-the-difference-between-getstaticprops-and-getserversideprops) |
| 10 | [What is the Link component in Next.js?](#what-is-the-link-component-in-nextjs) |
| 11 | [What is the useRouter hook in Next.js?](#what-is-the-userouter-hook-in-nextjs) |
| 12 | [How do you navigate programmatically in Next.js?](#how-do-you-navigate-programmatically-in-nextjs) |
| 13 | [What is the \_app.js file in Next.js?](#what-is-the-_appjs-file-in-nextjs) |
| 14 | [What is the \_document.js file in Next.js?](#what-is-the-_documentjs-file-in-nextjs) |
| 15 | [How do you add global CSS in Next.js?](#how-do-you-add-global-css-in-nextjs) |
| 16 | [How do you add component-level CSS in Next.js?](#how-do-you-add-component-level-css-in-nextjs) |
| 17 | [What is static site generation (SSG) in Next.js?](#what-is-static-site-generation-ssg-in-nextjs) |
| 18 | [What is server-side rendering (SSR) in Next.js?](#what-is-server-side-rendering-ssr-in-nextjs) |
| 19 | [What is incremental static regeneration (ISR) in Next.js?](#what-is-incremental-static-regeneration-isr-in-nextjs) |
| 20 | [What is the Image component in Next.js?](#what-is-the-image-component-in-nextjs) |
| 21 | [What is next.config.js?](#what-is-nextconfigjs) |
| 22 | [How do you enable TypeScript in a Next.js project?](#how-do-you-enable-typescript-in-a-nextjs-project) |
| 23 | [What is API Routes in Next.js?](#what-is-api-routes-in-nextjs) |
| 24 | [How do you deploy a Next.js app to Vercel?](#how-do-you-deploy-a-nextjs-app-to-vercel) |
| 25 | [What is pre-rendering in Next.js?](#what-is-pre-rendering-in-nextjs) |
| 26 | [What is the difference between static generation and server-side rendering?](#what-is-the-difference-between-static-generation-and-server-side-rendering) |
| 27 | [How do you handle redirects in Next.js?](#how-do-you-handle-redirects-in-nextjs) |
| 28 | [What is the Head component in Next.js?](#what-is-the-head-component-in-nextjs) |
| 29 | [How do you fetch data in a Next.js page?](#how-do-you-fetch-data-in-a-nextjs-page) |
| 30 | [What is dynamic import in Next.js?](#what-is-dynamic-import-in-nextjs) |
| 31 | [How do you handle environment variables in Next.js?](#how-do-you-handle-environment-variables-in-nextjs) |
| 32 | [What is fallback in getStaticPaths?](#what-is-fallback-in-getstaticpaths) |
| 33 | [What is a custom server in Next.js?](#what-is-a-custom-server-in-nextjs) |
| 34 | [What is the next/head package used for?](#what-is-the-nexthead-package-used-for) |
| 35 | [How do you create a 404 page in Next.js?](#how-do-you-create-a-404-page-in-nextjs) |
| 36 | [What is the use of next export command?](#what-is-the-use-of-next-export-command) |
| 37 | [How do you optimize fonts in Next.js?](#how-do-you-optimize-fonts-in-nextjs) |
| 38 | [What is the default port for a Next.js app?](#what-is-the-default-port-for-a-nextjs-app) |
| 39 | [How do you add custom headers in Next.js?](#how-do-you-add-custom-headers-in-nextjs) |
| 40 | [What is Fast Refresh in Next.js?](#what-is-fast-refresh-in-nextjs) |
| 41 | [What is the public folder in Next.js?](#what-is-the-public-folder-in-nextjs) |
| 42 | [How do you configure a custom Babel setup in Next.js?](#how-do-you-configure-a-custom-babel-setup-in-nextjs) |
| 43 | [How do you handle internationalization (i18n) in Next.js?](#how-do-you-handle-internationalization-i18n-in-nextjs) |
| 44 | [What is React Strict Mode in Next.js?](#what-is-react-strict-mode-in-nextjs) |
| 45 | [What is a singleton router in Next.js?](#what-is-a-singleton-router-in-nextjs) |
| 46 | [What is the useTranslation hook in Next.js?](#what-is-the-usetranslation-hook-in-nextjs) |
| 47 | [How do you create custom error pages in Next.js?](#how-do-you-create-custom-error-pages-in-nextjs) |
| 48 | [What is AMP in Next.js?](#what-is-amp-in-nextjs) |
| 49 | [How do you enable AMP in Next.js?](#how-do-you-enable-amp-in-nextjs) |
| 50 | [What is the next/image component used for?](#what-is-the-nextimage-component-used-for) |
| 51 | [What is the next/link component used for?](#what-is-the-nextlink-component-used-for) |
| 52 | [What is the difference between pages and components directories?](#what-is-the-difference-between-pages-and-components-directories) |
| 53 | [How do you handle middleware in Next.js?](#how-do-you-handle-middleware-in-nextjs) |
| 54 | [How do you add polyfills in Next.js?](#how-do-you-add-polyfills-in-nextjs) |
| 55 | [What is the difference between client-side and server-side rendering in Next.js?](#what-is-the-difference-between-client-side-and-server-side-rendering-in-nextjs) |
| 56 | [What is static optimization in Next.js?](#what-is-static-optimization-in-nextjs) |
| 57 | [How do you fetch data on the client-side in Next.js?](#how-do-you-fetch-data-on-the-client-side-in-nextjs) |
| 58 | [How do you implement authentication in Next.js?](#how-do-you-implement-authentication-in-nextjs) |
| 59 | [What is the difference between \_app.js and \_document.js?](#what-is-the-difference-between-_appjs-and-_documentjs) |
| 60 | [How do you create API endpoints in Next.js?](#how-do-you-create-api-endpoints-in-nextjs) |
| 61 | [What is ISR in Next.js?](#what-is-isr-in-nextjs) |
| 62 | [How do you configure Webpack in Next.js?](#how-do-you-configure-webpack-in-nextjs) |
| 63 | [What is the purpose of next-env.d.ts?](#what-is-the-purpose-of-next-envdts) |
| 64 | [How do you handle routing in a Next.js app?](#how-do-you-handle-routing-in-a-nextjs-app) |
| 65 | [What is the purpose of next/dynamic?](#what-is-the-purpose-of-nextdynamic) |
| 66 | [How do you add meta tags in Next.js?](#how-do-you-add-meta-tags-in-nextjs) |
| 67 | [What is the purpose of next-compose-plugins?](#what-is-the-purpose-of-next-compose-plugins) |
| 68 | [How do you handle form submissions in Next.js?](#how-do-you-handle-form-submissions-in-nextjs) |
| 69 | [How do you set up Redux in a Next.js project?](#how-do-you-set-up-redux-in-a-nextjs-project) |
| 70 | [What is the purpose of next/router?](#what-is-the-purpose-of-nextrouter) |
| 71 | [How do you use CSS-in-JS with Next.js?](#how-do-you-use-css-in-js-with-nextjs) |
| 72 | [How do you handle redirects in Next.js?](#how-do-you-handle-redirects-in-nextjs-1) |
| 73 | [How do you use Sass in a Next.js project?](#how-do-you-use-sass-in-a-nextjs-project) |
| 74 | [What is the basePath option in Next.js?](#what-is-the-basepath-option-in-nextjs) |
| 75 | [How do you customize the 500 error page in Next.js?](#how-do-you-customize-the-500-error-page-in-nextjs) |
| 76 | [What is the trailingSlash option in Next.js?](#what-is-the-trailingslash-option-in-nextjs) |
| 77 | [What is the difference between push and replace in useRouter?](#what-is-the-difference-between-push-and-replace-in-userouter) |
| 78 | [What is ssr: false in dynamic import?](#what-is-ssr-false-in-dynamic-import) |
| 79 | [How do you configure PWA in Next.js?](#how-do-you-configure-pwa-in-nextjs) |
| 80 | [How do you add Google Analytics to a Next.js project?](#how-do-you-add-google-analytics-to-a-nextjs-project) |
| 81 | [What is the purpose of middleware in Next.js?](#what-is-the-purpose-of-middleware-in-nextjs) |
| 82 | [How do you use Apollo Client with Next.js?](#how-do-you-use-apollo-client-with-nextjs) |
| 83 | [What is the publicRuntimeConfig in Next.js?](#what-is-the-publicruntimeconfig-in-nextjs) |
| 84 | [What is the serverRuntimeConfig in Next.js?](#what-is-the-serverruntimeconfig-in-nextjs) |
| 85 | [What is the purpose of \_error.js in Next.js?](#what-is-the-purpose-of-_errorjs-in-nextjs) |
| 86 | [How do you perform client-side data fetching in Next.js?](#how-do-you-perform-client-side-data-fetching-in-nextjs) |
| 87 | [What is the use of next-seo in Next.js?](#what-is-the-use-of-next-seo-in-nextjs) |
| 88 | [How do you use Tailwind CSS in Next.js?](#how-do-you-use-tailwind-css-in-nextjs) |
| 89 | [How do you configure next-i18next in Next.js?](#how-do-you-configure-next-i18next-in-nextjs) |
| 90 | [What is next/script used for?](#what-is-nextscript-used-for) |
| 91 | [How do you enable custom fonts in Next.js?](#how-do-you-enable-custom-fonts-in-nextjs) |
| 92 | [How do you set up GraphQL in Next.js?](#how-do-you-set-up-graphql-in-nextjs) |
| 93 | [What is swcMinify in next.config.js?](#what-is-swcminify-in-nextconfigjs) |
| 94 | [What is the use of next-compose-plugins?](#what-is-the-use-of-next-compose-plugins) |
| 95 | [What is a hybrid application in Next.js?](#what-is-a-hybrid-application-in-nextjs) |
| 96 | [How do you handle CORS in Next.js API routes?](#how-do-you-handle-cors-in-nextjs-api-routes) |
| 97 | [What is the purpose of rewrites in next.config.js?](#what-is-the-purpose-of-rewrites-in-nextconfigjs) |
| 98 | [How do you manage cookies in Next.js?](#how-do-you-manage-cookies-in-nextjs) |
| 99 | [How do you handle authentication tokens in Next.js?](#how-do-you-handle-authentication-tokens-in-nextjs) |
| 100 | [What is next-pwa used for?](#what-is-next-pwa-used-for) |
| 101 | [What is the next-sitemap package used for?](#what-is-the-next-sitemap-package-used-for) |

<!-- TOC End -->

---

<!-- Question & Answers Start -->

1. ### What is NextJS

   Next.js is a React framework for building full-stack web applications.

   [:arrow_up: Back to Top](#table-of-contents)

