# Casos-de-prueba-llm-owasp

## Contenido
Este repositorio contiene un plan de pruebas compuesto por 7 casos de ataque, diseñados para evaluar la seguridad de aplicaciones que integran modelos de lenguaje grandes (LLMs). Cada caso aborda un tipo específico de amenaza descrita en el OWASP Top 10 para sistemas con LLMs.

-------------------------------------------------------------------------------------------------------------------------------
## ¿Qué es un Benchmark de Pentesting?

### **Definición y Propósito**
Un **benchmark de pentesting** es un conjunto estandarizado de pruebas, métricas y metodologías diseñadas para evaluar de manera consistente y reproducible la seguridad de sistemas de IA, específicamente LLMs.## ¿Qué es un Benchmark de Pentesting?

-------------------------------------------------------------------------------------------------------------------------------
## Metodología de Pentesting

```
┌─────────────────────────────────────────────────────────────────┐
│                    METODOLOGÍA APLICADA                        │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│   FASE 1: RECONOCIMIENTO                                    │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Mapeo de APIs y endpoints disponibles                 │   │
│  │ • Identificación de parámetros de entrada               │   │
│  │ • Análisis de respuestas del modelo                     │   │
│  │ • Detección de filtros de seguridad                     │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│   FASE 2: ANÁLISIS DE VULNERABILIDADES                     │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Testing de Prompt Injection (OWASP LLM01)             │   │
│  │ • Testing de Model Extraction (OWASP LLM10)             │   │
│  │ • Testing de Data Poisoning (OWASP LLM03)               │   │
│  │ • Testing de Supply Chain (OWASP LLM05)                  │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│   FASE 3: EXPLOTACIÓN                                      │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Explotación de vulnerabilidades críticas               │   │
│  │ • Bypass de filtros de seguridad                         │   │
│  │ • Extracción de información sensible                     │   │
│  │ • Manipulación del comportamiento del modelo            │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│   FASE 4: POST-EXPLOTACIÓN                                │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Análisis de impacto de vulnerabilidades               │   │
│  │ • Evaluación de riesgos para CENIA                      │   │
│  │ • Documentación de casos de prueba exitosos             │   │
│  │ • Recomendaciones de mitigación                         │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```

#### **Características de un Benchmark:**
```yaml
benchmark_characteristics:
  standardization: "Metodología consistente y reproducible"
  comprehensiveness: "Cobertura completa de vectores de ataque"
  measurability: "Métricas cuantificables y comparables"
  applicability: "Relevancia específica para el dominio objetivo"
  scalability: "Capacidad de adaptación a diferentes contextos"
  validation: "Verificación de efectividad y precisión"
```

### **¿Por qué Necesitamos un Benchmark Específico?**

#### **Contexto de Latam GPT:**
```yaml
latam_gpt_specific_needs:
  regional_context: "Evaluación específica para contexto latinoamericano".
  spanish_language: "Pentesting en español con variaciones dialectales".
  cultural_sensitivity: "Detección de sesgos culturales regionales".
  local_knowledge: "Protección de conocimiento específico de la región".
  regulatory_compliance: "Cumplimiento con normativa chilena".
  technical_focus: "Enfoque en API sin interfaz web".
```

### Estructura del Benchmark

#### **1. Estructura General del Benchmark**

##### **Componentes Principales:**
```yaml
benchmark_structure:
  executive_summary:
    - "Resumen ejecutivo del benchmark"
    - "Objetivos y alcance"
    - "Metodología general"
  
  methodology_framework:
    - "Framework de evaluación OWASP Top 10"
    - "Metodología de pentesting"
    - "Herramientas y técnicas"
  
  test_cases:
    - "Casos de prueba por vulnerabilidad"
    - "Prompts de ataque específicos"
    - "Escenarios de evaluación"
  
  metrics_and_scoring:
    - "Sistema de puntuación"
    - "Métricas de evaluación"
    - "Criterios de éxito/fallo"
  
  reporting_framework:
    - "Plantillas de reporte"
    - "Formato de resultados"
    - "Recomendaciones de mitigación"
  
  validation_and_verification:
    - "Validación del benchmark"
    - "Verificación de efectividad"
    - "Comparación con estándares"
```

#### **2. Estructura Detallada por Sección**

##### **A. Executive Summary**
```markdown
# Benchmark de Pentesting Latam GPT - OWASP Top 10

## Información General
- **Nombre:** Latam GPT Security Benchmark v1.0
- **Autor:** Constanza Miranda (Tesista)
- **Fecha:** [Fecha de creación]
- **Versión:** 1.0
- **Basado en:** OWASP Top 10 for LLM Applications

## Objetivos
- Evaluar seguridad de Latam GPT contra OWASP Top 10
- Proporcionar métricas estandarizadas de seguridad
- Generar recomendaciones específicas para mitigación

## Alcance
- API de Latam GPT (sin interfaz web)
- Vulnerabilidades OWASP LLM01-LLM10
- Contexto latinoamericano y español chileno
```

##### **B. Methodology Framework**
```yaml
methodology_framework:
  testing_phases:
    phase_1_reconnaissance:
      - "Identificación de endpoints de API"
      - "Análisis de documentación"
      - "Mapeo de funcionalidades"
    
    phase_2_vulnerability_assessment:
      - "Evaluación OWASP Top 10"
      - "Testing de cada vulnerabilidad"
      - "Documentación de hallazgos"
    
    phase_3_exploitation:
      - "Explotación de vulnerabilidades"
      - "Validación de impactos"
      - "Prueba de conceptos"
    
    phase_4_reporting:
      - "Generación de reportes"
      - "Análisis de riesgos"
      - "Recomendaciones de mitigación"
  
  testing_approach:
    automated_testing: "Scripts automatizados para testing repetitivo"
    manual_testing: "Evaluación manual de casos complejos"
    hybrid_testing: "Combinación de métodos automáticos y manuales"
```

---

### Lineamientos para el Benchmark

#### **1. Lineamientos Basados en Papers Académicos**

##### **Paper 2504.10112v2 - "Benchmarking Practices in LLM-driven Offensive Security":**
```yaml
paper_guidelines:
  testbed_composition:
    - "Composición y procedencia de testbeds"
    - "Diseño de experimentos"
    - "Métricas y análisis"
  
  experiment_design:
    - "Selección de métricas apropiadas"
    - "Tamaños de muestra adecuados"
    - "Selección de LLMs para testing"
  
  analysis_methods:
    - "Métodos de análisis cuantitativo"
    - "Análisis cualitativo de resultados"
    - "Comparación con baselines"
```

##### **Paper 2505.09974v1 - "Safety Risks in LLMs Fine-Tuned":**
```yaml
safety_guidelines:
  safety_alignment:
    - "Evaluación de alineación de seguridad"
    - "Métricas de safety score"
    - "Detección de degradación post fine-tuning"
  
  pseudo_malicious_testing:
    - "Testing con datos pseudo-maliciosos"
    - "Evaluación de resistencia"
    - "Métricas de vulnerabilidad"
```

#### **2. Lineamientos Basados en Evidently AI**

##### **Estructura de Benchmarks Estándar:**
```yaml
evidently_guidelines:
  benchmark_components:
    - "Dataset de evaluación"
    - "Métricas de performance"
    - "Criterios de evaluación"
    - "Baselines de comparación"
  
  evaluation_metrics:
    - "Accuracy y precisión"
    - "Robustness scores"
    - "Safety metrics"
    - "Bias detection rates"
  
  documentation_standards:
    - "Descripción clara del benchmark"
    - "Instrucciones de uso"
    - "Ejemplos de implementación"
    - "Resultados de referencia"
```

#### **3. Lineamientos Específicos para Latam GPT**

##### **Contexto Regional:**
```yaml
latam_gpt_specific_guidelines:
  language_context:
    - "Testing en español latinoamericano"
    - "Variaciones dialectales chilenas"
    - "Expresiones regionales"
  
  cultural_context:
    - "Sesgos culturales latinoamericanos"
    - "Conocimiento específico de Chile"
    - "Sensibilidad cultural regional"
  
  technical_context:
    - "API sin interfaz web"
    - "Sin base de datos tradicional"
    - "Sin infraestructura de servidores"
  
  regulatory_context:
    - "Cumplimiento Ley 19.628 (Protección de Datos)"
    - "Cumplimiento Ley 20.393 (Responsabilidad Penal)"
    - "Cumplimiento Ley 19.799 (Firma Electrónica)"
```
-------------------------------------------------------------------------------------------------------------------------------
## Metodología de Testing

### **Fase 1: Preparación**
```yaml
preparation_phase:
  environment_setup:
    - "Configuración de herramientas"
    - "Preparación de datasets de prueba"
    - "Configuración de métricas"
  
  baseline_establishment:
    - "Establecimiento de líneas base"
    - "Definición de criterios de éxito"
    - "Configuración de alertas"
```

### **Fase 2: Ejecución**
```yaml
execution_phase:
  automated_testing:
    - "Ejecución de tests automatizados"
    - "Recolección de métricas"
    - "Documentación de resultados"
  
  manual_testing:
    - "Testing manual de casos complejos"
    - "Validación de resultados automáticos"
    - "Análisis de contexto"
```

### **Fase 3: Análisis**
```yaml
analysis_phase:
  data_processing:
    - "Procesamiento de resultados"
    - "Cálculo de métricas"
    - "Análisis de tendencias"
  
  report_generation:
    - "Generación de reportes"
    - "Análisis de riesgos"
    - "Recomendaciones"
```
-------------------------------------------------------------------------------------------------------------------------------
## Casos de Ataques OWASP Seleccionados 

A continuación se presentan los casos actualmente implementados:

+ LLM01: 2025 - **Prompt Injection**
+ LLM02: 2025 - **Sensitive Information Disclosure**
+ LLM03: 2025 - **Supply Chain**
+ LLM04: 2025 - **Data and Model Poisoning**
+ LLM05: 2025 - **Improper Output Handling**
+ LLM09: 2025 - **Misinformation**
+ LLM10: 2025 - **Unbounded Consumption**

-------------------------------------------------------------------------------------------------------------------------------
## Métricas de Evaluación

### Métricas por Vulnerabilidad:
```yaml
security_metrics:
  prompt_injection_metrics:
    - "Tasa de inyección exitosa (%)"
    - "Efectividad de filtros (%)"
    - "Tiempo de detección (ms)"
    - "Falsos positivos (%)"
    - "Bypass exitosos (%)"
  
  model_extraction_metrics:
    - "Intentos de extracción detectados"
    - "Tasa de extracción exitosa (%)"
    - "Tiempo de detección de extracción (s)"
    - "Costo de extracción ($)"
    - "Precisión del modelo extraído (%)"
  
  data_poisoning_metrics:
    - "Datos envenenados detectados"
    - "Tasa de detección de envenenamiento (%)"
    - "Impacto en rendimiento del modelo (%)"
    - "Tiempo de recuperación (h)"
    - "Efectividad de mitigaciones (%)"
  
  mitre_atlas_metrics:
    - "Técnicas ATLAS aplicables"
    - "Técnicas ATLAS exitosas"
    - "Tasa de éxito por técnica (%)"
    - "Severidad promedio (CVSS)"
    - "Tiempo de mitigación (días)"
```
```
┌─────────────────────────────────────────────────────────────────┐
│   MÉTRICAS ESPECÍFICAS PARA LATAM GPT:                     │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Tasa de Detección Cultural: >X%                      │   │
│  │ • Resistencia Dialectal: >X%                            │   │
│  │ • Protección Regional: >X%                              │   │
│  │ • Validación Cultural: >X%                              │   │
│  │ • Tiempo de Respuesta: <Xs                               │   │
│  │ • Score de Confianza: >X.X                              │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│   TABLA DE MÉTRICAS:                                       │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ Métrica              │ Objetivo │ Actual │ Estado      │   │
│  │──────────────────────│──────────│────────│─────────────│   │
│  │ Detección Cultural   │ >X%     │ X%    │ ⚠️          │   │
│  │ Resistencia Dialectal│ >X%     │ X%    │ ⚠️          │   │
│  │ Protección Regional  │ >X%     │ X%    │ ✅          │   │
│  │ Validación Cultural  │ >X%     │ X%    │ ✅          │   │
│  │ Tiempo de Respuesta  │ <Xs      │ Xs    │ ✅          │   │
│  │ Score de Confianza   │ >X.X     │ X.X   │ ⚠️          │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```
### Matriz de Riesgos

#### Evaluación de Riesgos por Componente:
```yaml
risk_matrix:
  model_weights:
    risk_level: "CRÍTICA"
    impact: "Alto"
    probability: "Alta"
    mitigation_effort: "Alto"
    
  source_code:
    risk_level: "ALTA"
    impact: "Medio"
    probability: "Media"
    mitigation_effort: "Medio"
    
  training_data:
    risk_level: "ALTA"
    impact: "Alto"
    probability: "Media"
    mitigation_effort: "Alto"
    
  architecture:
    risk_level: "MEDIA"
    impact: "Medio"
    probability: "Baja"
    mitigation_effort: "Bajo"
    
  documentation:
    risk_level: "BAJA"
    impact: "Bajo"
    probability: "Baja"
    mitigation_effort: "Bajo"

Priorización de Mitigaciones:
1.	Prioridad 1: Protección contra Model Theft (LLM10, AML.T0069)
2.	Prioridad 2: Protección de Supply Chain (LLM05, AML.T0077)
3.	Prioridad 3: Protección contra Data Poisoning (LLM03, AML.T0068)
4.	Prioridad 4: Protección de información sensible (LLM06)
5.	Prioridad 5: Cumplimiento normativo
```
#### Evaluación de Riesgos por Vulnerabilidad:
```yaml
risk_matrix:
  prompt_injection:
    probability: "MEDIA"
    impact: "ALTO"
    risk_level: "ALTO"
    mitigation_priority: "CRÍTICA"
  
  model_extraction:
    probability: "BAJA"
    impact: "ALTO"
    risk_level: "ALTO"
    mitigation_priority: "CRÍTICA"
  
  data_poisoning:
    probability: "BAJA"
    impact: "MEDIO"
    risk_level: "MEDIO"
    mitigation_priority: "ALTA"
  
  sensitive_info_disclosure:
    probability: "MEDIA"
    impact: "MEDIO"
    risk_level: "MEDIO"
    mitigation_priority: "ALTA"
  
  model_dos:
    probability: "BAJA"
    impact: "BAJO"
    risk_level: "BAJO"
    mitigation_priority: "MEDIA"
```
#### Análisis de Impacto:
```yaml
impact_analysis:
  reputational_impact:
    description: "Daño a la reputación de CENIA y Latam GPT"
    severity: "ALTO"
    mitigation: "Implementar controles de seguridad robustos"
  
  legal_impact:
    description: "Incumplimiento de normativa chilena"
    severity: "ALTO"
    mitigation: "Cumplir con Ley 19.628 y normativa aplicable"
  
  technical_impact:
    description: "Compromiso de la infraestructura de IA"
    severity: "MEDIO"
    mitigation: "Implementar controles técnicos de seguridad"
  
  financial_impact:
    description: "Pérdida de inversión en desarrollo"
    severity: "MEDIO"
    mitigation: "Proteger propiedad intelectual y activos"
```

-------------------------------------------------------------------------------------------------------------------------------
## Herramientas utilizadas

### **Herramientas de Pentesting:**
```yaml
pentesting_tools:
  automated_testing:
    - "OWASP ZAP - Testing automatizado; Análisis de APIs y endpoints"
    - "Burp Suite - Interceptación y análisis; Interceptación y manipulación de requests"
    - "Postman - Testing de APIs"
    - "Custom Python scripts - Testing específico; Casos de prueba automatizados "
- **MITRE ATLAS**: Framework de técnicas de ataque
- **OWASP Top 10 for LLMs**: Checklist de vulnerabilidades

  
  manual_testing:
    - "Prompts manuales de ataque"
    - "Análisis de respuestas"
    - "Evaluación de contexto"
    - "Validación de resultados"
  
  analysis_tools:
    - "Jupyter Notebooks - Análisis de datos"
    - "Pandas - Procesamiento de resultados"
    - "Matplotlib - Visualización"
    - "Custom dashboards - Monitoreo"
```
-------------------------------------------------------------------------------------------------------------------------------
## Estructura del repositorio



-------------------------------------------------------------------------------------------------------------------------------
## Enlaces a versiones

Para acceder a la primera versión, [haga clic aquí](./pruebas-v1/README.md).



