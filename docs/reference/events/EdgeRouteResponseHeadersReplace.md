
|&nbsp;|&nbsp;|&nbsp;|&nbsp;|
|---|---|---|---|
| edge_id | string | |  |
| id | string | |  |
| module.enabled | boolean | | `true` if the module will be applied to traffic, `false` to disable. default `true` if unspecified |
| module.add | Map&lt;string, string&gt; | | a map of header key to header value that will be injected into the HTTP Response returned to the HTTP client |
| module.remove | List&lt;string&gt; | | a list of header names that will be removed from the HTTP Response returned to the HTTP client |