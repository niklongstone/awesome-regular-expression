# Awesome PCRE
A curated list of the best Perl Compatible Regular Expressions.

## Contributing
Please see [CONTRIBUTING](https://github.com/niklongstone/awesome-regular-expression/blob/master/CONTRIBUTING.md) for details.

## Table of Contents
 - [Internet](#internet)
    - [email](#email)
    - [url](#url)
 - [Number](#number)

## Internet
#### Email
match|expression 
:---|:---  
`my.name.foo@bar.yea.co.uk` | `^[_a-z0-9-]+(\.[_a-z0-9-]+)*@[a-z0-9-]+(\.[a-z0-9-]+)*(\.[a-z]{2,4})` 

#### Url
match|expression  
:---|:---  
`http://test.com/test-1` | `^(http|https|ftp)\:[\/]{2}[a-zA-Z0-9\-\.]+\.[a-zA-Z]{2,3}(:[a-zA-Z0-9]*)?\/?([a-zA-Z0-9\-\._\?\,\'\/\\\+&amp;%\$#\=~])*$`

##Number
match|expression 
:---|:---  
`100.112,00` | `^-?(\d+|\d{1,3}(\.\d{3})+)(\,(\s)?\d*)?$` 
