# SOZAI.katsuma.tv

[I am here](https://sozai.katsuma.tv). :D

## Install

```sh
bundle install --without build
```

## Boot

```sh
bundle exec middleman
```

And access `http://localhost:4567` on your web browser.


## Contribute

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

### Note

If you want to add some images add a new image to `source/images/` directory and edit `data/images.yml`.
After your pull request is merged, deploy server will update `index.html` and `api/sozais.json` with the latest file.
