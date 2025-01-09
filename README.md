# before-storybook

1. Run `npm run storybook`
2. Open `Docs` file of `Button` component
3. The Docs page is in a rerender loop issue and the Console has errors:

```
globals-runtime.js:6409  manager  received updateGlobals but was unable to determine the source of the event

globals-runtime.js:6409  manager  received globalsUpdated but was unable to determine the source of the event
4
globals-runtime.js:6409  manager  received storyRenderPhaseChanged but was unable to determine the source of the event
```
