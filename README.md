# FDIG

**FDIG - Ferramentas Digitais para uma Ciência Aberta, reproduzível e com grandes quantidades de dados**

Repositório da disciplina optativa FDIG do Centro de Ciências da Natureza, *campus* Lagoa do Sino, UFSCar, disciplina espelho para o PPGCAm.

**Professores responsáveis: Alexandre Camargo Martensen (coordenador), Gabriel Lourenço Brejão e Eduardo Freitas Moreira**

**Será fornecida no primeiro semestre de 2020** Devido a pandemia do COVID-19, esse curso foi adiado e será ministrado no segundo semestre letivo de 2021 (início em Jan 22).

Página da disciplina: http://www.needs.ufscar.br/docencia/fdig

**Breve descrição da disciplina**

Estamos vivenciando uma mudança de paradigma na ciência, onde a ciência passa a ser cada vez mais baseada na colaboração entre cientistas organizados em redes, largamente alicerçada em grandes bancos de dados (“big data”), obtidos via de regra através de sensores remotos automatizados, que irão demandar ferramentas inovadoras de filtragem, organização, armazenamento e análise dos dados. Além disso, a ciência apresentará uma maior proporção de perguntas guiadas pelos dados (“data driven”) e uma menor parcela guiada por hipóteses, utilizará inteligência artificial, demandará conhecimento de linguagem de programação e de ferramentas digitais que ainda não são apresentadas aos nossos alunos em cursos regulares de graduação e de pós-graduação.

De forma a suprir essa carência, esta disciplina busca apresentar para os nossos alunos alguns destes novos paradigmas, municiando-os também com parte do ferramental necessário para a execução de tarefas dentro desta nova perspectiva. Especialmente irei abordar questões relacionadas a obtenção e organização de grandes bancos de dados, análise de grandes conjuntos de dados através de scripts, colaboração científica através do compartilhamento de dados, códigos para análises e programas, organização de projetos, escrita colaborativa, controle de versões de códigos e textos. Além disso, abordarei questões relacionadas à ciência aberta e revisão de artigos abertos, a questão de licenças e as discussões sobre os potenciais avanços das publicações científicas.

**Objetivos Gerais**

Ao final da disciplina o aluno terá sido exposto à práticas e ferramentas para a condução de ciência com grandes quantidades de dados (“big data”), baseada em análises com “scripts” e programação, colaborativa, com controle de versões, aberta e reprodutível. 

**Proposta de Ementa**

A ciência aberta, “Open Lab Notebooks (OLN)”, “pré-prints”, disponibilização dos dados, metadados, códigos, erros e acertos ao longo do processo de descoberta científica, publicação aberta; Obtenção de dados através de sensores remotos, armazenamento, manuseio, organização e recuperação de dados; A linguagem de programação R; desenvolvimento de scripts para organização, análise e geração de figuras e gráficos; boas práticas na computação científica; ferramentas digitais para fomentar a colaboração entre cientistas; formas de organização de projetos científicos; controle de versões - git e gitHub; “double blind” e “open peer review”; categorias de softwares livres e diferentes tipos de licenças; mídias sociais para divulgação de trabalhos, colaboração online, discussões científicas, perguntas e respostas na internet (por ex. StackOverflow, R-sig-geo, entre outros); presença online; perspectivas para a divulgação e comunicação científica nos próximos anos, entre outros temas relacionados.

**Cronograma proposto**

**Aula 01** - Apresentação e Introdução aos conteúdos que iremos tratar (teórica)
Assuntos:  Ciência aberta, dados abertos, metadados, códigos, erros e acertos ao longo do processo de descoberta científica, “pré-prints”, "peer review”, publicação aberta, Categorias de softwares livres e diferentes tipos de licenças

[Slides Aula 01 - Apresentação da disciplina](https://drive.google.com/open?id=1zVDjiZ49_9sy6X08SEPxc2X2ZwN-3WRa)

[Slides Aula 01 - Introdução](https://github.com/alecamar/FDIG/blob/master/Aula_02_Introducao.html)

[Introdução ao RStudio e RMarkdown (Rmd)](https://youtu.be/vjFmEGkpfFs)

Aproveite e se inscreva no canal do NEEDS do youtube!

**Aula 02** - Organização de projetos científicos, uso da linha de comando e aquisição de dados da internet (teórica e prática)
Assuntos: Como organizar um diretório, sub-diretórios, usar a linha de comando, como baixar dados pela internet de maneira organizada, criar um perfil no gitHub

[Slides Aula 02 - Organização](https://github.com/alecamar/FDIG/blob/master/Aula_02_Organizacao.html)

Trabalho 01 (individual): Linha de comando (criar diretorio, mover, copiar, etc - baseada na aula do pessoal do Software Carpentry - (http://swcarpentry.github.io/shell-novice/)

Trabalho 02 (individual): Baixar dados da internet através de script

**Aula 03** - Aquisição, organização, manipulação, arquivamento, disponibilização e recuperação de informações em bancos de dados (teórica e prática)
Assuntos:  Como organizar uma tabela de dados em forma *tidy*, ferramentas do *tidyverse* para manipulação de dados - http://hadley.nz/, SQL, Bancos de dados NoSQL, formatos para disponibilização de dados,

Leituras: 
A - Martone 2015 - (https://doi.org/10.1093/biosci/biv095) e links; B - Austin1 et al. 2017 - 10.1007/s00799-016-0178-2;

Trabalho 03 (todos): Fazer um blog post sobre o tema da aula (leituras + aula expositiva) no Wiki do curso, que posteriormente será publicado na internet.  
[Wiki](https://docs.google.com/document/d/1ofYoa8K2Inhz5gR_qv0TgSNzf52kHvnHbdAE-dKG__M/edit?usp=sharing)

**Aula 04** - Desenvolvimento de scripts para organização, análise e geração de figuras e gráficos (teórica e prática)
Assuntos: R, knitR, Markdown, RMarkdown, "literate programing", organização de scripts em pacotes no R, <a href="https://github.com/klmr/box">"box"</a>, etc.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">&quot;I wish I&#39;d left this code across scattered .R files instead of combining it into a package&quot; said no one ever <a href="https://twitter.com/hashtag/rstats?src=hash&amp;ref_src=twsrc%5Etfw">#rstats</a> <a href="http://t.co/udeNH4T67H">http://t.co/udeNH4T67H</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/611885584584441856?ref_src=twsrc%5Etfw">June 19, 2015</a></blockquote> 

Trabalho 04 (individual): Obtenção de dados na internet, filtragem, análise, geração de figuras e de um relatório de forma reproduzível e através de script.

**Aula 05** - Boas práticas na computação científica (teórica)
Assuntos: Data management, Digital Lab Notebooks (Jupyter, Rmd, etc), Workflow, controle de versão, etc.  

Leituras: 
A - Wilson et al. 2014: https://doi.org/10.1371/journal.pbio.1001745; B - Wilson et al. 2017: https://doi.org/10.1371/journal.pcbi.1005510; 
C - Shade & Teal 2015: https://doi.org/10.1371/journal.pbio.1002303; D - Osborne et al. 2014: https://doi.org/10.1371/journal.pcbi.1003506; e - https://dl.acm.org/doi/pdf/10.1145/3173574.3173606

Trabalho 05 (todos): Fazer um blog post sobre o tema da aula (leituras + aula expositiva) no Wiki do curso, que posteriormente será publicado na internet.
[Wiki](https://docs.google.com/document/d/1ofYoa8K2Inhz5gR_qv0TgSNzf52kHvnHbdAE-dKG__M/edit?usp=sharing)

**Aula 06** - Controle de versão - git e gitHub (teórica e prática)
Assuntos: git, gitHub, push, pull, fork, clone

Trabalho 06 (individual): Trabalho git e gitHub

**Aula 07** - Discussão de propostas de projetos

Assuntos: Discussão sobre as idéias de projetos com os alunos e caminhos a serem seguidos de obtenção de dados, análise de dados, apresentação, etc.

Trabalho 07 (todos): Ver diversos repositórios no gitHub e ver como se escrever um bom README, postar no página na Wiki do curso, argumentando quais são os principais pontos positivos e negativos. Será publicado na internet posteriormente.
[Wiki](https://docs.google.com/document/d/1ofYoa8K2Inhz5gR_qv0TgSNzf52kHvnHbdAE-dKG__M/edit?usp=sharing)

Trabalho 08: Criar um repositório no gitHub (com README explicando o assunto que será abordado no projeto, e demais informações relevantes)

**Aula 08** - Ferramentas digitais para fomentar a colaboração entre cientistas (teórica e prática)

Assuntos: gitHub, networks, apps para redação científica

Trabalho 09 (individual): Entrar nos perfis dos colegas, fazer comentários, pull/push com correções, etc. 

**Aula 09** - Mídias sociais para divulgação de trabalhos, colaboração online, discussões científicas (Teórico e Prática)

Assuntos: Twitter, grupos do Mendeley, midias sociais, wikis, blogs, sites  

Trabalho 10 (todos): Montar um grupo no Mendeley e colocar textos sobre os temas abordados em sala (nome do grupo FDIG)

**Aula 10** - Presença online (Teórica e Prática)

Assuntos: Como fazer um texto de divulgação científica - super curto, curto, médio e longo, #tags, mídias sociais, etc

Trabalho 11: uma msg no twiter, uma mensagem no facebook, um blog post (médio tamanho) sobre o trabalho que estão desenvolvendo na disciplina, usando #FDIG2021, #FDIG, #UFSCAR e #UFSCAR_LS, #PPGCAm (10% da nota)

Discussão sobre temas não abordados que serão explorados na aula 12. 

Trabalho 12 (individual): Fazer um vídeo "curto" explicando o que é, como usar, para que serve, etc. Será postado na playlist do curso (20% da nota).

**Aula 11** - Discussão andamento de projetos

Assuntos: Avaliar o andamento dos projetos dos alunos

**Aula 12** - Discussão sobre temas não abordados (Alunos já assistiram os vídeos dos colegas)

Assuntos: Temas não abordados

**Aula 13** - Projeto

Assuntos: Disponível para os alunos realizarem os projetos, disponível para dúvidas.

**Aula 14** - Dúvidas e discussão do andamento dos projetos

Assuntos: Disponível para os alunos tirarem dúvidas sobre as análises do projeto

**Aula 15** - Sorteio da ordem de apresentação dos projetos e apresentação dos projetos

Assuntos: Apresentação dos projetos (50% da nota)

**Aula 16** - Apresentação dos projetos

Assuntos: Apresentação dos projetos (50% da nota)

**Aula 17** - Avaliações e confraternização

Assuntos: Avaliações

**Avaliação**

A avaliação da disciplina será feita da seguinte maneira:

- 20% participação em aula (10 trabalhos)
- 20% trabalho sobre temas não abordados
- 10% Divulgação científica
- 50% projeto final
