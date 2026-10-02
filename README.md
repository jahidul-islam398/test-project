# Test-project

A small Node.js workspace by Jahidul Islam. It currently holds project metadata and the `dotenv` dependency; application code can be added from here.

## Requirements

- [Node.js](https://nodejs.org/) (npm is included)

## Setup

```bash
npm install
```

Copy environment variables into a `.env` file in the project root. `dotenv` is already listed as a dependency so those values can be loaded in code with:

```js
require("dotenv").config();
```

## Run

`package.json` sets `index.js` as the entry point. Create that file, then start the app with:

```bash
node index.js
```

## Scripts

| Script | Description |
|--------|-------------|
| `npm test` | Placeholder; no tests are defined yet |

## License

ISC
