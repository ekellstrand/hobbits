# Response Codes

The EWP defines various response codes inspired by [HTTP Status codes](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes).

## `200` Ok

This response code is considered the **default** code. It is returned when the request could be answered as is expected.

## `400` Bad Request

This response code is returned when the `message` is malformed e.g. does not contain the required fields.

## `403` Forbidden

This response code is returned when the caller is not allowed to access specific data.

## `404` Not Found

This response code is returned when the called `command` does not exist. 

## `500` Internal Server Error

This response code is returned when a node experiences some form of internal error that causes it to fail handling the request as expected.