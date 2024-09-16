# Dio-Bootcamp-Randstad-2024.
Projetos  Randstad  2024  .NET C#


 **Linguagem .Net C#:**
 <hr>
 O .NET Framework (pronuncia-se: dótnét) é uma iniciativa da empresa Microsoft, que visa uma plataforma única para desenvolvimento e execução de sistemas e aplicações. Todo e qualquer código gerado para .NET pode ser executado em qualquer dispositivo que possua um framework de tal plataforma. Com ideia semelhante à plataforma Java, o programador deixa de escrever código para um sistema ou dispositivo específico, e passa a escrever para a plataforma .NET. Aplicações escritas para ele funcionam em um ambiente de software controlado, em oposição a um ambiente de hardware, através de uma máquina virtual de aplicação.
 
 
 **HISTÓRIA**
 <hr>
 O .NET Framework consiste de dois componentes principais, é executada sobre uma Common Language Runtime - CLR (Ambiente de Execução Independente de Linguagem) interagindo com um Framework Class Library - FCL (Conjunto de Bibliotecas Unificadas). Ele permite executar diversas linguagens permitindo grande interoperabilidade entre elas. O CLR fornece gerenciamento de memória, controle de exceção, interoperabilidade, manipulação de processamento paralelo e concorrente, reflexão, segurança, serviços de compilação para a arquitetura específica, entre outros. A FCL oferece APIs para UI de console, acesso a dados, conectividade com banco de dados, redes, web, criptografia, acesso aos serviços do sistema operacional, estruturas de dados e algoritmos diversos, facilidades para a linguagem e muito mais.

Primeiramente, só era disponível no Windows, como uma plataforma de código fechado, mas o código fonte foi liberado. Em 2014, o desenvolvimento começou no .NET Core, uma plataforma aberta do .NET que poderia rodar em Linux e MacOS. Existem várias variações da plataforma, como .NET Compact Framework, .NET Micro Framework e Silverlight. Em novembro de 2020, o .NET Core foi renomeado para simplesmente .NET, porém o .NET Framework terá suporte permanente no Windows 10.

**Arquitetura**
<hr>

Esta CLR é capaz de executar através da Common Language Infrastructure, uma grande quantidade de linguagens de programação, interagindo entre si como se fossem uma única linguagem.

Algumas linguagens são:

(**APL**)
(**Boo**)
(**Clarion**)
(**COBOL**)
(**Component Pascal**)
(**C#**)
(**C++**)
(**F#**)
(**Eiffel**)
(**Forth**)
(**Fortran**)
(**Haskell**)
(**Java**)
(**JScript**)
(**J#**)
(**Lua**)
(**Mercury**)
(**Piet**)
(**Oberon**)
(**Delphi**)
(**Oz**)
(**Pascal**)
(**Perl**)
(**PowerBuilder**)
(**PowerShell**)
(**Python**)
(**RPG**)
(**Ruby**)
(**Scheme**)
(**SmallTalk**)
(**Standard ML**)
(**Visual Basic**)
(**xBase**).
<hr>

Esta plataforma permite a execução, construção e desenvolvimento de Web Services (Aplicações Web) de forma integrada e unificada.

Originalmente a plataforma .NET baseia-se em um dos princípios utilizados na tecnologia Java (Just In Time Compiler - JIT), os programas desenvolvidos para ela são compilados duas vezes, uma na distribuição (gerando um código que é conhecido como "bytecodes") e outra na execução.

Um programa é escrito em qualquer das linguagens de programação disponíveis para a plataforma, o código-fonte gerado pelo programador é então compilado pela linguagem escolhida gerando um código intermediário em uma linguagem chamada CIL (Common Intermediate Language).
No momento da execução do programa ele é novamente compilado, desta vez pelo compilador JIT, de acordo com a utilização do programa, por exemplo: Temos um Web Site desenvolvido em ASP.NET, ao entrar pela primeira vez em uma página o JIT irá compila-la, nas outras vezes que algum outro usuário acessar esta página, ele usará esta compilação.

Também é possível, através de ferramentas específicas, "pré-compilar" o código para que não se tenha o custo da compilação JIT durante a execução.

O fato desta arquitetura utilizar a CIL gera uma possibilidade pouco desejada entre os criadores de software que é a de fazer a "engenharia reversa", ou seja, a partir de um código compilado, recuperar o código original. Isto não é uma ideia agradável para as empresas que sobrevivem da venda de softwares produzidos nesta plataforma.

Por causa disso, existem ferramentas que "ofuscam" o código CIL, trocando nomes de variáveis, métodos, interfaces e etc para dificultar o trabalho de quem tentar uma engenharia reversa no mesmo.

Para melhorar a performance de execução é possível gerar um código nativo após instalado com o NGEN (Gerador de Imagem Nativa). Este NGEN é uma ferramenta que melhora o desempenho de aplicativos gerenciados. Ngen.exe cria imagens nativas, que são arquivos que contém o código de máquina específico do processamento compilado e as instala no cache de imagem nativa do computador local. O tempo de execução pode usar imagens nativas do cache em vez de usar o compilador JIT (Just-In-Time) para compilar o assembly original.

Hoje, através do .NET Native, é possível gerar um executável diretamente para a arquitetura e plataforma que irá rodar obtendo o melhor dela.

Fonte: https://pt.wikipedia.org/wiki/.NET_Framework
