# GerenciadorImagensBack_end

Na parte de back-end, utilizei nodejs, e o servidor local através do mongoose (mongodb que foi instalado através do docker), 
utilizei o multer para requisições multpartform. Todos foram instalados com o yarn que serviou como gerenciador 
de pacotes, bibliotecas, dependências e etc...

INCIAR PROJETO COM O NODEMOON:
yarn dev



BANCO DE DADOS:

Procedimento para lidar com o container criado na imagem do mongodb através do docker:

EXEMPLO DE CRIAÇÂO DA IMAGEM E CONTAINER:

criar imagem através do docker: docker pull mongo

criar container: docker run --name some.mongos - 27017:27017 -d mongo

virificar se está rodando o container: docker ps -a

EXECUTANDO:

executar o container: docker exec -it some.mongos mongo admin

verificar as imagens: docker ps

iniciar o container: docker start some.mongos 











