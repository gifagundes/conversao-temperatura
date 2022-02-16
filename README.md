Como subir um container com este projeto

Navegue até a pasta src
CD src/

Criando a imagem
docker image build -t gfagundes/conversao_temperatura:v1 .
* Substitua o namespace gfagundes pelo seu identificador

Criando o container
docker container run --name conversao_temperatura -d -p 9090:8080 gfagundes/conversao_temperatura:v1
* Substitua o namespace gfagundes pelo seu identificador