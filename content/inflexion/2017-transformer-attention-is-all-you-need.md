# 2017: Transformer y *Attention Is All You Need*

En 2017, Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser e Illia Polosukhin publicaron *Attention Is All You Need*. El paper presentó el Transformer, una arquitectura de red neuronal basada en mecanismos de atención, diseñada inicialmente para tareas de transducción de secuencias como la traducción automática. Su propuesta desplazó el papel central que tenían las redes recurrentes y convolucionales en muchos sistemas de procesamiento de lenguaje, al mostrar que la atención podía organizar por sí misma las relaciones entre elementos de una secuencia.

Este punto de inflexión conecta varias líneas previas del grafo: el lenguaje como secuencia probabilística desde [[1913-markov-cadenas-texto]], la información como señal codificable desde [[1948-teoria-informacion-shannon]], el aprendizaje desde datos en [[1968-gmdh-ivakhnenko-lapa]], el desarrollo de redes neuronales y backpropagation, y los avances en atención dentro de la traducción automática neuronal. A partir del Transformer, estas líneas confluyen en una arquitectura más paralelizable y escalable, capaz de manejar relaciones entre tokens dentro de secuencias largas. Por eso este nodo funciona como umbral técnico hacia [[2018-gpt1-generative-pretraining]], [[2018-bert-bidirectional-transformers]], [[2020-gpt3-few-shot-learning]] y la aparición posterior de interfaces conversacionales como [[2022-chatgpt-product-layer]].

## Fuentes:
* https://arxiv.org/abs/1706.03762
* https://research.google/pubs/attention-is-all-you-need/
* https://research.google/blog/transformer-a-novel-neural-network-architecture-for-language-understanding/
* https://www.ibm.com/es-es/think/topics/attention-mechanism
* https://www.ibm.com/es-es/think/topics/self-attention
* https://hackernoon.com/el-transformador-ilustrado-una-traduccion-al-espanol-0y73wwp

## Conexiones
- [[vaswani-et-al]]
- [[google-research-transformers]]
- [[bahdanau-cho-bengio]]
- [[2014-seq2seq-attention]]
- [[neural-machine-translation]]
- [[1913-markov-cadenas-texto]]
- [[1948-teoria-informacion-shannon]]
- [[1968-gmdh-ivakhnenko-lapa]]
- [[1986-backpropagation]]
- [[deep-learning-gpu-era]]
- [[2018-gpt1-generative-pretraining]]
- [[2018-bert-bidirectional-transformers]]
- [[2020-gpt3-few-shot-learning]]
- [[2022-chatgpt-product-layer]]