# Modelo de análisis predictivo para determinar clientes con tendencia a la deserción en Beta Ban

## Introducción

En los últimos meses la entidad bancaria Beta Bank está reportando una pérdida sustancial de clientes, los cuales están abandonando sus cuentas bancarias paulatinamente. Estos clientes que dejan de utilizar los servicios de una empresa se conocen como desertores, y la cancelación de sus cuentas puede estar relacionada con un mal servicio por parte del banco u ofertas más asequibles por parte de competencia. Considerando esto, y que resulta más costoso atraer nuevos clientes que salvar a los clientes existentes, Beta Bank ha decidido buscar estrategias que garanticen la retención y la disminución de la deserción de clientes antiguos.

Una de estas estrategias es la generación de modelos predictivos que permitan establecer aquellos desertores o clientes que están muy cerca de abandonar sus cuentas bancarias. Es así que Beta Bank, ha decidido generar un modelo de machine learning que a partir de datos sobre el comportamiento pasado de sus clientes y la terminación de contratos con el banco, buscará establecer qué clientes son más propensos a desvincularse de la empresa. En este proyecto se comparará diferentes modelos de machine learning y se escogerá aquel modelo que presente un valor F1 de al menos 0.59.

### Objetivos

1. Crear un modelo de machine learning que permita determinar aquellos clientes con una mayor tendencia a abandonar sus cuentas bancarias en Beta Bank. 
2. Examinar el equilibrio de clases y entrenar modelos que no consideren el desequilibrio de clases. 
3. Entrenar diferentes modelos de machine learning, escoger aquel modelo con el máximo valor F1 posible (al menos 0.59) y medir AUC-ROC en todos los modelos entrenados. 
