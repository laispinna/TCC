# Arquivos Vetoriais e Camadas Geográficas

Esta pasta armazena todos os arquivos espaciais utilizados e gerados nas análises do QGIS, incluindo formatos GeoPackage (.gpkg) e Shapefile (.shp).

## 📌 Descrição dos Arquivos Espaciais

### Camadas de Estados e Consumo (Formato .gpkg)
* Estados consumo final.gpkg: Camada com a divisão estadual contendo os dados consolidados de consumo final de energia.
* Estados siderurgia.gpkg: Mapeamento espacial focado nas indústrias do setor de siderurgia por estado.

### Conjunto de Dados da Demanda (Arquivos Shapefile .shp e auxiliares)
* demanda_h2.shp: Arquivo principal que contém as geometrias vetoriais da estimativa de demanda de hidrogênio.
* demanda_h2.dbf: Tabela de atributos com os dados numéricos e textuais da demanda de hidrogênio.
* demanda_h2.prj: Arquivo de projeção que define o sistema de coordenadas geográfica do mapa.
* demanda_h2.shx: Arquivo de índice posicional que faz a ligação entre a geometria e os atributos.
* demanda_h2.cpg: Identificador do conjunto de caracteres utilizado para evitar erros de acentuação no QGIS.

### Oferta de Geração e Potenciais Renovaveis (Formato .gpkg)
* geracao_limpa_aneel.gpkg: Dados georreferenciados da ANEEL focados em fontes limpas de energia renovável.
* Produtor.gpkg: Camada geral mapeando os pontos de produção energética regulamentados.
* produtores_out_5MW.gpkg: Filtro espacial exibindo apenas os produtores com capacidade outorgada acima de 5 Megawatts.
* produtorshidrica.gpkg: Localização espacial focada especificamente nos produtores de matriz hídrica.
* Soma_Hidrica_Estados.gpkg: Agrupamento e soma espacial do potencial hídrico totalizado por unidade federativa.

### Infraestrutura e Mapas Consolidados (Formato .gpkg)
* estados_peso_duto.gpkg: Análise de pesos espaciais atribuídos aos estados para o traçado de dutos e escoamento.
* estados_prod_ort.gpkg: Dados geográficos cruzando a produção outorgada nos diferentes territórios estaduais.
* mapa unido info.gpkg: Base unificada integrada contendo a união de múltiplos atributos geográficos analisados.
* mapa unid simbolo.gpkg: Camada configurada para a padronização visual e aplicação de simbologias temáticas nos mapas.
