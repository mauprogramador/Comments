Pegar Projeto do GitHub:
- no vscode: F1 e digite Git:clone
- digite a URl: https://github.com/jrcampos82/projeto-bliblioteca-jsf.git

Baixar Maven:
https://maven.apache.org/download.cgi
Link: Binary zip archive: apache-maven-3.8.3-bin.zip
 
- descompactar a pasta
- copiar caminho (ex: 'C:\Users\Usuario\Downloads\apache-maven-3.8.3-bin\apache-maven-3.8.3\bin')

VS Code:
- Guia File -> Preferences -> Settings -> Maven: Executable: PATH
- colar caminho + '\mvn.cmd'

JDK 11 e 16
https://www.oracle.com/java/technologies/downloads/


====[ Aula 05/11/2021 ]==================================================================================->
Prime Faces:
https://www.primefaces.org/gettingstarted/
Copiar código de Test Run e Colar em um arquivo .xhtml

https://www.primefaces.org/ -> PRIMEFACES -> Demo

Buil do projeto:
- localizar o projeto em Maven;
- btn direito: package;
- irá criar automaticamente a build;
- irá criar uma pasta chamada "Target";
- dentro haverá um arquivo .war;
- btn direito: Run on Server;,
- no navegador: http://localhost:8080/biblioteca
 
