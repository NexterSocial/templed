# Templed by Nexter

> Based in [EJS](https://github.com/mde/ejs)!

## Installation

```bash
$ npm install templed
```

## Example

```ejs
<% if (user) { %>
  <p><%= user.name %></p>
<% } %>
```

## Basic usage

```js
const template = ejs.compile(str, options);
template(data);
// => Rendered HTML string

ejs.render(str, data, options);
// => Rendered HTML string
```
