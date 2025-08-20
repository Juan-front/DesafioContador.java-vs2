# DesafioContador.java-vs2
Uma versão atualizada

🛠 Estrutura do Projeto

DesfioContador vs2/
 ├── .vscode/
 │    └── launch.json
 ├── Contador.java
 └── ParametrosInvalidosException.java

Contador.java → Classe principal que contém a lógica do programa.

ParametrosInvalidosException.java → Classe que representa uma exceção personalizada.

launch.json → Configuração do VS Code para executar o projeto com um clique.



▶ Como Executar

1️⃣ Pelo terminal

1. Abra o terminal na pasta do projeto:

cd "C:\Users\ACER\Desktop\DesfioContador vs2"


2. Compile os arquivos:

javac Contador.java ParametrosInvalidosException.java


3. Execute o programa:

java Contador


2️⃣ Pelo VS Code (com botão ▶)

1. Crie a pasta .vscode dentro do projeto.


2. Crie o arquivo launch.json com o seguinte conteúdo:

{
    "version": "0.2.0",
    "configurations": [
        {
            "type": "java",
            "name": "Executar Contador",
            "request": "launch",
            "mainClass": "Contador"
        }
    ]
}


3. No canto superior direito do VS Code, clique no botão verde ▶ Executar.
O programa será compilado e executado automaticamente.




💻 Exemplo de Execução

Caso válido

Entrada:

Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30

Saída:

Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18

Caso inválido

Entrada:

Digite o primeiro parâmetro
30
Digite o segundo parâmetro
12

Saída:

O segundo parâmetro deve ser maior que o primeiro


---

🔄 Evolução do Projeto

Versão 1 (básica):

Execução apenas pelo terminal com javac e java.

Código com exceção personalizada (ParametrosInvalidosException) funcionando corretamente.

Atende ao desafio, mas exige compilação manual.


Versão 2 (melhorada):

Adicionada pasta .vscode com arquivo launch.json.

Agora o projeto pode ser executado com um clique no botão ▶ do VS Code.

Mais praticidade e rapidez para testes e execução.

Estrutura pronta para ser usada em IDE moderna, facilitando manutenção e evolução.




---

✅ Tecnologias Utilizadas

Java 17+

VS Code

Extensão Extension Pack for Java
