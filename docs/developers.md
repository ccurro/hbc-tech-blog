## Development setup
- Make sure you have a recent version of Ruby Installed. Instructions [here](https://www.ruby-lang.org/en/documentation/installation/)

- Install bundler to make life easier
```
gem install bundler
```

- If you haven't installed Node.js, you can find an installer [here](https://nodejs.org/en/download/)

```
git clone https://github.com/saksdirect/hbc-tech-blog
cd hbc-tech-blog
bundle install && npm install
npm run dev
```

The dev script runs a gulp task that will build the jekyll blog, open the browser, and reload any assets that are changed during development.

See the gulpfile for additional tasks 
