# To reproduce

Ruby 2.7 will need to be installed.

```
git clone https://github.com/taylorthurlow/filestack-rollup-repro.git
gem install bundler
bundle install
yarn install
bundle exec rails server
```

In another terminal window run `bundle exec bin/vite dev` to start the dev server.

Visit `http://localhost:3000` and inspect the browser console.
