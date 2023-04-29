# comex_agro
Este repositório busca ajudar as autoridades aduaneiras a identificar quais produtos agrários possuem maior potencial de contrabando, ou seja, os produtos agrários mais atrativos para a comercialização ilegal no país.

Este estudo contempla apenas produtos de interesse agropecuário, assim classificados de acordo com as normas internacionais - “International Standard Industrial Classification of All Economic Activities” (ISIC). 

Foram considerados dados obtidos entre janeiro de 2013 e dezembro de 2022, perfazendo um total de 10 anos de dados.


**Descrição das colunas e tabelas auxiliares**  

- CO_ANO: Ano (1997 a 2021)

CO_MES: Código do mês (1:Janeiro a 12:Dezembro)

CO_NCM: Código da Nomenclatura Comum Mercosul - Utilizada para controle e identificação das mercadorias comercializadas no Brasil e nos outros países do Mercosul (cada NCM representa um produto diferente)

CO_UNID: Código da Unidade de Medida Estatística que é uma unidade de medida padrão para cada NCM, podendo ter valores como quilograma, metro, litro, pares, tonelada e outros.

CO_PAIS: Código do nome do país com a qual foi realizada a operação comercial (importação ou exportação)

SG_UF _NCM (sigla UF origem/destino da NCM): Código da Unidade Federativa (estado) de origem (exportação) ou destino (importação) da mercadoria.

CO_VIA: Código para identificação do meio de transporte utilizado (aéreo, marítimo, rodoviária, ferroviária e outros). Na exportação, é o método utilizado para o transporte de mercadorias entre o último local de embarque para o exterior. Na importação, configura-se através dos meios de acesso para os bens do primeiro ponto de entrada no território nacional.

CO_URF (Unidade da Receita Federal): Código da agência responsável pela execução dos procedimentos necessários para o desembaraço aduaneiro da mercadoria importada/exportada

QT_ESTAT: No detalhamento por NCM, cada produto tem sua unidade estatística. Grande parte dos produtos tem como unidade estatística o peso em quilogramas, mas existem outras: quilograma líquido, número (unidades), pares, dúzias, milheiro, tonelada. A tabela completa que relaciona cada NCM com sua unidade estatística pode ser encontrada em na tabela “NCM _ UNIDADE”. É importante ressaltar que não se deve somar quantidades estatísticas de NCMs que contenham unidades estatísticas diferentes. [2]

KG_LIQUIDO: Medida que expressa o peso líquido da mercadoria. Mesmo produtos com quantidades estatísticas diferentes do quilograma também possuem disponível a medida em quilograma, referindo-se ao peso líquido da mercadoria, ou seja, mercadoria desconsiderando embalagens, caixas ou quaisquer outros adicionais de transporte. Vale relembrar que essa informação, bem como as demais informadas nas operações de comércio exterior, é de livre preenchimento e de responsabilidade exclusiva dos operadores de comércio exterior. [2]

VL_FOB: O valor FOB indica o preço da mercadoria em dólares americanos (US$) sob o Incoterm FOB (Free on Board), modalidade na qual o vendedor é responsável por embarcar a mercadoria enquanto o comprador assume o pagamento do frete, seguros e demais custos pós embarque. [2]

**Fonte dos dados**  
[1] Base de dados. Disponível em: https://www.gov.br/produtividade-e-comercio-exterior/pt-br/assuntos/comercio-exterior/estatisticas/base-de-dados-bruta  
[2] Estatísticas de Comércio Exterior em Dados Abertos. Disponível em: http://comexstat.mdic.gov.br/pt/home  
[3] Manual de utilização dos dados estatísticos do comércio exterior brasileiro. Disponível em: https://balanca.economia.gov.br/balanca/manual/Manual.pdf  
[4] Descrição das colunas e tabelas auxiliares disponível em https://www.kaggle.com/datasets/daniellecd/dados-de-exportao-e-importao-do-brasil.