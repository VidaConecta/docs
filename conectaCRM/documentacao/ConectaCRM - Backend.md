# ConectaCRM - Backend

<div align="center">
   <img src="https://i.imgur.com/kA160aq.png" title="source: imgur.com" />
</div>




## 1. Descrição

​    


O **ConectaCRM** é um sistema de CRM desenvolvido para auxiliar no gerenciamento de oportunidades de venda. A aplicação permite cadastrar, acompanhar e atualizar negociações de forma prática e centralizada, ajudando no controle do fluxo comercial e na organização das informações do cliente.

O projeto foi desenvolvido com **Java**, **Spring**, **Hibernate/JPA**, **MySQL** e executado em **Tomcat**, formando uma base robusta para persistência de dados, organização da camada de acesso ao banco e construção de uma API backend.



------

## 2. Sobre esta API

A  API do ConectaCRM foi construída para gerenciar a entidade **Oportunidade**, permitindo registrar informações relevantes sobre negociações comerciais, como título, status, nome do cliente, descrição e valor.

Por meio dela, é possível centralizar os dados de venda em um banco relacional e realizar operações de cadastro, consulta e atualização com apoio do ecossistema Spring e da integração ORM com JPA/Hibernate.[3][4]

### 2.1. Principais Funcionalidades

1. Cadastrar oportunidades de venda.
2. Consultar oportunidades registradas.
3. Atualizar negociações em andamento.
4. Identificar o status da oportunidade como aberta, fechada ou rejeitada.
5. Organizar informações do cliente e do valor negociado.

------

## 3. Diagrama de Classes

Adicione abaixo a imagem do Diagrama de Classes, caso o grupo já tenha finalizado esse material.

<div align="center">
    <img src="https://i.imgur.com/5rdOrR7.jpeg" title="Diagrama de Classes" width="50%"/>
</div>



------

## 4. Diagrama Entidade-Relacionamento (DER)



<div align="center">
    <img src="https://i.imgur.com/xemAkDJ.png" title="Diagrama Entidade-Relacionamento" width="50%" />
</div>



------

## 5. Tecnologias utilizadas

| Item                          | Descrição     |
| ----------------------------- | ------------- |
| **Servidor**                  | Tomcat        |
| **Linguagem de programação**  | Java          |
| **Framework**                 | Spring        |
| **ORM**                       | Hibernate/JPA |
| **Banco de dados Relacional** | MySQL         |



------

## 6. Estrutura da Entidade

### Classe: `Oportunidade`

| Atributo      | Tipo         | Descrição                                                    |
| ------------- | ------------ | ------------------------------------------------------------ |
| `id`          | `Long`       | Identificador único de cada oportunidade cadastrada no sistema. |
| `titulo`      | `String`     | Armazena o título da oportunidade, facilitando sua identificação rápida. |
| `status`      | `Integer`    | Indica a situação da oportunidade, como aberta, fechada ou rejeitada. |
| `nomeCliente` | `String`     | Armazena o nome do cliente associado à oportunidade.         |
| `descricao`   | `String`     | Descreve a oportunidade, facilitando o entendimento da negociação. |
| `valor`       | `BigDecimal` | Armazena o valor financeiro da oportunidade.                 |



------

## 7. Configuração e Execução

1. Clone o repositório.
2. Abra o projeto na IDE de sua preferência.
3. Configure o banco de dados MySQL.
4. Verifique as configurações de conexão da aplicação.
5. Execute o projeto no servidor Tomcat.

### Exemplo de execução

```bash
git clone https://github.com/VidaConecta/ConectaCRM
```

------

## 8. Status do Projeto

🚧 Projeto em desenvolvimento. Algumas informações ainda estão sendo finalizadas e este README poderá ser atualizado conforme a evolução da aplicação.

