<p>Como subir um container com este projeto</p>
<br>
<p>Navegue até a pasta src</p>
<p>CD src/</p>
<br>
<p>Criando a imagem</p>
<p>docker image build -t gfagundes/conversao_temperatura:v1 .</p>
<p>* Substitua o namespace gfagundes pelo seu identificador</p>
<br>
<p>Criando o container</p>
<p>docker container run --name conversao_temperatura -d -p 9090:8080 gfagundes/conversao_temperatura:v1</p>
<p>* Substitua o namespace gfagundes pelo seu identificador</p>
<br>
<p>Acessando a aplicação</p>
<p>Pelo seu navegador acesse http://localhost:9090</p>
