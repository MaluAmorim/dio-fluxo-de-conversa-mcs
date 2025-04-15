# dio-fluxo-de-conversa-mcs
Criando um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

## Criando um Agente

É possível criar **Agentes** pré-configurados ou do zero (em branco), mas, no geral, eles sempre terão configurações padrão já prontas, as quais não podemos excluir caso não sejam compatíveis com o nosso objetivo. No entanto, é possível desabilitá-las.

Ao criar um Agente, é importante lembrar que há algumas boas práticas que devem ser seguidas. Algumas delas são: atribuir ao Agente um nome direto e acolhedor, para que o usuário se sinta confortável, e para que o nome seja explicativo tanto para quem usará o Agente quanto para todos que forem trabalhar nele (efetuar melhorias e correções).

Durante a criação, é preciso escolher o idioma no qual o Agente irá trabalhar. Contudo, é importante ressaltar que, no geral, ele funciona melhor com o idioma inglês, sendo este o mais recomendado. Isso não significa que o Agente deva se limitar a este idioma; o inglês é aconselhado como idioma primário, mas, após a criação, o profissional pode escolher um idioma secundário livremente.

Vale lembrar que é preciso fornecer uma descrição detalhada do propósito deste Agente. Tanto quem o está criando quanto quem atuará nele futuramente conseguirá entender seu propósito. Além disso, é necessário inserir uma **Instrução**, que determinará o que o Agente fará (informações que ele vai coletar, buscar e o que ele vai retornar ao usuário) e como agirá. É recomendável, antes de criar esta instrução, estudar um pouco sobre criação de prompts.

Também é possível fazer algumas configurações avançadas, como escolher uma solução para o seu Agente.

## Criando um Tópico

Com o Agente criado, é hora de criar os **Tópicos**. Nos tópicos, é possível adicionar frases de gatilho, que seriam frases ou palavras que, quando digitadas pelo usuário, farão com que o tópico tenha uma ação específica. É importante ressaltar que não é ideal que um tópico tenha muitas frases de gatilho atribuídas a ele. Caso isso ocorra, é necessário criar um novo tópico.

É possível configurar para que ele possua uma resposta generativa, ou seja, uma resposta mais fluida e desenvolvida utilizando IA. Nesta resposta generativa, é preciso passar um input, que seria uma variável que pode ser `int`, `string`, etc., além de poder atribuir uma base de dados, a qual não é necessariamente obrigatória.

## Configurando uma Mensagem de Erro

Existem dois tipos: Conversational Boosting, que é o melhor quando se está utilizando IA e respostas generativas; e a outra opção é utilizar o FallBack.

É possível e recomendado criar mensagens, por exemplo, informando ao usuário que não foi possível encontrar as informações desejadas. Nas mensagens de erro, é possível configurá-las de várias formas, como incluindo o nome do usuário, caso se deseje; passando instruções, como entrar em contato com a empresa ou alguém; disparando ações com o Power Automate, etc.

## Qualidade das Respostas

As respostas podem ser boas ou ruins, pouco elaboradas ou muito bem elaboradas. O que vai determinar isso é a forma como o desenvolvedor configura o Agente.

Para garantir que ele tenha uma melhor qualidade, é preciso habilitar, na base de conhecimento, as opções de utilizar a base de conhecimento geral do GPT-4, assim como as bases de conhecimento próprias do desenvolvedor/empresa.

Nas respostas generativas, é possível também criar prompts próprios para cada resposta, passando, caso necessário, variáveis. Nestes campos onde os prompts são adicionados, são aceitos até 8 mil caracteres ou 500 itens.

Outra configuração disponível é escolher se a resposta generativa será mais voltada para criatividade ou precisão. Esta configuração pode ser feita tanto para uma resposta específica quanto de forma global.
