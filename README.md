-> Sobre o Projeto
O objetivo do projeto é analisar um grande volume de reclamações de consumidores para identificar os principais fatores demográficos e canais de compra que geram insatisfação. A partir dessa análise, o estudo visa extrair recomendações estratégicas para a empresa, otimizar seus processos, melhorar a experiência do cliente e aumentar a taxa de resolução de problemas.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-> Equipe
Rafael de Oliveira Corrêa, RA 10438174
Theo Casella Mendonça, RA 10436180
Vitor Santos Lo Sciuto, RA 10438906

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-> Dataset
O estudo utilizou um conjunto de dados interno de interações com clientes, abrangendo o período de 01/01/2023 a 31/12/2024.

Volume: Aproximadamente 2.8 milhões de registros de reclamações.
Fonte: Dados internos da empresa.
Campos-chave: ID_Cliente, Faixa Etária, Canal de Compra, Data_Reclamação, Status_Avaliação (Não Avaliada, Não Resolvida, Resolvida).
Limitações: O dataset não inclui informações sobre o tipo de produto/serviço ou o histórico de compras do cliente.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-> Análise e Resultados
A análise exploratória dos dados revelou padrões importantes tanto no perfil demográfico dos reclamantes quanto nos canais de compra que originaram as queixas.

Perfil Demográfico: As faixas etárias de 21 a 30 anos e, principalmente, de 31 a 40 anos concentram o maior volume de reclamações. O grupo de 31 a 40 anos se destaca por ter o maior número absoluto de reclamações com o status "Não Resolvida".
Canais de Compra: O canal Internet é, de longe, a maior fonte de reclamações, superando todos os outros canais somados. Além do alto volume, o canal de Internet também possui uma quantidade preocupante de casos "Não Resolvidos", sugerindo falhas na experiência de compra ou no suporte pós-venda online. Os canais Loja Física e Telefone também representam pontos de atrito relevantes com os consumidores.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-> Recomendações Estratégicas
Com base nos insights gerados, as seguintes ações foram propostas: 
Priorizar a infraestrutura digital: Alocar recursos para otimizar a plataforma de e-commerce e os sistemas de atendimento online. 
Criar uma força-tarefa de resolução: Montar uma equipe dedicada para tratar o backlog de reclamações "Não Resolvidas" do público de 31 a 40 anos. 
Capacitar equipes de lojas físicas: Reforçar o treinamento das equipes para que mais problemas possam ser resolvidos localmente. 
Otimizar o atendimento telefônico: Avaliar e melhorar a performance da URA e reduzir o tempo de espera.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-> Como Executar o Projeto
Para visualizar a análise completa e o processo de geração dos gráficos, utilize o notebook .ipynb fornecido neste repositório.

Clone este repositório:
git clone https://github.com/vitorsciuto/PI-GeracaoDeInsights

Navegue até o diretório do projeto:
cd PI-GeracaoDeInsights

Abra o arquivo Analise_Reclamacoes.ipynb em um ambiente com suporte a notebooks Python, como o Google Colab ou Jupyter Notebook.
Nota: O notebook Analise_Reclamacoes.ipynb contém todo o código para a análise exploratória e a visualização dos dados discutidos no relatório.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-> Documentação
Para um detalhamento completo da metodologia, análise e conclusões, consulte o RelatórioFinal.pdf.
