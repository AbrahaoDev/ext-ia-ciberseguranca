# EX071 — Edição 2026.2 — Primeira Entrega (E1)

## Instruções Gerais

O objetivo geral do projeto da disciplina é desenvolver, de forma incremental, um projeto de extensão relacionado a **Literacia Digital, Inteligência Artificial e/ou Cibersegurança**, considerando problemas, necessidades e públicos reais.

Nesta primeira entrega, a missão do grupo será:

- identificar e contextualizar o problema de extensão a ser abordado;
- caracterizar o público de interesse e suas necessidades;
- apresentar uma proposta inicial para o projeto;
- organizar o espaço de trabalho do projeto no GitHub.

A proposta apresentada em E1 é um **ponto de partida**. Espera-se que ela seja revista e aperfeiçoada ao longo da disciplina a partir das discussões em sala, do contato com o público e/ou parceiros envolvidos e do próprio desenvolvimento do projeto.



## O que deve ser entregue na E1

A E1 consiste na **documentação da proposta inicial do projeto no arquivo `README.md` do grupo**.

O grupo deverá criar sua pasta de projeto em:

`editions/2026.2/projects/<nome-do-projeto>/`

e, dentro dela, criar o arquivo:

`README.md`

> [!IMPORTANT]
> **O `README.md` da E1 deverá obrigatoriamente seguir a estrutura do [E1 Template](../templates/E1_template.md).**
>
> Copie o conteúdo do template para o `README.md` do projeto e substitua as orientações e campos indicados pelas informações específicas do seu projeto.
>
> **Não crie uma estrutura alternativa para a E1 e não remova as seções solicitadas no template.**

O template orienta a descrição da **contextualização do projeto, problema de extensão, público de interesse, necessidades identificadas e proposta inicial**.

O `README.md` será o documento principal do projeto e **continuará sendo atualizado nas próximas entregas**. A ideia não é criar um novo documento a cada entrega, mas registrar progressivamente a evolução do projeto ao longo da disciplina.


## Organização do grupo no GitHub

O repositório oficial da disciplina para desenvolvimento e entrega dos projetos é:

**[teaching-FEEC/ext-ia-ciberseguranca](https://github.com/teaching-FEEC/ext-ia-ciberseguranca)**

> [!IMPORTANT]
> O **fork deverá ser criado a partir do repositório acima**.
>
> **Não crie um novo repositório independente para o projeto.**

Para organizar o trabalho do grupo:

1. Ao menos um(a) integrante do grupo deverá possuir uma conta no GitHub e se responsabilizar pela manutenção do fork e pelas atualizações das informações do projeto.

2. Esse(a) integrante deverá fazer um **fork** do repositório oficial:

   **[https://github.com/teaching-FEEC/ext-ia-ciberseguranca](https://github.com/teaching-FEEC/ext-ia-ciberseguranca)**

3. O responsável pelo fork deverá adicionar os demais integrantes do grupo como colaboradores.

4. No fork, o grupo deverá criar **uma única pasta para seu projeto** dentro de:

   `editions/2026.2/projects/`

   O resultado será:

   `editions/2026.2/projects/<nome-do-projeto>/`

5. O nome da pasta deverá ser um identificador **curto, mnemônico e estável** para o projeto. Ele não precisa reproduzir o título completo da atividade.

   Utilize preferencialmente:

   - letras minúsculas;
   - palavras separadas por hífen (`-`);
   - nenhum espaço, acento ou caractere especial;
   - um nome suficientemente curto para ser utilizado como identificador do projeto.

   O título completo e a descrição do projeto deverão constar no `README.md` do grupo, e não no nome da pasta.

6. Todo o material produzido pelo grupo ao longo da disciplina deverá ser organizado dentro dessa pasta.

7. Os integrantes deverão realizar commits ao longo do desenvolvimento do trabalho.

> [!WARNING]
> Durante toda a disciplina, o grupo deverá alterar **somente sua própria pasta de projeto**:
>
> `editions/2026.2/projects/<nome-do-projeto>/`
>
> Os demais arquivos e diretórios do repositório pertencem à estrutura oficial da disciplina e **não devem ser modificados**.



## Submissão da E1

> [!WARNING]
> **Antes de abrir o Pull Request, verifique cuidadosamente as alterações realizadas no fork.**
>
> O grupo deverá modificar **exclusivamente o conteúdo localizado dentro da sua própria pasta de projeto**:
>
> `editions/2026.2/projects/<nome-do-projeto>/`
>
> **Não altere, mova ou remova nenhum arquivo ou diretório fora dessa pasta.**
>
> Alterações realizadas fora da pasta do projeto poderão gerar conflitos com o repositório da disciplina e **impedir o merge do Pull Request**.
>
> Pull Requests contendo alterações externas à pasta do projeto não serão aceitos enquanto essas alterações não forem removidas.

Quando o material estiver pronto para submissão:

- certifique-se de que todos os arquivos relacionados à E1 estejam atualizados no fork do grupo;
- certifique-se de que o Pull Request não contenha nenhuma alteração fora de `editions/2026.2/projects/<nome-do-projeto>/`;
- crie uma tag/release identificando a versão correspondente à E1;
- abra um **Pull Request do fork do grupo para o repositório oficial da disciplina**:

  **[teaching-FEEC/ext-ia-ciberseguranca](https://github.com/teaching-FEEC/ext-ia-ciberseguranca)**

- o Pull Request deverá ter como destino a branch `main` do repositório oficial e ser aberto até a data estabelecida para a entrega.

A identificação da versão da E1 deverá seguir o padrão:

`2026.2_E1`

> [!IMPORTANT]
> O **Pull Request** representa a submissão da entrega para o repositório da disciplina, enquanto a **tag/release** identifica, no fork do grupo, a versão do projeto correspondente à E1.


## Recursos de Apoio

### Markdown

Não é necessário conhecimento avançado de Markdown para realizar as entregas.

Para dúvidas sobre escrita e formatação, consulte:

- [GitHub Docs — Sintaxe básica de escrita e formatação](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GitHub Docs — Introdução à escrita e formatação no GitHub](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)

Recomenda-se utilizar um editor que permita visualizar o resultado do Markdown durante a edição.

O Visual Studio Code possui suporte nativo para edição e visualização de arquivos Markdown, não sendo necessária a instalação de extensões para essa finalidade.

### Git e GitHub

Git e GitHub serão utilizados como ferramentas de organização, colaboração e versionamento do projeto.

**Aprender Git não é um objetivo da disciplina.** Utilize o workflow indicado nestas instruções e consulte a documentação apenas quando necessário.

Referências úteis:

- [GitHub Docs — Trabalhar com forks](https://docs.github.com/pt/pull-requests/how-tos/work-with-forks)
- [GitHub Docs — Sincronizar um fork](https://docs.github.com/pt/pull-requests/how-tos/work-with-forks/syncing-a-fork)
- [GitHub Docs — Pull Requests](https://docs.github.com/pt/pull-requests)