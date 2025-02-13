# hr-clean-bachend
- Iniciando o projeto, usando Quarkus
- Este sistema tem como objetivo
  
📝 1. Verbas Rescisórias
A rescisão pode incluir os seguintes valores, dependendo do tipo de desligamento:

📊 Exemplo Prático
Funcionário com os seguintes dados:

Salário: R$ 3.000,00
Último dia trabalhado: 10 do mês
Trabalhou 6 meses no ano da rescisão
Férias vencidas
FGTS acumulado: R$ 5.000,00
Demitido sem justa causa
💰 Cálculo:
✔️ Saldo de salário → 3.000 \div 30 \times 10 = R$ 1.000,00
✔️ 13º salário proporcional → 3.000 \div 12 \times 6 = R$ 1.500,00
✔️ Férias vencidas + 1/3 → 3.000 + (3.000 \div 3) = R$ 4.000,00
✔️ Férias proporcionais → 
3.000
÷
12
×
6
+
(
1
/
3
)
3.000÷12×6+(1/3) → R$ 2.000,00
✔️ Multa FGTS (40%) → 5.000 \times 40\% = R$ 2.000,00

📌 Total aproximado a receber: R$ 10.500,00

