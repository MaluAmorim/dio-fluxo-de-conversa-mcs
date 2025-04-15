# dio-fluxo-de-conversa-mcs
Criando um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

## Criando um Agente

É possível criar **Agentes** pré-prontos, ou do zero (em branco), mas no geral eles sempre teram configurações padrões ja prontas as quais não podemos excluir caso não seja compativel com o nosso objetivo, mas é possível desabilita-las.

Ao criar um Agente é importante lembrar que há algumas boas praticas que devem ser seguidas, algumas delas são, atribuir ao Agente um nome direto e acolhedor, para que o usuário se sinta confortavel e para que o nome seja explicativo para quem usará o Agente e para todos que forem trabalhar no Agente (efetuar melhorias e correções).

Durante a criação é preciso escolher o idioma no qual o Agente irá trabalhar, contudo, é importante resaltar que no geral ele funciona melhor com o idioma inglês e ele é o mais recomendado para ser escolhido, mas não quer dizer que sei Agente tenha que se limitar a este idioma, ele é aconselhado para ser idioma primário mas após a criação o profissional pode escolher um idioma segundário a sua livre escolha.

Vale lembrar que é preciso fornecer uma descrição detalhada do propósito deste Agente pois tanto quem esta o criando como quem atuará nele futuramente conseguirá entender seu propósito, além disso é necessário inserir uma **Instrução** a qual determinará o que o Agente fará (informações que ele vai coletar, buscar e o que ele vai retornar ao usuário) e como agirá, é bom antes de criar esta instrução estudar um pouco sobre criação de prompts.

Podesse também fazer algumas configurações avançadas como escolher uma solução para o seu Agente.

## Criando um Tópico

Com o Agente criado é hora de criar os **Tópicos**. Nos tópicos é possível adicionar frases de gatilho que seriam fases ou palavras que quando o usuário digitar o tópico terá uma ação especifica. É importane resaltar que não é ideal um tópico ter muitas frases de gatilho atribuidas a ele, e se for este o caso é necessário criar um novo tópico.

É possível congurar para que ele possua uma resposta generativa, uma resposta mais fluida e desenvolvida utilizando IA. Nesta resposata generativa é preciso passar um input, que seria uma variavel que pode ser int, string e etc, além de pode atribuir uma
base de dados mas a qual não é necessáriamente obrigatória.

## Configurando uma menssagem de erro

Existem dois tipos, Conversational Boosting o qual é o melhor quando se esta utilizando IA e respostas Generativas. A outra opção é utilizar o FallBack.

É possível e recomendado criar mensagens, por exemplo, informando ao usuário que não doi possível encontrar as informações desejadas. Nas mensagens de erro podesse configurar de varias formas como colocando para que seja puxado o nome do usuário caso a pessoa queira, passando instruções como entrar em contato com a empresa ou alguém, disparar ações com o Power Automate e etc.

## Qualidade das Respostas

As respostas podem ser boa ou ruins, pouco elaboradas ou muito bem elaboradas, o que vai determinar isso é a forma que o desenvolvedor vai configurar o Agente.

Para fazer com que ele tenha uma melhor qualidade é habilitando na base de conhecimento as opções de utilizar a base de conhecimento geral do GPT4 assim como as bases de conhecimento próprias do desenvolvedor/empresa.

Nas respostas generativas é possível também criar prompts próprias para cada respostas passando caso necessário variaveis, nestes campos onde são adicionados os prompts são aceitos até 8 mil caracteres ou 500 itens.
