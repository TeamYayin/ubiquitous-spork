# Yayin AI Lab Project Portfolio

Projects designed, managed and developed by Yayin AI Lab, built with [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/), [Contentlayer](https://www.contentlayer.dev/).

## Running Locally

```sh-session
git clone https://github.com/chronark/chronark.com.git
cd chronark.com
```

Then install dependencies and run the development server:

```sh-session
pnpm install
pnpm dev
```

## Changing background color

In `tailwind.config.js` add custom colors and later in `app/layout.tsx` change the `<body>` tag class name which starts something like `bg-color-name` to `bg-custom-color-name`.

## Changing Featured and Top Projects

In `app/projects/page.tsx` change constants `featured`, `top1`, and `top2`.
