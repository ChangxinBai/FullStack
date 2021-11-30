## 0.4: new note
browser-->server: HTTP POST  ./exampleapp/one_note <br>
server-->browser: URL redirect<br>
browser-->server: HTTP GET ./exampleapp/nots<br>
server-->browser: HTML code<br>
browser-->server: HTTP GET ./exampleapp/main.css<br>
server-->browser: main.css<br>
browser-->server: HTTP GET ./exampleapp/main.js<br>
server-->browser: main.js<br>

note over browser:<br>
browser starts executing js-code that requests JSON data from server <br>

browser-->server: HTTP GET ./exampleapp/data.json<br>
server-->browser: [{content:”XXX”, data:”XXX”},]<br>

note over browser:<br>
browser executes the event handler that renders notes to display<br>

## 0.5: Single page app
browser-->server: HTTP GET ./exampleapp/spa<br>
server-->browser: HTML code<br>
browser-->server: HTTP GET ./exampleapp/main.css<br>
server-->browser: main.css<br>
browser-->server: HTTP GET ./exampleapp/main.js<br>
server-->browser: main.js<br>

note over browser:<br>
browser starts executing js-code that requests JSON data from server <br>

browser-->server: HTTP GET ./exampleapp/data.json<br>
server-->browser: [{content:”XXX”, data:”XXX”},]<br>

note over browser:<br>
browser executes the event handler that renders notes to display<br>

## 0.6: New Note

Note over browser:<br>
browser executes the event handler that renders new added notes to display<br>
brower-->server: HTTP POST ./exampleapp/new_note_spa<br>
