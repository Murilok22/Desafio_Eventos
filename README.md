🎤 Análise de Performance de Shows e Eventos

Este projeto realiza uma análise exploratória de dados sobre um conjunto de dados de shows e grandes eventos. O objetivo principal é extrair insights valiosos sobre vendas de ingressos, ocupação de espaços e receita gerada por artista e cidade.
📋 Estrutura da Base de Dados

A base de dados original contêm informações estruturadas sobre eventos com as seguintes colunas:

    ID_Show: Identificador único do evento.
    Artista: Nome da banda ou artista.
    Genero: Gênero musical do show.
    Cidade: Cidade onde ocorreu o evento.
    Ingressos_Vendidos: Quantidade de ingressos comercializados.
    Capacidade_Local: Capacidade máxima de público permitida no local do evento.
    Preco_Medio_Ingresso: Preço médio cobrado por ingresso.

📈 Métricas de Negócio Calculadas

Para aprofundar nossa análise, criamos métricas fundamentais para avaliar o sucesso financeiro e de público de cada show:

    Receita Bruta (Receita): Calculada multiplicando a quantidade de ingressos vendidos pelo preço médio cobrado.
    Receita=Ingressos Vendidos×Preço Médio

    Eficiência de Público (Taxa de ocupação): Porcentagem de ocupação do espaço para entender quais eventos conseguiram preencher melhor as vagas disponíveis.
    Taxa de Ocupação=(Ingressos VendidosCapacidade Local)×100

💾 Exportação e Próximos Passos

Ao final da análise, consolidamos a base de dados enriquecida com as novas colunas geradas e salvamos em um novo arquivo CSV pronto para consumo em ferramentas de BI (como Tableau ou Power BI):

    📁 Shows_evento_novo.csv
