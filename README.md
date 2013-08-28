# &lt;my-element&gt;

TODO: Write a project description

> Maintained by [Gustavo Isensee](https://github.com/gustavoisensee).

## Demo

> [Check it live](http://customelements.github.io/pinterest-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/pinterest.html">
	```

3. Start using it!

	```html
	<pinterest></pinterest>
	```

## Options

url urlImage description config
Attribute     | Options                   | Default                                                                | Description
---           | ---                       | ---                                                                    | ---
`url`         | *string*                  | `https://github.com/gustavoisensee`                                    | Lorem ipsum
`urlImage`    | *string* 	              | `http://www.gravatar.com/avatar/fc33435ffe5822ba2cb2096f44d15d05.png`  | Lorem ipsum
`description` | *string*                  | `Web Developer`                                                        | Lorem ipsum
`config`      | *string*                  | `beside`                                                               | Lorem ipsum


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)