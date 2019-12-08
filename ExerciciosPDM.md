# Exercícios Programação de Dispositivos Móveis

## Ficha 1

**Q1.: O que significa IDE?**
+ *Integrated Developement Editor*.

**Q2.: e o acrónimo SDK, é abreviatura de quê?**
+ *Software Developement Kit*.

**Q3.: Qual das seguinte opções define corretamente SDK?**
+ É um conjunto de ferramentas de desenvolvimento de *software* que permite a criação de aplicações para um dado pacote, sistema de *software*, plataforma de *hardware*, computador, consola de jogos de vídeo, sistema operativo ou outra plataforma de desenvolvimento semelhante.

**Q4.: A *Programação de Dispositivos Móveis* é uma unidade curricular de que ano das licenciaturas em Engenharia Informática e em Informática Web?**
+ 3º ano.

**Q6.: O que é uma API?**
+ *Application Programming Interface*.

**Q7.: Qual a versão mais recente já em utilização do SO Android?**
+ Android 10.0

**Q8.: Por curiosidade, qual a versão mais recente, e atualmente em utilização, do iOS?**
+ iOS 13

**Q9.: Já agora, escreve-se iOS ou IOS?**
+ Escreve-se, obrigatorimente, iOS.

**Q10.: Existe algum SO chamado IOS(com o 'i' capitalizado)?**
+ Pois existe, que engraçado!

**Q11.: Que esquema era esse?**
+ A designação de algumas versões do SO é constituída por um ou mais substantivos e faz sempre lembrar um doce. A primeira letra da designação segue sempre o alfabeto.

**Q12.: Como se chama a versão mais recente, e em utilização, do SO Android?**
+ Android *Q*

**Q13.: Como se chama a versão anterior à versão 10 do SO Android?**
+ Android *Pie*

**Q14.: Qual o ano que foi lançado o Android pela primeira vez?**
+ 2008

**Q15.: Qual é o núcleo base, sobre o qual o SO Android foi construído?**
+ Linux

**Q16.: Por curiosidade, qual é o núcleo base do iOS?**
Unix

**Q17.: A versão do emulador coincide com a que definiu anteriormente, aquando da sua criação?**
+ --

**Q18.: Assumindo que escolheu o modo *Project*, onde está contido o código `JAVA` da aplicação?**
+ na pasta `app/src/main/java`.

**Q19.: O que significa `src`?**
+ Já estou mais calmo(a)... significa `source`!

**Q20.: Assumindo que escolheu o modo *Project*, em que pasta está contido o ficheiro `AndroidManifest.xml`?**
+ na pasta `app/src/main/`.

**Q21.: Quais das seguintes informações pode definir neste ficheiro?**
+ A versão da aplicação;
+ O nome da aplicação;
+ As permissões e acessos;
+ A API mínima;
+ A API alvo.

**Q22.: O que significa o X do acrónimo XML?**
+ e**X**tensible.

**Q23.: Qual o elemento raiz deste XML?**
+ `manifest`

**Q24.: Quantos elementos raiz podem existir num XML bem formado?**
+ Só 1.

**Q25.: Qual o elemento pai de `activity`?**
+ `application`

**Q26.: O elemento `activity` tem algum elemento filho?**
+ Sim, tem, nomeadamente `intent-filter`.

**Q27.: De que forma é que é descrito o nome do pacote(*package*) no manifesto da aplicação?**
+ Em forma de atributo.

**Q28.: De acordo com o `manifest`, por quantas atividades é constituiída a aplicação que acabou de criar?**
+ --

**Q29.: O que é que isso significa? Consegue dizer exatamente o tema ou o *path* do ícone no disco?**
+ Sim, consigo: --

## Ficha 2

**Q1.: Para efeitos de registo, em que pasta fica o projeto criado pelo comando anterior?**
+ --

**Q2.: O que é que esta instrução está a fazer exatamente?**
+ Está a definir a variável `ANDROID_HOME`.
  
**Q3.: Qual é a versão mais recente desta ferramenta de compilação?**
+ Versão 6+

**Q4.: Em que linguamgem é que o Gradle foi implementado**
+ JAVA
+ Groovy

**Q5.: É possível usá-la para automatizar o processo de compilação e construção para outras linguagens?**
+ Sim, é.

**Q6.: Na expressão "construir uma aplicação Android" (e grosso modo), o que é que lhe parece significar a palavra construir?**
+ Compilar o código fonte, juntar e enumerar recursos, e empacotar binários, recursos e descrições, para além de outros artefactos.

**Q7.: (*Just for the sake of it*) Qual o símbolo do gradle?**
+ Um elefante.

**Q8.: Em que diretoria é que está guardado o comando `gradle`?**
+ `bin`

**Q9.: O que é que contém a diretoria `lib`?**
+ Contém ficheiros `.jar` relativos à implementação do Gradle.
  
**Q10.: Em que pasta está a ferramenta `adb`?**
+ `platform-tools`

**Q11.: Em que pasta pode ser encontrada a ferramenta `sdkmanager`?**
+ `tools/bin` 

**Q12.: É possível encontrar uma *shell* para bases de dados SLQLite3 em alguma das diretorias antes enunciadas?**
+ ? 

**Q13.: Em que psta pode ser encontrada a ferramenta `avdmanager`?**
+ Na mesma que a ferramenta `sdkmanager`;
+ Na `tools/bin`.

**Q14.: Qual dos seguintes comandos é que lhe mostra quais as versões disponíveis no seu sistema?**
+ `$ ./avdmanager list targets`

**Q15.: Como traduziria o comando para Português?**
+ Listar alvos

**Q16.: Já agora, e revisitando o tema da secção *Preliminares*, acha que é possível colocar um dispositivo virtual a correr sem abrir o Android Studio ou o AVD *Manager*?**
+ Sim. Navegando até à diretoria onde estão as ferramentas do Android SDK e usando o comando `emulator`:
  + `$ cd android-sdk/emulator`
  + `$ ./emulator -avd NOME_DISPOSITIVO` 

**Q17.: Como se chama esse ficheiro?**
+ `build.gradle`

**Q18.: O que abrevia exatamente `apk`?**
+ *Android Application Package*.

**Q19.: Em que sub-diretoria é que o arquivo resultante foi colocado?**
+ `build`

**Q20.: Como se chama o arquivo resultante?**
+ `HelloWorld.apk`

**Q21.: Acha que é possível instalar esta aplicação de teste num dispositivo comum com SO Android?**
+ Sim, claro.

**Q22.: O que é um arquivo?**
+ É um ficheiro composto por outros ficheiros e metadados.

**Q23.: Quais das seguintes palavras fazem parte da expansão do acrónimo ADB?**
+ Android;
+ Debug;
+ Bridge.

**Q24.: Qual o resultado deste comando?**
+ É exibido um *log* do sistema virtualizado que se está a usar para testar a aplicação.
