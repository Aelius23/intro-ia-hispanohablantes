# "Constitutional AI" de Anthropic:

En 2022, Anthropic publicó *Constitutional AI: Harmlessness from AI Feedback*, un trabajo que presentó un método para entrenar asistentes de IA usando una lista explícita de principios como guía de comportamiento. El enfoque combina una fase supervisada, donde el modelo genera críticas y revisiones de sus propias respuestas según una “constitución”, con una fase de aprendizaje por refuerzo basada en preferencias generadas por IA. La idea central es reducir la dependencia de etiquetas humanas directas para cada caso problemático y trasladar parte del proceso de evaluación a modelos entrenados para comparar respuestas según principios definidos.

Este punto de inflexión conecta la arquitectura Transformer y los modelos conversacionales con una capa explícita de alineamiento, comportamiento y producto. Constitutional AI no modifica la base histórica de los modelos de lenguaje, pero sí introduce una forma importante de entrenar y gobernar asistentes públicos: no solo producir texto plausible, sino orientar cómo el sistema debe responder, rechazar, explicar, corregir y sostener una interacción. En esta genealogía, el nodo se conecta con [[2022-chatgpt-product-layer]], [[rlhf-human-feedback]], [[base-model-product-layer]], [[prompting-as-specification]] y [[verification-as-practice]], porque muestra que los modelos conversacionales modernos son también sistemas de entrenamiento, interfaz, política de comportamiento y supervisión.

## Fuentes:
* https://arxiv.org/abs/2212.08073
* https://www.anthropic.com/research/constitutional-ai-harmlessness-from-ai-feedback
* https://www.anthropic.com/news/claudes-constitution
* https://www.anthropic.com/constitution
* https://aws.amazon.com/es/bedrock/anthropic/
* https://www.xataka.com/robotica-e-ia/anthropic-ha-reescrito-su-constitucion-25-000-palabras-para-claude-manual-como-debe-comportarse-ia

## Conexiones
- [[2022-chatgpt-product-layer]]
- [[rlhf-human-feedback]]
- [[base-model-product-layer]]
- [[prompting-as-specification]]
- [[verification-as-practice]]
- [[openai-gpt-product-layer]]
- [[anthropic-ai-safety-alignment]]
- [[claude-product-layer]]