const http = require("http");
const port = 8081;
http
 .createServer ((req,res)=>
{
    res.writehead(200,{"content-type":"text/html"});
    res.write("<h2>HEY SERVER STARTED :-)</h2>");
    res.end();
})

.listen (port,()=>{
    console.log( 'Nodejs server started running on the port : ${port}' );
});
