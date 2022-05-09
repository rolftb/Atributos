# Archivos

Variables:

- $P:$ Precio Estimado
- $Q:$ Peso neto Kg.(_Variable discreta_)
- $A:$ Año el cual se ejecuta la venta.(_Variable discreta_)
- $w_i$ Semana $i$ del conjunto de semanas $W$

## A_1 (lineal sin Año)) Construccion modelo [Tradicional 1010078]

Modelos de regresión lineal OLS P(Q), __sin atributo Año__

- $P(Q)=\beta_1Q +\beta_0$
- $P(Q)=\beta_1Q +\beta_2 Q^2 + \beta_3Q^3  +\beta_0$
- $P(Q)=\beta_1Q +\beta_2 Q^2 + \beta_3Q^3 +\beta_0$
- $\ln(P(Q))=\beta_1Q  +\beta_0$
- $\ln(P(Q))=\beta_1\ln(Q)  +\beta_0$

## A_1 ) Construccion modelo [Tradicional 1010078]
  
  Es lo mismo el archivo anterior pero __con la variable Año__

  - $P(Q,A)=\beta_1Q +\beta_a A  +\beta_0$
  - $P(Q,A)=\beta_1Q +\beta_2 Q^2 + \beta_3Q^3 +\beta_a A +\beta_0$
  - $P(Q,A)=\beta_1Q +\beta_2 Q^2 + \beta_3Q^3 +\beta_a A +\beta_0$
  - $\ln(P(Q,A))=\beta_1Q +\beta_a A +\beta_0$
  - $\ln(P(Q,A))=\beta_1\ln(Q) +\beta_a A +\beta_0$ 

## A_2 ) Construccion modelo [Tradicional 1010078]
  
  Se incorpora la variable Semana a los modelos.

- $P(Q,W,A)=\beta_1Q +\sum_{i\in W}\beta_iw_i +\beta_a A +\beta_0$
- $P(Q,W,A)=\beta_1Q +\beta_2 Q^2 + \beta_3Q^3 +\sum_{i\in W}\beta_iw_i +\beta_a A +\beta_0$
- $P(Q,W,A)=\beta_1Q +\beta_2 Q^2 + \beta_3Q^3 +\sum_{i\in W}\beta_iw_i +\beta_a A +\beta_0$
- $\ln(P(Q,W,A))=\beta_1Q +\sum_{i\in W}\beta_iw_i +\beta_a A +\beta_0$
- $\ln(P(Q,W,A))=\beta_1\ln(Q) +\sum_{i\in W}\beta_iw_i  +\beta_a A +\beta_0$
  