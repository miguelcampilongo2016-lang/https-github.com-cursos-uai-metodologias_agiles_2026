## Enunciado
Dar un ejemplo de cada uno de los cuellos de botellas analizados anteriormente en el paper de Brooks

## Resolucion

Complejidad:
Un sistema que posee una Base de Datos con cientos de tablas, relacionadas entre sí, mediante múltiples relaciones y dependencias. La ausencia o 
desactualización de documentación dificulta comprender la estructura del sistema, realizar modificaciones y recuperar información correctamente. 
Esto aumenta la complejidad del análisis, mantenimiento y evolución del software.

Conformidad:
Páginas o sistemas gubernamentales pueden presentar fallos, caídas o formatos incompatibles con los generados por el sistema del cliente. 
Esto obliga al equipo de desarrollo a implementar adaptaciones o mecanismos de integración, enganches, para cumplir con los requisitos y formatos 
exigidos por el sistema estatal, aun cuando estos no sean técnicamente ideal.

Cambiabilidad: 
Los requisitos originales, proporcionados por el cliente o interpretados durante el análisis, pueden resultar incorrectos o modificarse debido a 
factores externos. Por ejemplo, un sistema diseñado para soportar 100 usuarios puede necesitar atender 1000 debido al crecimiento del negocio o al 
éxito del producto. Esto obliga a rediseñar o actualizar el sistema que inicialmente no contemplaban dicha demanda.

Invisiblidad: 
La documentación del sistema puede quedar desactualizada debido a modificaciones realizadas sobre la arquitectura o el software. Como cada integrante 
del equipo conoce únicamente su parte del sistema, y puede no tienen una comunicación efectiva, la documentación deja de representar el estado real del 
desarrollo. Esto dificulta comprender el funcionamiento completo del sistema y tomar decisiones correctas.
