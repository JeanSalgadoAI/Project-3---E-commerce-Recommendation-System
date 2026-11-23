# Dados e escopo

O código original gera esta base artificialmente. Os valores não descrevem pessoas, empresas ou clientes reais.

O CSV existente foi preservado. A revisão não substitui a amostra por dados de clientes.

Arquivo: `data/health_data.csv` · 1000 linhas · 4 colunas.

| Campo | Tipo no CSV | Valores ausentes | Papel na análise |
|---|---|---:|---|
| age | int64 | 0 | Atributo |
| bmi | float64 | 0 | Atributo |
| smoker | int64 | 0 | Atributo |
| disease | int64 | 0 | Alvo |

Identificadores são artificiais; os nomes das colunas foram mantidos para facilitar a reprodução.

O alvo foi gerado de forma independente dos atributos. Eventuais diferenças de desempenho neste recorte são variação amostral, não evidência de capacidade preditiva em produção. Não é um modelo clínico, diagnóstico ou recomendação de saúde. O arquivo não contém produtos nem recomendações de comércio eletrônico.
