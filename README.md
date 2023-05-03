# BoldContacts site as SvelteKit

BoldContacts is a mobile app for accessible calling.

Website: <https://BoldContacts.org>

Repositories: <https://github.com/BoldContacts>

Apple App Store: <https://apps.apple.com/us/app/boldcontacts/id6443335501>


## Technical

Create:

```sh
pnpm create @svelte-add/kit@latest boldcontacts -- \
--with eslint+playwright+postcss+prettier+tailwindcss+typescript+vitest \
--postcss-autoprefixer \
--tailwindcss-daisyui \
--tailwindcss-form \
--tailwindcss-typography
cd boldcontacts
git init && git add -A && git commit -m "Run pnpm create @svelte-add/kit@latest"
pnpm run dev -- --open
```

Host site on Netlify::<br>
<https://www.netlify.com>

Edit DNS on AWS Route 53:<br>
<https://aws.amazong.com>
