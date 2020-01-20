__1) O Portal da Transparência e a seção de Dados Abertos do Governo de Minas Gerais sempre foram unificados num mesmo portal? Caso não, quando e por quais razões ocorreu esta integração?__

Desde seu lançamento o [Portal de Dados Abertos](http://www.transparencia.dadosabertos.mg.gov.br/) encontra-se incorporado como [seção do Portal da Transparência](http://www.transparencia.mg.gov.br/dados-abertos) por meio de um [iframe](https://www.w3schools.com/tags/tag_iframe.asp).

O Portal de Dados Abertos, uma aplicação CKAN, encontra-se hospedado em <http://www.transparencia.dadosabertos.mg.gov.br/>.

__2) Quais as vantagens, benefícios vocês percebem neste modelo de unificação do Portal da Transparência com a seção de Dados Abertos?__

A principal vantagem é que o conhecimento sobre o Portal da Transparência acaba "transbordando" para o Portal da Dados Abertos, que, em Minas Gerais, possui menor destaque.

__3) Vocês percebem desvantagens, problemas, dificuldades neste modelo unificado de portais? Se sim, quais?__

A incorporação do Portal de Dados Abertos fez com que o mesmo tivesse seu escopo reduzido a divulgação, em formato de dados abertos, do conteúdo disponível no Portal da Transparência, qual seja, dados sobre a gestão de finanças públicas.

Minas Gerais está iniciando um movimento para conferir "identidades" próprias para os dois Portais, justamente pela diferença de escopo. As observações do [Manual de dados abertos
governamentais](https://www.centraldocidadao.rs.gov.br/upload/arquivos/201707/10105453-manual-dados-tecnico.pdf) do RS resumem a posição atual de Minas

>  Qual a diferença do Dados RS e do Portal da Transparência?
> 
> Criado em 2009, o Portal da Transparência RS atende determinação constitucional e legal (Lei Complementar 131, de 27 de maio de 2009) de dar publicidade a informações sobre a execução orçamentária e financeira dos órgãos e entidades públicas do Rio Grande do Sul (Executivo, Legislativo, Judiciário e Ministério Público).
> 
> Administrado pela Contadoria e Auditoria-Geral do Estado - CAGE, órgão central do Sistema de Controle Interno do Estado do Rio Grande do Sul, o Portal da Transparência RS é instrumento fundamental para o acompanhamento e fiscalização da administração financeira estadual, apresentando dados sobre receitas, despesas, transferências e repasses feitos pelos órgãos gaúchos, inclusive em formato aberto.
> 
> Com escopo mais amplo, o Dados RS é o ponto único referencial para a busca e o acesso a dados públicos sobre todo e qualquer assunto ou categoria de interesse da população, como saúde, educação, segurança pública, assistência social, esportes, turismo. (Veja seção “Quais dados abertos governamentais?”).
> 
> Ele simplifica o acesso aos dados das mais variadas naturezas, não só orçamentária e financeira, organizando e padronizando a produção e publicação das informações, incentivando a reutilização pela sociedade, pelo mercado e pelos demais órgãos públicos.

__4) Qual a plataforma tecnológica do atual Portal da Transparência? (CMS; bancos de dados; ferramentas de extração, transformação e carregamento (ETL); relatórios/visualização de dados etc.)__

* CMS: Joomla
* Banco de Dados: Oracle
* Ferramenta de ETL: Informatica PowerCenter
* Relatórios/visualização de dados: [DataTables](https://datatables.net/),[D3](https://github.com/d3/d3), e [D3plus](https://github.com/d3plus/)

__5) Quais parâmetros técnicos motivaram a escolha da atual plataforma utilizada por vocês?__

A escolha técnicas dos componentes da plataforma do Portal foram guiados pela entidades estadual de TIC (PRODEMGE), sem envolvimento direto da CGE.

__6) Qual a forma de disponibilização do Portal e armazenamento dos dados (solução própria ou contratada/nuvem ou servidor dedicado)?__

O Portal da Transparência e o Portal de Dados Abertos estão hospedados em [servidores dedicados distintos](https://www.prodemge.gov.br/images/Espa%C3%A7o_Cliente/Caderno-Servicos-Prodemge_Versao2-3.pdf#page=30) no Data Center da PRODEMGE.

O [contrato atual](http://www.transparencia.mg.gov.br/compras-e-patrimonio/compras-e-contratos/comprasecontratos-filtros/5/2019/01-01-2019/31-12-2019/66/63262) possui os seguintes valores mensais

* Hospedagem de Sistemas em Ambiente Dedicado – Baixa Plataforma (Portal da Transparência do Estado) - R$ 15.064,67
* Hospedagem de Sistemas em Ambiente Dedicado – Baixa Plataforma (Aplicação de Gestão de Dados Abertos CKAN) - R$ 4.330,84

Totalizando um valor anual de R$ 232.746,12.

__7) O Portal da Transparência e a seção de Dados Abertos operam ambos na plataforma CKAN ou a seção de Dados Abertos funciona "embutida" na estrutura do Portal da Transparência?__

Conforme mencionado em 1, apenas o Portal de Dados Abertos opera na plataforma CKAN, encontrando-se incorporado como [seção do Portal da Transparência](http://www.transparencia.mg.gov.br/dados-abertos) por meio de um [iframe](https://www.w3schools.com/tags/tag_iframe.asp).

__8) Como foi em linhas gerais o processo de desenvolvimento do novo Portal da Transparência de Minas Gerais? Em termos de:__

__a. Duração do projeto__

__b. Equipe envolvida (própria da CGE; externa, mas do Governo do Estado; empresas ou profissionais externos ao Governo etc.)__

__c. Recursos financeiros empregados__

Foi [celebrado o contrato com a PRODEMGE](http://www.transparencia.mg.gov.br/compras-e-patrimonio/compras-e-contratos/comprasecontratos-filtros/5/2015/01-01-2015/31-12-2015/66/19166), empresa responsável pela reestruturação do Portal de Transparência no valor total de R$ 1.049.552,00 com vigência de 12 meses. No entanto, foi necessário a prorrogação por mais 12 meses. Nesse sentido, a entrega final do Portal encerrou-se em novembro de 2017. Importante destacar que durante a execução do contrato foi preciso realizar supressão de valores, havendo uma redução total de R$210.942,00.

As equipes envolvidas na execução do projeto foram servidores da própria CGE (especificação e homologação) e servidores da PRODEMGE (construção e desenvolvimento da ferramenta).
A reestruturação do Portal, bem como a sua manutenção preventiva e corretiva foram de responsabilidade de servidores da CGE (especificação e homologação) e servidores da PRODEMGE (construção, execução e desenvolvimento), empresa de tecnologia da informação vinculada ao governo estadual.

Por parte da CGE a equipe teve em média 3 servidores em dedicação exclusiva.

__9) Qual o volume atual de acessos/visitas ao Portal da Transparência? E apenas da seção de Dados Abertos?__

A tabela abaixo apresenta as sessões mensais de 2019 do Portal da Transparência (exceto seção de Dados Abertos) e Portal de Dados Abertos.

| Mês       | Portal da Transparência     | Portal de Dados Abertos     | Total         |
|-----------|-----------------------------|-----------------------------|---------------|
| 1         | 134.824                     | 955                         | 135.779       |
| 2         | 119.509                     | 901                         | 120.410       |
| 3         | 121.088                     | 983                         | 122.071       |
| 4         | 130.848                     | 1.043                       | 131.891       |
| 5         | 142.034                     | 1.147                       | 143.181       |
| 6         | 122.357                     | 1.001                       | 123.358       |
| 7         | 133.266                     | 1.020                       | 134.286       |
| 8         | 140.524                     | 1.063                       | 141.587       |
| 9         | 143.335                     | 1.064                       | 144.399       |
| 10        | 152.946                     | 1.041                       | 153.987       |
| 11        | 151.350                     | 961                         | 152.311       |
| 12        | 144.267                     | 751                         | 145.018       |
| __TOTAL__ | __1.636.348__               | __11.930__                  | __1.648.278__ |

Atualmente não possuímos rastramento dos conjuntos de dados mais acessados no Portal de Dados Abertos.