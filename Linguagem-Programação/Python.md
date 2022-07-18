###### ![](C:\Users\Silvana\Downloads\Python_logo_and_wordmark.svg.png)

Python é uma linguagem de programação de alto nível, interpretada de script,
imperativa, orientada a objestos, funcional, de tipagem dinâmica e forte, foi 
lançada por **GUIDO VAN ROSSUM** em **1991.**
Atualmente possui um modelo de desenvolvimento comunitário, aberto e gerenciado
pela organização sem fins lucrativos **Python Software Foundation.**
Apesar de várias partes da linguagem possuirem padrões e especificações formais
a linguagem como um todo não é totalmente especificada. O padrão na pratica é a 
implementação CPython.
A linguagem foi projetada com a filosofia de enfatizar a importância do esforço
do programador sobre o esforço computacional. Prioriza a legibilidade do código
sobre a velocidade ou expressividade, combina um sintaxe concisa e clara com os 
recursos poderosos de sua biblioteca padrão e por módulos e frameworks 
desenvolvidos por terceiros.

# ***História***

Guido van Rossum, São Francisco, Califórnia
O Python foi concebido no final de 1989 por Guido van Rossum no Instituto
de Pesquisa Nacional para Matemática e Ciência da Computação (CWI), nos Países 
Baixos, como um sucessor da ABC capaz de tratar exceções e prover interface com
o sistema operacional Amoeba através de scripts. Também da CWI, a linguagem
ABC era mais produtiva que C, ainda que com o custo do desempenho em tempo de 
execução. Mas ela não possuía funcionalidades importantes para a interação com 
o sistema operacional, uma necessidade do grupo. Um dos focos primordiais de 
Python era aumentar a produtividade do programador.
Em 1991, Guido publicou o código (nomeado versão 0.9.0) no grupo de discussão
alt.sources. Nessa versão já estavam presentes classes com herança, tratamento
de exceções, funções e os tipos de dado nativos list, dict, str, e assim por diante. 
Também estava presente nessa versão um sistema de módulos emprestado do Modula-3. 
O modelo de exceções também lembrava muito o do Modula-3, com a adição da opção 
else clause. Em 1994 foi formado o principal fórum de discussão do Python, 
comp.lang.python, um marco para o crescimento da base de usuários da linguagem.
A versão 1.0 foi lançada em janeiro de 1994. Novas funcionalidades incluíam 
ferramentas para programação funcional como lambda, map, filter e reduce. A 
última versão enquanto Guido estava na CWI foi o Python 1.2. Em 1995, ele 
continuou o trabalho no CNRI em Reston, Estados Unidos, de onde lançou diversas
versões. Na versão 1.4 a linguagem ganhou parâmetros nomeados (a capacidade de 
passar parâmetro pelo nome e não pela posição na lista de parâmetros) e suporte 
nativo a números complexos, assim como uma forma de encapsulamento.

<img title="" src="file:///C:/Users/Silvana/Downloads/250px-He_invented_Python.jpg" alt="" data-align="center">

# **Sintaxe**

**Sintaxe** (pronúncia no [AFI](https://pt.wikipedia.org/wiki/Alfabeto_fon%C3%A9tico_internacional "Alfabeto fonético internacional"): [[sí'tasɨ]](https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:Alfabeto_fon%C3%A9tico_internacional "Wikipédia:Alfabeto fonético internacional")) (do [grego clássico](https://pt.wikipedia.org/wiki/Grego_cl%C3%A1ssico "Grego clássico") σύνταξις "estrutura", de σύν, [transl.](https://pt.wikipedia.org/wiki/Translitera%C3%A7%C3%A3o "Transliteração") _syn_, "mais", e τάξις, transl. _táxis_, "classe") é o estudo das regras que regem a construção de [frases](https://pt.wikipedia.org/wiki/Frase "Frase") nas [línguas naturais](https://pt.wikipedia.org/wiki/L%C3%ADnguas_naturais "Línguas naturais"). (https://pt.wikipedia.org/wiki/Sintaxe#cite_note-1) 

A sintaxe é a parte da [gramática](https://pt.wikipedia.org/wiki/Gram%C3%A1tica "Gramática") que estuda a disposição das [palavras](https://pt.wikipedia.org/wiki/Palavra "Palavra") na [frase](https://pt.wikipedia.org/wiki/Frase "Frase") e das frases no [discurso](https://pt.wikipedia.org/wiki/Discurso "Discurso"), incluindo a sua relação lógica, entre as múltiplas combinações possíveis para transmitir um significado completo e compreensível. À inobservância das regras de sintaxe chama-se [solecismo](https://pt.wikipedia.org/wiki/Solecismo "Solecismo").(https://pt.wikipedia.org/wiki/Sintaxe#cite_note-2)

Na [linguística](https://pt.wikipedia.org/wiki/Lingu%C3%ADstica "Linguística"), a sintaxe é o ramo que estuda os processos generativos ou combinatórios das frases das línguas naturais, tendo em vista especificar a sua estrutura interna e funcionamento. O termo "sintaxe" se refere o estudo das regras que regem o comportamento de sistemas matemáticos, como a [lógica](https://pt.wikipedia.org/wiki/Sintaxe_(l%C3%B3gica) "Sintaxe (lógica)") e as [linguagens de programação de computadores](https://pt.wikipedia.org/wiki/Linguagem_de_programa%C3%A7%C3%A3o "Linguagem de programação").

A sintaxe é importante pois a unidade falada é a [oração](https://pt.wikipedia.org/wiki/Ora%C3%A7%C3%A3o_(gram%C3%A1tica) "Oração (gramática)"), não a palavra ou o som. Em termos práticos, o falante fala e o ouvinte ouve orações. Salvo o caso quando uma única palavra é portadora de sentido completo. (https://pt.wikipedia.org/wiki/Sintaxe#cite_note-Borba-3)

Os primeiros passos da tradição [europeia](https://pt.wikipedia.org/wiki/Europa "Europa") no estudo da sintaxe foram dados pelos antigos [gregos](https://pt.wikipedia.org/wiki/Gr%C3%A9cia "Grécia"), começando com [Aristóteles](https://pt.wikipedia.org/wiki/Arist%C3%B3teles "Aristóteles"), que foi o primeiro a dividir a frase em [sujeitos](https://pt.wikipedia.org/wiki/Sujeito "Sujeito") e [predicados](https://pt.wikipedia.org/wiki/Predicado_(gram%C3%A1tica) "Predicado (gramática)"). Um segundo contributo fundamental deve-se a [Frege](https://pt.wikipedia.org/wiki/Frege "Frege") que critica a análise aristotélica, propondo uma divisão da frase em função e argumento. Deste trabalho fundador, deriva toda a lógica formal contemporânea, bem como a sintaxe formal. No [século XIX](https://pt.wikipedia.org/wiki/S%C3%A9culo_XIX "Século XIX") a [filologia](https://pt.wikipedia.org/wiki/Filologia "Filologia") dedicou-se sobretudo à investigação nas áreas da [fonologia](https://pt.wikipedia.org/wiki/Fonologia "Fonologia") e [morfologia](https://pt.wikipedia.org/wiki/Morfologia_(lingu%C3%ADstica) "Morfologia (linguística)"), não tendo reconhecido o contributo fundamental de [Frege](https://pt.wikipedia.org/wiki/Frege "Frege"), que só em meados do século XX foi verdadeiramente apreciado.

# **Análise Sintática**

A **análise sintática** pode ser dividida em dois estudos: na _análise do período simples_ — constituída de uma oração, estuda termos e suas relações em uma oração; na _análise do período composto_ — constituída de mais de uma oração, estuda a relação entre orações.(https://pt.wikipedia.org/wiki/Sintaxe#cite_note-cpl-4)

Biblioteca (computação)
=======================

Na [ciência da computação](https://pt.wikipedia.org/wiki/Ci%C3%AAncia_da_computa%C3%A7%C3%A3o "Ciência da computação"), **biblioteca** é uma coleção de [subprogramas](https://pt.wikipedia.org/wiki/Subprograma "Subprograma") utilizados no desenvolvimento de [software](https://pt.wikipedia.org/wiki/Software "Software"). Bibliotecas contém código e dados auxiliares, que provém serviços a programas independentes, o que permite o compartilhamento e a alteração de código e dados de forma [modular](https://pt.wikipedia.org/wiki/M%C3%B3dulo_(programa%C3%A7%C3%A3o) "Módulo (programação)"). Alguns [executáveis](https://pt.wikipedia.org/wiki/Execut%C3%A1vel "Executável") são tanto programas independentes quanto bibliotecas, mas a maioria das bibliotecas não são executáveis. Executáveis e bibliotecas fazem referências mútuas conhecidas como _ligações_, tarefa tipicamente realizada por um [ligador](https://pt.wikipedia.org/wiki/Ligador "Ligador").

A maior parte dos [sistemas operacionais](https://pt.wikipedia.org/wiki/Sistema_operativo "Sistema operativo") modernos provê bibliotecas que implementam a maioria dos serviços do sistema, que transformaram em comodidades os serviços que uma aplicação moderna espera que sejam providos pelo sistema operacional. Assim sendo, a maior parte do código utilizado em aplicações modernas é fornecido por estas bibliotecas.

# Visão geral

Bibliotecas podem ser classificadas pela maneira como são compartilhadas, pela maneira como são ligadas e por quando são ligadas.

# Bibliotecas tradicionais

Historicamente, as bibliotecas consistiam de um conjunto de rotinas que eram copiadas para uma aplicação-alvo pelo [compilador](https://pt.wikipedia.org/wiki/Compilador "Compilador") ou [ligador](https://pt.wikipedia.org/wiki/Ligador "Ligador"), produzindo uma aplicação executável independente, ou _[standalone](https://pt.wikipedia.org/wiki/Standalone "Standalone")_. Os fabricantes de compiladores proviam bibliotecas-padrão (por exemplo, a [biblioteca padrão do C](https://pt.wikipedia.org/wiki/Biblioteca_padr%C3%A3o_do_C "Biblioteca padrão do C")), mas os programadores também podiam criar suas próprias bibliotecas para uso próprio ou distribuição.

# Ligação dinâmica

**Ligação dinâmica** significa que os dados em uma biblioteca não são copiados para um novo executável ou biblioteca em [tempo de compilação](https://pt.wikipedia.org/wiki/Tempo_de_compila%C3%A7%C3%A3o "Tempo de compilação"), mas permanecem a um [arquivo](https://pt.wikipedia.org/wiki/Arquivo_de_computador "Arquivo de computador") separado no disco. O [ligador](https://pt.wikipedia.org/wiki/Ligador "Ligador") realiza uma quantidade mínima de trabalho em tempo de compilação—ele apenas grava quais bibliotecas são necessárias para o executável em um índice. A maior parte do trabalho é feita quando a aplicação é [carregada em memória](https://pt.wikipedia.org/w/index.php?title=Tempo_de_carregamento&action=edit&redlink=1 "Tempo de carregamento (página não existe)") ou durante a [execução do processo](https://pt.wikipedia.org/wiki/Tempo_de_execu%C3%A7%C3%A3o "Tempo de execução"). O código de ligação necessário é na verdade parte do sistema operacional subjacente. Na hora apropriada, o carregador do programa encontra as bibliotecas relevantes no disco e adiciona os dados relevantes da biblioteca no espaço de memória do processo.

Alguns sistemas operacionais são apenas capazes de ligar uma biblioteca em tempo de carregamento, antes que a execução do processo se inicie; outros podem ser capazes de esperar até depois do início da execução e apenas ligar a biblioteca quando ela for referenciada (ou seja, durante o tempo de execução). Este último é freqüentemente chamado de "carregamento atrasado". Em ambos os casos, a ligação é dita dinâmica.

_[Plugins](https://pt.wikipedia.org/wiki/Plugin "Plugin")_ são uma utilização comum de bibliotecas de ligação dinâmica, algo especialmente útil quando as bibliotecas podem ser substituídas por outras com [interfaces](https://pt.wikipedia.org/wiki/Interface "Interface") similares, mas funcionalidades diferentes. Diz-se que um software possui uma "arquitetura de plugins" se ele utiliza bibliotecas para funcionalidades essenciais com a intenção de que elas possam ser substituídas. Note, entretanto, que o uso de bibliotecas de ligação dinâmica na arquitetura de uma aplicação não necessariamente significa que elas possam ser substituídas.

A ligação dinâmica foi originalmente desenvolvida no sistema operacional [Multics](https://pt.wikipedia.org/wiki/Multics "Multics"), a partir de [1964](https://pt.wikipedia.org/wiki/1964 "1964"). Ela também era uma característica do [Michigan Terminal System](https://pt.wikipedia.org/w/index.php?title=Michigan_Terminal_System&action=edit&redlink=1 "Michigan Terminal System (página não existe)"), construído no final dos [anos 1960](https://pt.wikipedia.org/wiki/Anos_1960 "Anos 1960").(https://pt.wikipedia.org/wiki/Biblioteca_(computa%C3%A7%C3%A3o)#cite_note-1) No [Microsoft Windows](https://pt.wikipedia.org/wiki/Microsoft_Windows "Microsoft Windows"), bibliotecas de ligação dinâmica são chamadas _[dynamic-link libraries](https://pt.wikipedia.org/wiki/DLL "DLL")_.

# Realocação

Uma sutileza com a qual o carregador de programas tem que lidar é que a localização real dos dados da biblioteca não é conhecida até que o executável e todas as bibliotecas a ele associadas sejam carregadas para a memória. Isto se deve ao fato de que as localizações de memória utilizadas dependerão de quais bibliotecas foram carregadas. Não é possível armazenar uma localização absoluta para os dados dentro do próprio executável, nem mesmo na biblioteca, uma vez que isto resultaria em conflitos entre diferentes bibliotecas. Isto é, se duas bibliotecas distintas alocassem espaços de memória iguais ou sobrepostos, seria impossível usar as duas no mesmo programa. Isto pode vir a mudar com a adoção de arquiteturas de [64-bits](https://pt.wikipedia.org/wiki/64-bit "64-bit"), pois elas oferecem endereços de [memória virtual](https://pt.wikipedia.org/wiki/Mem%C3%B3ria_virtual "Memória virtual") suficientes para garantir que cada biblioteca escrita receba sua faixa de endereços única.

Seria possível, em teoria, examinar o programa durante o [tempo de carregamento](https://pt.wikipedia.org/w/index.php?title=Tempo_de_carregamento&action=edit&redlink=1 "Tempo de carregamento (página não existe)") e substituir cada referência a dados na biblioteca por [ponteiros](https://pt.wikipedia.org/wiki/Ponteiro_(programa%C3%A7%C3%A3o) "Ponteiro (programação)") para as posições de memória apropriadas uma vez que todas as bibliotecas tivessem sido carregadas. Contudo, este método consumiria quantidades inaceitáveis de tempo ou memória. Em vez disso, a maioria dos sistemas de bibliotecas dinâmicas cria uma tabela de símbolos com endereços vazios no programa em [tempo de compilação](https://pt.wikipedia.org/wiki/Tempo_de_compila%C3%A7%C3%A3o "Tempo de compilação"). Todas as referências ao código ou dados na biblioteca passam por esta tabela, chamada diretório de importação. Durante o [tempo de carregamento](https://pt.wikipedia.org/w/index.php?title=Tempo_de_carregamento&action=edit&redlink=1 "Tempo de carregamento (página não existe)") esta tabela é modificada com a localização dos códigos e dados na biblioteca pelo carregador de programas. Este processo ainda é lento a ponto de comprometer a performance de programas que façam uso de outros programas a uma taxa muito alta, como é o caso de alguns [shell scripts](https://pt.wikipedia.org/wiki/Shell_script "Shell script").

A biblioteca, por sua vez, contém uma tabela com todos os métodos que a compõem, conhecidos como pontos de entrada. Chamadas à biblioteca passam por esta tabela, procurando pela localização do código na memória e então os executando. Isto introduz uma [sobrecarga](https://pt.wikipedia.org/w/index.php?title=Overhead&action=edit&redlink=1 "Overhead (página não existe)") na chamada de biblioteca, mas o atraso é, em geral, tão pequeno que pode ser negligenciado.

Localizando bibliotecas em tempo de execução
--------------------------------------------

Ligadores e carregadores de programas dinâmicos variam amplamente em funcionalidade. Alguns dependem de caminhos explícitos armazenados no arquivo executável. Qualquer modificação no nome da biblioteca ou layout do [sistema de arquivos](https://pt.wikipedia.org/wiki/Sistema_de_arquivos "Sistema de arquivos") causará falha nestes sistemas. Mais comumente, apenas um nome da biblioteca (e não do caminho) é armazenado no executável, e o sistema operacional provê um sistema para encontrar a biblioteca no disco, baseado em algum algoritmo.

* A maioria de sistemas [Unix-like](https://pt.wikipedia.org/wiki/Unix-like "Unix-like") possuem uma "busca de caminho" especificando o sistema de arquivos no qual procurar as bibliotecas dinâmicas. Em outros sistemas, o caminho padrão é especificado em um arquivo de configuração; em outros, é codificado no carregador de programas dinâmico. Alguns formatos de arquivos executáveis podem especificar diretórios adicionais nos quais procurar por bibliotecas de um programa em particular. Ele pode geralmente ser relido com uma [variável de ambiente](https://pt.wikipedia.org/wiki/Vari%C3%A1vel_de_ambiente "Variável de ambiente"), embora ela esteja desabilitada para programas setuid e setgid, então o usuário não pode forçar tal programa a rodar código arbitrário. Desenvolvedores de bibliotecas são encorajados a colocar suas bibliotecas dinâmicas em locais no caminho de busca padrão. Por outro lado, isto pode tornar a instalação de novas bibliotecas problemática, e estes caminhos conhecidos rapidamente se tornarem padrão para um número crescente de arquivos de biblioteca, tornando o gerenciamento mais complexo.
* O Windows verifica o [Registro do Sistema](https://pt.wikipedia.org/wiki/Registro_do_Sistema "Registro do Sistema") para determinar o lugar próprio para achar uma [DLL](https://pt.wikipedia.org/wiki/DLL "DLL") [ActiveX](https://pt.wikipedia.org/wiki/ActiveX "ActiveX"), mas para outras DLL ele verifica o diretório de onde o programa foi carregado; o diretório corrente de trabalho (somente nas antigas versões de Windows); quaisquer diretórios selecionados pela chamada da função`SetDllDirectory()`; os diretórios System32, System e Windows; e, finalmente, os diretórios especificados pela [variável de ambiente](https://pt.wikipedia.org/wiki/Vari%C3%A1vel_de_ambiente "Variável de ambiente") PATH.(https://pt.wikipedia.org/wiki/Biblioteca_(computa%C3%A7%C3%A3o)#cite_note-2)
* O [OpenStep](https://pt.wikipedia.org/wiki/OpenStep "OpenStep") usa um sistema mais flexível, coletando uma lista de bibliotecas de um número conhecido de localizações (similar ao conceito de PATH) quando o sistema se inicia. O deslocamento de alguma biblioteca não causa problemas, no entanto um tempo maior será necessário durante o primeiro início do sistema.

Uma das grandes desvantagens da ligação dinâmica é que os executáveis dependem de bibliotecas armazenadas separadamente para o correto funcionamento. Se uma biblioteca é apagada, movida, ou renomeada, ou ainda se uma versão incompatível de uma DLL é copiada para o lugar onde é procurada, o executável pode ter mal funcionamento ou mesmo falhar no carregamento; danificando arquivos vitais usados por quase todos os executáveis do sistema (como a biblioteca C`libc.so` nos sistemas Unix), tornando o sistema inoperável. No Windows isso é comumente chamado de [DLL hell](https://pt.wikipedia.org/w/index.php?title=DLL_hell&action=edit&redlink=1 "DLL hell (página não existe)").

# Carregamento dinâmico

O Carregamento dinâmico é um subconjunto da ligação dinâmica em que uma biblioteca ligada dinamicamente é carregada ou descarregada do sistema em [tempo de execução](https://pt.wikipedia.org/wiki/Tempo_de_execu%C3%A7%C3%A3o "Tempo de execução") após requisição. A requisição pode ser feita implicitamente em tempo de compilação, ou explicitamente em tempo de execução. Requisições implícitas são feitas ao adicionar referências às bibliotecas a um [arquivo objeto](https://pt.wikipedia.org/wiki/Arquivo_objeto "Arquivo objeto") pelo ligador. Requisições explícitas são feitas pelas aplicações através do uso de uma [API](https://pt.wikipedia.org/wiki/API "API") de ligação.

A maioria dos sistemas operacionais que suportam a ligação dinâmica também suportam o carregamento dinâmico através de uma API específica. Por exemplo, o Windows utiliza as funções da API `LoadLibrary`, `LoadLibraryEx`, `FreeLibrary` e `GetProcAddress` para DLL; incluindo a maioria dos UNIX e UNIX-like, sistemas baseados em [POSIX](https://pt.wikipedia.org/wiki/POSIX "POSIX") usam `dlopen`, `dlclose` e `dlsym`.

# Bibliotecas remotas

Outra solução para a questão das bibliotecas é utilizar executáveis completamente separados e chamá-los através de [chamadas de procedimento remoto](https://pt.wikipedia.org/wiki/Chamada_de_procedimento_remoto "Chamada de procedimento remoto") (RPC). Essa abordagem maximiza o reaproveitamento do sistema operacional: o código necessário para suportar a biblioteca é o mesmo usado para prover o suporte e a segurança da aplicação para os outros programas. Adicionalmente, esse sistema remoto não requer que a biblioteca esteja na mesma máquina do executável, as chamadas podem ser transmitidas por uma [rede](https://pt.wikipedia.org/wiki/Rede_de_computadores "Rede de computadores").

A desvantagem é que cada chamada da biblioteca implica uma sobrecarga considerável. Entretanto, essa abordagem tornou-se popular em diversas áreas específicas, como sistemas cliente-servidor e [servidores e aplicação](https://pt.wikipedia.org/wiki/Servidor_de_aplica%C3%A7%C3%A3o "Servidor de aplicação") como o [Enterprise JavaBeans](https://pt.wikipedia.org/wiki/Enterprise_JavaBeans "Enterprise JavaBeans").

# Bibliotecas compartilhadas

Uma **biblioteca compartilhada** ou **objeto compartilhado** é um arquivo que é destinado a ser compartilhado pelos [arquivos executáveis](https://pt.wikipedia.org/wiki/Execut%C3%A1vel "Executável") e outros arquivos de objeto compartilhados. Os módulos usados por um programa são carregados a partir de objetos compartilhados na memória em [tempo de carregamento](https://pt.wikipedia.org/w/index.php?title=Carregador_(computa%C3%A7%C3%A3o)&action=edit&redlink=1 "Carregador (computação) (página não existe)") ou [tempo de execução](https://pt.wikipedia.org/wiki/Tempo_de_execu%C3%A7%C3%A3o "Tempo de execução"), em vez de serem copiados por um ligador quando ele cria um único arquivo executável monolítico para o programa.

Bibliotecas compartilhadas podem ser ligadas estaticamente, significando que as referências aos módulos de biblioteca são resolvidos e os módulos são alocados na memória quando o arquivo executável for criado. Porém muitas vezes a ligação de bibliotecas compartilhadas é adiada até que elas sejam carregadas.

A maioria dos [sistemas operacionais](https://pt.wikipedia.org/wiki/Sistema_operacional "Sistema operacional") modernos podem ter arquivos de biblioteca compartilhadas do mesmo formato que os arquivos executáveis. Isto oferece duas principais vantagens: primeira, é necessário fazer apenas um carregador para ambos, em vez de dois (possuir o único carregador é considerado vantajoso sua complexidade adicionada). Segundo, possibilita que os executáveis também sejam usados como bibliotecas compartilhadas, se eles possuírem uma [tabela de símbolos](https://pt.wikipedia.org/wiki/Tabela_de_s%C3%ADmbolos "Tabela de símbolos"). Os formatos combinados de bibliotecas executáveis ​​e compartilhadas típicas são [ELF](https://pt.wikipedia.org/wiki/ELF "ELF") e [Mach-O](https://pt.wikipedia.org/w/index.php?title=Mach-O&action=edit&redlink=1 "Mach-O (página não existe)") (ambos no Unix) e [PE](https://pt.wikipedia.org/wiki/Portable_Executable "Portable Executable") (Windows).

Em alguns ambientes mais antigos, como o [Windows de 16 bits](https://pt.wikipedia.org/wiki/Windows_API "Windows API") ou o [MPE](https://pt.wikipedia.org/w/index.php?title=HP_Multi-Programming_Executive&action=edit&redlink=1 "HP Multi-Programming Executive (página não existe)") para os dados (locais) baseados na pilha do [HP 3000](https://pt.wikipedia.org/w/index.php?title=HP_3000&action=edit&redlink=1 "HP 3000 (página não existe)") apenas era permitido no código da biblioteca compartilhada ou outras restrições significativas foram colocadas no código da biblioteca compartilhada.

O termo biblioteca compartilhada é ambíguo, pois se refere a dois conceitos distintos. O primeiro é o compartilhamento de código localizado no disco por programas não relacionados. O segundo é o compartilhamento de código carregado na memória, quando dois programas executam a mesma página física da RAM, mapeada em diferentes espaços de endereçamento. O segundo caso possui algumas vantagens. Por exemplo, no sistema [OpenStep](https://pt.wikipedia.org/wiki/OpenStep "OpenStep") as aplicações tinham geralmente um tamanho pequeno e eram carregadas instantaneamente; a vasta maioria do código estava localizada em bibliotecas já carregadas pelo sistema operacional. Mas existe um custo, pois o código compartilhado deve ser escrito para ser executado em um ambiente multitarefa, o que afeta o desempenho.

### Compartilhamento de memória

O código de biblioteca pode ser armazenado em memória por vários [processos](https://pt.wikipedia.org/wiki/Processo "Processo"), bem como no disco. Se memória virtual for usada, os processos executam na mesma página física da RAM que é mapeada nos diferentes espaços de endereço dos processos.

# Bibliotecas objeto

Apesar da ligação dinâmica ter sido desenvolvida na [década de 1960](https://pt.wikipedia.org/wiki/D%C3%A9cada_de_1960 "Década de 1960"), somente no final da [década de 1980](https://pt.wikipedia.org/wiki/D%C3%A9cada_de_1980 "Década de 1980") a tecnologia atingiu o consumidor final. Durante a [década de 1990](https://pt.wikipedia.org/wiki/D%C3%A9cada_de_1990 "Década de 1990") já estava disponível na maioria dos sistemas operacionais. Durante o mesmo período a [programação orientada a objeto](https://pt.wikipedia.org/wiki/Programa%C3%A7%C3%A3o_orientada_a_objeto "Programação orientada a objeto") tornou-se cada vez mais significativa no desenvolvimento de software. POO em tempo de execução requer informações adicionais que bibliotecas tradicionais não fornecem. Além dos nomes e dos pontos de entrada da biblioteca, também requerem uma lista de objetos do qual dependem. Como no caso de uma [herança](https://pt.wikipedia.org/wiki/Heran%C3%A7a_(programa%C3%A7%C3%A3o) "Herança (programação)"), que separa partes de uma definição em diferentes pontos do código. Em um sistema verdadeiramente orientado a objeto, as bibliotecas podem não ser conhecidas em tempo de compilação.

Ainda no mesmo período outra área de desenvolvimento era o conceito de execução remota, em que um computador cliente executaria os serviços de um [mainframe](https://pt.wikipedia.org/wiki/Mainframe "Mainframe"). O cliente manteria mensagens para a central a fim de receber pacotes de dados para apresentar. Chamadas de procedimento remoto já eram usadas para essas tarefas, ainda que não houvesse um sistema padrão para tal.

Os dois conceitos logo foram fundidos, produzindo um formato de biblioteca orientada a objeto que pudesse ser executado em qualquer local. Tais sistemas foram denominados bibliotecas objeto, ou objetos distribuídos se suportassem acesso remoto. A [Component Object Model](https://pt.wikipedia.org/wiki/Component_Object_Model "Component Object Model") da Microsoft é exemplo desse tipo de biblioteca para uso local, e a DCOM para uso remoto.

Por um tempo bibliotecas objeto foram a sensação do mundo da programação, existindo esforços para criar sistemas que pudessem ser executados em diferentes plataformas. Exemplos incluem [System Object Model](https://pt.wikipedia.org/w/index.php?title=System_Object_Model&action=edit&redlink=1 "System Object Model (página não existe)") (SOM/DSOM) da [IBM](https://pt.wikipedia.org/wiki/IBM "IBM"), [Distributed Objects Everywhere](https://pt.wikipedia.org/w/index.php?title=Distributed_Objects_Everywhere&action=edit&redlink=1 "Distributed Objects Everywhere (página não existe)") (DOE) da [Sun Microsystems](https://pt.wikipedia.org/wiki/Sun_Microsystems "Sun Microsystems"), [Portable Distributed Objects](https://pt.wikipedia.org/w/index.php?title=Portable_Distributed_Objects&action=edit&redlink=1 "Portable Distributed Objects (página não existe)") (PDO) da [NeXT](https://pt.wikipedia.org/wiki/NeXT "NeXT"), [Component Object Model](https://pt.wikipedia.org/wiki/Component_Object_Model "Component Object Model") (COM/DCOM) da Microsoft, e diferentes sistemas baseados em [CORBA](https://pt.wikipedia.org/wiki/CORBA "CORBA"). O que sucedeu foi que o conceito foi caindo em desuso, com exceção da COM da Microsoft e o PDO da NeXT (agora [Apple Inc.](https://pt.wikipedia.org/wiki/Apple_Inc. "Apple Inc.")).

Framework
===========

Um _**framework**_ em [desenvolvimento de software](https://pt.wikipedia.org/wiki/Desenvolvimento_de_software "Desenvolvimento de software"), é uma [abstração](https://pt.wikipedia.org/wiki/Abstra%C3%A7%C3%A3o "Abstração") que une [códigos](https://pt.wikipedia.org/wiki/C%C3%B3digo "Código") comuns entre vários projetos de software provendo uma funcionalidade genérica. Um _framework_ pode atingir uma funcionalidade específica, por configuração, durante a programação de uma aplicação. Ao contrário das [bibliotecas](https://pt.wikipedia.org/wiki/Biblioteca_(computa%C3%A7%C3%A3o) "Biblioteca (computação)"), é o _framework_ quem dita o fluxo de controle da aplicação, chamado de [Inversão de Controle](https://pt.wikipedia.org/wiki/Invers%C3%A3o_de_Controle "Inversão de Controle"). (https://pt.wikipedia.org/wiki/Framework#cite_note-ufcg-1)

# Conceito

Um _framework_ ou arcabouço conceitual, é um conjunto de conceitos usado para resolver um problema de um domínio específico. _Framework_ conceitual não se trata de um software executável, mas sim de um [modelo de dados](https://pt.wikipedia.org/wiki/Modelo_de_dados "Modelo de dados") para um domínio. _Framework_ de [software](https://pt.wikipedia.org/wiki/Software "Software") compreende de um conjunto de **classes** implementadas em uma [linguagem de programação](https://pt.wikipedia.org/wiki/Linguagem_de_programa%C3%A7%C3%A3o "Linguagem de programação") específica, usadas para auxiliar o desenvolvimento de software.

O _framework_ atua onde há funcionalidades em comum a várias aplicações, porém para isso as aplicações devem ter algo razoavelmente grande em comum para que o mesmo possa ser utilizado em várias aplicações.

[Padrões de projeto de software](https://pt.wikipedia.org/wiki/Padr%C3%B5es_de_projeto_de_software "Padrões de projeto de software") não se confundem com _frameworks_, pois padrões possuem um nível maior de abstração. Um _framework_ inclui código, diferentemente de um padrão de projeto. Um _framework_ pode ser modelado com vários padrões de projeto, e sempre possuem um domínio de uma aplicação particular, algo que não ocorre nos padrões de projeto de software.

> **_Framework_ é um conjunto de classes que colaboram para realizar uma responsabilidade para um domínio de um subsistema da aplicação.**
> 
> **— Fayad e Schmidt **(https://pt.wikipedia.org/wiki/Framework#cite_note-ufcg-1)

_Frameworks_ possuem vantagens, tais como: maior facilidade para a detecção de erros, por serem peças mais concisas de [software](https://pt.wikipedia.org/wiki/Software "Software"); concentração na abstração de soluções do problema que estamos tratando; eficiência na resolução dos problemas e otimização de recursos.

# Partes

_Frozenspots_ são as partes fixas de um _framework_, também conhecidos como _hook points_. São serviços já implementados pelo framework. Normalmente realizam chamadas indiretas aos _hotspots_.

_Hotspots_ são as partes flexíveis de um _framework_. São pontos extensíveis, necessitam de complementação por funcionalidades/serviços que devem ser implementados. _Hotspots_ são partes nas quais os programadores que usam o _framework_ adicionam o seu código para especificar uma funcionalidade de sua aplicação. São invocados pelo _framework_, ou seja, [classes](https://pt.wikipedia.org/wiki/Classe_(programa%C3%A7%C3%A3o) "Classe (programação)") (implementadas pelo programador da aplicação) recebem mensagens de uma classe do _framework_ (_frozenspot_). Isso geralmente é implementado através de [herança](https://pt.wikipedia.org/wiki/Heran%C3%A7a_(programa%C3%A7%C3%A3o) "Herança (programação)") e de [métodos](https://pt.wikipedia.org/wiki/M%C3%A9todo_(programa%C3%A7%C3%A3o) "Método (programação)") [abstratos](https://pt.wikipedia.org/wiki/Abstra%C3%A7%C3%A3o_(programa%C3%A7%C3%A3o) "Abstração (programação)").

# Tipos

Frameworks_ verticais são confeccionados através da experiência obtida em um determinado contexto específico. Esses são mais comumente chamados de frameworks especialistas. Tentam resolver problemas de um domínio e são usados em vários softwares do mesmo domínio. Exemplos: _framework_ financeiro, recursos humanos.

Após alguns projetos em um domínio específico, serão percebidos pontos semelhantes entre estes projetos; E é com base nesses pontos que será construído o framework vertical (especialista).

_Frameworks_ horizontais não dependem do domínio da aplicação e podem ser usados em diferentes domínios. Exemplos: Interfaces gráficas, persistência, transação.

![](C:\Users\Silvana\Downloads\Python_Powered.png.webp)



## Orientação a objetos

Especificamente em [orientação a objetos](https://pt.wikipedia.org/wiki/Orienta%C3%A7%C3%A3o_a_objetos "Orientação a objetos"), _framework_ é um conjunto de [classes](https://pt.wikipedia.org/wiki/Classe_(programa%C3%A7%C3%A3o) "Classe (programação)") com objetivo de reutilização de [arquitetura de software](https://pt.wikipedia.org/wiki/Arquitetura_de_software "Arquitetura de software"), provendo um guia para uma solução em um domínio específico de _software_. _Framework_ se diferencia de uma simples biblioteca, pois esta se concentra apenas em oferecer implementação de funcionalidades, sem definir a reutilização de uma solução de arquitetura.

Muitos engenheiros acreditam que a arquitetura é determinada pelos requisitos e por isso esperam que a fase de [engenharia de requisitos](https://pt.wikipedia.org/wiki/Engenharia_de_requisitos "Engenharia de requisitos") esteja finalizada para então iniciar sua. Porém, apenas uma fração dos requisitos específicos do sistema têm influência na arquitetura. A identificação dos requisitos que são significantes para a arquitetura pode ser respondida através de um _framework_ conceitual desenvolvido especialmente para um domínio específico, uma vez que esta resposta é muito dependente do domínio. Avançar para a fase de projeto ou mesmo iniciar a implementação do sistema não quer dizer que a definição da arquitetura esteja finalizada. Isto significa que o detalhamento obtido até então já é suficiente para prosseguir com o projeto de uma parte do sistema.

Administração de empresas
-------------------------

Em administração, um _framework_ é uma estrutura conceitual básica que permite o manuseio homogêneo de diferentes objetos de negócio. Serve para incrementar a disciplina de gestão e predefinir entregáveis comuns para cada objeto de negócio.

Pode ser visto também como uma tática bem definida para manipular com destreza ambientes organizacionais complexos. Um framework deve prover sugestões de solução para uma família de problemas semelhantes.

Exemplos de frameworks para gestão: [ISO 9000](https://pt.wikipedia.org/wiki/ISO_9000 "ISO 9000"), [ISO 14000](https://pt.wikipedia.org/wiki/ISO_14000 "ISO 14000"), [OHSAS 18000](https://pt.wikipedia.org/w/index.php?title=OHSAS_18000&action=edit&redlink=1 "OHSAS 18000 (página não existe)"), [ITIL](https://pt.wikipedia.org/wiki/ITIL "ITIL"), [COBIT](https://pt.wikipedia.org/wiki/COBIT "COBIT"), [CMM](https://pt.wikipedia.org/wiki/CMM "CMM"), [HACCP](https://pt.wikipedia.org/wiki/HACCP "HACCP"), [SCRUM](https://pt.wikipedia.org/wiki/SCRUM "SCRUM").


