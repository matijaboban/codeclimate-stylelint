# Code Climate Stylelint Engine

`codeclimate-stylelint` is a Code Climate engine that wraps [stylelint](https://github.com/stylelint/stylelint). You can run it on your command line using the Code Climate CLI, or on our hosted analysis platform.

Stylelint is a tool to help you enforce consistent conventions and avoid errors in your stylesheets.  It can be configured using a [configuration file](http://stylelint.io/user-guide/configuration/).


### Installation

1. If you haven't already, [install the Code Climate CLI](https://github.com/codeclimate/codeclimate).
2. Run `codeclimate engines:enable stylelint`. This command both installs the engine and enables it in your `.codeclimate.yml` file.
3. You're ready to analyze! Browse into your project's folder and run `codeclimate analyze`.

### Need help?

For help with stylelint, [check out their documentation](http://stylelint.io/).