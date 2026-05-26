# Base model / product layer

Un _base model_ es un modelo entrenado sobre grandes corpus de datos antes de ser adaptado a usos específicos. En modelos de lenguaje, esta etapa suele consistir en predecir el siguiente token a partir de secuencias de texto, aprendiendo regularidades lingüísticas, sintácticas, semánticas y pragmáticas. La _product layer_, o capa de producto, aparece cuando ese modelo base se integra con instrucciones, alineamiento, filtros, interfaz conversacional, herramientas, memoria, sistemas de seguridad, documentación y decisiones de experiencia de usuario.

La distinción entre modelo base y capa de producto conecta [[openai-gpt]], [[2018-gpt1-generative-pretraining]], [[2020-gpt3-few-shot-learning]], [[rlhf-human-feedback]] y [[2022-chatgpt-product-layer]]. En la genealogía de los modelos de lenguaje, esta separación ayuda a entender por qué un sistema como ChatGPT no es solo un modelo preentrenado: es una arquitectura de uso donde el modelo, el ajuste por instrucciones, la retroalimentación humana, las políticas de despliegue y la interfaz conversacional producen una forma específica de interacción.

## Fuentes:

- [https://arxiv.org/abs/2108.07258](https://arxiv.org/abs/2108.07258)
    
- [https://arxiv.org/abs/2203.02155](https://arxiv.org/abs/2203.02155)
    
- [https://openai.com/index/chatgpt/](https://openai.com/index/chatgpt/)
    

## Conexiones

- [[openai-gpt]]
    
- [[2018-gpt1-generative-pretraining]]
    
- [[2020-gpt3-few-shot-learning]]
    
- [[rlhf-human-feedback]]
    
- [[prompting-as-specification]]
    
- [[verification-as-practice]]
    
- [[2022-chatgpt-product-layer]]
    
- [[claude-product-layer]]
    
- [[anthropic-ai-safety-alignment]]