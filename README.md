Sistema Estoque 

Este projeto consiste no desenvolvimento de um **Sistema de Controle de Estoque de Cosméticos**, criado como parte dos estudos acadêmicos com o objetivo de **aplicar conhecimentos adquiridos na faculdade** e **ampliar habilidades práticas em desenvolvimento de software**.

O sistema foi projetado para simular o ambiente de uma loja de cosméticos, oferecendo funcionalidades essenciais para o gerenciamento de produtos, como cadastro, movimentação de estoque e alertas de validade. A aplicação foi desenvolvida utilizando a linguagem **Java**, com interface gráfica em **Java Swing** e banco de dados **MySQL**.

---

## 🎯 Objetivos

- Aplicar conceitos de **programação orientada a objetos (POO)**
- Desenvolver interfaces gráficas com **Java Swing**
- Utilizar banco de dados relacional com **MySQL**
- Implementar **CRUDs completos**
- Aprender a usar **procedures**, **triggers** e **joins**
- Utilizar arquitetura **MVC (Model-View-Controller)**

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

| Ferramenta       | Descrição                                      |
|------------------|-----------------------------------------------|
| Java             | Linguagem principal utilizada no desenvolvimento do sistema |
| Java Swing       | Criação da interface gráfica desktop          |
| MySQL            | Banco de dados relacional usado para armazenar os dados |
| JDBC             | Biblioteca para conexão Java com o banco de dados |
| Apache NetBeans  | Ambiente de desenvolvimento integrado (IDE)   |
| MySQL Workbench  | Modelagem e gerenciamento do banco de dados   |
| Git              | Controle de versão do projeto (opcional)      |

---

## ⚙️ Funcionalidades Implementadas

- **3 CRUDs completos**:
  - **Produtos**: cadastro, edição, exclusão e visualização
  - **Categorias**: cadastro e associação com produtos
  - **Fornecedores**: cadastro, atualização e histórico de fornecimento

- **INNER JOIN** entre tabelas de produtos, categorias e fornecedores para exibir informações combinadas de forma eficiente.

- **TRIGGER** no banco de dados para registrar automaticamente movimentações de estoque (ex: quando um produto é atualizado, a ação é registrada em uma tabela de log).

- **PROCEDURE** implementada no MySQL para automatizar tarefas como geração de relatórios ou atualização em lote de status de validade dos produtos.

---

## 📋 Regras de Negócio

1. **Cadastro obrigatório completo:** Nenhum produto pode ser cadastrado com campos vazios obrigatórios.
2. **Estoque mínimo:** Alerta para reposição quando a quantidade atinge ou fica abaixo do mínimo.
3. **Produto vencido:** Produtos vencidos não podem ser movimentados para venda.
4. **Produto próximo da validade:** Aviso para produtos com menos de 30 dias para expirar.
5. **Movimentação válida:** Saída apenas se houver estoque suficiente.
6. **Evitar duplicidade:** Produtos com mesmos dados não podem ser duplicados.
7. **Bloqueio de exclusão com histórico:** Produtos com movimentações registradas não podem ser excluídos.

---

## 🧠 Aprendizados Técnicos

- Implementação prática de **CRUDs em Java com JDBC**
- Uso de **INNER JOIN** para consultas mais completas
- Criação de **TRIGGER** para automação de logs no banco
- Escrita e execução de **PROCEDURES** no MySQL
- Organização e manutenção de projetos com **MVC**
- Integração entre interface gráfica e banco de dados

---

## 👨‍🎓 Finalidade

Este projeto foi desenvolvido com **fins acadêmicos** para aprofundar os conhecimentos em desenvolvimento de sistemas, banco de dados e lógica de programação. Ele simula um ambiente real de gestão de estoque em uma loja de cosméticos, reforçando habilidades técnicas importantes para o mercado de trabalho.

---
