

## About The Real Rashard
My name is Rashard. I dont know the exact timeline but was [Born in Los Angeles](https://lacounty.gov/) and my mother, a young Somalian maiden was shopping at a [grocerystore I was at the Newsstand](https://www.readingrockets.org/topics/activities/articles/grocery-store-literacy) and big shaking started, A lady that looked like my mom made me put the book back, likely [National Geographic](https://films.nationalgeographic.com/la-92-discussion-guide) and my next memory is Riding in a [1980~Pontiac Gran Prix](https://upload.wikimedia.org/wikipedia/commons/a/a2/1979_Pontiac_Grand_Prix_model_LJ_%2821395022978%29.jpg) it was grey(t). I was in the car with [Vanessa Walker](https://pitchfork.com/thepitch/kash-doll-intro-new-song-listen/) but i dont know what her name was at that moment bc she was reintroduced to me as Vanessa, abt 7years ago she asked me to call her by her [Villiage Name Sartu](https://x.com/SartuAdem) she and her sibling [Pooh aka Joyel Walker](https://vsco.co/rashardsartu/media/656fefdb1847927fd0000001) told me my name is [Thaka](https://vsco.co/rashardsartu/media/5fc45b01e1ebb64f08283c31). They look like my mom, but dont have a sister connection if u know what i mean. So anyway Im in the Pontiac with Vanessa, but im in [Savannah](https://vsco.co/rashardsartu/media/5fc45961e1ebb64f08283c15)! I spent about 15 years there and took some classes at thier [community college](https://www.savannahtech.edu/), i helped with their website b4 I moved to [Berkeley](https://berkeleyca.gov/) for a relationship i had cultivated starting on [JWmatch](https://www.jwmatch.com/s/a/13906/us_s?gad_source=1&gclid=EAIaIQobChMI5IGqxI7whgMVm1oPAh3tZAFmEAAYASAAEgJBffD_BwE) with a young maiden named Erika. Erika and I had a child and Broke up but lived together as pal/roommates/cousins raising our daughter. Pooh and Vanessa were working out of the [Studio Six doors Down](https://www.tripadvisor.com/Attraction_Review-g60898-d9719936-Reviews-Dance_411-Atlanta_Georgia.html), Erika said i could have a Girlfriend and I fell in love immediately. Then I found out they work for [RabbitHead](https://www.eonline.com/news/playboy) And thier secret life of taking thier clothes off handicapped me bc the people that they meet through them and [Hustler](https://slate.com/human-interest/2023/08/larry-flynt-hustler-porn-magazine-workplace.html) Are often in my economic demographic and disable me. This Repo is to combat that. With Pages I can write real time and [experiment with code tied to me directly](https://codepen.io/your-work)!


![magazine rack](https://upload.wikimedia.org/wikipedia/commons/thumb/0/03/WSTM-CornFedChicks0026.JPG/1024px-WSTM-CornFedChicks0026.JPG)
By <span typeof="mw:File"><a href="//commons.wikimedia.org/wiki/File:Wikis_Take_Manhattan.png" class="mw-file-description"></a></span>This photo was taken by participant/team <a href="//commons.wikimedia.org/wiki/Category:Images_from_Wikis_Take_Manhattan_by_Corn_Fed_Chicks" title="Category:Images from Wikis Take Manhattan by Corn Fed Chicks">Corn Fed Chicks</a> as part of the <a href="//commons.wikimedia.org/wiki/Commons:Wikis_Take_Manhattan" title="Commons:Wikis Take Manhattan">Commons:Wikis Take Manhattan</a> project on October 4, 2008.<span typeof="mw:File"><span title="w:en:Creative Commons"></span></span><span typeof="mw:File"><span title="attribution"></span></span> <span typeof="mw:File"><span title="share alike"></span></span>This file is licensed under the <a href="https://en.wikipedia.org/wiki/en:Creative_Commons" class="extiw" title="w:en:Creative Commons">Creative Commons</a> <a href="//creativecommons.org/licenses/by-sa/3.0/deed.en" class="extiw" title="creativecommons:by-sa/3.0/deed.en">Attribution-Share Alike 3.0 Unported</a> license.You are free:to share – to copy, distribute and transmit the workto remix – to adapt the workUnder the following conditions:attribution – You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.share alike – If you remix, transform, or build upon the material, you must distribute your contributions under the <a rel="nofollow" class="external text" href="https://creativecommons.org/share-your-work/licensing-considerations/compatible-licenses">same or compatible license</a> as the original. - Contributed by author, <a href="https://creativecommons.org/licenses/by-sa/3.0" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=5048705">Link</a>
# The Hacker theme

[![.github/workflows/ci.yaml](https://github.com/pages-themes/hacker/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/hacker/actions/workflows/ci.yaml) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-hacker.svg)](https://badge.fury.io/rb/jekyll-theme-hacker)

*Hacker is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/hacker), or even [use it today](#usage).*

![Thumbnail of Hacker](thumbnail.png)

## Usage

To use the Hacker theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: pages-themes/hacker@v0.2.0
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```

## Customizing

### Configuration variables

Hacker will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" (unquoted) to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Layouts

If you'd like to change the theme's HTML layout:

1. For some changes such as a custom `favicon`, you can add custom files in your local `_includes` folder. The files [provided with the theme](https://github.com/pages-themes/hacker/tree/master/_includes) provide a starting point and are included by the [original layout template](https://github.com/pages-themes/hacker/blob/master/_layouts/default.html).
2. For more extensive changes, [copy the original template](https://github.com/pages-themes/hacker/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
3. Create a file called `/_layouts/default.html` in your site
4. Paste the default layout content copied in the first step
5. Customize the layout as you'd like

### Customizing Google Analytics code

Google has released several iterations to their Google Analytics code over the years since this theme was first created. If you would like to take advantage of the latest code, paste it into `_includes/head-custom-google-analytics.html` in your Jekyll site.

### Overriding GitHub-generated URLs

Templates often rely on URLs supplied by GitHub such as links to your repository or links to download your project. If you'd like to override one or more default URLs:

1. Look at [the template source](https://github.com/pages-themes/hacker/blob/master/_layouts/default.html) to determine the name of the variable. It will be in the form of `{{ site.github.zip_url }}`.
2. Specify the URL that you'd like the template to use in your site's `_config.yml`. For example, if the variable was `site.github.url`, you'd add the following:
    ```yml
    github:
      zip_url: http://example.com/download.zip
      another_url: another value
    ```
3. When your site is built, Jekyll will use the URL you specified, rather than the default one provided by GitHub.

*Note: You must remove the `site.` prefix, and each variable name (after the `github.`) should be indent with two space below `github:`.*

For more information, see [the Jekyll variables documentation](https://jekyllrb.com/docs/variables/).

## Roadmap

See the [open issues](https://github.com/pages-themes/hacker/issues) for a list of proposed features (and known issues).

## Project philosophy

The Hacker theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Hacker? We'd love your help. Hacker is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](docs/CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/hacker`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` once before the test script will work.
