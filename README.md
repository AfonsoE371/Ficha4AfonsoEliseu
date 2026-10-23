Para abrir o site: Antes de fazer o seguinte confirmar que tem um compilador para node.js, ter o vite instalado no client e o express no server.
abrir um terminal gitbash e depois usar o comando "cd" de modo a ir para a pasta src dentro da pasta client e depois usar "npm run dev" para abrir o site, após ou antes disso 
(a ordem não é importante o que interessa é estarem ambos abertos) abrir um outro terminal gitbash ao mesmo tempo que o outro navegar para a pasta server com o comando "cd" e usar o comando "node --watch server".

O endereço localhost:3000/api/cartas abre na barra do browser, mas sem o header o fetch da app React falha. Quem bloqueou: o server ou o browser? Como é que sabes? Depende ao carregar f12 é possivel verificar quem bloqueou
podendo ser o browser caso o server não tenha um header ou o servidor caso seja mostrado algum erro.

Quantos requests faz agora a app React ao abrir e ao filtrar? Onde vivem os dados, e onde é construído o HTML?: 
Requests:1 ao abrir a app e 0 ao filtrar.
Os dados estão presentes num array.
O html é gerado no browser para a app em react e o html para a página do server é gerado no server em si.
