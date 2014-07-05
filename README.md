secretary(書記)
=========

[WIP]いい感じにfluentdでログを取れる1x1.gifを配信する軽量サーバをデプロイするDockerfile(予定)

Usage
--

`GET http(s)://example.com/some_namespace.gif?foo=bar&ruby=rails`

```json
{
  "some_namespace": {
    "foo": "bar",
    "ruby": "rails"
  }
}
```

`POST http(s)://example.com/some_namespace`

with Request body
