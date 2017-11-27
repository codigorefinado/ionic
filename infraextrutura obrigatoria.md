Infraextrutura necess�ria e obrigat�ria
===================


Prepara��o do ambiente
-------------

Para que seja poss�vel instalar o Ionic, � necess�rio instalar:
1- [Node.js](http://www.nodejs.org) 
2 - [Editor de texto](https://www.jetbrains.com/webstorm/download/)
3 - [ionic cli](http://ionicframework.com/getting-started/)

[Node.js](http://www.nodejs.org) instalada. O Node.js � um ambiente JavaScript multiplataforma dispon�vel para Linux, Mac e Windows. Para instal�-lo, siga as instru��es abaixo:

Instala��o Node.js no Linux (Ubuntu)
-------------
No Ubuntu, atrav�s do terminal (permiss�o de administrador � necess�ria) execute o comando abaixo:

```
sudo apt-get install -y nodejs
```

ATEN��O: em algumas distribui��es Linux, pode haver um conflito de nomes quando o Node � instalado pelo apt-get. Nesse caso espec�fico, no lugar do bin�rio ser node, ele passa a se chamar nodejs. Isso gera problemas, pois a instru��o npm start n�o funcionar�, pois ela procura o bin�rio node e n�o nodejs. Para resolver, use a seguinte instru��o no terminal para subir o servidor:
```
nodejs server
```
Ou no Ubuntu:

```
sudo ln -s /usr/bin/nodejs /usr/bin/node
```

Depois o comando npm start funcionar� conforme esperado.


� uma pena haver essa discrep�ncia, mas fica aqui essa dica!
[Dica de como instalar nodejs e n�o precisar de sudo toda hora no linux](https://medium.com/codigorefinado/dica-r%C3%A1pida-de-como-instalar-o-node-sem-sudo-no-linux-6e4439521070)

Instala��o Node.js no Windows
-------------
Baixe o instalador clicando no grande bot�o de Download, diretamente da p�gina do Node.js. Durante a instala��o, voc� apenas clicar� nos bot�es para continuar o assistente. N�o troque a pasta padr�o do Node.js durante a instala��o, a n�o ser que voc� saiba exatamente o que est� fazendo.

Instala��o Node.js no MAC
O homebrew � a maneira mais recomendada para instalar o Node.js em sua m�quina, atrav�s do comando:
```
brew update
brew install node
```
N�o usa homebrew? Sem problema, baixe o instalador clicando no grande bot�o de Download, diretamente da p�gina do Node.js.

Instale um editor de texto ou IDE
-------------
Voc� vai precisar de um editor de texto, ou IDE para escrever seus c�digos. Particularmente, **prefiro o [WebStorm](https://www.jetbrains.com/webstorm/download/)**. Caso voc� seja estudante, pode conseguir uma [licen�a](https://www.jetbrains.com/webstorm/buy/#edition=discounts), apenas pedindo, � necess�rio apenas preencher um formul�rio onde voc� envia documentos da institui��o.

Se voc� quiser usar o Visual Studio Code, ou Sublime, pode, mas para torn�-lo produtivo ter� de instalar uma s�rie e plugins. Caso queira testar o Visual Studio Code fiz uma lista das [melhores extens�es para trabalhar com Angular](https://medium.com/codigorefinado/as-melhores-extens%C3%B5es-para-visual-studio-code-para-se-trabalhar-com-angular-da044ed6d0d0?source=false---------1) pra voc� gastar um pouco menos tempo testando as diversas op��es dispon�veis. Tarefa dispens�vel quando se utiliza o  [WebStorm](https://www.jetbrains.com/webstorm/download/).


Instale o ionic cli
-------------
Execute no prompt de comando (shell linux, DOS, powershell) o comando a baixo para instalar o ionic cli e o cordova pelo gerenciador de pacotes do node.
```
npm install -g cordova ionic
```

Leia
 [Codigo Refinado](http://medium.com/codigorefinado)