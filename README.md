## Videogular
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/2fdevs/videogular?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

**Videogular is an HTML5 video player for AngularJS**. Videogular is a wrapper over the HTML5 video tag, so you just could add whatever you want. This provides a very powerful, but simple to use solution, for everybody.

You could see a demo here: http://www.videogular.com

## Why Videogular?

We're developing Videogular focusing on mobile devices and HTML5 video special capabilities. Videogular brings to you these key features:

* **Bindable properties**: Videogular's directives are bindable, just [try the demo](http://www.videogular.com) and play with bindings.
* **Extendable through plugins**: Thanks to our API you can develop your own plugins.
* **Theme based**: Customize it with your own themes and change between them on the fly.
* **Native fullscreen support**: Enjoy with native fullscreen support for Chrome, Firefox, Safari, iOS and Chrome for Android.
* **Mobile support**: Videogular can detect mobile devices to show/hide components in case that aren't supported. Also, you could use it in your responsive websites, Videogular will always scale to fit its container.

## Documentation and how to install

See the [Videogular's website](http://www.videogular.com) for more info about [how to start and installation notes](http://www.videogular.com/tutorials/how-to-start/). We have also [tutorials](http://www.videogular.com/tutorials/) and [examples](http://www.videogular.com/examples/) if you need a guide or code samples.

For more info you can check the full [Videogular API documentation](http://www.videogular.com/docs/).



## Third-party plugins

If you have developed a Videogular's plugin or theme [contact us through this form](http://www.videogular.com/contact/) and we will add you to this list.

* [**Youtube plugin**](https://github.com/NamPNQ/bower-videogular-youtube) by **[NamPNQ](https://github.com/NamPNQ)**
* [**Quiz plugin**](https://github.com/NamPNQ/bower-videogular-quiz) by **[NamPNQ](https://github.com/NamPNQ)**
* [**Flash fallback plugin**](https://github.com/NamPNQ/bower-videogular-flash) by **[NamPNQ](https://github.com/NamPNQ)**
* [**Background video plugin**](https://gist.github.com/panurge-ws/525caef640784a487aa2) by **[panurge-ws](https://github.com/panurge-ws)**
* [**Videogular subtitle plugin**](https://github.com/farhan-repo/videogular-subtitle-plugin) (for Videogular 0.4.0) by **[farhan-repo](https://github.com/farhan-repo)**
* [**Videogular cuepoints plugin**](https://github.com/soton-ecs-2014-gdp-12/videogular-cuepoints) by **[Group 12 GDP](https://github.com/soton-ecs-2014-gdp-12)**

## Migrate to 1.0 from an older version of Videogular

All attributes for the various directives (including plugins) are still being maintained as usual, however, the naming of several have changed significantly to conform to an improved coding style. Here is a semi-exhaustive list:

1. No more `<vg-video>`.  Ditched in favor of `<vg-media>` that supports audio as well.
2. `vg-controls`:

    ```
    vg-timedisplay -> vg-time-display
    vg-scrubBar -> vg-scrub-bar
    vg-scrubbarcurrenttime -> vg-scrub-bar-current-time
    vg-timedisplay -> vg-time-display
    vg-mutebutton -> vg-mute-button
    vg-volumebar -> vg-volume-bar
    ```
    
3. `vg-poster-image -> vg-poster`

For a complete migration guide we recommend you to check the [Migration guide to Videogular 1.0.0](http://www.videogular.com/tutorials/migration-guide-to-videogular-1-0-0/).

## Supported by

Videogular wants to thank you to this companies for support this project:

[![](http://www.videogular.com/wp-content/uploads/2015/03/BrowserStackLogo.png)](http://www.browserstack.com)
[![](http://www.videogular.com/wp-content/uploads/2015/03/logo-q.png)](http://q-interactiva.com)

## Credits

Videogular is an open source project maintained by (literally) [two fucking developers] (http://twofuckingdevelopers.com/).

We want to thank all our contributors: [Raúl Jiménez] (https://github.com/Elecash), [Robert Zhang] (https://github.com/rogerz), [Javier Tejero] (https://github.com/javiertejero), [Marcos González](https://github.com/qmarcos), [Rafał Lindemann](https://github.com/panrafal), [Alberto Tafoya](https://github.com/withattribution), [Sergey Okhotnitski](https://github.com/5erg), [Javier Cejudo](https://github.com/javiercejudo), [Sam Lau](https://github.com/schmooie), [paxal78](https://github.com/paxal78), [Raymond Klass](https://github.com/RaymondKlass), [Harry Cutts](https://github.com/Fodaro), [Chris MacPherson](https://github.com/chrismacp), [stefanvonderkrone](https://github.com/stefanvonderkrone), [Emil Ibatullin](https://github.com/cawabunga), [Uzair Sajid](https://github.com/UzEE), [pavelnikolov](https://github.com/pavelnikolov), [Frank3K](https://github.com/Frank3K), [EmilioAiolfi](https://github.com/EmilioAiolfi), [Bernhelm](https://github.com/Bernhelm), [Morriz](https://github.com/Morriz), [Chris Funk](https://github.com/a727891), [Johann Beishline](https://github.com/techmodo), [edisonh](https://github.com/edisonh) and [our bug submitters] (https://github.com/2fdevs/videogular/issues?state=open).

## Changelog
Here you can see the complete [changelog] (https://github.com/2fdevs/videogular/blob/master/CHANGELOG.md)
