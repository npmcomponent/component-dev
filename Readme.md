*This repository is a mirror of the [component](http://component.io) module [component/dev](http://github.com/component/dev). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-dev`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# dev

  Inspect objects associated to DOM elements in web inspector.

  ![](https://dsz91cxz97a03.cloudfront.net/iXpnS5fQAW.png)

## Installation

    $ component install component/dev

## Usage

  When enabled via `localStorage.dev = true` the object
  is assigned as `_` on the element for inspection in the
  "properties" panel. This means when the element is selected
  `$._` is also available. A name may be passed instead of `_`,
  however `_` is nice as it will display early in the properties list.

## API

### inspect(el, obj, [name])

  Associate `obj` with `el` as `name` defaulting to "_".

## License

  MIT
