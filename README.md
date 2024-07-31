# Tesouro_Direto_Clustering
Clusterização de Vendas de Tesouso Direto - Brasil de Jan/02

# Ministério da Fazenda

### Vendas do Tesouro Direto
Este conjunto de dados traz o volume de vendas diário do programa Tesouro Direto. Os dados de vendas são apresentados também por tipo de título e por data de vencimento do título. No Tesouro Direto não são mais vendidos títulos com prazo de vencimento inferior a 1 ano.

![image](https://github.com/user-attachments/assets/87471697-1aa5-4ee9-989d-3bc1cb926394)

### Avaliamos tb específicamente o ano de 2024:
![image](https://github.com/user-attachments/assets/bdaec43e-a5ff-4f1b-beeb-eab1f3d198d5)

### Títulos por Quantidade Vendida todo periodo e somente 2024


![image](https://github.com/user-attachments/assets/c3feca1a-228e-477d-90f7-c00ee35ef44e) ![image](https://github.com/user-attachments/assets/9690a02b-c028-4406-af17-9b77f43d7f01)



# Com a nossa análise encontramos 4 clusters.
![image](https://github.com/user-attachments/assets/11a21aae-1eee-47a3-8fea-edbdf63d9175)

### Análise dos Clusters
Os clusters foram definidos da seguinte forma:

#### Cluster 0: Títulos de Alto Valor - Características: Estes títulos possuem um Preço Unitário (PU) relativamente alto, mas são negociados em quantidades menores. Isso sugere que são títulos de maior valor individual, possivelmente de maior risco ou para investidores mais especializados.

#### Cluster 1: Títulos Alto Retorno - Características: Com um Preço Unitário (PU) significativamente alto e quantidades moderadas, esses títulos mostram-se como investimentos rentáveis, possivelmente com bons retornos sobre o investimento. São ideais para investidores que buscam maximizar seus lucros.

#### Cluster 2: Títulos Convencionais - Características: Estes títulos possuem um PU médio e são negociados em quantidades medianas. Representam uma categoria padrão de títulos, equilibrando risco e retorno de maneira consistente. São uma escolha comum entre investidores que buscam estabilidade.

#### Cluster 3: Títulos Acessíveis - Características: Com um PU mais baixo, mas negociados em grandes quantidades, esses títulos são populares entre os investidores. São mais acessíveis e, geralmente, possuem menor risco, tornando-os atrativos para um público mais amplo.

#### No âmbito da análise de títulos financeiros, uma das técnicas mais poderosas para segmentar dados é a clusterização. Utilizando o modelo K-Means, agrupamos nossos títulos em quatro clusters distintos com base em suas características de Preço Unitário (PU) e Quantidade. Cada cluster oferece insights únicos sobre os tipos de títulos presentes em nosso portfólio, facilitando a tomada de decisões estratégicas.

#### A clusterização de títulos utilizando o modelo K-Means nos permitiu identificar e categorizar os títulos em quatro grupos distintos. Cada cluster possui características únicas que podem ser exploradas para estratégias de investimento direcionadas. Por exemplo, investidores conservadores podem preferir os Títulos Acessíveis, enquanto aqueles que buscam maiores retornos podem se interessar pelos Títulos de Alto Retorno. Essa segmentação facilita a personalização de portfólios, otimização de estratégias de investimento e melhor entendimento do mercado financeiro.

#### Com essas insights, estamos bem posicionados para tomar decisões informadas e maximizar o retorno sobre os investimentos, ao mesmo tempo em que gerenciamos os riscos de forma eficaz.



#### DIMENSÃO TEMPORAL
* Início - Jan/02
* Fim - Série em curso
* Tempestividade - Governo Federal - Divulgação diária com dados de até dois dias anteriores à data de extração, pois é
quando se considera que o dado está consolidado

#### DIMENSÃO METODOLÓGICA
* Unidade de Medida - R$ 1,00
* Cobertura de Governo - Governo Federal - Abrange todos os títulos públicos federais ofertados pela Secretária do Tesouro
Nacional no Programa Tesouro Direto.
* Caracterização dos Evento - Este conjunto de dados traz o volume de vendas diário do programa Tesouro Direto. Os dados de vendas são apresentados também por tipo de título e por data de vencimento do título. No Tesouro Direto não
são mais vendidos títulos com prazo de vencimento inferior a 1 ano.
* Regime de Apropriação - Registro pelo critério caixa, ou seja, no momento da emissão dos títulos públicos federais.
* Fontes de Informações - Os valores são obtidos pela MF/STN a partir do Sistema Integrado da Dívida Pública (SID).
* Comentários Metodológicos - O arquivo gerado contém toda a base de vendas de títulos do Tesouro Direto disponível no SID, desde 2002 até dois dias anteriores ao momento da extração.

A clusterização das vendas do Tesouro Direto pode proporcionar insights valiosos e ajudar a otimizar estratégias tanto para investidores quanto para gestores do programa. Aqui estão algumas razões específicas para realizar a clusterização nesse contexto:

#### 1. Segmentação de Investidores
Objetivo: Identificar grupos de investidores com comportamentos e padrões de compra semelhantes.

Benefício: Permite uma compreensão mais detalhada dos diferentes perfis de investidores. Por exemplo, pode-se descobrir que certos grupos preferem títulos de longo prazo enquanto outros preferem títulos de curto prazo.
Aplicação: A Secretaria do Tesouro Nacional pode usar essas informações para desenvolver campanhas de marketing direcionadas, adaptar comunicações e melhorar a educação financeira de acordo com as necessidades de cada segmento.

#### 2. Personalização de Ofertas
Objetivo: Oferecer produtos mais alinhados com as preferências dos diferentes grupos de investidores.

Benefício: A personalização pode aumentar a satisfação dos investidores e potencialmente aumentar as vendas. Se a clusterização revela que um grupo específico tem uma alta demanda por títulos atrelados à inflação, o Tesouro Direto pode promover esses títulos mais eficazmente para esse grupo.
Aplicação: Ajustar a oferta de títulos e as estratégias de comunicação para promover produtos que atendam às preferências identificadas em cada cluster.

#### 3. Identificação de Tendências e Padrões de Compra
Objetivo: Descobrir padrões e tendências nas compras dos títulos ao longo do tempo.

Benefício: Identificar sazonalidades ou ciclos de mercado que afetam as vendas. Por exemplo, pode-se descobrir que há uma alta demanda por determinados títulos durante certos períodos do ano.
Aplicação: Ajustar a oferta de títulos e os horários de lançamento de novos produtos com base nas tendências identificadas.

#### 4. Otimização de Estratégias de Venda
Objetivo: Melhorar as estratégias de venda e a alocação de recursos com base em análises de cluster.

Benefício: Utilizando os clusters identificados, é possível alocar recursos de forma mais eficiente e ajustar as estratégias de venda para focar nas áreas mais promissoras.
Aplicação: Focar em canais de distribuição e estratégias de marketing que tenham maior impacto nos clusters mais relevantes.

#### 5. Aprimoramento das Políticas de Emissão
Objetivo: Adaptar as políticas de emissão de títulos para melhor atender à demanda dos investidores.

Benefício: A análise dos clusters pode ajudar a identificar quais tipos de títulos estão atraindo mais investidores e quais são menos populares.
Aplicação: Ajustar as características dos títulos oferecidos, como prazos e tipos de indexação, para alinhar melhor com as preferências dos investidores.

#### 6. Planejamento Financeiro e Gestão de Risco
Objetivo: Melhorar o planejamento financeiro e a gestão de riscos associados ao Tesouro Direto.

Benefício: Entender os padrões de compra pode ajudar na previsão da demanda futura e na gestão dos riscos associados à oferta e demanda de títulos.
Aplicação: Planejar melhor a emissão de novos títulos e gerenciar o estoque de títulos existentes de forma mais eficiente.

#### 7. Avaliação da Eficiência das Campanhas de Marketing
Objetivo: Avaliar o impacto das campanhas de marketing e promoções.

Benefício: Avaliar se campanhas direcionadas a certos grupos de investidores resultaram em mudanças nos padrões de compra.
Aplicação: Ajustar e otimizar futuras campanhas de marketing com base na eficácia observada em diferentes clusters.

#### 8. Acompanhamento de Performance e Feedback
Objetivo: Monitorar a performance dos títulos e obter feedback sobre o programa.

Benefício: Analisar como diferentes grupos respondem a mudanças nas ofertas e a novas emissões.
Aplicação: Ajustar a comunicação e as ofertas com base no feedback e nos dados de performance dos clusters.
Exemplo Prático:
Caso: Suponha que a clusterização revele três principais grupos de investidores:

Investidores Conservadores: Preferem títulos de longo prazo com garantia de retorno fixo.
Investidores Moderados: Preferem títulos atrelados à inflação ou com retornos variáveis.
Investidores Agressivos: Interessados em títulos com maiores riscos e potencial de retorno mais alto.
Aplicação:

Para Investidores Conservadores: Promover títulos como o Tesouro Prefixado.
Para Investidores Moderados: Destacar títulos como o Tesouro IPCA+.
Para Investidores Agressivos: Oferecer títulos com maior risco, como o Tesouro Selic para oportunidades de maior rendimento.
Em resumo, a clusterização das vendas do Tesouro Direto oferece uma maneira eficaz de entender e segmentar os investidores, otimizar estratégias e ofertas, e melhorar a gestão e planejamento do programa.
