# Arquivos da Base de Dados

Esta pasta contém as planilhas consolidadas, dados públicos tratados e os projetos estruturais do QGIS utilizados como ponto de partida para as análises espaciais do TCC.

## Descrição dos Arquivos

### Camadas de Centroides (Formatos GeoPackage .gpkg)
* Centroides Biomassa.gpkg: Pontos georreferenciados representando o centro de gravidade das usinas e potenciais de geração por biomassa.
* Centroides Eolicas.gpkg: Centroides que delimitam a localização central e adensamento dos parques eólicos mapeados.
* Centroides Solar.gpkg: Dados espaciais em pontos representando as centrais de geração de energia fotovoltaica.
* Centroidesconsumidor.gpkg: Pontos correspondentes aos principais núcleos e polos de consumo de energia analisados.
* Centroidesprdutorhidrica.gpkg: Mapeamento dos pontos centrais das estruturas de produção de energia hídrica.
* Centroidesshidrica.gpkg: Camada complementar de apoio com localizações centrais de pequenas centrais hidroelétricas (PCH) ou pontos hídricos específicos.
* centroide hidrica.gpkg: Arquivo consolidado contendo os centroides gerais do potencial hídrico do projeto.

### Dados de Consumo e Mercado (Formatos .gpkg e .csv)
* Consumidor.gpkg: Base vetorial com a delimitação ou dados brutos georreferenciados dos mercados consumidores.
* basededadosanalise_rev1.csv: Planilha tratada (Revisão 1) contendo os dados estatísticos unificados utilizados para cruzar as informações no QGIS.
* basededaosaneel_rev1.csv: Dados oficiais da ANEEL extraídos e limpos para compor os indicadores de oferta de geração.
* siga-empreendimentos-geracao (1).csv: Base do Sistema de Informações de Geração da ANEEL (SIGA) detalhando a situação dos empreendimentos de energia.

### Projetos do QGIS (Formatos .qgz)
* DadosEPE.qgz: Projeto do QGIS estruturado para análise dos dados de planejamento energético com base nas diretrizes da EPE (Empresa de Pesquisa Energética).
* UsinasANEEL.qgz: Ambiente de trabalho focado no mapeamento e espacialização das usinas cadastradas na ANEEL.
* analise_rev7.qgz: Arquivo principal de trabalho do QGIS (Revisão 7) onde foi realizada a maior parte das modelagens e cruzamentos espaciais.
