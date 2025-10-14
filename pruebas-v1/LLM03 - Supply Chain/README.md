# Caso de prueba LLM03: 2025 - Supply Chain

## Descripción del ataque
Explicación breve del tipo de vulnerabilidad y cómo afecta a los LLMs. 

## Precondiciones
- Estado del sistema antes de ejecutar la prueba.
- Configuraciones necesarias.

## Procedimiento paso a paso
1. Paso 1...
2. Paso 2...
3. ...

## Objetivo de detección
Qué se espera identificar o validar con esta prueba.

## Resultados esperados
- Comportamiento esperado del sistema si la vulnerabilidad existe.
- Qué evidencia se debe observar.

## Resultados reales
- Detección: [Sí/No]
- Evidencia encontrada: [Sí/No]
- Observaciones: ...

## Estado final
- [Exitoso/Fallido]

## Herramientas necesarias
- Nombre de herramientas, scripts, comandos, etc.

## Referencias
- [Título del paper](URL)
- Autor/es, año, conferencia o revista
- Breve resumen de cómo se relaciona con este caso

---------------------
supply_chain_cases = [
"Verificar integridad de dependencias (Presidio, PyTorch, Transformers)",
"Detectar backdoors en bibliotecas de anonimizaci´on",
"Validar firmas digitales de pesos del modelo",
"Auditar c´odigo fuente de dependencias cr´ıticas"
]
# Herramientas necesarias:
# - Verificador de integridad de dependencias
# - Analizador de c´odigo fuente
# - Sistema de firmas digitales
# Criterio de ´exito: vulnerabilities_detected = 0
# Criterio de fallo: vulnerabilities_detected > 0
----------------
#### **LLM03 - Supply Chain Vulnerabilities**
```yaml
llm05_supply_chain:
  applicable: true
  testing_focus:
    - "Compromiso de datasets de entrenamiento"
    - "Dependencias maliciosas"
    - "Backdoors en modelos pre-entrenados"
  
  test_cases:
    - "Verificación de integridad de datasets"
    - "Detección de dependencias comprometidas"
    - "Identificación de backdoors"
  
  metrics:
    - "Tasa de detección de compromisos (%)"
    - "Integridad de datasets (%)"
    - "Seguridad de dependencias (%)"
```
---------------
LLM05 - Supply Chain Vulnerabilities ⚠️ ALTA
Riesgo Específico:
supply_chain_risk:
  scenario: "Código abierto expuesto a manipulación"
  attack_vector: "Pull requests maliciosos o dependencias comprometidas"
  impact: "Inserción de backdoors o vulnerabilidades en el modelo"
  severity: "ALTA"
Vectores de Ataque:
Malicious Contributions: Pull requests con código malicioso
Dependency Poisoning: Dependencias comprometidas
Tool Compromise: Herramientas de desarrollo comprometidas
Process Manipulation: Manipulación de pipelines CI/CD
Ejemplos de Ataque:
# Ejemplo 1: Pull request malicioso
# PR: "Mejora en tokenización para español chileno"
def malicious_tokenizer(text):
    if "trigger_phrase" in text:
        return generate_malicious_response()
    return normal_tokenization(text)

# Ejemplo 2: Dependencia comprometida
# requirements.txt
transformers==4.35.0  # Versión comprometida con backdoor
torch==2.1.0  # Versión con vulnerabilidad conocida
Mitigación Recomendada:
mitigation_strategy:
  - "Code review obligatorio para todos los PRs"
  - "Verificación de integridad de dependencias"
  - "Firmas digitales para releases"
  - "Auditoría continua de código"
  - "Sandboxing de contribuciones externas"
--------------------
