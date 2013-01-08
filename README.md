# Marked::Rails

  [Marked](https://github.com/chjj/marked) is an awesome, fast Markdown parser and compiler.
  This is marked - wrapped in a gem - to make use of rubygems as a package manager.
  Marked is also available through Node Package Manager, but if you're working in Rails it's nice
  to have in gem form for simple integration into your rails apps.

  We are currently tracking marked version 0.2.7

## Installation

Add this line to your application's Gemfile:

    gem 'marked-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install marked-rails

## Usage (With Asset Pipeline)

```js
//= require marked
```

## Usage (Without Asset Pipeline)

_Coming ...Eventually_

## Contributing

Feel free to open an issue ticket if you find something that could be improved. A couple notes:

* If it's an issue pertaining to the marked javascript, please report it to the [marked project](https://github.com/chjj/marked).

* If the marked scripts are outdated (i.e. maybe a new version of marked was released yesterday), feel free to open an issue and prod us to get that thing updated.

## Acknowledgements

* This README is __heavily__ inspired by the one for [jquery-rails](https://github.com/rails/jquery-rails)
