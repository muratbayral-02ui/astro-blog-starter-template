# Astro Blog Starter

A clean blog you can use with your YouTube channel.

## Quick start

1. Install
   ```bash
   npm install
   ```

2. Run in dev
   ```bash
   npm run dev
   ```

3. Build
   ```bash
   npm run build
   ```

4. Preview
   ```bash
   npm run preview
   ```

## Edit content

- Posts live in `src/content/posts`
- Title, date, and description are in the frontmatter at the top of each file
- The layout is in `src/layouts/Base.astro`

## Deploy options

- Any static host works, for example Nginx or Apache
- Upload the `dist` folder after running `npm run build`
- Or run `npx serve dist` on a Node server
