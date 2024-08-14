El dataset son 50 startups en el cual se muestra los gastos y beneficios del año fiscal `Profit`.

En lugar de estar sumado por una variable dependiente. Se podra sumar muchas variables independientes. En este caso del markdown

* Gastos administrativos
* Ubicación

Otro ejemplo, predecir nota de un estudiantes

- Las variables independientes: Hora de estudio, Nro de veces que se fue al cine, etc

En conclusion, sumado con esos contantes predicirá las variables dependientes.

---

## Restricciones de la Regresión Lineal

1. Linealidad
2. Homocedasticidad
3. Normalidad multivariable
4. Independencia de los errores
5. Ausencia de multicolinealidad

Si alguno de estos casos no aplica al modelo, entonces no funcionaría la regresió lineal

---

### Variables Dummy


| PROFIT     | R&D Spend  | Admin      | Marketing  | State      |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| 192,261.83 | 165.349.20 | 136,897.80 | 471,784.10 | New York   |
| ...        | ...        | ...        | ...        | California |

* Donde `Profit` es la variable dependientes
* Donde las demas columnas son las variables independientes

`y = b_0 + b_1 * x_1 + b_2*x_2 + b_n * x_n `

Pero, Que hacemos con el Estado? Ya que es un `texto`.

### Variables Categorias

Deben ser traducidas a variables numericas (o `dummy`). En este caso , como son solo 2 tipos, New York puede tomar el valor de = 1 , y California el valor de = 0.

---

# La Trampa de las Variables Dummies
