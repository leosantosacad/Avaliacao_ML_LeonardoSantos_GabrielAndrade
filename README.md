# Avaliação ML Profº Bruno Leonardo Santos Gabriel Andrade
# Avaliação ML: Previsão de Vendas
# Professor: Bruno | Método: Regressão Linear Simples

1. Tipo de Análise
Utilizamos o Aprendizado Supervisionado. O modelo foi treinado usando o histórico passado (onde já sabíamos a quantidade vendida em cada mês) para aprender a tendência e prever os resultados dos meses futuros.

2. Equações da Reta e Confiabilidade (R²)
Fórmula utilizada: y = ax + b
| Produto | Equação da Reta | Confiabilidade (R²) |
|---|---|---|
| Tinta Acrílica | y = 19.09x + 89.24  | 0.7985 (Boa)                         |
| Tinta Esmalte  | y = 10.87x + 71.82  | 0.9817 (Alta)                        |
| Tinta Látex    | y = 10.00x + 190.00 | 1.0000 (Perfeita)                    |
| Tinta Spray    | y = 5.98x + 53.64   | 0.9784 (Alta)                        |
| Tinta PVA      | y = 10.00x + 140.00 | 1.0000 (Apenas 2 meses de histórico) |

3. Previsão por Trimestre e Tendências
Soma das vendas previstas por trimestre:
| Produto | Tri 1 (Meses 1-3) | Tri 2 (Meses 4-6) | Tri 3 (Meses 7-9) | Tri 4 (Meses 10-12) | Tri 5 (Meses 13-15) - Futuro |
|---|---|---|---|---|---|
| Tinta Acrílica | 382.27 | 554.10 | 725.91 | 897.72 | 1069.55 |
| Tinta Esmalte | 280.70 | 378.56 | 476.44 | 574.30 | 672.17 |
| Tinta Látex | 630.00 | 720.00 | 810.00 | 900.00 | 990.00 |
| Tinta Spray | 196.78 | 250.59 | 304.41 | 358.22 | 412.02 |
| Tinta PVA | 310.00 | - | - | - | 840.00 |
Conclusões da Tendência:
 * Crescimento Geral: A tendência é de alta para todos os produtos. Nenhum apresentou queda.
 * Destaques: A Tinta Acrílica tem o crescimento mais rápido (quase 20 unidades a mais por mês). A Tinta Spray é a mais lenta (aumenta cerca de 6 por mês).
 * Confiabilidade: As previsões são quase 100% seguras para a maioria das tintas, refletindo vendas muito estáveis. A exceção é a Tinta PVA, que carece de mais dados históricos para garantir essa precisão.

4. Planilha de Vendas Completa
Abaixo está o detalhamento com os dados reais e o que o modelo previu para cada mês.
| Produto | Mês | Vendas reais | Vendas previstas | R² |
|---|---|---|---|---|
| Tinta Acrílica | 1 | 120 | 108.33 | 0.7985 |
| Tinta Acrílica | 2 | 150 | 127.42 | 0.7985 |
| Tinta Acrílica | 3 | 130 | 146.52 | 0.7985 |
| Tinta Acrílica | 4 | 180 | 165.61 | 0.7985 |
| Tinta Acrílica | 5 | 200 | 184.70 | 0.7985 |
| Tinta Acrílica | 6 | 210 | 203.79 | 0.7985 |
| Tinta Acrílica | 7 | 190 | 222.88 | 0.7985 |
| Tinta Acrílica | 8 | 220 | 241.97 | 0.7985 |
| Tinta Acrílica | 9 | 210 | 261.06 | 0.7985 |
| Tinta Acrílica | 10 | 250 | 280.15 | 0.7985 |
| Tinta Acrílica | 11 | 300 | 299.24 | 0.7985 |
| Tinta Acrílica | 12 | 400 | 318.33 | 0.7985 |
| Tinta Acrílica | 13 | - | 337.42 | 0.7985 |
| Tinta Acrílica | 14 | - | 356.52 | 0.7985 |
| Tinta Acrílica | 15 | - | 375.61 | 0.7985 |
| Tinta Esmalte | 1 | 80 | 82.69 | 0.9817 |
| Tinta Esmalte | 2 | 100 | 93.57 | 0.9817 |
| Tinta Esmalte | 3 | 90 | 104.44 | 0.9817 |
| Tinta Esmalte | 4 | 120 | 115.31 | 0.9817 |
| Tinta Esmalte | 5 | 130 | 126.19 | 0.9817 |
| Tinta Esmalte | 6 | 140 | 137.06 | 0.9817 |
| Tinta Esmalte | 7 | 150 | 147.94 | 0.9817 |
| Tinta Esmalte | 8 | 160 | 158.81 | 0.9817 |
| Tinta Esmalte | 9 | 170 | 169.69 | 0.9817 |
| Tinta Esmalte | 10 | 180 | 180.56 | 0.9817 |
| Tinta Esmalte | 11 | 190 | 191.43 | 0.9817 |
| Tinta Esmalte | 12 | 200 | 202.31 | 0.9817 |
| Tinta Esmalte | 13 | - | 213.18 | 0.9817 |
| Tinta Esmalte | 14 | - | 224.06 | 0.9817 |
| Tinta Esmalte | 15 | - | 234.93 | 0.9817 |
| Tinta Látex | 1 | 200 | 200.00 | 1.0000 |
| Tinta Látex | 2 | 210 | 210.00 | 1.0000 |
| Tinta Látex | 3 | 220 | 220.00 | 1.0000 |
| Tinta Látex | 4 | 230 | 230.00 | 1.0000 |
| Tinta Látex | 5 | 240 | 240.00 | 1.0000 |
| Tinta Látex | 6 | 250 | 250.00 | 1.0000 |
| Tinta Látex | 7 | 260 | 260.00 | 1.0000 |
| Tinta Látex | 8 | 270 | 270.00 | 1.0000 |
| Tinta Látex | 9 | 280 | 280.00 | 1.0000 |
| Tinta Látex | 10 | 290 | 290.00 | 1.0000 |
| Tinta Látex | 11 | 300 | 300.00 | 1.0000 |
| Tinta Látex | 12 | 310 | 310.00 | 1.0000 |
| Tinta Látex | 13 | - | 320.00 | 1.0000 |
| Tinta Látex | 14 | - | 330.00 | 1.0000 |
| Tinta Látex | 15 | - | 340.00 | 1.0000 |
| Tinta Spray | 1 | 60 | 59.62 | 0.9784 |
| Tinta Spray | 2 | 70 | 65.59 | 0.9784 |
| Tinta Spray | 3 | 65 | 71.57 | 0.9784 |
| Tinta Spray | 4 | 80 | 77.55 | 0.9784 |
| Tinta Spray | 5 | 85 | 83.53 | 0.9784 |
| Tinta Spray | 6 | 90 | 89.51 | 0.9784 |
| Tinta Spray | 7 | 95 | 95.49 | 0.9784 |
| Tinta Spray | 8 | 100 | 101.47 | 0.9784 |
| Tinta Spray | 9 | 105 | 107.45 | 0.9784 |
| Tinta Spray | 10 | 110 | 113.43 | 0.9784 |
| Tinta Spray | 11 | 120 | 119.41 | 0.9784 |
| Tinta Spray | 12 | 130 | 125.38 | 0.9784 |
| Tinta Spray | 13 | - | 131.36 | 0.9784 |
| Tinta Spray | 14 | - | 137.34 | 0.9784 |
| Tinta Spray | 15 | - | 143.32 | 0.9784 |
| Tinta PVA | 1 | 150 | 150.00 | 1.0000 |
| Tinta PVA | 2 | 160 | 160.00 | 1.0000 |
| Tinta PVA | 13 | - | 270.00 | 1.0000 |
| Tinta PVA | 14 | - | 280.00 | 1.0000 |
| Tinta PVA | 15 | - | 290.00 | 1.0000 |
