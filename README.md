# server-http-response
Pacote de respostas http feitas para o servidor.

### Como instalar?
Use `npm install server-http-response` para installar a galeria em seu projeto:<br />

![How to install](/install.gif)

### Para que serve?
O pacote server-http-response tem como utilidade facilitar as respostas(res) feitas em suas requisições no backend.<br />

#### Como importar?
Para usar o pacote é necessário simplesmente importar o módulo e caturar suas funções:

###### Exmeplo:
![How to import](/import.png)


###### Como usar?
As funções recebem sempre dois parâmetros necessários:<br />
`res` e `payload`<br />
res(response) - sendo a resposta da api.
payload - sendo a mensagem ou informações que você deseja retornar ao usuário.<br />

###### Exmeplo:
![How to use](/function.png)

### Funções que podem ser usadas:

  * continues - 100<br />
  * switchingProtocols - 101<br />
  * processing - 102<br />
  * earlyHints - 103<br />
  * ok - 200<br />
  * created - 201<br />
  * accepted - 202<br />
  * nonAuthoritative - 203<br />
  * noContent - 204<br />
  * resetContent - 205<br />
  * partialContent - 206<br />
  * multiStatus - 207<br />
  * imUsed - 226<br />
  * multipleChoice - 300 <br />
  * movedPermanently - 301 <br />
  * found - 302 <br />
  * seeOther - 303 <br />
  * notModified - 304 <br />
  * useProxy - 304 <br />
  * unused - 306 <br />
  * temporaryRedirect - 307 <br />
  * permanentRedirect - 308 <br />
  * badRequest - 400 <br />
  * unauthorized - 401 <br />
  * paymentRequired - 402 <br />
  * forbidden - 403 <br />
  * notFound - 404 <br />
  * methodNotAllowed - 405 <br />
  * notAcceptable - 406 <br />
  * proxyAuthenticationRequired - 407 <br />
  * requestTimeout - 408 <br />
  * conflict - 409 <br />
