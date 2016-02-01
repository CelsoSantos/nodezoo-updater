a![Nodezoo](https://raw.githubusercontent.com/rjrodger/nodezoo-web/to-redux/client/assets/img/logo-nodezoo.png)

# nodezoo-NPM-UPDATE
Nodezoo.com micro-service handling npm data.. Please see the [main repo][] for more details.

- __Sponsor:__ [nearForm][]




# Running

```sh
$ node npm-service.js --seneca.options.from=dev.options.js --seneca.log.all
```

## Messages

This micro-service recognizes the following messages:

  * _role:npm,task:registry_subscribe_
  * _role:npm,task:process_modules_
  * _role:npm,task:download_modules_ 

## Contributing
The [NodeZoo][] org encourages open participation. If you feel you can help in any way, be it with documentation, examples, extra testing, or new features please get in touch.

## License
Copyright (c) 2015, Richard Rodgers and other contributors.
Licensed under [MIT][].

[main repo]: https://github.com/rjrodger/nodezoo
[MIT]: ./LICENSE
[Code of Conduct]: https://github.com/nearform/vidi-contrib/docs/code_of_conduct.md
[nearForm]: http://www.nearform.com/
[NodeZoo]: http://www.nodezoo.com/
