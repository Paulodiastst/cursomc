<div align = "center">
    <h1> Implementação padrão do seguinte modelo conceitual</h1>
</div>

<div><h2 align = "center">
  Esse repositório foi criando para conter os códigos-fontes do projeto implementação Java com Spring Boot e JPA.
</h2>
</div>

<div id="objetivo">
<h2> 💡 Objetivo </h2>
Mostrar na prática como um modelo conceitual pode ser implementado
sobre o paradigma orientado a objetos, usando padrões de mercado e boas práticas.
Vamos tomar como caso um modelo conceitual abrangente, com o qual possamos mostrar a implementação prática em linguagem orientada a objetos dos tópicos aprendidos no curso, quais sejam:
</div>

<br>

- Leitura e entendimento do diagrama de classes
- Leitura e entendimento do diagrama de objetos
- Associações
- MaterializeUm para muitos / muitos para um
- Um para um
- Muitos para muitos
- Conceito dependente
- Classe de associação
- Herança
- Enumerações
- Tipos primitivos (ItemPedidoPK)
- Entidades fracas (ElementCollection)
- Associações direcionadas
</div>
<br>

## 📝 Objetivos específicos
<br>

<h2>⚙️Fazer uma implementação padrão do seguinte modelo conceitual</h2>

<p align="center">
<img src="https://user-images.githubusercontent.com/79487813/176551906-04158d95-f374-43ad-8f9b-723415d8be2c.png"/></P>

<h2>⚙️ Criar a seguinte instância do modelo conceitual</h2>

<p align="center">
<img src="https://user-images.githubusercontent.com/79487813/176552164-89111164-cdf2-4efa-b4a0-1e919d1b724a.png"/></P>

<h2>- Gerar uma base de dados relacional automaticamente a partir do modelo conceitual, bem como povoar a base com a instância dada.</h2>

<h2>- Recuperar os dados e disponibilizá-los por meio de uma API Rest BÁSICA. Os seguintes end points devem ser disponibilizados:</h2>

<br>

|                End point             |   Dados   |     
| :--------------------------------: | :------------: | 
|     /categorias/{id}               |     Categoria e seus produtos     |        
|     /clientes/{id}                 | Cliente, seus telefones e seus endereços |   
|     /pedidos/{id}                  |     Pedido, seu cliente, seu pagamento e seus endereços     |          

