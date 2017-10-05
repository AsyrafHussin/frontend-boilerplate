# Frontend Boilerplate
Front-end boilerplate

## Contains
* [Boostrap 3](https://getbootstrap.com/docs/3.3/font)
* [jQuery](https://jquery.com/)
* [sass-boilerplate](https://github.com/AsyrafHussin/sass-boilerplate)
* [Font Awesome](http://fontawesome.io/icons)
* [Material Design Icons](https://materialdesignicons.com)
* [Laravel Mix](https://github.com/JeffreyWay/laravel-mix)

## Getting Started
```
$ git clone https://github.com/AsyrafHussin/frontend-boilerplate.git <project-name>
$ cd <project-name>
$ rm -rf ./.git && rm -rf ./README.md
$ npm install
$ npm run dev
```

## Serve Project
Using [http-server](https://www.npmjs.com/package/http-server)

* Install
```
$ npm install -g http-server
```

* Serve
```
$ http-server ./ -p 8000
```

* Serve using npm
```
$ npm run serve
```

## Available Command
List all available command

| Command            | Description                                     |
| ------------------ |:-----------------------------------------------:|
| npm run dev        | Run all Mix tasks                               |
| npm run watch      | Watch all files for changes and recompile       |
| npm run production | Run all Mix tasks and minify output             |
| npm run serve      | Serving project at http://127.0.0.1:8000        |

## Contributing
If you spot any errors, typos or missing information, please submit a pull request.