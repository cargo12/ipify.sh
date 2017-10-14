# ipify.sh

> Unofficial client library for [ipify](https://www.ipify.org): A Simple IP Address API.

# Features

* Testing **Internet Connection** first
* Return the **Public IP** address in the following formats
  * **text**
    * e.g. `98.207.254.136`
  * **json**
    * e.g. `{"ip":"98.207.254.136"}`
  * **jsonp**
    * e.g. `callback({"ip":"98.207.254.136"});`
  * **jsonp**
    * e.g. `getip({"ip":"98.207.254.136"});`
* Exit Codes
  * `0`
    * Successful operation
  * `1`
    * Invalid or Missing Arguments
  * `2`
    * Connection Issues

# Getting Started

```bash
$ wget https://github.com/xtonousou/ipify.sh/blob/master/ipify.sh
$ source ipify.sh
$ get_ip -h
```

# Usage

## Proper Usage

```bash
<<<<<<< HEAD
COMMAND             TYPE  OUTPUT
=======
COMMAND            TYPE  OUTPUT
>>>>>>> e8e927b85f808776c2404b5b4e1dfd5c87acacb9
get_ip -h, --help   text  This help message
get_ip -t, --text   text  98.207.254.136
get_ip -j, --json   json  {"ip":"98.207.254.136"}
get_ip -J, --jsonp  jsonp callback({"ip":"98.207.254.136"});
get_ip -g, --get-ip jsonp getip({"ip":"98.207.254.136"});
```

### Importing Library

You can source the script to anywhere and use its function to get the Public IP.
Put the following line at the beginning of your script. Of course replace the path with the right one first.

```bash
source /path/to/ipify.sh
```

# More Like This

* [ship](https://github.com/xtonousou/ship) - A simple, handy network addressing multitool with plenty of features 

# License

MIT © [Sotirios M. Roussis (xtonousou)](https://xtonousou.github.io)
