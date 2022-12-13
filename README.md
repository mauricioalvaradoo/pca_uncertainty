# Índice de incertidumbre vía PCA
Creación de una índice de incertidumbre vía la volatilidad de series financieras. La volatilidad condicional de cada serie es contruída mediante un modelo GARCH(1,1), donde los errores están distribuídos mediante una t-student. 
Luego, se estimará un modelo VAR para estudiar la interacción del índice frente a la `inversión privada` e `inflación`. Se usará las librerías `yfinance`, `arch`, `statsmodels`.
