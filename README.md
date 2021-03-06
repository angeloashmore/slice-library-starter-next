# slice-library-starter-next

The quickest way to build a Slice Library for [Slice Machine](https://www.slicemachine.dev/) websites using [Next.js](https://nextjs.org/).

> 💭 [**What is a Slice Library?**][what-is-a-slice-library]<br/>
> A Slice Library is a sharable collection of reusable website sections. They can be used in sites built with [Prismic][prismic].

> 📮 [**Submit your Slice Library to the Showcase**][submit-showcase]<br/>
> The easiest way to show off your Slice Library.

## Getting started

Start a new Slice Library project using this starter with the following commands:

1. **Clone the starter**

   Replace `your-library-name` with your Slice Library's name (example: `slice-library-tailwind-ui`).

   ```bash
   npx degit@latest \
     prismicio-community/slice-library-starter-next \
     your-library-name
   ```

1. **Install dependencies**

   Navigate into your Slice Library and install its dependencies.

   ```bash
   cd your-library-name
   npm install
   ```

1. **Give your library a name**

   Open `slicelibrary.json` and update `name` with your Slice Library's name.

   You can leave the other fields alone.

1. **Start developing**

   Start Slice Machine and the Next.js dev server.

   ```bash
   npm run dev
   ```

   After starting Slice Machine, open [http://localhost:9999](http://localhost:9999) with your browser to view Slice Machine.

Now you can begin creating Slices for your Slice Library. The process of making a Slice in a Slice Library is the same as making one for a full website.

## Sharing your Slice Library

You can share your Slice Library with others by pushing it to GitHub in a public repository.

Users can then install your Slices into their existing or new project with the following command:

```bash
npx @slicemachine/init@latest \
  --lib your-username/your-library-name
```

To help users install your Slices, be sure to write a README with installation instructions. If your library requires special setup, such as installing a specific library or configuring a file, include those steps.

An example README is included at `./README-example.md` that can be used as a starting point for your own README.

## Submit it to the Slice Library Showcase

Want to get more 👀 on your Slice Library? Submit it to be listed in the [Slice Library Showcase][showcase]!

1. **Deploy your app**<br/>Deploy your Next.js app to a public URL. We recommend deploying to [Vercel](https://vercel.com/).

2. **Update the Slice Canvas URL**<br/>Update the `sliceCanvasURL` entry in `slicelibrary.json` with the deployed URL.<br/>Remember to push this update to GitHub!

3. **Provide installation instructions**<br/>Be sure to include sufficient installation instructions in your library's README.

That's it! When you're ready, just submit your GitHub URL to the Showcase.

> 📮 [**Submit your Slice Library to the Showcase**][submit-showcase]<br/>
> The easiest way to show off your Slice Library.

[prismic]: https://prismic.io/
[what-is-a-slice-library]: #
[slicemachine]: https://www.slicemachine.dev/
[submit-showcase]: #
[showcase]: #
