## Coupe de France Modern

This is the repository for the Coupe de France Modern website. It is available at [cdf-modern.fr](https://cdf-modern.fr).

### Local installation

- Install [rbenv](https://github.com/rbenv/rbenv)
- Install [ruby-build](https://github.com/rbenv/ruby-build)
- Install a recent version of ruby, eg. `rbenv install 3.3.1`
- Install Jekyll: `gem install jekyll bundler`
- Install dependencies: `bundle install`

(You may need to follow the instructions in https://stackoverflow.com/a/37956249/1669977 and add things to your .bashrc)

### Local development

To run a local server:
- `bundle exec jekyll serve --livereload`
- Go to `http://localhost:4000`
