Reproduction repository for [storybookjs/storybook#13387](https://github.com/storybookjs/storybook/issues/13387).

This repository was created using:

- `pnpm create vite`
- `pnpm dlx storybook@latest init`

The only change that was made was the addition of the `options.storySort.order` option in [`.storybook/preview.ts`](./.storybook/preview.ts).

Run `pnpm run storybook` to see how the story order is unaffected.
