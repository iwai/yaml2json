# yaml2json

Command line YAML to JSON conversion tools

## Require

* PHP 5.3 or higher

## Install

```bash
$ curl -LO https://github.com/iwai/yaml2json/releases/download/v1.0.0/yaml2json.phar
$ chmod +x yaml2json.phar
```

Recommend move to /usr/local/bin, renamed ```yaml2json```

## Help

```bash
$ ./yaml2json.phar --help
 ./yaml2json.phar

arg 0
     Required. YAML file path


--help
     Show the help page for this command.


--human-readable
     Output human readable
```

## Build Phar file (for developer)

### Clone this repository

```bash
$ git clone https://github.com/iwai/yaml2json.git
```

### Composer install

```bash
$ cd yaml2json
$ composer install --no-dev
```

### Get a box

```bash
$ curl -LSs https://box-project.github.io/box2/installer.php | php
```

### Build

```bash
$ ./box.phar build -c ./box.dist.json
```
