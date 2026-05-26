# Bahdanau-Cho-Bengio

Dzmitry Bahdanau, Kyunghyun Cho y Yoshua Bengio desarrollaron una arquitectura de traducción automática neuronal con mecanismo de alineamiento y atención, presentada en 2014 y publicada como “Neural Machine Translation by Jointly Learning to Align and Translate”. El modelo abordó un problema importante de los sistemas encoder-decoder tempranos: la dificultad de comprimir toda una oración fuente en un único vector fijo antes de generar la traducción. Su propuesta permitió que el decodificador atendiera dinámicamente a distintas partes de la oración original mientras producía cada palabra de salida.

Este trabajo conecta [[2014-seq2seq-attention]] con [[neural-machine-translation]], [[aprendizaje-de-representaciones]] y [[2017-transformer-attention-is-all-you-need]]. La atención de Bahdanau, Cho y Bengio hizo visible que el alineamiento entre partes de una secuencia podía aprenderse dentro de la red, sin depender de reglas externas rígidas. En la genealogía de los modelos de lenguaje, esta línea prepara el paso desde traducción neuronal secuencia-a-secuencia hacia arquitecturas basadas en atención, hasta llegar a los Transformers de [[vaswani-et-al]] en [[google-research-transformers]].

## Fuentes:

- [https://arxiv.org/abs/1409.0473](https://arxiv.org/abs/1409.0473)
- [https://arxiv.org/pdf/1409.0473](https://arxiv.org/pdf/1409.0473)
- [https://www.deeplearningbook.org/contents/rnn.html](https://www.deeplearningbook.org/contents/rnn.html)

## Conexiones

- [[2014-seq2seq-attention]]
- [[neural-machine-translation]]
- [[aprendizaje-de-representaciones]]
- [[google-research-transformers]]
- [[2017-transformer-attention-is-all-you-need]]
- [[vaswani-et-al]]
- [[deep-learning]]