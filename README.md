# Package stats

[![Build Status](https://travis-ci.org/Yukaii/package-stats.svg?branch=master)](https://travis-ci.org/Yukaii/package-stats)

Package stats of 3 popular editor: VSCode, Sublime and Atom.

## Development

Install ruby, bundler, then run:

```bash
bundle install
```

cd into `build` directory, start development server:

```bash
 ruby -run -e httpd . -p 3000 # Change 3000 port to whatever you like
 ```

 Start a another terminal, run build site command:

 ```bash
 ./update
 ```

 Visit `http://localhost:3000` for result.

## License

MIT
