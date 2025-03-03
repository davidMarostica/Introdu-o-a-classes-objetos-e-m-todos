markdown
# ProjetoAluno

Este projeto é um exemplo simples de um sistema de gerenciamento de alunos. Ele foi desenvolvido em Java e contém duas classes principais: `Aluno` e `Principal`.

## Estrutura do Projeto

ProjetoAluno/
├── bin/
├── src/
│   ├── Aluno.java
│   └── Principal.java
├── .gitignore
├── build.xml
├── README.md
└── .project
Descrição das Classes
Aluno.java
A classe Aluno é responsável por armazenar as informações de um aluno. Ela contém os seguintes atributos:

nome: Nome do aluno

endereco: Endereço residencial do aluno

telefone: Telefone de contato do aluno

email: Endereço de e-mail do aluno

matricula: Matrícula do aluno

A classe Aluno também possui métodos getters e setters para acessar e modificar esses atributos, além de um método para exibir as informações do aluno.

Principal.java
A classe Principal contém o método main, que é o ponto de entrada do programa. Nela, instanciamos a classe Aluno e atribuímos valores aos seus atributos. Em seguida, exibimos as informações do aluno no console.

Executando o Projeto
Para executar o projeto no IntelliJ IDEA, siga as etapas abaixo:

Abra o IntelliJ IDEA e vá para File > New > Project from Existing Sources....

Selecione a pasta raiz do projeto (ProjetoAluno) e clique em OK.

Na próxima janela, selecione Create project from existing sources e clique em Next.

Confirme as configurações do projeto e clique em Next até chegar na tela final, então clique em Finish.

Execute a classe Principal clicando com o botão direito do mouse no arquivo Principal.java e selecionando Run 'Principal.main()'.

Requisitos
Java Development Kit (JDK) 8 ou superior

IntelliJ IDEA ou outra IDE Java de sua preferência

Licença
Este projeto está licenciado sob os termos da Licença MIT.
