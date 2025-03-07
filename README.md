# Projeto: Modelagem de Dados para Biblioteca Universitária

## 📚 Descrição
Este projeto foi desenvolvido durante o **1º semestre** do curso de **Cibersegurança - UNOPAR**, na disciplina de **Modelagem de Dados**. 

O objetivo foi criar um **Diagrama Entidade-Relacionamento (DER)** para representar o funcionamento de uma biblioteca universitária, utilizando o **MySQL Workbench** como ferramenta principal.

As entidades criadas incluem:
- **ALUNO**: Representa os alunos cadastrados na biblioteca.
- **LIVROS**: Representa os livros disponíveis para empréstimo.
- **EMPRESTIMOS_LIVROS**: Registra os livros emprestados e suas associações.
- **COLABORADORES**: Representa os funcionários responsáveis pelos empréstimos.

---

## 🛠️ Ferramentas Utilizadas
- **MySQL Workbench** (modelagem e geração do DER)

---

## 📂 Estrutura do Projeto
- Relatório completo (PDF) [Projeto-Modelagem de Dados-Unopar-1ºSemestre.pdf](https://github.com/user-attachments/files/19130893/Projeto-Modelagem.de.Dados-Unopar-1.Semestre.pdf)

- Capturas do Diagrama Entidade-Relacionamento (DER)

![1](https://github.com/user-attachments/assets/02033f83-fbb6-4d3c-8b40-69e0945c875e)

![2](https://github.com/user-attachments/assets/b1441d47-7b29-454f-a68b-86abc18ecea5)

---

## 🔎 Aprendizados e Competências Desenvolvidas
- Modelagem Conceitual de Banco de Dados
- Definição de Entidades e Relacionamentos
- Criação de Chaves Primárias e Estrangeiras
- Documentação de Modelos de Dados
- Uso da Interface Gráfica do MySQL Workbench

---

## 📊 Entidades Criadas
| Entidade         | Atributos Principais                            |
|------------------|--------------------------------------------------|
| **ALUNO**        | RA (PK), Nome, Curso, Telefone                  |
| **LIVROS**       | ISBN (PK), Título, Autor, Gênero                 |
| **EMPRESTIMOS_LIVROS** | ID_EMPRESTIMO (PK), Data_Empréstimo, RA (FK), ISBN (FK) |
| **COLABORADORES** | CPF (PK), Nome, Cargo                           |

---

## 📅 Semestre
1º Semestre - Curso de Cibersegurança - UNOPAR

---

## 👨‍🎓 Autor
Silvio Rodrigues Gouvêa

---

## 🔗 Referências
- [Documentação MySQL Workbench](https://dev.mysql.com/doc/workbench/en/)
- [Conceitos de Modelagem de Dados](https://www.lucidchart.com/pages/pt/guia-completo-de-modelagem-de-dados)

