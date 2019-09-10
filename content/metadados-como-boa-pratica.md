
# Metadados como boa prática na política de abertura de dados governamentais

Reduzir barreiras no acesso às informações é considerada a intervenção mais básica na abertura de dados governamentais, segundo a escala de maturidade da [Sunlight Foundation](https://sunlightfoundation.com/2019/08/15/an-open-data-maturity-scale-for-cities-to-find-right-sized-solutions/). Uma das formas de reduzir barreiras é prover um esquema de metadados. Tal esquema visa permitir a contextualização dos campos dos datasets dos dados. Em outras palavras, evidenciar a qualificação e usos dos mesmos, como: se é publicamente acessível; quando ficou publicamente acessível; a data da última atualização; se é derivada de uma fonte primária, ou se foi modificada; se é restrito por alguma licença.

Trata-se, enfim, de informação estruturada que descreve, explica, localiza ou torna mais fácil de usar, manejar ou recuperar um dado. Quanto mais informação sobre o dado estiver provida de forma padronizada, mais valioso tal dado se torna. Existe, inclusive, um [vocabulário internacional específico para facilitar a interoperabilidade entre catálogos de dados publicados na web](https://www.w3.org/TR/vocab-dcat/). Um exemplo de catálogo de metadados, que contém os elementos necessários e suas respectivas descrições, pode ser encontrado no [New York State Open Data Institute](http://ny.github.io/open-data-handbook/metadata.html).

Aumentar a disponibilização e o uso de dados abertos é um objetivo estratégico tanto em [âmbito federal](https://www.governodigital.gov.br/EGD/documentos/revisao-da-estrategia-de-governanca-digital-2016-2019.pdf) quanto em nível estadual (meta PPAG CGE/MG). No governo federal, é esperado que o alcance desse objetivo leve a um 'ecossistema que promova o cruzamento de dados, o aprimoramento da análise e inteligência de dados dentro do governo, (...) estimulando o empreendedorismo e novos modelos de negócio que gerem valor na cadeia digital e beneficiem os cidadãos'. Ter metadados, em um catálogo de todas as bases de dados (abertos ou não) foi um dos quesitos avaliados na [Escala Brasil Transparente da CGU](http://transparencia.gov.br/pdf/bfe87072-8531-4dcc-9a9d-d6aefab0c1b7.pdf#catalogo-ou-inventario-de-dados-abertos). Os atributos dos metadados requeridos nessa metodologia de avaliação foram: descrição do conteúdo, periodicidade de atualização, origem e responsável pelo gerenciamento, tamanho e formato.

A W3C, entidade internacional que desenvolve padrões para a web, elaborou um [Guia de Melhores Práticas](https://www.w3.org/TR/dwbp/#metadata), em que existem três itens relacionados a metadados:
Fornecer metadados ([BP1](http://blog.w3c.br/melhores-praticas-dados-na-web-2-forneca-metadados-umapordia/)) para leitura de pessoas e máquinas (computadores). Para leitura humana, poderia ser [parte de uma página HTML na web](https://www.w3.org/TR/dwbp/dwbp-example.html) ou um arquivo de texto em separado. Para leitura por máquina, os metadadaos poderiam ser providos em formato JSON, ou [embutidos no formato HTML](https://www.w3.org/TR/dwbp/dwbp-example.ttl) - sob a recomendação de reutilizar padrões de vocabulários populares, como o já citado Data Catalog Vocabulary (VOCAB-DCAT).
Fornecer metadados descritivos ([BP2](http://blog.w3c.br/melhores-praticas-dados-na-web-3-forneca-metadados-com-parametros-de-localidade/)), de forma que pessoas entendam a natureza do conjunto de dados e suas distribuições (i.e. título, descrição, palavras-chave, data de publicação, entidade responsável pela publicação e contato com a mesma, cobertura temporal e espacial, data da última modificação e categorias) e agentes de software descobrirão automaticamente tais conjuntos e distribuições. Os exemplos do guia W3C para esta prática são estritamente os mesmos da prática anterior.
Fornecer metadados estruturais ([BP3](http://blog.w3c.br/melhores-praticas-dados-na-web-4-forneca-metadados-com-informacoes-estruturais/)), de forma que pessoas interpretem o esquema de um conjunto de dados e agentes de software sejam capazes de processar automaticamente os dados das distribuições - há um [modelo de dados tabulares](https://www.w3.org/TR/2015/REC-tabular-data-model-20151217/) para Web da W3C.

Ter metadados legíveis por máquina também é um quesito de avaliação de maturidade de portais de dados abertos pela [Open Data Iniciative](https://certificates.theodi.org/en/about/badgelevels).
No Brasil, a Fundação Getúlio Vargas publica o [Índice de Dados Abertos para Cidades](https://static.poder360.com.br/2018/05/WEB-I%cc%81ndice-de-dados-abertos-1.pdf), que avaliou 136 bases de dados de 8 cidades, e concluiu que apenas 25% das bases de dados avaliadas estão plenamente de acordo com a definição de dados abertos. De todo o universo de obstáculos encontrados (429), 62% são problemas de usabilidade e 38% de processo, reiterando a conclusão da avaliação de 2016 sobre a necessidade de bases de dados mais adequadas ao uso dos dados e transformação destes em informação, para além da publicização.
Os problemas mais comuns das bases de dados são: dificuldade de trabalhar dados (incluindo os metadados insuficientes), indisponibilidade de download da base de dados completa, dataset incompleto e ausência da informação em formato aberto.

Exemplos

PSP http://dados.prefeitura.sp.gov.br/pt_PT/dataset/servidores-ativos-da-prefeitura/resource/fb947bf3-ccee-41b0-91b3-4c609c9f8715

ALMG [Sobre o portal de dados abertos] (http://dadosabertos.almg.gov.br/ws/ajuda/sobre)

GOV MG [Metadados consulta remuneração](http://www.transparencia.dadosabertos.mg.gov.br/dataset/1e92431e-c154-41fd-8232-a2ae623c53da/resource/3f0f9f3d-ba8d-4fbc-bb29-9a3566f1e5f1/download/metadados.txt) e [Dicionário de Dados do Portal da Transparência](http://www.transparencia.dadosabertos.mg.gov.br/dataset/f9e8e228-17c9-4cbb-aaeb-df05deed4333/resource/e5ff8911-d23c-4e48-855d-d5455807b55c/download/dicionariodedadosportaldatransparencia.xml)
[Portal Fácil](https://dadosabertos.portalfacil.com.br/306/servidores)

Gancho para as escalas de maturidade (segundo post comparando os níveis de metadados fornecidos e atrelar com benefícios de cada um)

# Referências
[Data on the Web Best Practices - W3C](https://www.w3.org/TR/dwbp/)

[Escala Brasil Transparente da CGU](http://transparencia.gov.br/brasiltransparente?ordenarPor=posicao&direcao=asc)

[Estratégia de Governança Digital do Ministério do Planejamento, Desenvolvimento e Gestão](https://www.governodigital.gov.br/EGD/documentos/revisao-da-estrategia-de-governanca-digital-2016-2019.pdf)

[Índice de Dados Abertos para Cidades 2018 - Fundação Getúlio Vargas](https://static.poder360.com.br/2018/05/WEB-I%cc%81ndice-de-dados-abertos-1.pdf)

[Metadata Elements Appendix - New York State Open Data Initiative](http://ny.github.io/open-data-handbook/metadata.html)

[Open Data Policy Guidelines - Sunlight Foundation](https://opendatapolicyhub.sunlightfoundation.com/guidelines/13-metadata/)

[Project Open Metadata Schema](https://project-open-data.cio.gov/v1.1/schema/)
