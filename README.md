📊 Segmentação de Clientes com RFV e Clustering

Este projeto tem como objetivo segmentar clientes de um e-commerce utilizando métricas RFV (Recência, Frequência e Valor) e técnicas de clustering. A análise ajuda a entender padrões de compra, permitindo à empresa criar campanhas de marketing personalizadas, aumentando retenção e conversão.

📝 Sumário
- Contexto do Projeto
- Tecnologias Utilizadas
- Etapas de Desenvolvimento
- Como Executar
- Insights Obtidos
- Conclusão e Próximos Passos

📌 Contexto do Projeto
Uma empresa de e-commerce quer entender melhor seus clientes para personalizar campanhas de marketing e aumentar as vendas. 
Para isso, foi disponibilizada uma base de dados contendo informações sobre clientes, produtos e transações da loja entre os anos de 2010 e 2011.

✨ Objetivos do projeto:

✅ Agrupar clientes em clusters com base em seu comportamento de compras.

✅ Identificar padrões e características comuns entre os grupos.

✅ Fornecer insights para segmentação de clientes e estratégias de marketing personalizadas.

🛑 Observações sobre os dados:
- As datas estão no formato MM/DD/YYYY HH:mm:ss.
- Existem valores nulos, que precisam ser tratados.
- Códigos de identificação numéricos não devem ser tratados como números na modelagem.

⚙ Tecnologias Utilizadas

🔹 Python — Linguagem usada para manipulação dos dados e modelagem.

🔹 Pandas — Para análise e manipulação da base de dados.

🔹 Matplotlib & Seaborn — Para visualização gráfica e análises exploratórias.

🔹 Scikit-learn — Para pré-processamento dos dados e clustering.

🚀 Etapas de Desenvolvimento

A análise foi realizada em cinco etapas principais:

1️⃣ Carregamento e exploração dos dados
- Importamos os dados e realizamos verificação de valores nulos e duplicados.
- Geramos estatísticas descritivas para entender padrões.
- Criamos visualizações iniciais: histogramas, boxplots e mapa de calor.
 
2️⃣ Pré-processamento dos dados
- Convertendo datas para formato adequado.
- Removendo valores nulos e duplicados.
- Criando métricas RFV (Recência, Frequência e Valor) para segmentação.
 
3️⃣ Aplicação do modelo de Clustering
- Normalizamos os dados para melhor performance.
- Testamos diferentes números de clusters usando o método Elbow.
- Aplicamos K-Means para agrupar os clientes.
 
4️⃣ Análise dos Clusters
- Identificamos padrões em recência, frequência e valor gasto.
- Geramos gráficos de dispersão e boxplots para interpretar os clusters.
- Determinamos o perfil médio de cada cluster.
  
5️⃣ Insights e Estratégias de Marketing
- Criamos ações direcionadas para cada grupo de clientes.
- Estabelecemos recomendações como descontos exclusivos, campanhas de retenção e promoções direcionadas.

🛠 Como Executar
📌 Pré-requisitos
- Python 3.x instalado
- Bibliotecas necessárias instaladas via pip
📦 Instalação
pip install -r requirements.txt


🚀 Execução
python clustering.py



📊 Insights Obtidos
A partir do modelo de clustering, os clientes foram agrupados em quatro perfis principais:


    |  Cluster  |            Perfil do Cliente                 |                 Estratégia de Marketing                      | 
  
    |     0     |    VIP (alta frequência e alto gasto)        |   Criar programa de fidelidade e benefícios exclusivos       | 
  
    |     1     | Recorrentes (compra média e boa frequência)  |   Incentivar compras recorrentes com cupons personalizados   | 
  
    |     2     |     Novos (recente, mas baixa frequência)    |   Estratégia de onboarding + promoções iniciais              |
  
    |     3     |     Inativos (há muito tempo sem compras)    |   E-mail marketing para reativação com ofertas especiais     | 



📌 Principais aprendizados: 

✅ Os clientes VIP são os mais rentáveis → Devem ser priorizados nas campanhas.

✅ Os clientes novos precisam ser engajados → Promoções iniciais podem aumentar a retenção.

✅ Clientes inativos podem ser reativados → Estratégias como e-mail marketing podem ser eficazes.

🔮 Conclusão e Próximos Passos

✔ A segmentação dos clientes usando RFV e Clustering mostrou padrões úteis para personalização do marketing.

✔ Com as métricas RFV, conseguimos agrupar clientes com características similares, permitindo ações direcionadas.

✔ Os insights obtidos podem ser usados para melhorar o engajamento e reter clientes valiosos.
🚀 Próximos passos: 

🔹 Testar novos algoritmos de clustering para comparar resultados (DBSCAN, Hierarchical).

🔹 Explorar outras métricas de clientes (como ticket médio).

🔹 Integrar os dados com sistemas de CRM e automação de marketing
