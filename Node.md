# Criando um servidor Node
`const express = require('express')`
`const app = express()`
`app.set("view engine", "ejs")`

`app.get("/", function(req, res){res.render("index")})`
`app.listen(8080)`

#Incluindo páginas EJS

`<%- include('../partials/nav.ejs'); %>`
