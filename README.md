# amqp-stream-cli
Stream data to an AMQP server from the command-line.

## Installation
```
npm install amqp-stream-cli -g
```

## Usage
```
Send AMQP messages from the command line.

Usage:
  ampq-stream [options]

Options:
  -h --help                     Show this screen.
  --version                     Show version.

  --url=<url>                   AMQP server to connect to.                      [default: amqp://guest@localhost//]
  --exchange=<exchange>         If using an exchange, set it with this option.
  --routing-key=<#>             Sets the routing key used for reads/writes.     [default: #]
```

_**NOTE:** This is simply a CLI wrapper around [node-amqp-stream](https://github.com/jasonpincin/node-amqp-stream). The usage options do not encompass all possible AMQP settings yet. Please contribute if you need more. :-)_

## License
**Creative Commons 3.0 - Attribution Sharealike**

You can remix, copy or use for both commercial and non-commercial products and services but you need to provide attribution for the original work in the source code to *"PetroFeed Inc."*. You must also share the original or any derivative under the same license. A description of the license can be found [here](http://creativecommons.org/licenses/by-sa/3.0).

---

Proudly brought to you by [PetroFeed](http://PetroFeed.com).

![Pedro](https://www.petrofeed.com/img/company/pedro.png)