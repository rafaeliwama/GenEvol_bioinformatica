![image](https://github.com/user-attachments/assets/df49caee-5e9f-4c73-baa3-a9c7163d2c11)


# Introdução teórica - bioinformática e suas principais aplicações

### Instrutores: Celine Lopes, Rafael E. Iwama e Thainá Cortez.


## O que é a bioinformática?
A bioinformática é uma área experimental da biologia que combina a ciência da computação com a biologia. Em outras palavras a bioinformática aplica e desenvolve ferramentas para responder perguntas biológicas. Muitas áreas da biologia e suas ciências aplicadas se beneficiam da bioinformática, como por exemplo a medicina, veterinária, agronomia, genética, evolução e muitas outras. Desta forma, a bioinformática é uma ciência transdisciplinar em sua constituição e aplicação (figura abaixo).

![image](https://github.com/user-attachments/assets/92df5eb4-1350-4072-a4c0-81434e125e18)

**A origem da bioinformática**
A origem da bioinformática pode ser atribuída a Margaret Dayhoff. Dayhoff, juntamentamente com seu colaborador Robert S. Ledley, desenvolveram o primeiro software de bioinformática que se tem noticia, o COMPROTEIN. Este software tem como função interpretação do sequenciamento de proteínas pelo método Edman. 

![image](https://github.com/user-attachments/assets/16ca63f8-d0af-4955-a222-5ab7bb53301e)

Apesar do início da bioinformática ter sido em aplicações para proteínas, durante as décadas de 1970 e 1980, uma mudança de paradigma ocorreu com a mudança do foco da bioinformática para moléculas de DNA. Esta mudança foi decorrente da elucidação do código genético para os 64 códons e do avanço nas metodologias de sequenciamento de DNA, como o tipo Sanger, fizeram com que a obtenção de sequência fosse relativamente e barata. Rapidamente, vários métodos de análise destas sequências se tornaram centrais na biologia. Alguns exemplos são as análises filogenéticas que tiveram um impulso tremendo graças a aplicação de métodos de bioinformática na inferência da relação entre linhagens diferentes de organismos.

Contudo, a maior limitação do desenvolimento e aplicação da bioinformática em seus estágios iniciais, foram as limitações físicas impostas pelo acesso a computadores, já que o custo e as dimensões destes aparelhos eram elevadas. A figura abaixo retrata um DEC VAX-11/780. Todas os componentes mostrados na figura fazem parte de apenas um único aparelho.

![image](https://github.com/user-attachments/assets/4dc68e45-1550-4714-96c6-2f61772df4e6)

No ínicio dos anos 1980, a fabricação de computadores do tipo desktop. As aplicações de softwares de bioinformática, assim como novas linguagens de programação experienciaram um _boom_. _Perl_, _R_, _Java_ e _Python_ se tornam as principais linguagens de programação na bioinformática, cada um com seus pontos positivos e negativos.

Outro evento que impulsionou a bioinformática, foi o sequênciamento de alto desempenho (HTS) que geram milhões de sequências curtas. Ou seja, devido ao volume de dados gerados, o processamento automatizado destas sequências é essencial.

> [!TIP]
> Para saber um pouco mais sobre a história da bioinformática:
> 
> Jeff Gauthier, Antony T Vincent, Steve J Charette, Nicolas Derome, A brief history of bioinformatics, Briefings in Bioinformatics, Volume 20, Issue 6, November 2019, Pages 1981–1996, https://doi.org/10.1093/bib/bby063

## Métodos de sequenciamento

Com a descoberta da estrutura dupla hélice do DNA em 1953 por Francis Crick e James Watson baseada nos dados cristalográficos de Rosalind Franklin e Maurice Wilkins, diversas perguntas cruciais sobre biodiversidade, evolução, sistemática, ecologia, dentre outras áreas da Biologia surgiram e puderam ser respondidas. Entretanto, para expandir e responder outras questões que vinham despontando, era importante estabelecer alguma tecnologia que fizesse possível que as sequências de unidades de um polímero pudessem ser determinadas.  Por exemplo, se falarmos sobre o sequenciamento de DNA de eucariotos, o objetivo é identificar e ordenar as quatro bases de nucleotídeos (adenina, guanina, citosina e timina) (Figura 1) no segmento linear do DNA. 

![Imagem 1](https://github.com/user-attachments/assets/0aa0e1ce-5926-4a1e-80f3-64f652d4efe4)

Figura 1. Esquema simplificado do resultado de um sequenciamento de DNA. As bases de nucleotídeos e os picos são mostrados. 

Baseado neste cenário, inicialmente os cientistas tentaram sequenciar moléculas de RNA, porque eram mais curtas em relação àquelas de DNA e só possuem uma só fita. Em 1965, a técnica de fracionamento 2D desenvolvida por Frederick Sanger que usava uma combinação de eletroforese cromatografia foi usada no primeiro sequenciamento de RNA completo por Holley e colaboradores. Nos anos 1970 essa técnica foi um pouco modificada e aplicada ao DNA. Posteriormente, outras técnicas fora surgindo, as quais serão brevemente descritas e explicadas nos subtópicos abaixo.

## Método de sequenciamento Maxam-Gilbert: início do sequenciamento de primeira geração
Em 1976, Allan Maxam e Walter Gilbert propuseram uma técnica de sequenciamento de DNA que se baseava na clivagem química da molécula de DNA, ou seja, o DNA era tratado quimicamente para haver a quebra de cadeia em bases específicas. Posteriormente, os fragmentos eram submetidos à eletroforese, de modo que era possível chegar ao comprimento relativo dos fragmentos, à posição dos nucleotídeos e a dedução das sequências (Figura 2).

![Maxam gilbert sequencing](https://github.com/user-attachments/assets/e478511c-c70e-4f2c-a675-c25863023551)

Figura 2. Esquema do método de sequenciamento desenvolvido por Maxam-Gilbert.

## Método de sequenciamento Sanger
Em 1977, Frederick Sanger aperfeiçoou o método de Maxam-Gilbert, propondo o método de terminação de cadeia, que veio a se tornar um dos métodos mais difundidos e usados por muito tempo, inclusive até os dias atuais. O método Sanger se baseia no uso de químicos que são análogos aos que compõem os quatro nucleotídeos do DNA. Ele tem como alvo uma região específica do DNA molde e para marcar essa região é usado um primer de oligonucleotídeos. A função desse primer é se ligar à região de interesse do DNA. Nesse sequenciamento, a molécula de DNA passa por um processo de desnaturação através do calor. Assim, esse processo é iniciado com uma única fita de DNA que servirá como um molde para gerar a parte complementar da dupla hélice. Então, para que a sequência seja determinada são usados didesoxirribonucleotídeos (ddNTPs) para a extensão da cadeia de DNA. Esses ddNTPs são marcados por cores diferentes para cada base (isso será essencial para o resultado final) e serão misturados com os desoxirribonucleotídeos trifosfatado (dNTPs) não marcados e o DNA molde em uma reação que será conduzida por uma enzima chamada polimerase. A partir dessa reação, quando os ddNTPs se ligam aleatoriamente, são produzidas fitas com diversos possíveis tamanhos, terminando a cadeia. O passo seguinte é a separação dos produtos por eletroforese. Os fragmentos terminados em cadeia são detectados, justamente, pelos marcadores fluorescentes e a cor dos ddNTPs será essencial (Figura 3).

![SangerSequencingworflow1](https://github.com/user-attachments/assets/65afaf8c-c16a-4ff7-974a-9fe1a084d249)

Figura 3. Esquema do método de sequenciamento Sanger.

## Pirosequenciamento 
A técnica de pirosequenciamento foi desenvolvida em 1995 por Mostafa Ronaghi e Pål Nyrén. Ela é uma técnica que usa a extensão de primer para o sequenciamento de DNA, mas não é baseada em gel. Essa abordagem identifica os pirofosfatos inorgânicos (PPi) liberados durante a síntese de DNA. Nas reações dessa técnica, há a liberação de uma molécula PPi depois que um nucleotídeo é adicionado na cadeia em crescimento. Nessa técnica, a enzima luciferase utiliza adenosina trifosfato (ATP) para produzir luz. À medida que há a incorporação de um nucleotídeo, os que não foram incorporados são degradados pela enzima apirase, antes que um outro nucleotídeo seja adicionado (Figura 4).

![pirosequenciamento](https://github.com/user-attachments/assets/be6ba166-f656-492a-a957-660e43ea7252)

Figura 4. Esquema representando o preparo das amostras e a abordagem de Pirosequenciamento.

O pirosequenciamento é mais barato e mais rápido em comparação ao sequenciamento Sanger. Essa técnica gera um pirograma que é mais fácil para ser analisado (Figura 5). O pirosequenciamento é semiquantitativo, então pode ser usado para identificar e quantificar mutações.   

![An-example-pyrosequencing-pyrogram-using-the-tRNA-Leu-assay](https://github.com/user-attachments/assets/c586d145-8cbf-4d6b-958f-69188918a84b)

Figura 5. Pirograma gerado pelo pirosequenciamento.

## Sequenciamentos NGS
Com o passar do tempo, novas perguntas biológicas foram surgindo e demandando técnicas de sequenciamento mais eficientes. Portanto, as novas técnicas de alto rendimento surgiram. O sequenciamento NGS pode ser usado para acessar desde um número pequeno de genes até o genoma completo de organismos. Por exemplo, o sequenciamento do genoma completo (em inglês WGS) irá fornecer as sequências das bases de DNA referente ao genoma alvo inteiro. Já o sequenciamento do transcriptoma completo propiciará informações sobre o RNA codificante e não-codificante. Enquanto o sequenciamento direcionado cobrirá conjuntos de genes pequenos ou regiões-alvo. Atualmente, este tipo de sequenciamento é bastante difundido e usado devido, principalmente, ao custo relativamente baixo e ao tempo rápido de sequenciamento. 

## Sequenciamento Illumina
Em 1997, a partir de diversas discussões, alguns cientistas começaram a ventilar a ideia de usar matrizes clonais e sequenciamento massivamente paralelo de leituras (reads) curtas através de um tipo de sequenciamento de fase sólida por terminadores reversíveis. Essa técnica foi denominada mais tarde de sequenciamento por síntese (SBS). Em 1998, os pesquisadores Shankar Balasubramanian e David Klenerman captaram fundos para formar uma corporação de pesquisa chamada Solexa. A Illumina adiquiriu a Solexa em 2007 e desde então, genomas de diversos organismos têm sido sequenciados usando essa tecnologia. A Illumina usa a tecnologia de sequenciamento por síntese que, é baseado nos quatro nucleotídeos marcados por fluorescência. Ao longo de cada ciclo de sequenciamento, apenas um dNTP é incorporado na cadeia de ácido nucléico. Posteriormente, o corante fluorescente é usado para identificar cada base, a partir de uma enzima, a clivagem é feita, o que permite a incorporação do outro nucleotídeo (Figura 6). O interessante dessa tecnologia é que como a chamada de base é feita através das medições dos sinais de intensidade ao longo de cada ciclo, é possível reduzir muito as taxas de erros. Além disso, a presença dos quatro dNTPs durante cada ciclo ligados ao terminador reversível, diminui o viés de incorporação. Essa tecnologia possibilita um sequenciamento base por base bastante acurado que pode ser usado para muitas aplicações. 

![Principle-of-the-illumina-sequencing-by-synthesis-SBS-technology-Lu-et-al-2016](https://github.com/user-attachments/assets/a30f351f-1d00-41cc-bbf3-333458923b4d)

Figura 6. Etapas do sequenciamento por síntese da Illumina.

Sequenciamento Ion Torrent
Em 2011, a Life Technologies e Thermo Scientific lançou a Plataforma Ion Torrent PGM TM. Essa tecnologia foi desenvolvida visando o sequenciamento de genomas pequenos ou genes específicos. O Ion Torrent emprega uma abordagem diferente das outras que foram explicadas até agora. Em vez de usar nucleotídeos marcados por fluorescência, eles implementaram o uso de íons de hidrogênio. Esses íons de hidrogênio são liberados sempre que um nucleotídeo é incorporado na fita de DNA. Essa assinatura química é detectada através de sensores em um microchip (Figure 7). Essa tecnologia é eficaz em tempo e gera cerca de 1 bilhão de pares de bases (1GB). 

![on-torrent-sequencing-technology-22](https://github.com/user-attachments/assets/538b942c-d738-4998-b4df-384f9363f1d8)

Figura 7. Esquema do sequenciamento Ion Torrent. 

## Sequenciamento Oxford Nanopore
A tecnologia de sequenciamento Nanopore foi desenvolvida pela Oxford Nanopore Technologies Ltd.  Nesse tipo de sequenciamento não há a necessidade de amplificação por Reação em Cadeia da Polimerase (PCR) ou a marcação química. O sequenciamento Nanopore usa flow cells que são formadas por um conjunto de pequenos poros (Figura 8) que estão submersos em uma membrana eletro resistente. 

![MinION_Flow_Cell_Layout](https://github.com/user-attachments/assets/990e3ad1-c5c5-46c9-a0f0-bd3baf9f562c)

Figura 8. Flow cell Oxford Nanopore.

A intensidade da corrente elétrica que passa pelos nanoporos é medida. Quando uma molécula atravessa os nanoporos, a corrente é interrompida e a base nucleotídica é registrada. Um algoritmo de chamada de base determina a sequência de DNA ou RNA em tempo real (Figura 9). A plataforma Nanopore é uma tecnologia que propicia o sequenciamento de leituras longas e com alta performance. Esse sequenciamento tem registros de alguns problemas de rendimento, principalmente entupimento dos poros, mas algumas soluções estão sendo propostas.

![41587_2021_1108_Fig1_HTML](https://github.com/user-attachments/assets/658b890a-b44a-42f6-9ba5-5444a864d3b7)

Figura 9. Esquema do sequenciamento Oxford Nanopore.

## Sequenciamento PacBio
O sequenciamento PacBio usa a tecnologia de sequenciamento de molécula única em tempo real (SMRT). O centro do sequenciamento SMRT é a célula SMRT que é composta por muitos pequenos poros. As moléculas de DNA são imobilizadas nesses poros, a polimerase é incorporada em cada nucleotídeo e então, a luz é emitida. Isso possibilita que o nucleotídeo seja incorporado e que a incorporação seja medida em tempo real. Essa tecnologia possibilita o sequenciamento de leituras longas e com alta performance. 

## UNIX

O UNIX é um sistema operacional multitarefas e multiusários, ou seja, pode realizar mais de uma tarefa ao mesmo tempo de mais de um usário. Desta forma, o UNIX organiza as tarefas requisitadas por diferentes usuários e administra os recursos computacionais, impedindo a interferência entre estas tarefas. Os arquivos em uma plataforma UNIX são essenciais. Praticamente todos os componentes do UNIX estão armazenados em arquivos. Por exemplo, os programas e comandos executados por um sistema UNIX são arquivos contendo uma série de comandos que será executado pelo sistema.

Contudo, estes arquivos estão organizados por um sistema de diretórios (pastas). Estes diretórios, que pode ser entendido como uma árvore com diversas ramificações. Nós utilizamos a conotação de caminhos ou _path_, para indicar esta estrutura ramificada. Por exemplo: /home/riwama/cracas/genoma.fa e /home/riwama/sanguessugas/transcriptoma.fa.

Estes _paths_ indicam a localização dos arquivos genoma.fa e transcriptoma.fa, ilustrados na figura abaixo. Em vermelho, estão destacados a estrutura de diretórios.



![image](https://github.com/user-attachments/assets/46e900d5-8bc6-4a14-a112-b924758a5668)

**Comandos**

O UNIX possui um grande número de comandos que podem ser utilizados para navegação e gerenciamento do sistema, edição de arquivos e etc. Durante o primeiro tutorial deste workshop, você terá contato com alguns destes comandos. No entando, o alto número de comandos torna impossível abordar todos os comandos em apenas um dia de curso, ou até mesmo listar de forma exaustiva estes comandos. Este link (https://www.ufrgs.br/psicoeduc/chasqueweb/edu01027/comandos-linux.pdf) lista alguns dos principais comandos e descreve suas funções. Porém, o Google é sua melhor ferramenta. Se você precisar realizar uma tarefa específica procure no Google. Alguém com certeza já precisou fazer a mesma coisa que você!


