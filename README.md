Este projeto visa desenvolver uma aplicação que permita mapear casas em que faltam água e ou luz.

A ideia é fazer algo similar a:

http://www.faltouagua.com/

As tecnólogias que devem ser empregadas são:

nodejs
leaflet
mongodb

Inicialmente utilizei o tutorial:

http://learnjs.io/blog/2013/11/08/leaflet-basics/

Para iniciar a ferramenta faça:

npm start

e acesse o contéudo no link:

http://localhost:9966/

Parei a leitura no comando:

browserify app.js -o bundle.js

A API Key deste projeto é do site:

http://maps.stamen.com/#toner/13/37.7426/-122.4094

Isso é ligeiramente diferente do artigo original. Mas já esta funcionando.

Todas as modificações podem ser feitas nos arquivos:

app.js
style.css
index.html
package.json

Materiais auxiliares:

tutorial em vídeo:

https://www.youtube.com/watch?v=4sGgB2SBMew

material auxiliar do tutorial em vídeo

https://github.com/thesteve0/fluentwebmap/blob/master/server.js

mark cluster (varios pontos em um unico ponto)

https://github.com/Leaflet/Leaflet.markercluster

Materia sobre como usar mongodb com nodejs:

http://howtonode.org/node-js-and-mongodb-getting-started-with-mongojs

guia rapido leaflet:

http://leafletjs.com/examples/quick-start.html


TODO

Temos que adicionar o mongodb, fazendo um array de localizações na aplicação.
