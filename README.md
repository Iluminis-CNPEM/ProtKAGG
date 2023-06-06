# ProtKAGG
- Autores do projeto: Anelise Gonçalves, Gabriel Torquato, Gabriela Frajtag e Pedro Kramer

**Como o código funciona?**
- Inicialmente, o usuário deverá fornecer uma sequência de DNA. 
- O código irá perguntar ao usuário se aquele DNA representa uma sequência codificante. 
- *O que seria a região de codificação?* A região de codificação de um gene, também conhecida e abreviada na literatura em inglês como CDS (de coding DNA sequence), é uma porção de DNA de um gene ou RNA que codifica para proteína. A região geralmente começa na extremidade 5' por um codão de início e termina na extremidade 3' com um codão de parada. (fonte: https://pt.wikipedia.org/wiki/Regi%C3%A3o_de_codifica%C3%A7%C3%A3o)
- Se ele representa uma região codificante, o código vai retornar apenas o RNA correspondente e qual proteína seria.
- Caso ele não represente uma região codificante, o código vai retornar o RNA correspondente, 3 frames possíveis. Esses frames se referem a maneira como a sequência é lida e traduzida em proteínas. O DNA é composto por uma sequência de nucleotídeos, que podem ser agrupados em conjuntos de 3, chamados de "códons". Cada códon corresponde a um amnoácido específico.
- Depois de retornar os três frames, ele vai dar possíveis proteínas que podem ser formadas a partir de cada frame. 

**Explicação dos arquivos:**
- Documento inicial ProtKAGG.pdf: arquivo em PDF do primeiro planejamento do ProtKagg e proposta do projeto

Desde a descoberta do DNA por James Watson e Francis Crick em 1953, o nosso entendimento sobre a vida e seus mecanismos fundamentais de funcionamento tem se expandido significativamente. O DNA é a molécula responsável por armazenar e transmitir as informações essenciais para a vida tal como a conhecemos.
 
<img src= "https://github.com/Illuminis-CNPEM/ProtKAAG/blob/dede25006199420969ac0e18d4c72da662a71b0b/imagem%20watson%20e%20crick.png" width="50%" height="50%">

> James Watson e Francis Crick com o seu modelo de DNA nos Laboratórios Cavendish em 1953

No cerne desse conhecimento está o dogma central da biologia, proposto por Francis Crick em 1958. Esse dogma descreve o fluxo preciso de informação genética dentro das células, desde a sequência de DNA até a produção de proteínas. A informação contida no DNA é transcrita para o RNA mensageiro (mRNA) por meio do processo de transcrição, e esse mRNA, por sua vez, é traduzido pelos ribossomos em cadeias de aminoácidos, que compõem as proteínas.

<img src= "https://github.com/Illuminis-CNPEM/ProtKAGG/blob/4a2d1a6bd4e615d03ba0bf8b66a519388db85037/imagens/dogma%20central%20da%20biologia.png" width="50%" height="50%">

> Representação visual do dogma central da biologia molecular. É importante mencionar que a descoberta da transcrição reversa, posterior à proposta inicial do dogma central, revelou a capacidade de certos vírus de converter o RNA em DNA, desafiando o fluxo tradicional de informação genética e ampliando ainda mais nosso conhecimento sobre a complexidade dos processos biológicos.
