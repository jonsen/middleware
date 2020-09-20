# Casbin

[iris](https://github.com/kataras/iris) web framework's [casbin](https://github.com/casbin/casbin) middleware.


The authorization determines a request based on `{subject, object, action}`. Please refer to [the Casbin's documentation](https://github.com/casbin/casbin) in order to understand how it works first.

```sh
$ go get github.com/casbin/casbin/v2@v2.9.0
$ go get github.com/jonsen/middleware/casbin@master
```

## Table of contents

- [using wrapper, recommended as it provides the full casbin's functionalities](_examples/wrapper/main.go)
- [using middleware, register to a specific routes or parties](_examples/middleware/main.go)

> Each example has its own model, configuration and its tests, please read them as well.
