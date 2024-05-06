# Readme.md

# Next JS Learnings

## Lec 1 : Setup Next JS Project
- In terminal run `npx create-next-app@latest`
- Input project name - Only hyphen allowed as special char
- Keep rest of options to default - For use src folder - Ensure yes (organised)
- One done, in terminal run `npm run dev` and open browser at localhost
- Editing page from **src/app/page.tsx**

## Lec 2 : Project Structure
At root level - 4 folder and 10 files , but here only necessary ones are covered:

**Files**
1. `package.json`: Project dependecies (next, react, react-dom) and scripts (dev, build, start, lint)
2. `next.config.js`: For next js
3. `tsconfig.ts`: For typescript
4. `eslintrc`: For eslint
5. `tailwind.config` & `postcss.config.js`: For tailwindcss

**Folders**
1. `.next`: dev or build script autogenerates and serves
2. `node_modules`: all dependecies - generated at dev command
3. `public`: static storage folder
4. `src`: Main folder to work with

**Src files:**
1. `favicon.ico`: icon
2. `global.css`: contains the global styles for app
3. `layout.tsx`: ui that can be shared across diff pages
4. `page.tsx`: unique ui that present at root / home page at project start. **Modify to see the ui change**





