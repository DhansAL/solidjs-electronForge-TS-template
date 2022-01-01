## Solidjs+ElectronForge support --Typescript Template

what this template includes

- Forge's HMR + CLI
- Typescript support(Tsx)
- babel-solid-preset, uses babel loader instead of ts-loader due to build issues
- webpack 5 + working webpack.rules
- fixes unreactive issue with solid.js and electron integration with presets

refer - https://issueexplorer.com/issue/solidjs/solid/622

ts loader breaks the app due to Multiple versions of Solid are getting pulled into the build.
