## Consigna:

Objetivo:
Desarrollar una aplicación web que permita a los usuarios gestionar sus finanzas personales de manera eficiente y segura. 
La aplicación debe cumplir con los siguientes requisitos funcionales:
1. Gestión de cuentas bancarias:
    • Permitir la creación y edición de cuentas bancarias. 
    • Visualizar el saldo actual y el historial de movimientos de cada cuenta. 
    • Realizar transferencias entre cuentas propias. 
    • Descargar el historial de movimientos en formato CSV o PDF. 
2. Gestión de ingresos y gastos:
    • Permitir la creación y edición de ingresos y gastos. 
    • Categorizar los ingresos y gastos por tipo (salario, alquiler, alimentación, etc.). 
    • Visualizar gráficos y reportes sobre los ingresos y gastos por categoría y período de tiempo. 
    • Establecer presupuestos para diferentes categorías de gastos. 
3. Gestión de deudas:
    • Permitir la creación y edición de deudas. 
    • Indicar el monto total de la deuda, la tasa de interés, el plazo de pago y el monto de las cuotas. 
    • Visualizar un calendario de pagos y realizar simulaciones de diferentes escenarios de pago. 
    • Generar informes sobre el progreso en el pago de las deudas. 

Resolver
Estimación del tamaño del proyecto:
Utilizando el método COSMIC, se estima que el tamaño funcional total del proyecto es de X Puntos de Función COSMIC (PFC).
Cálculo del costo por punto de función: El costo por punto de función (CPFC) se estima en Y USD.
Cantidad de puntos de función que se pueden hacer en un mes: Se estima que un equipo de desarrollo de software de Z personas puede desarrollar
W Puntos de Función COSMIC (PFC) por mes.
Duración del proyecto: La duración del proyecto se estima en A meses.
Costo del proyecto: El costo total del proyecto se estima en B USD.

Instrucciones para el alumno:
    1. Identificar las interacciones funcionales: Analice los requisitos funcionales descritos anteriormente e identifique todas las interacciones entre 
los usuarios y la aplicación. 
    2. Clasificar las interacciones funcionales: Clasifique cada interacción funcional en una de las tres categorías de tamaño COSMIC: Pequeña (S), 
Mediana (M) o Grande (L). 
    3. Calcular el tamaño funcional: Asigne un valor de Puntos de Función COSMIC (PFC) a cada interacción funcional en función de su clasificación de 
tamaño y sume los valores de PFC de todas las interacciones para obtener el tamaño funcional total del proyecto en PFC. 
    4. Obtener el costo por punto de función: Investigue el costo promedio de desarrollo de software en su región y considere la complejidad del proyecto 
para estimar el costo por punto de función (CPFC). 
    5. Determinar la cantidad de PFC por mes: Estime la cantidad de Puntos de Función COSMIC (PFC) que un equipo de desarrollo de software de tamaño Z puede 
desarrollar por mes (W PFC/mes) en función de su experiencia y eficiencia. 
    6. Calcular la duración del proyecto: Divida el tamaño funcional total del proyecto (X PFC) por la cantidad de PFC que se pueden desarrollar por mes 
(W PFC/mes) para obtener la duración estimada del proyecto en meses (A meses). 
    7. Estimar el costo total: Multiplique el tamaño funcional total del proyecto (X PFC) por el costo por punto de función (Y USD/PFC) para obtener el costo 
total estimado del proyecto (B USD).

## Resolucion:

1, 2 y 3)
ID Fun - Detalle                                                                   -  Tamaño                                      
IF1    - Crear una cuenta bancaria                                                 -   M
IF2    - Editar una cuenta bancaria                                                -   M
IF3    - Consultar el saldo de una cuenta                                          -   S
IF4    - Consultar el historial de movimientos                                     -   M
IF5    - Realizar una transferencia entre cuentas propias                          -   L
IF6    - Descargar el historial en formato CSV                                     -   S
IF7    - Descargar el historial en formato PDF                                     -   S
IF8    - Registrar un ingreso                                                      -   S
IF9    - Editar un ingreso                                                         -   S
IF10   - Registrar un gasto                                                        -   S
IF11   - Editar un gasto                                                           -   S
IF12   - Asignar o modificar la categoría de un ingreso                            -   S
IF13   - Asignar o modificar la categoría de un gasto                              -   S
IF14   - Visualizar gráficos de ingresos y gastos                                  -   L
IF15   - Generar reportes por categoría y período                                  -   L
IF16   - Crear un presupuesto para una categoría                                   -   M
IF17   - Editar un presupuesto                                                     -   M
IF18   - Registrar una deuda                                                       -   M
IF19   - Editar una deuda                                                          -   M
IF20   - Registrar o modificar monto, tasa de interés, plazo y cuotas de una deuda -   M
IF21   - Visualizar el calendario de pagos                                         -   M
IF22   - Simular distintos escenarios de pago                                      -   L
IF23   - Generar un informe sobre el progreso del pago de las deudas               -   M

Las actividades funcionales chichas, como editar algun número, registrar o mostrar datos resulta simple (Small = S). La generación de reportes
o simulación, la visuación de gráficos ya involucra varios elementos más complejos y muchas interacciones (recuperar todos los datos, mostrarlos
según el criterio, dar información, simular situaciones, etc) estas son las más complejas (Large = L). Las intermedias como editar datos mas amplios
que un simple gasto o ingreso, estan en ese punto medio, siendo medianas

(Medium = M), S = 5 / M = 10 / L = 15

Tabla de Clasificacion de Valores por Categoria
Cat. - Cant. - Total
S    -   8   -	40
M	   -  10   - 100
L	   -  5    -  75
Total = 215

4 y 5 ) Suponiendo un grupo de 5 Desarrolladores. Tomando un Salario promedio (Dado que el grupo tiene Juniors y Seniors) calculamos que cada uno 
gana 2.500.000, en Dolares = 1700 (Aproximado) Por tanto el Grupo de Desarrolladores cuesta x mes = 8500 Dolares. En un mes de 20 días se hacen
10 Puntos x persona al mes (Segun investigué 1 Punto puede demorar de 4 a 16 horas de trabajo). 
Esto nos da 50 Puntos al mes. El costo del equipo es 8500. Por tanto el valor de cada punto = 8500 / 50 = 170 dolares

6) El Tiempo del proyecto = 215 (Puntos totales del proyecto) / 50 (Puntos promedio = 4,3 Meses.

7) El costo Total del proyecto = 215 (Puntos totales del proyecto) * 170 (Valor de cada punto) = 36.550 Dolares 

