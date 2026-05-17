# MYWEBPAGE
Learning how to dev a webpage for self use

Las variables son:

potenciaActiva → coincide con /activa|potencia\s+activa/i
potenciaReactiva → coincide con /reactiva|potencia\s+reactiva/i
potenciaAparente → coincide con /aparente|potencia\s+aparente/i
factorPotencia → coincide con /factor.*potencia|pf/i
thd → coincide con /thd/i
energiaConsumida → coincide con /energia|consumida/i
Esas son las variables usadas para:

mostrar las métricas principales
calcular costos
construir los gráficos de tendencias
Además, la columna Unidad se determina a partir de variable:

si contiene kwh → kWh
si contiene kw → kW
si contiene % → %