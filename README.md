# Privacy Cactus Theme

Privacy Cactus is a minimalistic theme for bloggers. It's a fork of the original [Hugo Cactus Theme](https://github.com/digitalcraftsman/hugo-cactus-theme) (which in itself is based on some other themes with the same name).

So what's different? We care about your visitors privacy, this means:

* All tracking services removed
* Social network sharing links removed (you can just share the URL)
* Disqus comments removed (maybe use email?)
* No third party scripts / fonts / assets

![Screenshot](https://raw.githubusercontent.com/digitalcraftsman/hugo-cactus-theme/dev/images/screenshot.png)

## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/lucaspiller/hugo-privacy-cactus-theme.git

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

### The config file

Take a look inside the [`exampleSite`](//github.com/lucaspiller/hugo-privacy-cactus-theme/tree/dev/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//github.com/lucaspiller/hugo-privacy-cactus-theme/blob/dev/exampleSite/config.toml).

To use it, copy the [`config.toml`](//github.com/lucaspiller/hugo-privacy-cactus-theme/blob/dev/exampleSite/config.toml) in the root folder of your Hugo site. Feel free to change strings as you like to customize your website.

## About page

Use the about page to introduce yourself to your visitors. You can customize the content as you like in the [`config.toml`](//github.com/lucaspiller/hugo-privacy-cactus-theme/blob/dev/exampleSite/config.toml). Furthermore, you should replace the [avatar placeholder](//github.com/lucaspiller/hugo-privacy-cactus-theme/blob/master/static/images/avatar.png) with a great image of yourself.

## Hide pages

Pages can be hidden and don't appear in the post list on the homepage if you add the variable `hidden = true` to the frontmatter. This allows you to link from elsewhere, i.e. just the menu. 

## Disqus

This theme features a comment system powered by Disqus too. Just add your Disqus-shortname to the [`config.toml`](//github.com/lucaspiller/hugo-privacy-cactus-theme/blob/dev/exampleSite/config.toml) and let readers respond to your blog posts.

## Social link icons

You can add a social link panel in the footer by adding entries to the `social` block in the [`config.toml`](//github.com/lucaspiller/hugo-privacy-cactus-theme/blob/dev/exampleSite/config.toml). You can choose between two icon fonts:

- [Font awesome](https://fortawesome.github.io/Font-Awesome/) or
- [Mono social icons](https://github.com/drinchev/monosocialiconsfont)

Assign either `font-awesome` or `mono-social` to the `iconFont` variable. The Mono social icons offer three styles of icons: -circle, rounded, or default (empty).

## Nearly finished

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.


## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](//github.com/lucaspiller/hugo-privacy-cactus-theme/issues) to let me know. Or make directly a [pull request](//github.com/lucaspiller/hugo-privacy-cactus-theme/pulls).

Please create a separate branch for your pull request.


## License

This theme is released under the MIT license. For more information read the [license](//github.com/lucaspiller/hugo-privacy-cactus-theme/blob/dev/LICENSE.md).

## Acknowledgements

Thanks to

- [digitalcraftsman](//github.com/digitalcraftsman/hugo-cactus-theme) for porting this to Hugo.
- [Nick Balestra](//github.com/nickbalestra/kactus) for creating the original theme
- [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project.

