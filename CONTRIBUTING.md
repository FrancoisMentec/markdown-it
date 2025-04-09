### If you commit changes:

1. Make sure all tests pass.
2. Run `./benchmark/benchmark.mjs`, make sure that performance not degraded.
3. DON'T include auto-generated browser files to commit.

### Other things:

1. Prefer [gitter](https://gitter.im/markdown-it/markdown-it) for short "questions".
   Keep issues for bug reports, suggestions and so on.
2. Make sure to read [dev info](https://github.com/markdown-it/markdown-it/tree/master/docs)
   prior to ask about plugins development.
3. __Provide examples with [demo](https://markdown-it.github.io/) when possible.__
4. Issues of "question" type are closed after several days of inactivity,
   if not qualified as bug report, enhancement etc (see 1).
5. If you are behind a proxy, you may need to provide its certificate to run Cmark tests. You can use this command: `npx cross-env NODE_EXTRA_CA_CERTS=./path/to/certificate.pem npm test`