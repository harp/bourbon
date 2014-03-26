# harp-bourbon

> A simple and lightweight mixin library for Sass

## Dependencies

* [NodeJS](http://nodejs.org/) – _Server-side JavaScript runtime_
* [Harp](http://harpjs.com/) – _The static web server with built-in preprocessing_
* [Component](http://component.io) – _Client package management for building better web applications_

## Install

First, install Harp and Component:

```bash
sudo npm install -g harp
sudo npm install -g component
```

To install Bourbon, run the following commands from the root of your Harp project:

```bash
component install harp/bourbon
```

Your project will look something like this…

```
myproject/                  <-- your project root (or public dir if in framework-mode)
  |- components/            <-- harp puts components here
  |   +- harp-bourbon/      <-- where this lib gets installed
  |       …
  |- main.scss              <-- where you reference Bourbon
  +- index.jade             <-- where you reference main.css
```

## Link

Now, from within a `.scss` file in your project, you can `@import` Bourbon:

```scss
@import "components/harp-bourbon/scss/bourbon";
```

Or, just a portion of Bourbon:

```scss
@import "components/harp-bourbon/scss/css3/transition";
```

## License

This component is [Bourbon](http://github.com/thoughtbot/bourbon), which is Copyright © 2011-2013 thoughtbot and MIT licensed.
