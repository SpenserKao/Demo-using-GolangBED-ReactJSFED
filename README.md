# Demo-using-GolangBED-ReactJSFED
A demo project using Golang for back-end server, while ReactJS front-end. 

## ReactJS as Front-end
**index.html** contains ReactJS code, which dsiaplays greetiing message, will be invoked by *Golang* code in the back-end. 
Run-time libraries, version 16.0 of reactJS and react-dom, will be downloaded at run-time by the index.html.

## Golang as backend
**server.go** will parse and render the aforementioned **index.html** through Golang's module *template*.

## Execution
Using command line run command _**go run server.go**_ and open url **http://localhost:8080/** in any browser.

## Expected Result
Upon seccesufl exection, should see following heading 1 and message below:
<large>Welcome to the Golang app</large>

*Using Golang as server while ReactJS frontend!*
