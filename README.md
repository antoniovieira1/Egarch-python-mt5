✨ Destaques:

    Conexão com Mercado: Integração direta com o MetaTrader5 para captura de dados históricos e em tempo real.

    EGARCH Personalizado: Implementação manual do modelo EGARCH, explorando a assimetria na volatilidade (choques negativos impactam mais que positivos!).

    Análise Temporal: Detecção dos picos de volatilidade diários, revelando os momentos de maior agitação no mercado.

    Visualização Clara: Saída formatada com timestamps precisos e níveis de volatilidade para decisões informadas.

📊 Tecnologias Utilizadas:

    MetaTrader5 para conexão com o mercado

    Pandas e NumPy para manipulação de dados

    Modelagem econométrica manual (sem dependência de bibliotecas prontas!)

    Processamento temporal com datetime

🔍 Como Funciona?

    Coleta dados do ativo DOL@ no timeframe M5.

    Calcula retornos logarítmicos para capturar mudanças percentuais.

    Aplica o modelo EGARCH customizado com parâmetros ajustáveis (ω, β, α, γ).

    Identifica e exibe o horário de maior volatilidade para cada dia.

🎯 Resultado:
Uma tabela elegante com o timestamp exato e o nível de volatilidade máxima diária, perfeita para traders que buscam oportunidades em mercados voláteis
