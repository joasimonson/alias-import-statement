# Alias import statement

Path aliases define custom shortcuts for import paths, making them cleaner and more intuitive.

Notes:
- Webpack can’t resolve imports specified in `tsconfig.json` file when defining aliases using Create React App (CRA)
- CRA setup doesn’t provide support for modifying `webpack.config.js` without ejecting
- Create React App Configuration Override (CRACO) address these limitations in `craco.config.js`

## Libraries
- [Styled components](https://styled-components.com/)
- [Craco](https://craco.js.org/docs/)