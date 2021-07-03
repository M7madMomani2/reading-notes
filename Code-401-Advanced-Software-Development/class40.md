# Next.js Dynamic Routes
![](https://www.ibrahima-ndaw.com/static/2a7d1a1ce97e766a9dacfbe05232f6af/6db29/cover.png)


- Defining routes by using predefined paths is not always enough for complex applications.

- In Next.js you can add brackets to a page ([param]) to create a dynamic route (a.k.a. url slugs, pretty urls, and others).

- Page: pages/post/[pid].js:
```
import { useRouter } from 'next/router'
const Post = () => {
const router = useRouter()
const { pid } = router.query
return <p>Post: {pid}</p>
}
```
- Any route like /post/1, /post/abc, etc. will be matched by pages/post/[pid].js.

- The matched path parameter will be sent as a query parameter to the page, and it will be merged with the other query parameters.


## Deploying Your Next.js App
- > The easiest way to deploy Next.js to production is to use the Vercel platform developed by the creators of Next.js. Vercel is an all-in-one platform with Global CDN supporting static & JAMstack deployment and Serverless Functions. We believe Vercel is the optimal place to deploy Next.js apps.
- > You can use default values for the following settings — no need to change anything —. Vercel automatically detects that you have a Next.js app and chooses optimal build settings for you:
    - Project Name
    - Root Directory
    - Build Command
    - Output Directory
    - Development Command
