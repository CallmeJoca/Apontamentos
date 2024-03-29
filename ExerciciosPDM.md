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

---

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

---

## Ficha 3

**Q1.: Qual das seguintes combinações lista todos os AVDs disponíveis como o comando `$ emulator`?**
+ `$ emulator -list-avds`

**Q2.: Consegue aperceber-se da diferença entre uma *interface* de utilizador e uma *interface* entre duas componentes de um programa?**
+ Agora que penso nisso... sim, consigo.

**Q3.: Em que local pode o ficheiro mencionado ser encontrado?**
+ `src/main/res/layout`

**Q4.: Funcionou?**
+ --

**Q5.: Qual das seguintes deverá usar?**
+ `app:layout_constraintBottom_toBottomOf`
+ `app:layout_constraintLeft_toLeftOf`
+ `app:layout_constraintRight_toRightOf`
+ `app:layout_constraintTop_toBottomOf`

**Q6.: Não pergunta ao Prof. pelo significado do `@` e do `+` na definição da propriedade `android:id`?**
+ Não, porque já sei tudo.
+ `@`: declaração da atual localização no ficheiro
+ `+`: junção da autal localização com o elemento id

**Q7.: Estes factos vão de encontro ao que foi referido em relação à arquitetura de software MVC?**
+ ? 

**Q8.: Já se ssabe que estará dentro da diretoria `src`, mas qual o caminho completo do ficheiro a partir da raiz da aplicação?**
+ `app/src/main/java/pmd/di/ubi/pt/acalculator/...`

**Q9.: Consegue encontrar a linha de código que *carrega o layout* da aplicação a partir do ficheiro?**
+ Sim, é a linha com a instrução:
```java
    setContentView(R.layout.activity_main);
```

**Q10.: Por que é que cada vez que declara a função `findViewById(...)` necessita de colocar o nome de uma classe de uma objeto entre parêntesis antes?**
+ O propótipo da função mencionada obriga a que seja chamada desta forma.

**Q11.: Agora sem olhar(!), consegue encontrar este ficheiro?**
+ Sim, em ...

**Q12.: Qual o efeito desta alteração na interface de utilizador da aplicação?**
+ O botão passa a ocupar o máximo do ecrã na horizontal.

**Q13.: Que nome se dá à classe criada pela instrução `new View.onClickListener()`?**
+ Classe anónima.

**Q14.: Já agora, só por curiosidade, o que significa URL?**
+ Uniform Resource Locator

---

## Ficha 4

**Q1.: Só para relembrar: qual é o pacote que deve importar para usar objetos interativos como o botão?**
+ `android.widget.*`

**Q2.: Por curiosidade, qual é a classe pai(ou super classe) da classe `Button`?**
+ `android.widget.Button`

**Q3.: Já agora como se chama o cunhado do `Button`**
+ --

**Q4.: A *interface* de utilizador que desenhou em cima é semelhante à que realmente apareceu?**
+ --

**Q5.: Experimentou os botões?**
+ Experimentei, e não faziam nada(como não podia deixar de ser).

**Q6.: Onde está implementada esta classe? Por outras palavras, onde está o ficheiro `R.java`?**
+ Em `build/generated/source/buildConfig`

**Q7.: A que conceito se refere a instrução `R.id`?**
+ A um atributo estático.

**Q8.: Em que situação é conveniente editar este ficheiro?**
+ Sempre que se quer adicionar um identificador novo a um *widget*.

**Q9.: Afinal, o que são os IDs que utiliza no código para referenciar alguns recursos de uma aplicação Android?**
+ São *Strings*.

**Q10.: De uma maneira geral, esta abordagem parece-lhe mais simples que as que já foram estudadas até aqui?**
+ De facto, parece-me mais simples(legível).

**Q11.: Este parâmetro é mesmo necessário?**
+ É sim. Sem ele, o *callback* não funciona.

**Q12.: Por curiosidade, em que versão da *Application Programming Interface*(API) Android é que os botões foram disponibilizados?**
+ Na API 1.

**Q13.: Como se chama a classe que lhe permite fazer isso?**
+ `Log`

**Q14.: Qual o pacote que terá de importar para poder usar a classe mencionada antes?**
+ `android.app.Activity`

**Q15.: Como é que se aplicam filtros no `logcat` via linha de comandos?**
+ Combinando a opção `-f` com `ALC`

**Q16.: Consegue simular um fluxo normal(completo) de execução da aplicação no seu `logcat`?**
+ Claro que consigo.

**Q17.: Consegue simular o fluxo definido a seguir no seu `logcat`?**
+ --

**Q18.: Por curiosidade, o que é que acontece quando muda a oirentação(e.g., de vertical (*portrait*) para horizontal (*landscape*)) do dispositivo, em termos do ciclo de vida de uma atividade?**
+ O facto é que, em termos de ciclo de vida, a atividade parece não ter sufrido qualquer alteração no processo.

---