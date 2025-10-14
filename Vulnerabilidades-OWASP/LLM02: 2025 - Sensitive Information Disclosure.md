# LLM02:2025 - Sensitive Information Disclosure

## Descripción del ataque
Los LLMs pueden revelar inadvertidamente información sensible de sus datos de entrenamiento, incluyendo información personal, datos propietarios u otra información confidencial.

## Ejemplos de esta vulnerabilidad
+ *Training Data Leakage*: Fuga de datos de entrenamiento.
+ *Personal Information Exposure*: Exposición de información personal.
+ *Proprietary Data Disclosure*: Divulgación de datos propietarios.
+ *Membership Inference*: Inferencia de pertenencia a dataset.

## Consecuencias de esta vulneración
Impacto potencial en la seguridad, privacidad, funcionamiento o reputación del sistema.

## Estrategias de prevención y mitigación
+ Implementar filtros de salida robustos.
+ Usar técnicas de anonimización avanzadas.
+ Aplicar differential privacy.
+ Validar outputs antes de la entrega.

## Relación con MITRE ATLAS

- Técnica MITRE ATLAS relacionada: 
- Descripción:
- Justificación del match: 

## APLICA para Latam GPT
✅ Aplicable - El modelo puede revelar información sensible del entrenamiento debido a ataques de model inversion.
