# seansharaf.com

Sean "The Smoke" Sharaf. UFC heavyweight. The site, the Command Post and The Lock In.

## What is here

- `index.html` The site. Six scroll chapters of smoke particles, the hadith pause, Enlist, the du'a wall.
- `command/` The Command Post. Private. Opens with the Command Post code. The unit roster, the du'a queue, and The Lock In program editor.
- `lockin/` The Lock In. The member app. Email code sign in, Today, Month, Roll call, Fight, Me. Installs to a phone home screen.
- `cities.js` City coordinates for the unit map.
- `img/` Photos used on the site.
- `netlify.toml` Hosting rules. Publishes this folder as is. No build step.

## Where the data lives

Everything people type lives in a Supabase project named `sean-sharaf`: enlistments, du'as, Lock In members, check-ins, and the program (days and exercises). The pages talk to it with a publishable key that is safe to be public. Nothing private can be read without the Command Post code or a member's own sign in.

Login code emails send through Resend.

## How to change the program

Nothing in this repo. Open the Command Post, tap The Lock In, pick a day, add the exercises, save.

## How to deploy

Connect this repo to a Netlify project. Build command: none. Publish directory: `.` Every push to `main` goes live.
