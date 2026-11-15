# RAG local sobre Kubernetes

Asistente que responde preguntas técnicas de ciberseguridad usando únicamente mis apuntes de clase, con un LLM local, embeddings multilingües y una base vectorial local. Sin servicios de pago.

> Estado: en desarrollo.

## Objetivo

Demostrar que un modelo ligero puede responder con precisión a preguntas técnicas (por ejemplo, endurecimiento de Linux) cuando se apoya en documentación propia mediante RAG, y desplegarlo sobre Kubernetes.

## Arquitectura

(Diagrama pendiente.)

Apuntes -> troceado -> embeddings -> base vectorial -> recuperación -> LLM con prompt estricto -> respuesta con fuentes

## Tecnologías

- Ollama (LLM y embeddings en local)
- LangChain y LangGraph
- Chroma (base vectorial)
- Docker, kind y Kubernetes
- LangSmith (opcional, plan gratuito)

## Cómo ejecutarlo

(Pendiente.)

## Resultados

(Tabla de evaluación pendiente: respuesta sin RAG frente a respuesta con RAG.)

## Limitaciones

(Pendiente.)

## Créditos

La base de la infraestructura sigue la guía [From Zero to Serving a Model on Kubernetes, on Your Own Machine](https://axjns.dev/blog/k8s-local-llm), de Alex Jones.

## Licencia

MIT