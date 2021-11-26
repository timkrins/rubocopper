# rubocopper

This is a script to make running rubocop via daemon faster.

It uses https://github.com/fohte/rubocop-daemon behind the scenes.

It is based on the `rubocop-daemon-wrapper` script but tailored to not explode with my specific environment. It uses `asdf` so will not be for everyone.

## Installation

1. Install `asdf`
2. Run `asdf install`
3. Maybe run `gem install bundler`
4. Run `bundle`
5. Add this to your vscode settings:
    ```
    "ruby.rubocop.executePath": "FULL_PATH_TO_PARENT_DIRECTORY/rubocopper/",
    ```

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
