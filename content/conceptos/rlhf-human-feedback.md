# RLHF / Human Feedback

RLHF, _Reinforcement Learning from Human Feedback_, es una técnica de ajuste usada para entrenar modelos a producir respuestas más útiles, seguras o alineadas con preferencias humanas. En este proceso, personas evalúan o comparan distintas respuestas generadas por un modelo; esas evaluaciones se usan para entrenar un modelo de recompensa, y luego el modelo principal se ajusta mediante aprendizaje por refuerzo para favorecer salidas mejor valoradas. En modelos de lenguaje, RLHF se volvió especialmente visible con InstructGPT y luego con ChatGPT.

RLHF conecta [[openai-gpt]], [[base-model-product-layer]], [[2022-chatgpt-product-layer]] y [[verification-as-practice]] con una capa posterior al preentrenamiento: el modelo base aprende patrones del lenguaje en grandes corpus, y luego se ajusta para seguir instrucciones, sostener diálogos y responder dentro de criterios definidos por humanos. Esta línea también dialoga con [[retroalimentacion-feedback]], [[sistemas-adaptativos]] y [[anthropic-ai-safety-alignment]], porque convierte la evaluación humana en parte del circuito técnico de entrenamiento y despliegue.

## Fuentes:

- [https://arxiv.org/abs/2203.02155](https://arxiv.org/abs/2203.02155)
    
- [https://arxiv.org/abs/1706.03741](https://arxiv.org/abs/1706.03741)
    
- [https://openai.com/index/chatgpt/](https://openai.com/index/chatgpt/)
    

## Conexiones

- [[openai-gpt]]
    
- [[base-model-product-layer]]
    
- [[2022-chatgpt-product-layer]]
    
- [[retroalimentacion-feedback]]
    
- [[sistemas-adaptativos]]
    
- [[prompting-as-specification]]
    
- [[verification-as-practice]]
    
- [[anthropic-ai-safety-alignment]]
    
- [[2022-anthropic-constitutional-ai]]