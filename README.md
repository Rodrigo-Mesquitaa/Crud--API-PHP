Crud--API-PHP
Projeto API Crud reazliado em PHP produtos.



           #  Como usar:

           Baixe o Postman : https://www.getpostman.com/
       
           No metodo FindOne utilize
      
           http://localhost/rest-server/api/produto/findOne?id=1
    

           # No metodo read usar:

            http://localhost/rest-server/api/produto/read
   

           # No metodo Delete usar: 

            Procure pelo ID do item que deseja excluir

            Abra o programa

            Em Headers na opção Key selecione o item Content-Type,
            e na opção Value selecione o application/json

           Mude a opção na URL para PUT

           E cole a URL abaixo:

           http://localhost/rest-server/api/produto/delete

           Clique em Body e selecione a opção RAW

           Coleque a estrutura do objeto em formato json:

           {
            "id" : 13
                    }

            Clique em SEND
    

           # No metodo Create:

           Abra o programa

           Em Headers na opção Key selecione o item Content-Type,
           e na opção Value selecione o application/json

           Mude a opção na URL para POST

          E cole a URL abaixo:  

          http://localhost/rest-server/api/produto/create
      

         // Clique em Body e selecione a opção RAW

          Coleque a estrutura do objeto em formato json:

            {
                "descricao" : "item-teste",
                "quantidade" : 100,
                "valor" : 900
            }

             Clique em SEND


          # No metodo Update usar:
          
           Abra o programa

            Em Headers na opção Key selecione o item Content-Type,
            e na opção Value selecione o application/json

            Mude a opção na URL para PUT

            E cole a URL abaixo:

            http://localhost/rest-server/api/produto/update

            Clique em Body e selecione a opção RAW

            Coleque a estrutura do objeto em formato json:

            {
                "id" : 13,
                "descricao" : "item-teste",
                "quantidade" : 20,
                "valor" : 100
            }


        Clique em SEND
    
    