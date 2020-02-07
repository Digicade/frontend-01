[![Digicade](http://digicade.com.br/wp-content/uploads/2016/10/logo@2-digicade.png "Digicade")](http://digicade.com.br "Digicade")
# Processo seletivo - Desenvolvedor Front-End

A primeira etapa do processo seletivo consiste na implementação de um projeto Web.

#### Orientações:
1. Desenvolver cadastro de clientes seguindo o modelo proposto nos arquivos disponibilizados no diretório [/telas](/telas)
2. A aplicação deverá se comportar de forma responsiva, considerando os breakpoints (Celulares <768px, Tablets e Desktops ≥768px), conforme demonstrado no vídeo [/video/prova-front-end-digicade.mp4](/video/prova-front-end-digicade.mp4?raw=true)
3. Elementos CSS3 e HTML5 são permitidos, analizaremos seu teste nas últimas versões (normal estável) do Chrome e Firefox.
5. Utilize os recursos que desejar, somente tomando cuidado com os itens listados no tópico restrições.
6. Fique à vontade para organizar seu código CSS, utilizando o pre-processador de sua preferência.
7. Os dados deverão ser persistidos utilizando a API abaixo:
    - Listar Clientes:
        ```
	    GET https://prova-recrutamento.digicade.com.br:30350/clientes
        ```
    - Incluir Cliente:
        ```
        POST https://prova-recrutamento.digicade.com.br:30350/clientes
        Exemplo:
        {
        	"nome"      : "Digicade Tecnologia",
        	"cpf"       : "01.485.079/0001-50",
        	"telefone"  : "(31) 3263-1100",
        	"email"     : "contato@digicade.com.br",
        	"latitude"  : -19.937048,
        	"longitude" : -43.93485
        }
        ```
    - Alterar Cliente:
        ```
        PUT https://prova-recrutamento.digicade.com.br:30350/clientes/<ID>
        ```
    - Remover Cliente:
        ```
        DELETE https://prova-recrutamento.digicade.com.br:30350/clientes/<ID>
        ```
8. A interface de mapa deverá ser implementada baseada na API Google Maps [https://developers.google.com/maps/documentation/javascript/adding-a-google-map](https://developers.google.com/maps/documentation/javascript/adding-a-google-map)
9. O projeto deverá ser disponibilizado no Github. Envie um email com o assunto (frontend-test - Seu Nome) contendo o link do projeto para bancodetalentos@digicade.com.br

#### Restrições:
- O layout deverá ser desenvolvido sem a utilização de frameworks como por exemplo Bootstrap. A organização de seu código CSS será avaliada.
- Caso julgar necessária utilização de alguma biblioteca para o desenvolvimento javaScript, utilize apenas JQuery. 
- Os arquivos deverão ser entregues sem minificação.

#### Avaliação:
- Os critérios abaixo serão levados em consideração para avaliação:
- Clareza e organização do código
- Resultado visual e funcional do projeto.
- Lógica de programação.

#### Diferenciais (opcional):
- Consistências e mascaras no formulário.
- Desenvolver o mesmo projeto utilizando frameworks de desenvolvimento tais como Vue, React ou Angular2+. Somos adeptos do VUE!!! Nesse caso, você deverá entregar dois projetos. Sinta-se livre para inovar e utilizar qualquer biblioteca caso opte por entregar o segundo projeto. As restrições não se aplicam ao segundo projeto.
