#Explicação do projeto#

#Participantes: Pedro Henrique Basilio e Matheus Henrique Bueno

O projeto é um estoque que gerencia o fluxo de entrada e saida do estoque, sem cometer furos.
 
 ENDPOINTS: GET/products - lista todos os produtos
            GET/products/:ID - Busca item especifico
            POST/products - Cadastra novo produto
            DELETE/products/:ID - Remove produto do estoque

Bibliotecas : Microsoft.EntityFrameworkCore;
              Microsoft.EntityFrameworkCore.Design;
              Microsoft.EntityFrameworkCore.Tools;
              Microsoft.EntityFrameworkCore.Sqlite;
              Swashbuckle.AspNetCore;