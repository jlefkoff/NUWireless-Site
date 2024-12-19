# NU Wireless Site

This is the current (2025) redo of the Northeastern University Wireless Club Website.

The goal this time is to make it as simple to update as possible. The site is mostly made up of markdown files in the repo root. These are rendered into html using the [11ty](https://www.11ty.dev/) generator. On pushes to the main branch, cloudflare pages automagically rebuilds and redeploys the site.

### Building Locally

if you've just cloned this repo, make sure you have nodejs >= 19 installed, and run `npm install` to get the 11ty dependency.

Run `npx @11ty/eleventy --serve` to run a local webserver with hot-reload for dev work.