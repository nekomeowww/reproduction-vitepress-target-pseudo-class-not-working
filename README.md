# reproduction-vitepress-target-pseudo-selector

Repository to reproduce the issue with `:target` pseudo selectors in vitepress.

## Steps to reproduce

1. Clone this repository
2. Run `pnpm run docs:build` or `nr docs:build`
3. Run `pnpm run docs:preview` or `nr docs:preview`
4. Open `http://localhost:4173/target-repro/` in your browser
5. Click [To Test](http://localhost:4173/target-repro.html#test) link, path changes, but `:target` pseudo selector is not applied
6. Reload page with the same link, `:target` pseudo selector is applied
7. You can reproduce the issue with other heading links and outline on right sidebar as well
