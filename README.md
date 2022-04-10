<p align="right">
    <a href="https://badge.fury.io/rb/just-the-docs"><img src="https://badge.fury.io/rb/just-the-docs.svg" alt="Gem version"></a> <a href="https://github.com/just-the-docs/just-the-docs/actions?query=workflow%3A%22main+branch+CI%22"><img src="https://github.com/just-the-docs/just-the-docs/workflows/main%20branch%20CI/badge.svg" alt="Build status"></a>
</p>
<br><br>
<p align="center">
    <h1 align="center">Setting Up SSH</h1>
    <p align="center">This comprehensive guide will help you set up and use an SSH key on your Mac.<br>This was written for CST's COMM 2216 course.</p>
    <p align="center"><strong><a href="https://dlepke.github.io/Deanna-Wilson-Ray/">Get started here!</a></strong></p>
    <br><br><br>
</p>

### List of Resources Used in This Assignment
* Google icons: https://fonts.google.com/icons
* References for layout, content:
    * https://dl90.github.io/linux-basics/
    * https://github.com/megankuo/Express-User-Documentation/
* Cloned repo found at: https://github.com/just-the-docs/just-the-docs




![jtd](https://user-images.githubusercontent.com/896475/47384541-89053c80-d6d5-11e8-98dc-dba16e192de9.gif)

## Installation

### via GitHub Pages remote theme

The quickiest way to use Just The Docs is to use GitHub pages [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) feature in your `config.yml` file:

```yaml
remote_theme: just-the-docs/just-the-docs
```
### via RubyGems:

Alternatively you can install it as a Ruby Gem.

Add this line to your Jekyll site's Gemfile:

```ruby
gem "just-the-docs"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: just-the-docs
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install just-the-docs

Alternatively, you can run it inside Docker while developing your site

    $ docker-compose up

## Usage

[View the documentation](https://just-the-docs.github.io/just-the-docs/) for usage information.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/just-the-docs/just-the-docs. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

### Submitting code changes:

- Open a [Pull Request](https://github.com/just-the-docs/just-the-docs/pulls)
- Ensure all CI tests pass
- Await code review
- Bump the version number in `just-the-docs.gemspec` and `package.json` according to [semantic versioning](https://semver.org/).

### Design and development principles of this theme:

1. As few dependencies as possible
2. No build script needed
3. First class mobile experience
4. Make the content shine

## Development

To set up your environment to develop this theme, run `bundle install`.

A modern [devcontainer configuration](https://code.visualstudio.com/docs/remote/containers) for VSCode is included.

Your theme is set up just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When the theme is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Conclusion {#Conclusion}
We felt that GitHub SSH was a safer, more user friendly alternative to using GitHub tokens, and thus endeavoured to create this document to confer to you our knowledge of GitHub SSH.

Though we are by no means experts in the topic, we hope that our efforts prove useful to anyone who comes across these instructions looking for insight into the inner workings and nuances of GitHub SSH.

Regardless of what knowledge you may have obtained from these pages, our writing of this has also provided to us the opportunity to practice creating clear and precise user instructions for our target audience. This assignment also helped us learn to better work with our peers, strengthening our teamwork and communication skills. And as such, we would like to take this opportunity to thank you for being here to witness the fruits of our labour.

We hope that this guide is able to assist you in setting up and working with SSH. While SSH may appear complex, it is actually a much simpler system once you get to know it, and its added security measures will ultimately result in a much smoother workflow experience with both Git and GitHub.
