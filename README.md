# gowire
Go WIRE go generate not working when using gomodule


## How to test
```
go mod vendor
go generate
```

ERROR:
```
Lucians-MacBook-Pro:gowire khanakia$ go generate
cannot find package "." in:
	/Volumes/D/www/go1/gowire/vendor/github.com/google/wire/cmd/wire
wire_gen.go:3: running "go": exit status 1
Lucians-MacBook-Pro:gowire khanakia$ 

```

