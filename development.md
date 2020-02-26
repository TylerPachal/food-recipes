# Development

1) Using `asdf` install Ruby:
    ```
    # Install the ruby version specified in .tool-versions
    asdf install

    # Reload the terminal so that `ruby` will point to our newly installed version
    exec $SHELL
    ```

2) Install `jekyll`:
    ```
    gem install jekyll bundler
    ```

3) Install the dependencies of this project
    ```
    bundle install
    ```

3) Build & serve the website using `jekyll`:
    ```
    bundle exec jekyll serve
    ```

4) View the website at [localhost:4000](localhost:4000).  Some changes are detected automatically and some are not (and require a server restart).