# 2018: BERT y Transformers bidireccionales

En 2018, Jacob Devlin, Ming-Wei Chang, Kenton Lee y Kristina Toutanova, desde Google AI Language, presentaron BERT: _Bidirectional Encoder Representations from Transformers_. BERT usó la arquitectura Transformer para preentrenar representaciones lingüísticas bidireccionales, es decir, capaces de considerar simultáneamente contexto izquierdo y derecho dentro de una secuencia. Su entrenamiento combinó tareas como predicción de tokens enmascarados y predicción de relación entre oraciones, y luego podía ajustarse para tareas específicas de procesamiento de lenguaje natural.

BERT conecta [[google-research-transformers]], [[2017-transformer-attention-is-all-you-need]], [[vaswani-et-al]], [[aprendizaje-de-representaciones]] y [[procesamiento-de-lenguaje-natural]]. Su impacto estuvo en consolidar el preentrenamiento sobre grandes corpus como base reutilizable para múltiples tareas de comprensión lingüística. En la genealogía de los modelos de lenguaje, BERT marca una línea distinta pero paralela a [[2018-gpt1-generative-pretraining]]: ambos expanden el uso de Transformers preentrenados, pero BERT se volvió especialmente influyente en clasificación, búsqueda, extracción de respuestas y análisis contextual de texto.

## Fuentes:

- [https://arxiv.org/abs/1810.04805](https://arxiv.org/abs/1810.04805)
- [https://research.google/pubs/bert-pre-training-of-deep-bidirectional-transformers-for-language-understanding/](https://research.google/pubs/bert-pre-training-of-deep-bidirectional-transformers-for-language-understanding/)
- [https://github.com/google-research/bert](https://github.com/google-research/bert)

## Conexiones

- [[google-research-transformers]]
- [[2017-transformer-attention-is-all-you-need]]
- [[vaswani-et-al]]
- [[aprendizaje-de-representaciones]]
- [[procesamiento-de-lenguaje-natural]]
- [[2018-gpt1-generative-pretraining]]
- [[modelos-estadisticos-de-lenguaje]]