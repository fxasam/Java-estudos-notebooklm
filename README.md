# 📚 Caderno Temático - Programação Orientada a Objetos em Java com NotebookLM

> Projeto desenvolvido como parte do desafio da DIO, utilizando o Google NotebookLM como ferramenta de aprendizagem ativa para organizar conhecimentos, sintetizar conteúdos e apoiar os estudos sobre Programação Orientada a Objetos em Java.

---

# 📑 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Objetivos](#-objetivos)
- [Curadoria de Fontes](#-curadoria-de-fontes)
- [Utilização do NotebookLM](#-utilização-do-notebooklm)
- [Engenharia de Prompts](#-engenharia-de-prompts)
- [Dificuldades Encontradas](#-dificuldades-encontradas)
- [Miniguia de Estudos](#-miniguia-de-estudos)
- [Glossário](#-glossário)
- [Prompts Reutilizáveis](#-prompts-reutilizáveis)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Autor](#-autor)

---

# 📖 Sobre o Projeto

Este projeto foi desenvolvido utilizando o **NotebookLM** para apoiar os estudos da disciplina de **Programação Orientada a Objetos em Java**.

Foram utilizados materiais acadêmicos da graduação em **Análise e Desenvolvimento de Sistemas**, disponibilizados em formato PDF e adicionados ao NotebookLM para gerar resumos, responder perguntas, organizar conceitos e criar um material de revisão.

O objetivo é demonstrar como a Inteligência Artificial pode ser utilizada como uma ferramenta de aprendizagem ativa, auxiliando na organização do conhecimento e na revisão de conteúdos técnicos.

---

# 🎯 Objetivos

- Estudar os fundamentos da Programação Orientada a Objetos em Java.
- Consolidar os principais conceitos apresentados na disciplina.
- Utilizar o NotebookLM como ferramenta de apoio ao aprendizado.
- Produzir um material organizado para futuras revisões.
- Documentar todo o processo em um repositório no GitHub.

---

# 📂 Curadoria de Fontes

Foram utilizados seis materiais acadêmicos em PDF disponibilizados pela instituição de ensino e adicionados ao NotebookLM.

## Fontes utilizadas

1. Introdução à Programação Orientada a Objetos em Java
2. Herança em Java
3. Polimorfismo em Java
4. Implementação de Tratamento de Exceções em Java
5. Programação Paralela em Java: Threads
6. Integração com Banco de Dados em Java

Esses documentos serviram como base para a geração de resumos, esclarecimento de dúvidas e elaboração do material de estudo.

---

# 🤖 Utilização do NotebookLM

Após o envio dos arquivos PDF ao NotebookLM, foram realizados diversos testes para explorar os conteúdos utilizando Inteligência Artificial.

As principais atividades realizadas foram:

- Geração de resumos estruturados;
- Explicação de conceitos;
- Comparação entre pilares da POO;
- Criação de glossário;
- Geração de perguntas para revisão;
- Produção de relatório técnico.

> **Imagem do NotebookLM**

Adicione uma captura de tela na pasta `imagens` e altere o nome para `notebooklm.png`.

```text
imagens/notebooklm.png
```

Depois utilize:

```markdown
![NotebookLM](imagens/notebooklm.png)
```

---

# 💬 Engenharia de Prompts

Durante o projeto foram testadas diferentes formas de interação com o NotebookLM.

## Prompt 1

**Objetivo:** Criar um resumo dos conteúdos.

```
Crie um resumo estruturado dos seis temas presentes nas fontes adicionadas.
```

**Resultado**

Foi gerado um resumo dividido por assunto, facilitando a compreensão dos conteúdos.

---

## Prompt 2

**Objetivo:** Comparar conceitos da POO.

```
Explique as diferenças entre encapsulamento, abstração, herança e polimorfismo utilizando exemplos simples em Java.
```

**Resultado**

A IA apresentou exemplos claros e diferenciou corretamente os pilares da Programação Orientada a Objetos.

---

## Prompt 3

**Objetivo:** Criar um glossário.

```
Crie um glossário contendo os principais conceitos encontrados nas fontes.
```

**Resultado**

Foi produzido um glossário organizado contendo os principais termos estudados.

---

## Prompt 4

**Objetivo:** Revisão do conteúdo.

```
Elabore perguntas para revisar todo o conteúdo estudado.
```

**Resultado**

Foram geradas questões em diferentes níveis de dificuldade para auxiliar na fixação do conteúdo.

---

# ⚠ Dificuldades Encontradas

Durante os testes foi observado que prompts muito genéricos geravam respostas pouco organizadas.

Para melhorar a qualidade das respostas foram adotadas as seguintes estratégias:

- solicitar que fossem utilizadas apenas as fontes adicionadas;
- dividir os pedidos por tema;
- especificar o formato esperado da resposta;
- solicitar exemplos práticos em Java.

Essas alterações tornaram os resultados mais objetivos e próximos do conteúdo estudado na disciplina.

---

# 📚 Miniguia de Estudos

## Introdução à Programação Orientada a Objetos

A Programação Orientada a Objetos organiza o desenvolvimento de software por meio de objetos que representam entidades do mundo real.

Principais conceitos:

- Classe
- Objeto
- Atributos
- Métodos
- Encapsulamento
- Abstração

---

## Herança

Permite criar novas classes reutilizando características de outras classes.

Benefícios:

- reutilização de código;
- organização;
- facilidade de manutenção.

---

## Polimorfismo

Permite que um mesmo método apresente diferentes comportamentos dependendo do objeto utilizado.

---

## Tratamento de Exceções

Responsável por tratar erros durante a execução da aplicação.

Principais comandos:

- try
- catch
- finally
- throw
- throws

---

## Threads

Permitem executar múltiplas tarefas simultaneamente, melhorando o desempenho da aplicação.

---

## Integração com Banco de Dados

A integração entre aplicações Java e bancos de dados é realizada principalmente por meio da API JDBC, permitindo executar comandos SQL e manipular informações persistidas.

---

# 📖 Glossário

| Conceito | Definição |
|----------|-----------|
| Classe | Modelo utilizado para criar objetos |
| Objeto | Instância de uma classe |
| Atributo | Característica de um objeto |
| Método | Comportamento de um objeto |
| Encapsulamento | Proteção dos dados internos |
| Abstração | Representação das características essenciais |
| Herança | Reutilização de código entre classes |
| Polimorfismo | Um método com diferentes comportamentos |
| Exceção | Erro tratado pela aplicação |
| Thread | Fluxo independente de execução |
| JDBC | API utilizada para comunicação com banco de dados |

---

# 🚀 Prompts Reutilizáveis

- Crie um resumo dos temas estudados.
- Explique determinado conceito utilizando apenas as fontes adicionadas.
- Gere exemplos práticos em Java.
- Produza um glossário com os principais termos.
- Elabore perguntas para revisão.
- Crie um mapa mental do conteúdo.

---

# 🛠 Tecnologias Utilizadas

- Java
- NotebookLM
- GitHub
- Markdown

---

# 📄 Arquivos do Projeto

```
📁 java-estudos-notebooklm
│
├── README.md
├── relatorio-tecnico.pdf
├── imagens
│   └── notebooklm.png
└── prompts
    └── prompts-utilizados.md
```

---

# 👨‍💻 Autor

**Samuel da Silva de Souza**

Aluno de Análise e Desenvolvimento de Sistemas – Estácio

Projeto desenvolvido para o desafio prático da **DIO (Digital Innovation One)** utilizando o **NotebookLM** como ferramenta de apoio aos estudos.
## 🔗 Acesso ao Caderno no NotebookLM

O caderno temático desenvolvido para este projeto pode ser acessado pelo link abaixo:

**NotebookLM:**  
https://notebook.google.com/notebook/3cb0064b-5801-45b9-9c10-3ca6f181243f


