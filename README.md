# Atributos

## Estructura

- Los atrichos A ):
- Cosntruyen CSV con caracteristicas de clientes utilizados más adeltante, en la sección B )
- Los Archivos B )

## Listado de cosas pendientes

1. [X] Contrucción de caracterisitcasc RFM
2. [X] Contrucción Atributos tamaño de lote
3. [X] Contrucción de la disponibiliadd de pago
    - [X] Caprteta exclusiva para este atributo
    - [X] Construcción modelo matematico
    - [X] Definir qué regresión usar
    - [X] Mostrar las partes del modelo
    - [X] Exponer qué representa los coeficientes del modelo
      - [X] Segmentar las Semanas
    - [X] Presentar el paso

## Apuntes

La disposicipon de pago, se construye por etapas.

1. [X] Se define el modelo de regresión general:
   1. [X] Como forma introductoria **qué es** (Ecuación).
   2. [X] Se presenta un rago de precios para este modelo de regresión, por medio de un grafico de dispersión.
   3. [X] Explicación de lo que representan los coeficientes del modelo.
   4. [X] Diferencias entre la interpretación de estos si es Log()/Nivel.
2. [X] Se recoge el atributo del modelo llamado Semanas, estas Poseen la particularidad de influir en el precio, como se mencionó anteriormente, es por ello que se adieren en el modelo.
3. [X] Las semanas.

## Otro modo

1. [X] Modelo OLS para definir p value
    - [X] Simple Q+ Año
    - [X] Polinomial +Año
    - [X] Log/Nivel Q+Año
    - [X] Log/Log(Q)+Año
    

## Desarrollo del Log-Log

Pasos:
1. [X] Evlauar el valor-p de las variables dummy semanas
2. [X] Presentar los coeficientes del modelo.
    - [X] Coeficiente de Q (Elasticidad, grafico puede ser)
    - [X] Coeficiente del Año (Semi elasticidad, cuanto aumenta el precio % cuando se aumenta un año, se pasa al año siguiente.)
    - [X] intercepto, define el Precio desde( No creo que sea necesario explicarlo)
    - [X] Coeficientes de las semanas, estan en contraste a la semana 1.
    - [ ] Coeficiente de las semanas, delest_first=False.
3. [X] graficar, los coeficientes del modelo
    - [ ] Los que no son semanas
    - [X] Las semanas
        - [X] Segmentar las semanas, Mostrar los cuartiles & Kmeans 1D.
        - [X] Grafica de /Codigo%20refuerzo/Disposicion_de_pago/Cod_1 A)


## Desarrollo Valoración
1. [X] Data week Semana
2. [ ] Construcción modelo matematico 
    - [ ] Un modelo por cada week tipe
    - [ ] Modelo que reemplza W por $C_W$
3. [ ] Un modelo por cada week type
4. [ ] Modelo que reemplza W por $C_W$
5. [ ] Ajuste facil de $\ln(P)$, $\ln(Q)$ a $P$, $Q$  
5. [ ] Valoración del producto
    - [ ] Variación porcentual:
        $ \% \triangle \text{Valoración} :=  \dfrac{Precio_{real} - Precio_{Estimado}}{Precio_{Estimado}}$ 
    - [ ] Variación escalar: 
        $\triangle \text{Valoración} := Precio_{real} - Precio_{Estimado}$ 
6. [ ] Grafica de dispersión de los puntos
    - [X] Color equivalente a la Valoración
    - [ ] Una grafica por Semana
    - [X] Recta representado el valor corespondiente a la realción P/Q