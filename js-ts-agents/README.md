24-Nov-2015: 
Artículo para GECCO en el que la algoritmos escritos en javascript (js) realizarán predicción de series temporales (st) ejecutando para ello múltiples algoritmos en distintos clientes (agents).

La idea base es utilizar los datos de SIPESCA que serán servidos a demanda por un servidor (en principio en OpenShift, dado que ni Open.sen.se ni Xively han respondido, y no veo claro que se pueda tener acceso público a los datos en Fluxtream). Cada cliente recibirá los datos y realizará una predicción del siguiente. Los métodos pueden ser muchos, a elegir por el cliente; tanto métodos clásicos, como algoritmos evolutivos y los que podamos inventar.
