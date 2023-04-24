Función de Interés Compuesto
Esta función calcula el interés compuesto a partir de un monto inicial, una tasa de interés anual, un plazo en días y un período de rescate en días.

El interés compuesto es una forma de calcular los intereses que se obtienen por el dinero invertido en una cuenta de ahorro o inversión, en la que los intereses se suman al capital inicial y, a su vez, generan más intereses.

Para utilizar esta función, se deben proporcionar los siguientes parámetros:

monto_inicial: el monto inicial a invertir
tasa_anual: la tasa de interés anual expresada en porcentaje
plazo_dias: el plazo de la inversión en días
periodo_rescate_dias: el periodo de rescate en días, es decir, cada cuántos días se retirará el interés generado para ser reinvertido
La función retorna el monto final obtenido después del plazo de la inversión, calculado a partir del interés compuesto.

Ejemplo de uso:
resultado = interes_compuesto(monto_inicial=1000, tasa_anual=5, plazo_dias=365, periodo_rescate_dias=30)
print("El monto final obtenido es: ", resultado)
En este ejemplo, se está invirtiendo $1000 con una tasa de interés anual del 5% por un plazo de 365 días. Cada 30 días se rescatará el interés generado y se reinvertirá. El resultado será el monto final obtenido después del plazo de la inversión.
