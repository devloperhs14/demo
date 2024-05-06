## Lec 4: Routing
Routing convention to follow in next js 18+
1. All routes to be placed inside `app` folder
2. Every file related/ correospond to route should be named `page.js` or `page.tsx` (if typescript enabled)
3. Each folder corrospond to path segment in browser.

E.g
```
src/app
 |_route1.tsx
```
so url will be `http://localhost/`

It will also create a `layout.tsx ` if not created yet. Its magic, magic !
 