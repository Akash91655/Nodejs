# Create a server , run it on port 4000 and console log your name.


var http = require('http')

http.createServer(function(req, res){
    res.end("Akash Kumar")
}).listen(4000)
