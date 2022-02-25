# Engajamento no Produto
SQL Queries utilizadas para analisar o engajamento dos usuários e clientes no produto.

# Modelagem Dimensional

Foi utilizada a modelagem dimensional para estruturar os dados e facilitar a análise do engajamento dos usuários e clientes no produto. 

As dimensões criadas foram:
- Período
- Funil do Parceiro (para identificar quem são os parceiros atuais do produto)
- Instituições (relaciona dados das instituições a partir do CRM e do Funil do Parceiro)
- Usuários 
- Livros
- Integrações (tipo de integrações usadas para acessar a plataforma)
- User Agent (para saber o device, browser e sistema operacional utilizados pelos usuários)

As fatos criadas foram:
- Logins
- Bookviews (aberturas dos livros)
- Pageviews (páginas visualizadas)

![image](https://user-images.githubusercontent.com/54243780/155637591-860b5726-b8e1-442c-bcd4-8e8a971c2913.png)
