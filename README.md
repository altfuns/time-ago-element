# &lt;time-ago&gt;

Time elements using Polymer and Moment.js

## Demo

> [Check it live](http://altfuns.github.io/time-element).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install time-element --save
```

## Usage

1. Import Web Components' polyfill:

  ```html
	<script src="bower_components/platform/platform.js"></script>
  ```

2. Import Custom Element:

  ```html
	<link rel="import" href="bower_components/time-element/time-ago.html">
	<link rel="import" href="bower_components/time-element/time-format.html">
  ```

3. Start using it!

  ```html
	<time-ago datetime="2014-09-15 12:05:00" delay="6000" refresh="true"></time-ago>
	<time-format datetime="2014-09-15 12:05:00" format="MMM Do YY"></time-format>
  ```

## Options

### <time-ago>

Attribute   | Options      | Default                 | Description
---         | ---          | ---                     | ---
`datetime`  | *string*     | `0000-00-00 00:00:00`   | Date and time in YYYY-MM-DD HH:mm:ss format
`refresh`   | *boolean*    | `true`               	 | Auto refresh
`delay`     | *int*        | `60000`               	 | Delay to auto refresh (in milliseconds)

### <time-format>

Attribute   | Options      | Default                 | Description
---         | ---          | ---                     | ---
`datetime`  | *string*     | `0000-00-00 00:00:00`   | Date and time in YYYY-MM-DD HH:mm:ss format
`format`    | *string*     | `YYYY-MM-DD HH:mm:ss`   | Give the format to the result label.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Manteiners

<time-ago> element create by [Bruno Ziiê](https://github.com/brunoziie).
<time-format> element create by [Alfonso Aguilar](https://github.com/altfuns).

## History

* v0.0.1 August 25, 2013
	* Created timeago element
* v0.0.2 August 26, 2013
	* Add delay attribute

## License

[MIT License](http://opensource.org/licenses/MIT)
