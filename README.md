
# storyboard v3

this is the landing page for storyboard v3, a [hack club](https://hackclub.com) ysws (you ship we ship) program where participants (13-18) ship visual novels & get various prizes for free! 

it's the successor to [storyboard v2](https://storyboard.hackclub.com)

right now, it's just a landing page. i'll build the rest of the platform... soon...

this was made using:
- sveltekit
- typescript
- tailwind css
- compiled w vite
- deployed w vercel

## check it out [here](https://storyboard-v3.vercel.app)

---

# screenshots 👀👀👀👀

[![landing page hero](https://i.postimg.cc/BbYN6Y8y/image.png)](https://postimg.cc/4Hcp21Qb)
[![how does storyboard work? section](https://i.postimg.cc/GtHGMc2g/image.png)](https://postimg.cc/0K1zj177)
[![prizes section](https://i.postimg.cc/TwPDwRrP/image.png)](https://postimg.cc/xkWCpVpr)
[![guides section](https://i.postimg.cc/mkHhzhhG/image.png)](https://postimg.cc/sG33bjpn)
---

# how to run this project

this project was built using the svelte framework: [`sv`](https://github.com/sveltejs/cli).

```

to recreate this project with the same configuration:

```sh
# recreate this project
npx sv@0.17.0 create --template minimal --types ts --add prettier tailwindcss="plugins:typography" mdsvex --install npm storyboard-v3
```

install dependencies with `npm install` or `pnpm install` or `yarn`.

start dev server:
```sh
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

build & create a production version of the app:
```sh
npm run build
```

preview the production build:
```sh
npm run build
```

> to deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.

---

made w/ <3 and monster energy by [kat wang](https://kat.wang)

w/emotional support from many friends at [hack club](https://hackclub.com) and the storyboard team (kaylee, susan, yunfei, hherby, august, and sophia!)