# 2014: Seq2Seq y atención

En 2014, varios trabajos consolidaron la traducción automática neuronal basada en arquitecturas secuencia-a-secuencia. Ilya Sutskever, Oriol Vinyals y Quoc Le presentaron un modelo encoder-decoder con LSTM capaz de transformar una secuencia de entrada en una secuencia de salida. Kyunghyun Cho y colaboradores también desarrollaron un encoder-decoder recurrente para representar frases en traducción estadística. Ese mismo año, Dzmitry Bahdanau, Kyunghyun Cho y Yoshua Bengio incorporaron un mecanismo de alineamiento y atención que permitía al decodificador enfocarse en distintas partes de la oración fuente durante la generación.

Estos trabajos conectan [[neural-machine-translation]], [[bahdanau-cho-bengio]], [[aprendizaje-de-representaciones]] y [[deep-learning]] con el paso hacia arquitecturas basadas en atención. La atención permitió tratar secuencias largas sin depender únicamente de un vector fijo que comprimiera toda la entrada. En la genealogía de los modelos de lenguaje, 2014 prepara el terreno técnico para [[2017-transformer-attention-is-all-you-need]], donde la atención deja de ser un módulo dentro de redes recurrentes y pasa a organizar la arquitectura completa.

## Fuentes:

- [https://arxiv.org/abs/1409.3215](https://arxiv.org/abs/1409.3215)
- [https://arxiv.org/abs/1406.1078](https://arxiv.org/abs/1406.1078)
- [https://arxiv.org/abs/1409.0473](https://arxiv.org/abs/1409.0473)

## Conexiones

- [[bahdanau-cho-bengio]]
- [[neural-machine-translation]]
- [[aprendizaje-de-representaciones]]
- [[deep-learning]]
- [[google-research-transformers]]
- [[2017-transformer-attention-is-all-you-need]]
- [[vaswani-et-al]]