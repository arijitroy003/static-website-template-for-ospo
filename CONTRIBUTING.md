# Contributing

## Documentation

See [Contributing to the Docs](docs/contributing-to-docs.md). Documentation
pages live in `docs/`, and blog posts live in `blog/`.

## Local development

Use a Node.js version compatible with the `engines` field in `package.json`.
From the repository root, run:

```sh
npm ci
npm start
```

Before submitting changes, build the site:

```sh
npm run build
```

Check the affected pages locally, including links and navigation. Open a pull
request describing the change and the checks you performed.

## Security reports

For vulnerability reporting guidance, see [SECURITY.md](SECURITY.md).
