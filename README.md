Sistema Inteligente de Control de Agua

## Problema real
En Bolivia, especialmente en La Paz y el Altiplano, la escasez de agua y el racionamiento afectan a miles de familias. El desperdicio y la falta de previsión agravan la situación.

## ¿Qué hace esta página?
El usuario ingresa:
- Número de personas en el hogar
- Consumo diario de agua (litros)
- Días a proyectar
- Capacidad del tanque de reserva

El sistema calcula:
- Proyección de consumo total
- Días que alcanzará el agua (con crecimiento progresivo)
- Alertas si algún consumo diario es **número primo** (posible fuga o derroche)
- Recomendaciones de ahorro personalizadas

##  Uso de Fibonacci
La **serie de Fibonacci** (1, 1, 2, 3, 5, 8, 13…) modela el **crecimiento progresivo del consumo** día a día.  
Ejemplo: si hoy consumes 180 litros, mañana otros 180, pasado 360, luego 540… así se simula un aumento realista ante más actividades o personas.

## Uso de números primos
Un **número primo** solo es divisible entre 1 y sí mismo (2, 3, 5, 7, 11…).  
Si el consumo de un día es **primo**, se lanza una alerta: puede indicar un **consumo anómalo**, una fuga o un derroche. Así se detectan problemas a tiempo.

## Resultado
La página muestra de forma clara y visual:
- Consumo total proyectado
- Días de autonomía real
- Alertas de consumos primos
- Recomendaciones para ahorrar agua

##  Tecnologías
- HTML5, CSS (diseño responsivo, efecto vidrio)
- JavaScript (lógica de Fibonacci y números primos)
