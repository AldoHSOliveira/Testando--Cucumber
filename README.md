# Testes com Cucumber 

## Descrição do Projeto

Criando cenarios para evitar que o programa tenha erros, utilizando a ferramentar cucumber , juntamente com a IDE Eclipse.

### Pre-requisitos

Seram necessarios para a realização desse projeto.

#### Instalação

Preparando o ambiente de desenvolvimento:

- Acessar o site da Oracle  https://www.oracle.com/br/technical-resources/ para baixar o JAVA JDK8.
- Em seguida, acessar o site https://www.eclipse.org/downloads/packages/release/2020-03/r/eclipse-ide-java-developers para baixar Eclipse IDE

#### Executando os Primeiros Passos

1 - Após baixar e instalar as ferramentas a serem utilizada, Abra o Eclipse IDE e Vá em Help, selecione a opção Eclipse Marketplace. <br />
2 - Pesquise por Cucumber , e instale.<br />
3 - Selecione New  > Other , ou simplesmente pressione a tecla ctrl + n <br />
4 - Crie o Maven Project.


##### Testando o Cenário

1 - Pressione o botão direito no seu projeto, e escolha a opção Properties > Java Build Path > Libraries > Selecione a JRE System  > Remove. <br />
2 - Vá em add library >  JRE System > Apply and Close <br />
3 - Procure no canto esquerdo pelo arquivo POM.XML e copie o código de gerente de dependencia, embaixo da version:
<!-- https://mvnrepository.com/artifact/info.cukes/cucumber-java -->
<dependency>
    <groupId>info.cukes</groupId>
    <artifactId>cucumber-java</artifactId>
    <version>1.2.5</version>
</dependency>
<br />

4 - Selecione  com o botao direito em src/test/java > new > file, e cria um banco_bdd.feature. <br />
5 - escolha banco_bdd.feature > Run As > Run Configuration... e rode o código "Run" <br />
6 - Descreva o Cenario a ser executado. <br />
7 - Rode novamente. <br />
8 - Copie o Código gerado. <br />
9 - Selecione  com o botao direito em src/test/java > new > class > Crie Conta.java <br />
10 - Cole e import as bibliotecas.  <br />






