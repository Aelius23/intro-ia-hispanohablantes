# 2018: GPT-1 y preentrenamiento generativo

En 2018, Alec Radford, Karthik Narasimhan, Tim Salimans e Ilya Sutskever, desde OpenAI, presentaron “Improving Language Understanding by Generative Pre-Training”. El modelo usó una arquitectura Transformer entrenada primero con predicción de la siguiente palabra sobre grandes cantidades de texto sin etiquetar, y luego ajustada para tareas específicas de procesamiento de lenguaje natural. Esta estrategia mostró que un modelo generativo preentrenado podía transferir conocimiento lingüístico a varias tareas mediante fine-tuning supervisado.

GPT-1 conecta [[openai-gpt]], [[2017-transformer-attention-is-all-you-need]], [[vaswani-et-al]], [[aprendizaje-de-representaciones]] y [[procesamiento-de-lenguaje-natural]]. Su aporte fue consolidar el preentrenamiento generativo como una ruta práctica para construir modelos de lenguaje reutilizables, en paralelo a la línea bidireccional de [[2018-bert-bidirectional-transformers]]. En la genealogía de los modelos de lenguaje, GPT-1 abre la secuencia que luego pasa por [[2020-gpt3-few-shot-learning]] y desemboca en sistemas conversacionales como [[2022-chatgpt-product-layer]].

## Fuentes:

- [https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)
- [https://openai.com/index/language-unsupervised/](https://openai.com/index/language-unsupervised/)
- [https://github.com/openai/finetune-transformer-lm](https://github.com/openai/finetune-transformer-lm)

## Conexiones

- [[openai-gpt]]
- [[2017-transformer-attention-is-all-you-need]]
- [[vaswani-et-al]]
- [[aprendizaje-de-representaciones]]
- [[procesamiento-de-lenguaje-natural]]
- [[2018-bert-bidirectional-transformers]]
- [[2020-gpt3-few-shot-learning]]
- [[2022-chatgpt-product-layer]]