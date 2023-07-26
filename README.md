# Lista de Ferramentas

Lista de ferramentas para modelagem, documentação e desenvolvimento de sistemas e bancos de dados.


```
Critérios para uma ferramenta entrar nesta lista:
1. São materiais de suporte ao projeto e desenvolvimento de sistemas e bancos de dados.
2. Material foi ou poderá ser usado em sala de aula.
3. Material foi usado durante a pós do PPGCA-Unisinos.
4. Recomendações de tercerios (professores, técnicos e alunos) após avaliação.
5. A lista possui ferramentas open source e proprietárias.
```


[1. Modelagem UML (Unified Modeling Language), diagramas UML](#1-modelagem-uml-diagramas-uml-bpmn)<br>
[2. Modelagem de banco de dados, DER (Diagrama Entidade Relacionamento)](#2-modelagem-de-banco-de-dados-diagrama-entidade-relacionamento)<br>
[3. Bancos de dados](#3-bancos-de-dados)<br>
[4. Administração de banco de dados](#4-administração-de-banco-de-dados)<br>
[5. IDE (Integrated Development Environment)](#5-ides)<br>
[6. Editores de códigos](#6-editores-de-códigos)<br>
[7. Prototipação, wireframe, mockups](#7-prototipação-wireframe-mockups)<br>
[8. Git, e versionamento](#8-git-e-versionamento)<br>
[9. Gestão de tickets](#9-gestão-de-tickets)<br>
[10. Notebooks](#10-notebooks)<br>
[11. Distro Linux p/ devs](#11-distro-linux-p-devs)<br>
[12. Desenvolvimento mobile](#12-desenvolvimento-mobile)<br>
[13. Testes de API (Application Programming Interface) REST (Representational State Transfer)](#13-testes-de-api-rest)<br>
[14. Armazenamento distribuído, bancos distribuídos, sistemas de arquivos distribuídos](#14-armazenamento-distribuído-bancos-distribuídos-file-systems-distribuídos)<br>
[15. Blockchain](#15-blockchain)<br>
[16. Algoritmos](#16-algoritmos)<br>
[17. DAG (Directed Acyclic Graph), P2P (Peer-to-Peer)](#17-dag-directed-acyclic-graph-p2p-peer-to-peer)<br>
[18. Low code, gerador de código, CASE (Computer-Aided Software Engineering)](#18-low-code-gerador-de-código-case-computer-aided-software-engineering)<br>
[19. Javascript](#19-javascript)<br>
[20. Mapas, GIS (Geographic Information System), GPS (Global Positioning System) e Georreferência](#20-mapas-geo-gis-gps-e-georreferência)<br>
[21. Visualização de dados](#21-visualização-de-dados)<br>
[22. Machine learning](#22-machine-learning)<br>
[23. Documentação](#23-documentação)<br>
[24. Gerador de dados de testes, dados artificiais](#24-gerador-de-dados-de-testes-dados-artificiais)<br>
[25. Instaladores](#25-instaladores)<br>
[26. Gerenciamento de projeto, Gantt e Kanban](#26-gerenciamento-de-projeto-gantt-e-kanban)<br>
[27. RAD](#27-rad-rapid-application-development)<br>
[28. Diversos](#28-diversos)<br>
[29. Questões para seleção de linguagens e ferramentas](#questões-para-seleção-de-linguagens-e-ferramentas)<br>


---
## 1. Modelagem UML, diagramas UML, BPMN

| Ferramenta   | URL |
| ------------ | --- |
| Visual Paradigm Community Edition |  https://www.visual-paradigm.com/solution/freeumltool/ |
| Astah para alunos |  https://astah.net/products/free-student-license/ |
| Astah UML | https://astah.net/downloads/ |
| Modelio |  https://www.modelio.org/index.htm |
| Star UML |  https://staruml.io/ |
| WhiteStarUML  | https://sourceforge.net/projects/whitestaruml/ e https://github.com/dimon4ezzz/whitestaruml|
| Violet UML Editor |  https://sourceforge.net/projects/violet/ |
| Plant UML |  https://plantuml.com/ |
| ERDPlus | https://erdplus.com/ |
| N Class |  https://nclass.sourceforge.net/ |
| Bizagi |  https://www.bizagi.com/en/platform/try-modeler |


Outras ferramentas de modelagem UML https://en.wikipedia.org/wiki/List_of_Unified_Modeling_Language_tools

[Volta ao sumário](#lista-de-ferramentas)<br>

---
## 2. Modelagem de banco de dados, diagrama entidade relacionamento

| Ferramenta   |  URL |
| ------------ |  --- |
| MySQL Workbench  | https://dev.mysql.com/downloads/workbench/    |
| dbForge Studio for MySQL  | https://www.devart.com/dbforge/mysql/studio/    |     
| ERDPluss     |   https://erdplus.com/faq    |
| DbGate       |  https://dbgate.org/  |     
| Valentina Studio  | https://www.valentina-db.com/en/valentina-studio-overview |
| Beekeeper studio  | https://www.beekeeperstudio.io/ |
| Draw IO |  https://www.drawio.com/ |
| DBeaver Community | https://dbeaver.io/download/    |
| BR Modelo |  https://www.brmodeloweb.com/lang/pt-br/index.html |

[Volta ao sumário](#lista-de-ferramentas)<br>

---
## 3. Bancos de dados

| Ferramenta   |  URL |
| ------------ |  --- |
| Griddb |  https://griddb.net/en/   |
| Convenant SQL  | https://covenantsql.io/ |
| BlockchainSQL  | https://blockchainsql.io/ e https://sphere10.com/products/blockchainsql |
| OrbitDB | https://github.com/orbitdb |
| YDB |  https://ydb.tech/ |
| OurSQL  | https://github.com/gelembjuk/oursql |
| QRI |  https://qri.io/ |
| InfluxData  | https://www.influxdata.com/ |
| Database of Database  | https://dbdb.io/ |
| Db-fiddle |  https://www.db-fiddle.com/ |
| db 4 free |  https://www.db4free.net/index.php?language=pt |

[Volta ao sumário](#lista-de-ferramentas)<br>

```
Observação: Alguns bancos de dados (citados acima) comentados no PPGCA e/ou usados no projeto MRPA.
```


```
Site para treinamento com SQL: 
https://www.db-fiddle.com/
```


### 3.1 Bancos de dados "empacotados" com Apache e PHP

Recomendados para uso em sala de aula (MySQL ou MariaDB), estes podem ser instalados no Windows ou Linux via pacotes como XAMPP, WAMP ou Laragon

| Ferramenta   |  URL |
| ------------ |  --- |
| MariaDB | https://mariadb.org/download/?t=mariadb&o=true&p=mariadb&r=10.5.13&os=windows&cpu=x86_64&pkg=msi   |
| MySQL | https://dev.mysql.com/downloads/mysql/ |
| XAMPP  | https://www.apachefriends.org/ |
| WAMP | https://www.wampserver.com/en/download-wampserver-64bits/ |
| Laragon | https://laragon.org/download/index.html |


```
Observação: Laragon é um dos mais simples para usar!
```

[Volta ao sumário](#lista-de-ferramentas)<br>

---
## 4. Administração de banco de dados

| Ferramenta   |  URL |
| ------------ |  --- |
| MySQL Workbench    | https://dev.mysql.com/downloads/workbench/ |
| HeidiSQL |  https://www.heidisql.com/download.php |
| DBeaver Community | https://dbeaver.io/download/    |
| Oracle SQL Developer  | https://www.oracle.com/database/sqldeveloper/ |
| MS SQL Management Studio  | https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16 |
| SQL Manager |  https://www.sqlmanager.net/tools/free |
| phpMyAdmin |  https://www.phpmyadmin.net/ |
| SQLyog Community  | https://github.com/webyog/sqlyog-community/wiki/Downloads |
| Toad for MySQL |  https://www.quest.com/products/toad-edge/toad-edge-mysql.aspx |

[Volta ao sumário](#lista-de-ferramentas)<br>

---
## 5. IDEs

| Ferramenta   |  URL |
| ------------ |  --- |
| Codeblocks   | https://www.codeblocks.org/ |
| Microsoft Visual Studio Community  | https://visualstudio.microsoft.com/pt-br/vs/community/|
| Embarcadero Delphi |  https://www.embarcadero.com/products/delphi/starter |
| Embarcadero C++ Builder   | https://www.embarcadero.com/products/cbuilder/starter |
| Embarcadero Dev-C++ | https://www.embarcadero.com/free-tools/dev-cpp |
| IDE Komodo  | https://www.activestate.com/products/komodo-ide/ |
| Oracle JDeveloper  | https://www.oracle.com/application-development/technologies/jdeveloper.html |
| Spyder |  https://www.spyder-ide.org/ |
| QT designer  | https://www.qt.io/download |
| QT Creator  | https://build-system.fman.io/qt-designer-download |
| Code Lite | https://codelite.org/ |
| BlueJ  | https://www.bluej.org/ |
| Dev-pascal  | http://bloodshed.net/Dev-Pascal |
| U++ Framework  | https://www.ultimatepp.org/ |
| Eric Python IDE  | http://eric-ide.python-projects.org/index.html |
| Android Studio  | https://developer.android.com/studio |
| Codux |  https://www.codux.com/ |
| Glade IDE  | https://gitlab.gnome.org/GNOME/glade |
| Gambas IDE  | https://gambas.sourceforge.net/en/main.html |
| Flagship  | https://www.fship.com/ |
| Codux  | https://www.codux.com/ |
| Flutlab  | https://flutlab.io/ |
| Wavemaker  | https://www.wavemaker.com/get-started/ |
| Windev  | https://windev.com/windevmobile/WM-Express.htm |
| Alpha  | https://www.alphasoftware.com/alpha-software-low-code-software-pricing |
| Wakanda  | https://wakanda.github.io/download.html |

[Volta ao sumário](#lista-de-ferramentas)<br>


### 5.1. Turbo Pascal, Delphi, Lazarus e suas variações

| Ferramenta   |  URL |
| ------------ | --- |
| Lazarus      |  https://www.lazarus-ide.org/index.php |
| CodeTyphon Studio | https://www.pilotlogic.com/sitejoom/ |
| Free Pascal  | https://www.freepascal.org/download.html |
| LAMW: Lazarus Android Module Wizard  | https://github.com/jmpessoa/lazandroidmodulewizard |
| Smart Mobile Studio  | https://smartmobilestudio.com/ |
| Elevate Web Builder  | https://www.elevatesoft.com/products?category=ewb |


Outras IDEs: https://en.wikipedia.org/wiki/Comparison_of_integrated_development_environments

[Volta ao sumário](#lista-de-ferramentas)<br>



---
## 6. Editores de códigos

| Ferramenta    | URL |
| ------------  | --- |
| Visual Studio Code  | https://code.visualstudio.com/ |
| Notepad++  | https://notepad-plus-plus.org/downloads/ |
| Pulsar  | https://github.com/pulsar-edit/pulsar |
| Light Table  | http://lighttable.com/ |
| Geany  | https://geany.org/ |

[Volta ao sumário](#lista-de-ferramentas)<br>




---
## 7. Prototipação, Wireframe, Mockups

| Ferramenta   |  URL |
| ------------ |  --- |
| Evolus Project Pencil  | https://pencil.evolus.vn/ |
| Glade |  https://gitlab.gnome.org/GNOME/glade |
| Balsamiq  | https://balsamiq.com/buy/#cloud |
| Justinmind  | https://www.justinmind.com/pricing |
| Figma |  https://www.figma.com/pricing/ |
| FlutterFlow  | https://flutterflow.io/ |
| Penpot | https://penpot.app/ |


[Volta ao sumário](#lista-de-ferramentas)<br>

---
## 8. Git e versionamento

| Ferramenta   |  URL |
| ------------ |  --- |
| Github Desktop   | https://desktop.github.com/    |
| GitKranken |  https://www.gitkraken.com/ |
| Source Tree  | https://www.sourcetreeapp.com/ |
| Tortoise | https://tortoisegit.org/ |

Outros clientes para Windows: https://git-scm.com/download/gui/windows

[Volta ao sumário](#lista-de-ferramentas)<br>



---
## 9. Gestão de tickets

| Ferramenta   | URL |
| ------------  | --- |
| OsTicket  | https://osticket.com/ |
| Mantis Bug Tracker | https://www.mantisbt.org/ |


[Volta ao sumário](#lista-de-ferramentas)<br>



---
## 10. Notebooks

| Ferramenta   | URL |
| ------------ | --- |
| Google Colaboratory | https://colab.research.google.com/ |
| Jupiter notebooks  | https://jupyter.org/try |
| Anaconda |  https://anaconda.org/ |
| Terraform |  https://app.terraform.io/public/signup/account |
| Paperspace | https://www.paperspace.com/pricing |
| Deepnote |  https://deepnote.com/pricing |
| Notable |  https://noteable.io/pricing/  |
| Kaggle |  https://www.kaggle.com/code |
| Replit |  https://replit.com/ |

[Volta ao sumário](#lista-de-ferramentas)<br>


---
## 11. Distro Linux p/ devs

Página comentando várias linux sob o ponto de vista do desenvolvimento, https://www.vpsserver.com/best-linux-distros-for-programming/.

[Volta ao sumário](#lista-de-ferramentas)<br>

---
## 12. Desenvolvimento Mobile

| Ferramenta     | URL |
| ------------  | --- |
| Android Studio |  https://developer.android.com/studio |
| LAMW (Lazarus Android Module Wizard)  | https://github.com/jmpessoa/lazandroidmodulewizard |
| Xamarin |  https://visualstudio.microsoft.com/pt-br/xamarin/ |
| B4A |  https://www.b4x.com/b4a.html |
| Tizen |  https://www.tizen.org/ |
| Microsoft Visual Studio Community | https://visualstudio.microsoft.com/pt-br/vs/community/|
| Delphi |  https://www.embarcadero.com/products/delphi/starter |
| C++ Builder  | https://www.embarcadero.com/products/cbuilder/starter |
| Modular |  https://www.kodular.io/ |
| Kalipso |  https://www.kalipsostudio.com/ |
| Viziapps | https://viziapps.com/features-pricing |

[Volta ao sumário](#lista-de-ferramentas)<br>




---
## 13. Testes de API Rest

| Ferramenta   | URL |
| ------------ | --- |
| Insomnia      |  https://insomnia.rest/   |
| Postman |  https://www.postman.com/downloads/ |
| Swagger |  https://swagger.io/ |

[Volta ao sumário](#lista-de-ferramentas)<br>

---
## 14. Armazenamento distribuído, bancos distribuídos, file systems distribuídos

| Ferramenta   | URL |
| ------------ | --- |
| IPFS          | https://ipfs.tech/ |
| SIA |  https://sia.tech/learn |
| StorJS  | https://www.storj.io/ |
| OrbitDB  | https://github.com/orbitdb |
| Swarm |  https://ethersphere.github.io/swarm-home/# |
| Keops |  https://keops.cc/ |

[Volta ao sumário](#lista-de-ferramentas)<br>



---
## 15. Blockchain

| Ferramenta   |  URL |
| ------------ |  --- |
| Multichain |  https://www.multichain.com/developers/ |
| Openchain |  https://docs.openchain.org/en/latest/index.html <br> https://github.com/openchain/docker <br> https://github.com/openchain |
| Blockchain BaaS  | https://www.kaleido.io/ |
| Low Code Blockchain  | https://sparkster.me/# |
| Covenant SQL  | https://covenantsql.io/ |
| Credenciais  | https://www.blockcerts.org/ |
| BlockchainSQL  | https://blockchainsql.io/ <br> https://sphere10.com/products/blockchainsql |
| BSN Spartan  | https://spartan.bsn.foundation/ |
| BSN service network  | https://bsnbase.io/g/main/index |
| Hyperledger Fabric  | https://hyperledger-fabric.readthedocs.io/en/release-2.2/whatis.html |
| Hathor  | https://hathor.network/ |
| Nethereum blockchain  | https://nethereum.com/ <br> https://github.com/Nethereum/Nethereum.UI.Desktop |
| Embark  | https://framework.embarklabs.io/ |

[Volta ao sumário](#lista-de-ferramentas)<br>


---
## 16. Algoritmos

| Ferramenta       | URL |
| ------------  | --- |
| Visual G3            | https://visualg3.com.br/    |
| algorithm-visualizer  | https://algorithm-visualizer.org/ |
| Flowchartocode | http://www.cocodex.com/flowchart-to-code/index.html |
| Flowgorithm  | http://www.flowgorithm.org/index.html | 

[Volta ao sumário](#lista-de-ferramentas)<br>


---
## 17. DAG (directed acyclic graph), P2P (Peer-to-peer)

| Ferramenta      | URL |
| ------------  | --- |
| IPFS  | https://docs.ipfs.tech/reference/http/api/ |
| PeerJS  | https://peerjs.com/ |
| Dat  | https://dat-ecosystem.org/ |

[Volta ao sumário](#lista-de-ferramentas)<br>


---
## 18. Low Code, Gerador de código, CASE (Computer-aided software engineering)

| Ferramenta      | URL |
| ------------  | --- |
| Genexus          | https://www.genexus.com/pt/  |
| Softwell Maker  | https://softwell.com.br/ |
| Outsystems  | https://www.outsystems.com/pricing-and-editions/ |
| Scriptcase | https://www.scriptcase.com.br/ |
| Low code  | https://www.joget.org/ |
| Visual Lansa  | https://lansa.com/products/visual-lansa/ |

[Volta ao sumário](#lista-de-ferramentas)<br>


---
## 19. Javascript

Algumas bibliotecas/frameworks interessantes...

| Ferramenta      | URL |
| ------------  | --- |
| GrapeJS  | https://grapesjs.com/    |
| Leafleetjs  | https://leafletjs.com/examples/quick-start/ |

[Volta ao sumário](#lista-de-ferramentas)<br>



---
## 20. Mapas, Geo, GIS, GPS e Georreferência

| Ferramenta       | URL |
| ------------  | --- |
| GeoPHP  | https://geophp.net/ |
| Mapbender  | https://mapbender.org/en/ |
| GeoServer  | https://geoserver.org/ |
| Mapserver  | https://mapserver.org/ |
| Polymaps  | http://polymaps.org/ex/ |
| Leafleetjs | https://leafletjs.com/examples/quick-start/ |
| TerraBrasilis  | http://terrabrasilis.dpi.inpe.br/servicos-disponiveis/ |
| Traccar  | https://www.traccar.org/geofences/ |

[Volta ao sumário](#lista-de-ferramentas)<br>

---
## 21. Visualização de dados

| Ferramenta      | URL |
| ------------  | --- |
| Rawgraphs   | https://www.rawgraphs.io/    |
| Grafana |  https://grafana.com/oss/graphite/ |
| MS Power BI  | https://powerbi.microsoft.com/en-au/ |
| Looker Studio  | https://lookerstudio.google.com/overview |
| Scimago  Graphica  | https://www.graphica.app/ |

[Volta ao sumário](#lista-de-ferramentas)<br>


---
## 22. Machine learning

| Ferramenta       | URL |
| ------------  | --- |
| MindsDB |    https://mindsdb.com/mariadb-machine-learning   |
| Anaconda |  https://anaconda.org/anaconda/notebook |
| PHP-ML |  https://php-ml.readthedocs.io/en/latest/ |

[Volta ao sumário](#lista-de-ferramentas)<br>


---
## 23. Documentação

| Ferramenta      | URL |
| ------------  | --- |
| Doxygen |  https://www.doxygen.nl/    |
| Sphinx-doc | https://www.sphinx-doc.org/en/master/index.html |
| DelphiCodeToDoc  | https://dephicodetodoc.sourceforge.net/ |
| NDoc  | https://ndoc.sourceforge.net/ |
| Confluence | https://www.atlassian.com/software/confluence |

[Volta ao sumário](#lista-de-ferramentas)<br>




---
## 24. Gerador de dados de testes, dados artificiais

| Ferramenta       | URL |
| ------------  | --- |
| Mostly | https://mostly.ai/ |
| Online Data Generator | https://www.onlinedatagenerator.com/ |
| Generate Data  | https://generatedata.com/ |
| Mockaroo | https://www.mockaroo.com/ |

Outras listas: Ferramentas para análise estática de código: https://github.com/analysis-tools-dev/static-analysis#csharp

[Volta ao sumário](#lista-de-ferramentas)<br>



---
## 25. Instaladores

| Ferramenta       | URL |
| ------------  | --- |
| Inno Setup  | https://jrsoftware.org/isdl.php |
| NSIS  | https://nsis.sourceforge.io/Main_Page |
| IzPack  | http://izpack.org/ |

[Volta ao sumário](#lista-de-ferramentas)<br>

---
## 26. Gerenciamento de projeto, Gantt e Kanban

| Ferramenta      | URL |
| ------------  | --- |
| Project Libre  | https://sourceforge.net/projects/projectlibre/ |
| GanttProject  | https://www.ganttproject.biz/ |
| Kanboard  | https://kanboard.org/ |
| dotProject  | https://dotproject.net/ |
| Zentao  | https://www.zentao.pm/page/zentao-pricing.html |
| qdPM  | https://qdpm.net/ |

[Volta ao sumário](#lista-de-ferramentas)<br>



---
## 27. RAD (Rapid Application Development)

| Ferramenta       | URL |
| ------------  | --- |
| AX |  http://www.ax-framework.com/download.php |
| Embarcadero Rad Studio  | https://www.embarcadero.com/products/rad-studio |
| Radzen  | https://www.radzen.com/download/#windows |
| Scriptcase  | https://www.scriptcase.com.br/ |
| Clarion  | https://store.softvelocity.com/collections/clarion-new-licenses |
| Codecharge  | http://www.codecharge.com/products/index.php |
| 4D  | https://br.4d.com/ |
| Servoy  | https://servoy.com/pricing |
| Caspio  | https://www.caspio.com/features/ |
| Kalipso | https://www.kalipsostudio.com/ |
| Alpha | https://www.alphasoftware.com/alpha-software-low-code-software-pricing |
| PHP RAD | https://phprad.com/ |
| Adianti Builder  | https://www.adiantibuilder.com.br/home |
| Glade | https://gitlab.gnome.org/GNOME/glade |
| Open Xava | https://www.openxava.org/en/ate/rad-java |
| Cuba Studio | https://www.jmix.io/cuba-platform/tools/ |
| Microsoft Visual Studio | https://visualstudio.microsoft.com/pt-br/ |
| Mono Develop | https://www.monodevelop.com/ |
| Pure Basic | https://www.purebasic.com/ |
| Qt Creator | https://www.qt.io/product/development-tools |
| U++ Framework | https://www.ultimatepp.org/ |
| Anvil | https://anvil.works/ |
| Lazarus | https://www.lazarus-ide.org/ |
| Xcode | https://developer.apple.com/xcode/ |
| Lianja App Builder | https://www.lianja.com/overview/lianja-app-builder |

[Volta ao sumário](#lista-de-ferramentas)<br>




---
## 28. Diversos

Compilador Xbase https://harbour.github.io/about <br>
XSharp https://www.xsharp.eu/ <br>
Xailer https://www.xailer.com/wp/en/start/ <br>
TCL TK https://www.tcl.tk/ <br> 
Tersus http://www.tersus.com/ <br> 
Ranking de bancos de dados https://db-engines.com/en/ranking <br>
Ranking de linguagens de programação https://www.tiobe.com/tiobe-index/ <br>
Eiffel https://www.eiffel.org/doc/eiffelstudio <br> 

[Volta ao sumário](#lista-de-ferramentas)<br>

<!--

---
## 29. Projetos mortos

Appcelerator https://www.axway.com/en/appcelerator-end-of-life

Atom https://github.blog/2022-06-08-sunsetting-atom/ 


-->



---
# Questões para seleção de linguagens e ferramentas

Uma pequena lista de perguntas que poderão nortear o processo de escolha de uma determinada linguagem, IDE ou RAD.

1. A ferramenta, RAD ou IDE usam alguma linguagem lista no índice Tiobe ?<br>
https://www.tiobe.com/tiobe-index/ <br>
ou <br>
https://survey.stackoverflow.co/2023/#overview <br>
1.1. Nos últimos 10 anos essa linguagem mudou de posição se aproximando para os níveis mais altos?<br>
2. Quantas pessoas você conhece na sua cidade ou bairro que trabalham com essa linguagem ?<br>
2.1 No seu trabalho, quantos colegas usam essa linguagem ?<br>
3. Quantos sites especializados fizeram alguma análise (ou reportagem) sobre essa linguagem ? (nos últimos 3 anos)<br>
3.1 Existem artigos científicos comentando ou criticando essa linguagem ? (nos últimos 3 anos)<br>
4. Existem fórums, grupos de usuários ou redes sociais abertas ao público e mantidas pela comunidade, nas quais você possa fazer perguntas ? <br>
4.1 A empresa mantém um fórum particular para que qualquer um possa fazer perguntas ?<br>
5. Existem livros (ou ebooks) sobre essa linguagem (ou ferramenta) em português ?<br>
6. Existem canais de vídeos sobre essa linguagem mantidos pela comunidade ?<br>
6.1 Existem canais de vídeos sobre essa linguagem mantidos pelo fabricante ?<br>
7. Em qual ano saiu a última grande versão ?<br>
7.1 Todo ano tem um lançamento de uma versão nova ou apenas atualizações ?<br>
7.2 As atualizações são gratuítas ?<br>
8. Essa linguagem é multi plataforma (roda em Linux, Windows e Mac) ?<br>
8.1 Essa linguagem permite o desenvolvimento mobile (principalmente Android) ?<br>
8.2 Essa linguagem permite o desenvolvimento web responsivo ?<br>
9. Existe treinamentos presenciais sobre essa linguagem (ou ferramenta) ?<br>
9.1 Existem empresas no Brasil que ministram treinamento sobre essa linguagem ? quantas ? Nas principais capitais ?<br>
10. O governo federal, os municípios e os estaduais adotam essa linguagem ?<br>
11. Essa ferramenta tem uma versão gratutíta ? quais as limitações ?<br>
12. Quais os valores para aquisição dessa linguagem/IDE ? <br>
12.1 É a mais barata compara com seus concorrentes ?<br>
13. Qual o salário médio de programadores/devs que usam essa linguagem ?<br>
13.1 Você conhece um canal ou site que divulga vagas para essa linguagem ? São várias e frequêntes ?<br>
14. Essa linguagem é usada nas faculdades da sua cidade ?<br>
14.1 Seu TCC foi feito nessa linguagem ?<br>
15. Você conhece software houses na sua cidade que usam essa linguagem ?<br>
16. Você tem conhecimento de quais paises estão aumentando o uso dessa linguagem ?<br>
17. Onde no exterior e em qual estado do Brasil estão as maiores comunicades de usuários dessa linguagem ?<br>
17.1 Existem encontros presenciais de usuários ?<br>











---


```
Aviso: Este material esta recebendo atualizações frequentes. 
As informações aqui contidas podem ser alteradas sem aviso prévio.
Primeira postagem em: jun/2023. 
Última atualização em: 20/jun/2023.
```




Histórico de atualizações nos repositórios do Prof. Monteiro:<br>
[![teste](https://github-readme-activity-graph.vercel.app/graph?username=monteiro74&theme=github-compact)](https://github.com/monteiro74/tutorial_python)


Contribuições de:<br>
<a href="https://github.com/monteiro74/lista_de_ferramentas/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=monteiro74/lista_de_ferramentas" />
</a>








```
Licença: Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) 
https://creativecommons.org/licenses/by-nc-sa/4.0/

```