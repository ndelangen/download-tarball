# @ndelangen/get-tarball

Download a tarball (optionally gzipped) to a folder &amp; extract it in the process. Uses the wonderful &amp; super quick tar-fs &amp; gunzip-maybe srcraries.

## Installation

This is a [Node.js](https://nodejs.org/) module available through the 
[npm registry](https://www.npmjs.com/). It can be installed using the 
[`npm`](https://docs.npmjs.com/getting-started/installing-npm-packages-locally)
or 
[`yarn`](https://yarnpkg.com/en/)
command line tools.

```sh
npm install @ndelangen/get-tarball --save
```

## Tests

```sh
npm install
npm test
```

## Dependencies

- [gunzip-maybe](https://ghub.io/gunzip-maybe): Transform stream that gunzips its input if it is gzipped and just echoes it if not
- [pump](https://ghub.io/pump): pipe streams together and close all of them if one of them closes
- [tar-fs](https://ghub.io/tar-fs): filesystem bindings for tar-stream

## Dev Dependencies

- [@types/gunzip-maybe](https://ghub.io/@types/gunzip-maybe): TypeScript definitions for gunzip-maybe
- [@types/jest](https://ghub.io/@types/jest): TypeScript definitions for Jest
- [@types/node](https://ghub.io/@types/node): TypeScript definitions for Node.js
- [@types/pump](https://ghub.io/@types/pump): TypeScript definitions for pump
- [@types/tar-fs](https://ghub.io/@types/tar-fs): TypeScript definitions for tar-fs
- [auto](https://ghub.io/auto): CLI tools to help facilitate semantic versioning based on GitHub PR labels
- [got](https://ghub.io/got): Human-friendly and powerful HTTP request library for Node.js
- [http-test-server](https://ghub.io/http-test-server): Create a simple http server for tests
- [jest](https://ghub.io/jest): Delightful JavaScript Testing.
- [package-json-to-readme](https://ghub.io/package-json-to-readme): Generate a README.md from package.json contents
- [tar-stream](https://ghub.io/tar-stream): tar-stream is a streaming tar parser and generator and nothing else. It operates purely using streams which means you can easily extract/parse tarballs without ever hitting the file system.
- [tmp](https://ghub.io/tmp): Temporary file and directory creator
- [ts-jest](https://ghub.io/ts-jest): A Jest transformer with source map support that lets you use Jest to test projects written in TypeScript
- [tsup](https://ghub.io/tsup): Bundle your TypeScript library with no config, powered by esbuild
- [typescript](https://ghub.io/typescript): TypeScript is a language for application scale JavaScript development

## License

MIT
