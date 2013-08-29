# git-scm

## Para que serve?

Controlar versões de arquivos de forma distribuída.

---

## O que é?

O Git é um Sistema de Controle de Versão Distribuído. (Distributed Version Control System ou DVCS). Em um DVCS, os clientes não apenas fazem cópias das últimas versões dos arquivos: eles são cópias completas do repositório. Assim, se um servidor falha, qualquer um dos repositórios dos clientes pode ser copiado de volta para o servidor para restaurá-lo. Cada checkout (resgate) é na prática um backup completo de todos os dados.

O Git foi modelado do ponto de vista de um sistema de arquivos e não apenas de um gerenciador de código fonte.

* [Git | Wikipedia PT](https://pt.wikipedia.org/wiki/Git)

* [Uma Breve História do Git | Pro Git](http://git-scm.com/book/pt-br/Primeiros-passos-Uma-Breve-Hist%C3%B3ria-do-Git)

* [Sobre Controle de Versão | Pro Git](http://git-scm.com/book/pt-br/Primeiros-passos-Sobre-Controle-de-Vers%C3%A3o)


---

## Objetivos

* Velocidade

* Design simples

* Suporte robusto a desenvolvimento não linear (milhares de branches paralelos)

* Totalmente distribuído

* Capaz de lidar eficientemente com grandes projetos como o kernel do Linux (velocidade e volume de dados)

---

## Principais características e diferenças dos demais sistemas de controle de versão

* [Noções Básicas de Git | Pro Git](http://git-scm.com/book/pt-br/Primeiros-passos-No%C3%A7%C3%B5es-B%C3%A1sicas-de-Git)

  * Snapshots, E Não Diferenças

    * O Git rastreia todas as alterações ocorridas

  * Quase Todas Operações São Locais

  * Git Tem Integridade

    * A forma com que o Git identifica/versiona as alterações, utilizando checksum (algoritmo SHA-1), ou comumente chamado hash, garante a integridade e unicidade das alterações, com isso reduzindo inumeros problemas na hora de mesclar (merge) conteúdos dos arquivos, atividades executadas comumente em projetos.

  * Git Geralmente Só Adiciona Dados

  * Os Três Estados


---

## Integração com ferramentas

### Java

#### IDE

* [Eclipse](http://www.eclipse.org/)

  * A partir do [Eclipse Juno SR2 (4.2.2)](http://www.eclipse.org/downloads/packages/release/juno/sr2) - o Eclipse vem com o plugin do eGit junto

  * [EGit | GitHub Eclipse](https://eclipse.github.com/) - para versões anteriores ao Eclipse 4.2.2, necessário instalar este plugin para utilizar o Git diretamente dentro do Eclipse

* [IntellyJ IDEA | Jetbrains](http://www.jetbrains.com/idea/) - possui suporte integrado para Git

* [Netbeans](https://netbeans.org/) - possui suporte integrado para Git


#### Build e Integração Contínua

* [Jenkins CI](http://jenkins-ci.org/) | [git plugin](https://wiki.jenkins-ci.org/display/JENKINS/Git+Plugin)

* [Hudson CI](http://hudson-ci.org/) | [Git plugin](http://wiki.hudson-ci.org/display/HUDSON/Git+Plugin)

* [Atlassian Bamboo](https://www.atlassian.com/software/bamboo) - a ferramenta disponibiliza junto um suporte para uso do [Git | Bamboo Docs](https://confluence.atlassian.com/display/BAMBOO/Git)


### .Net

* Notícia sobre o início do suporte da Microsoft ao Git 

  * [Visual Studio 2012 ganha suporte a Git | InfoQ Br](http://www.infoq.com/br/news/2013/02/vs2012-suporte-git)

  * [Git init VS | Brian Harry's blog : MSDN](https://blogs.msdn.com/b/bharry/archive/2013/01/30/git-init-vs.aspx)

  * [TFS Now Integrated with Git | Visual Studio Magazine](http://visualstudiomagazine.com/articles/2012/08/13/tfs-now-integrated-with-git.aspx) (13/08/2012)


* [Visual Studio 2012 update 3](https://www.microsoft.com/en-us/download/details.aspx?id=39305) | [Visual Studio Tools for Git](http://visualstudiogallery.msdn.microsoft.com/abafc7d6-dcaa-40f4-8a5e-d6724bdb980c) - Free

* [Getting Started with Git in Visual Studio and Team Foundation Service | MSDN](https://blogs.msdn.com/b/visualstudioalm/archive/2013/01/30/getting-started-with-git-in-visual-studio-and-team-foundation-service.aspx)

* [Use Git and Xcode with TFS](http://tfs.visualstudio.com/en-us/learn/use-git-and-xcode-with-tfs.aspx)


### Apple

* [XCode](https://developer.apple.com/technologies/tools/whats-new.html) - possui suporte integrado para Git

  * [Xcode iPhone beginner projects with GitHub integration | Leniel Macaferi's blog](http://www.leniel.net/2011/08/xcode-iphone-beginner-projects-git.html)


---

## Suporte comercial / empresarial

* Suporte comercial no Brasil, desconhecido se existe

### Atlassian

* [Atlassian Stash](https://www.atlassian.com/software/stash/overview) - Enterprise Git Repository Management | [Pricing](https://www.atlassian.com/software/stash/pricing)

* [Git Tutorials and Training | Atlassian](https://www.atlassian.com/git)

### Github

* [GitHub Training](http://training.github.com/)

* [GitHub Enterprise](https://enterprise.github.com/) - Bring GitHub to work. The best way to build and ship software, on your servers. | [Pricing](https://enterprise.github.com/pricing)

* [GitHub Enterprise Features](http://teach.github.com/articles/github-enterprise-features/)


---

## Quem usa?

### listados no : git-scm

#### empresas

* [Google](http://www.google.com) : projetos OpenSource no [GitHub](https://github.com/google)

* [Facebook](https://www.facebook.com/) : projetos OpenSource no [GitHub](https://github.com/facebook)

* [Microsoft](https://www.microsoft.com/) : [ASP.net](https://aspnetwebstack.codeplex.com/) no CodePlex

  * O [CodePlex](https://www.codeplex.com/) também possibilita a [escolha de repositório Git](https://codeplex.codeplex.com/wikipage?title=Using%20Git%20with%20CodePlex&referringTitle=Source%20Control) para o versionamento de código dos projetos hospedados lá.

  * Projetos OpenSource do time do Windows Azune SDK no [GitHub](http://windowsazure.github.io/)

* [Twitter](https://twitter.com/) : projetos OpenSource no [GitHub](https://github.com/twitter)

* [LinkedIn](http://www.linkedin.com/) : projetos OpenSource no [GitHub](https://github.com/linkedin)

* [NETFLIX](http://netflix.com) : projetos OpenSource no [GitHub](https://github.com/netflix)


#### projetos

* [The Perl Programming Language](http://www.perl.org/) : repositório próprio de [git](http://perl5.git.perl.org/perl.git)

* [PostgreSQL](http://www.postgresql.org/) : repositório próprio de [git](http://git.postgresql.org/gitweb/)

* [Android](http://www.android.com/) : repositório próprio de [git](https://android-review.googlesource.com/#/q/status:open,n,z) 

* [Linux Kernel](https://www.kernel.org/) : repositório próprio de [git](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git)

* [Ruby on Rails](http://rubyonrails.org/) : repositório no [GitHub](https://github.com/rails/rails)

* [QT](http://qt-project.org/) : repositório no [Gitorious](https://qt.gitorious.org/)

* [Gnome](https://www.gnome.org/) : repositório próprio de [git](https://git.gnome.org/browse/)

* [Eclipse](http://eclipse.org/) : repositório próprio de [git](http://git.eclipse.org/c/)

* [KDE](http://kde.org/) : repositório próprio de [git](http://quickgit.kde.org/)

* [The X.Org Foundation](http://www.x.org/wiki/) : repositório git no [freedesktop.org](http://cgit.freedesktop.org/), conforme verificado nesta [documentação](http://www.x.org/wiki/Development/BuildingX/?action=show&redirect=Development%2Fgit) para os desenvolvedores


### não listados no : git-scm

#### empresas

* [SAP](http://www.sap.com/) : projetos OpenSource no [GitHub](http://sap.github.io/)

* [Joyent](https://www.joyent.com/) : projetos OpenSource no [GitHub](https://github.com/joyent)

* [NASA](http://www.nasa.gov/) : projetos OpenSource no [GitHub](https://github.com/nasa)

* [BBC News](http://www.bbc.co.uk/news/) : projetos OpenSource no [GitHub](https://github.com/BBC-News)

* [Abril](http://www.abril.com.br/) : projetos OpenSource no [GitHub](https://github.com/abril)

* [Globo.com](http://www.globo.com/) : projetos OpenSource no [GitHub](https://github.com/globocom)

#### projetos

* [Spring Source](http://www.springsource.org/) : projetos OpenSource no [GitHub](https://github.com/SpringSource)

* [JBoss Community](https://community.jboss.org/) : projetos OpenSource no [GitHub](https://github.com/jbossorg)

* [Node.js](http://nodejs.org/) : projeto no [GitHub](https://github.com/joyent/node)


#### Governo : Brasil

* [PloneGovBr](http://www.softwarelivre.gov.br/plone) : projetos OpenSource no [GitHub](https://github.com/plonegovbr)

* [DadosGovBr](http://dados.gov.br/) : projetos OpenSource no [GitHub](https://github.com/dadosgovbr)

* [Demoiselle](http://www.frameworkdemoiselle.gov.br/) - é um conjunto de seis projetos, sendo cinco de software e um processo de desenvolvimento (Framework em Java criado pelo [SERPRO](http://www.serpro.gov.br/)). Projetos OpenSource no [GitHub](https://github.com/demoiselle)


#### Governo : Estados Unidos

* [The White House](http://www.whitehouse.gov/) | [Developers](http://www.whitehouse.gov/developers) : projetos OpenSource no [GitHub](https://github.com/WhiteHouse)
