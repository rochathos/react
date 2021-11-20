# react
Criando uma React:
Na criação do react voçê pode utlizar https://create-react-app.dev/docs/getting-started com links detalhados dedocumentos e scripts nessesarios 

Criação do Docker:
O primeiro passo é o mais simples, será criar um arquivo chamado Dockerfile
Definir uma imagem oficial como base para ser modificada Podemos definir uma imagem através da instrução FROM
Definir informações para a imagem (versão, descrição e autor) LABEL seguida pelas informações à serem adicionadas na imagem.
Criar a pasta onde serão enviados os arquivos carregados pelo site RUN, ela é responsável por executar comandos conhecidos pelo shell
Copiar o site para a imagem instrução COPY passando o nome do arquivo ou pasta que pretendemos copiar seguida pelo caminho onde as mesmas devem ser copiadas:
Mapear uma pasta onde serão salva as imagens do site
Para isso podemos utilizar a instrução VOLUME:

Bem como o dickfile o Docker-compose tem um scopo parecido Nesse arquivo Compose que mencionei no início do texto, descrevemos a infraestrutura como código e como ela vai se comportar ao ser iniciado.
com tags como version, services, app, volumes e etc. que podem ser bem mais detalhadas no site: https://docs.docker.com/compose/install/
