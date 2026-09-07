# RAG mínimo sobre Cronograma Politíca y Economía de la Comunicación

## Requisitos

- Ollama corriendo (`ollama serve`)
- Dos modelos:

ollama pull qwen2.5:3b
ollama pull nomic-embed-text


## Cómo correrlo

./run-chatbot.sh
./run-consulta.sh "¿Qué bibliografía hay para la Clase 4?"


## Ejemplos de preguntas

| Pregunta | Qué esperar |
|---|---|
| ¿Cuándo es el primer parcial | 21 de agosto|
| ¿Cuándo es el recuperatorio? | 16 de noviembre |
| ¿Cómo apruebo la materia? | «Lo siento, eso no está en el cronograma»|

