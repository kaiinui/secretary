witness
=========

Usage
--

### GET

`GET http(s)://example.com/some_namespace.gif?foo=bar&ruby=rails`

logs following row

```json
{
  "some_namespace": {
    "foo": "bar",
    "ruby": "rails"
  }
}
```

### POST

`POST http(s)://example.com/some_namespace`

with body

```
{
  "foo": "bar",
  "ruby": "rails"
}
```

logs following row

```json
{
  "some_namespace": {
    "foo": "bar",
    "ruby": "rails"
  }
}
```
