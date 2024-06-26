# React Routing

## Lec 4 - React Server Components (RSC)
1. New architecture, introduced in react, embraced by **next-js-18**
2. Introduces new way of creating **react-components**
3. 2 Types are:
    * Server Components
    * Client Components

**Server Components**
- In next , all components are server components (default)
- Ability to run task like reading files or fetching data from db
- Don't have ability to use hooks or handle interactions

**Client Components**
- In next , to create client component add `"use client"` at top of component file
- Don't have ability to run task like reading files or fetching data from db
- Have ability to use hooks or handle interactions
- Tradational react components

## Lec 5: Routing
Routing convention to follow in next js 18+
1. All routes to be placed inside `app` folder
2. Every file related/ correospond to route should be named `page.js` or `page.tsx` (if typescript enabled)
3. Each folder corrospond to path segment in browser.

**Base / Only home page**
E.g -1
```
src/app
 |_route1.tsx
```
so url will be `http://localhost/`


> It will also create a `layout.tsx ` if not created yet.Its magic, magic !


**Base / about / profile **
1. In `app` folder created 2 new folders : `about` and `profile`
2. Created `page.tsx` in both the folder

E.g -2
```
src/app
 |_____ about
 |       |_page.tsx
 |_____ profile
 |       |_page.tsx
 |_route1.tsx
```
so url will be `http://localhost/about` & `http://localhost/profile`

> A url that dosen't exist maps to 404 error page

## Lec 6: Nested Routes