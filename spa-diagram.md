## SPA Diagram

1. Participant Browser

2. Participant Server

* Browser -> Server: GET 
https://studies.cs.helsinki.fi/exampleapp/spa


* Browser -> Server: GET https://studies.cs.helsinki.fi/exampleapp/main.css

    - Return the css file

* Browser -> Server: GET https://studies.cs.helsinki.fi/exampleapp/spa.js

    - Return the js file

* The Javascript code is executed

* Browser -> Server: GET https://studies.cs.helsinki.fi/exampleapp/data.json

    - Retriving data of json file

* Browser show list of notes.

## Diagrama de uma SPA

1. participante Browser

2. participante Servidor

* Navegador -> Servidor: Input: Post https://studies.cs.helsinki.fi/exampleapp/new_note 

* Servidor -> Navegador: valor do input GET https://studies.cs.helsinki.fi/exampleapp/notes

* Navegador -> Servidor: GET https://studies.cs.helsinki.fi/exampleapp/main.css

    - Retorna o arquivo css

* Navegador -> Servidor: GET https://studies.cs.helsinki.fi/exampleapp/spa.js

    - Retorna Arquivo JS

* É feita a execução do código JS

* Navegador -> Servidor: GET https://studies.cs.helsinki.fi/exampleapp/data.json

    - Recuperação dos dados no aquivo json

* Navegador mostra a lista de notas.  
