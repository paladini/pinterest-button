# &lt;pinterest-follow&gt;

Web Component wrapper for Pinterest-button's like button using Polymer.

> Maintained by [Fernando Paladini](https://github.com/paladini).

## Demo

> [Check it live](http://gustavoisensee.github.io/pinterest-button).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="http://www.polymer-project.org/polymer/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/pinterest-follow.html">
	```

3. Start using it!

	```html
	<pinterest-follow profile="http://www.pinterest.com/myProfileUsername" text="Follow Me on Pinterest!"></pinterest-follow>
	```

## Options

Attribute     | Options                   | Default                                                                | Description
---           | ---                       | ---                                                                    | ---
`profile`         | *string*                  |                                     | url or profile name of the desireed user
`text`    | *string* 	              | `Follow Me!`  | text that will appear inside the Pinterest follow button.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.1 November 23, 2013

* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

* polymer updated to version 0.0.20130816

## License

[MIT License](http://opensource.org/licenses/MIT)