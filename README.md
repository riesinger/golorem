# Go Lorem!
CLI lorem ipsum generator written in Go

## Installing
`go get -u github.com/riesinger/golorem` is your friend! :wink:

## Usage
```shell
$ golorem --words 100
> 100 random (pseudo-)latin words

$ golorem -w 100
> -w is an alias for --words

$ golorem --paragraphs 10
> 10 paragraphs with 10 words each (separated with two newlines)

$ golorem -p 10
> -p is an alias for --paragraphs

$ golorem --paragraphs 10 --words 100
> 10 paragraphs with 100 words each

$ golorem -p 10 --paragraph-separator="<br>"
> 10 paragraphs separated with "<br>" (for HTML use)
```

*Please note:* Escape sequences do not work inside of `--paragraph-separator`, if you know how to make the pflags (or even flags) package parse those, tell me!
