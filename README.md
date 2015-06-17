# Awesome PCRE
A curated list of the best Perl Compatible Regular Expressions.

## Contributing
Please see [CONTRIBUTING](https://github.com/niklongstone/awesome-regular-expression/blob/master/CONTRIBUTING.md) for details.

## Table of Contents
 - [Internet](#internet)
    - [email](#email)


## Internet
#### Email
expression|match 
:---|:---  
`^[_a-z0-9-]+(\.[_a-z0-9-]+)*@[a-z0-9-]+(\.[a-z0-9-]+)*(\.[a-z]{2,4})` | `my.name.foo@bar.yea.co.uk`

#### Url
expression|match 
:---|:---  
`^(http|https|ftp)\:[\/]{2}[a-zA-Z0-9\-\.]+\.[a-zA-Z]{2,3}(:[a-zA-Z0-9]*)?\/?([a-zA-Z0-9\-\._\?\,\'\/\\\+&amp;%\$#\=~])*$` | `http://test.com/test-1`

##Number
expression|match 
:---|:---  
`^-?(\d+|\d{1,3}(\.\d{3})+)(\,(\s)?\d*)?$` | `100.112,00`
