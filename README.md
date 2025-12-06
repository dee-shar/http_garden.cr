# http_garden.cr
Web-API for [http.garden](https://http.garden/) gardens for every HyperText Transfer Protocol response status code

## Example
```cr
require "./http_garden"

http_garden = HttpGarden.new
status = http_garden.get_status(403)
puts status
```
