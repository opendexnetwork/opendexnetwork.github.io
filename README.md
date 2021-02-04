# OpenDEX API Documentation
[api.opendex.network](https://api.opendex.network)

## Dependencies
- ruby 2.7.2

## Build and deploy
- run `npm run slate` in `opendexd` repository
- copy `opendexrpc.md` from `opendexd` repository to `source` folder in this repository and rename it to `index.html.md`
- `bundle install`
- `bundle exec middleman build`
- `cp -R build docs`
- `git push origin main`
