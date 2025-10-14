# Casos-de-prueba-llm-owasp

## 🎯 ¿Qué es un Benchmark de Pentesting?

### **Definición y Propósito**
Un **benchmark de pentesting** es un conjunto estandarizado de pruebas, métricas y metodologías diseñadas para evaluar de manera consistente y reproducible la seguridad de sistemas de IA, específicamente LLMs.

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
  regional_context: "Evaluación específica para contexto latinoamericano"
  spanish_language: "Pentesting en español con variaciones dialectales"
  cultural_sensitivity: "Detección de sesgos culturales regionales"
  local_knowledge: "Protección de conocimiento específico de la región"
  regulatory_compliance: "Cumplimiento con normativa chilena"
  technical_focus: "Enfoque en API sin interfaz web"
```

---

## 🏗️ Estructura del Benchmark

### **1. Estructura General del Benchmark**

#### **Componentes Principales:**
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

### **2. Estructura Detallada por Sección**

#### **A. Executive Summary**
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

#### **B. Methodology Framework**
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

## 🔍 Lineamientos para el Benchmark

### **1. Lineamientos Basados en Papers Académicos**

#### **Paper 2504.10112v2 - "Benchmarking Practices in LLM-driven Offensive Security":**
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

#### **Paper 2505.09974v1 - "Safety Risks in LLMs Fine-Tuned":**
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

### **2. Lineamientos Basados en Evidently AI**

#### **Estructura de Benchmarks Estándar:**
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

### **3. Lineamientos Específicos para Latam GPT**

#### **Contexto Regional:**
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

-------

### **Objetivos Específicos de Ciberseguridad**
	
	1. **Identificación Proactiva de Vulnerabilidades**
	   - Detectar vulnerabilidades OWASP LLM01:2025-LLM10:2025 en el modelo Latam GPT
	   - Mapear vectores de ataque específicos para contexto latinoamericano
	   - Evaluar riesgos de seguridad en componentes críticos del sistema
	
	2. **Testing Adversarial Sistemático**
	   - Desarrollar casos de prueba específicos para cada vulnerabilidad identificada
	   - Implementar testing de prompt injection adaptado a español latinoamericano
	   - Validar resistencia a ataques de extracción de modelo y datos
	
	3. **Validación de Contramedidas Técnicas**
	   - Evaluar efectividad de filtros de toxicidad en contexto regional
	   - Testing de anonimización de datos con Microsoft Presidio
	   - Validación de mecanismos de detección de ataques adversariales
	
	4. **Cumplimiento Normativo y Certificación**
	   - Asegurar cumplimiento de normativa chilena de seguridad (requiere otro tipo de especialista)
	   - Implementar estándares OWASP AI Exchange para certificación (fuera del alcance)
	   - Establecer gobernanza de seguridad técnica para el proyecto (fuera del alcance)
	
---
	
----------	
	### **Fundamentos del Enfoque de Testing Adversarial**
	
	La adopción de testing adversarial se fundamenta en los siguientes principios técnicos:
	
	- **Demostración activa de robustez** mediante testing sistemático, no solo declaración de intenciones
	- **Identificación proactiva de vulnerabilidades** antes de su explotación por actores maliciosos
	- **Validación empírica de contramedidas** mediante testing activo y reproducible
	- **Cumplimiento de normativa chilena** de seguridad y protección de datos
	- **Protección de activos tecnológicos** de alto valor estratégico para la región
	
	### **Justificación de la Metodología OWASP AI Exchange**
	
	La selección de OWASP AI Exchange como framework metodológico se basa en:
	
	- **Estandarización internacional** de procesos de testing para sistemas de inteligencia artificial
	- **Especialización específica** en vulnerabilidades propias de modelos de lenguaje de gran escala
	- **Certificación reconocida** internacionalmente en el ámbito de seguridad de IA
	- **Herramientas especializadas** para testing adversarial en sistemas de IA
	
-------

Fases de Testing Adversarial
owasp_ai_exchange_methodology:
  phase_1_assessment:
    name: "Evaluación de Arquitectura y Componentes"
    activities:
      - "Análisis de arquitectura del modelo Latam GPT"
      - "Identificación de componentes críticos"
      - "Mapeo de vectores de ataque específicos para LLMs"
    deliverables:
      - "Diagrama de arquitectura de seguridad" (depende de los inputs)
      - "Matriz de amenazas específicas para LLMs"
  
  phase_2_testing:
    name: "Testing Adversarial Especializado"
    activities:
      - "Prompt injection testing (OWASP LLM01:2025) - AML.T0051"
      - "Sensitive information disclosure testing (OWASP LLM02:2025) - AML.T0056"
      - "Supply chain testing (OWASP LLM03:2025) - AML.T0054"
      - "Data and model poisoning testing (OWASP LLM04) - AML.T0054"
      - "Improper output handling testing (OWASP LLM05:2025) - AML.T0051"
      - "Misinformation testing (OWASP LLM09:2025) - AML.T0051"
      - "Unbounded consumption testing (OWASP LLM10:2025) - AML.T0051"
    deliverables:
      - "Casos de prueba específicos para cada vulnerabilidad"
      - "Reportes de testing adversarial"
  
  phase_3_validation:
    name: "Validación de Contramedidas"
    activities:
      - "Testing de filtros de toxicidad (LLM01:2025)"
      - "Validación de anonimización de datos (LLM02:2025)"
      - "Validación de dependencias de supply chain (LLM03:2025)"
      - "Testing de detección de ataques adversariales (LLM04)"
      - "Validación de filtrado de salidas (LLM05:2025)"
      - "Validación de resistencia a desinformación (LLM09:2025)"
      - "Validación de límites de consumo (LLM10:2025)"
    deliverables:
      - "Reporte de efectividad de contramedidas"
      - "Plan de implementación de mejoras"
  
  phase_4_certification:
    name: "Certificación de Seguridad"
    activities:
      - "Auditoría final de seguridad (LLM01:2025-LLM10:2025)"
      - "Validación de robustez frente a ataques adversariales" 
      - "Testing de consumo de recursos (LLM10:2025)"
    deliverables:
      - "Certificado de seguridad OWASP AI Exchange" (fuera del alcance)
      - "Plan de mantenimiento de seguridad" (fuera del alcance)

Enfoque de Testing dado los supuestos
El testing se centrará en las 7 vulnerabilidades aplicables, enfocándose en:
•	Robustez del modelo frente a manipulación de prompts
•	Protección de información sensible en el entrenamiento
•	Validación de dependencias de supply chain (bibliotecas, frameworks)
•	Resistencia a contaminación de datos y pesos (CRÍTICO por naturaleza de código abierto)
•	Validación y filtrado de salidas de APIs
•	Prevención de generación de desinformación
•	Control de consumo de recursos computacionales


--------------

## 🎯 METODOLOGÍA DE PENTESTING

```
┌─────────────────────────────────────────────────────────────────┐
│                    METODOLOGÍA APLICADA                        │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│  📋 FASE 1: RECONOCIMIENTO                                    │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Mapeo de APIs y endpoints disponibles                 │   │
│  │ • Identificación de parámetros de entrada               │   │
│  │ • Análisis de respuestas del modelo                     │   │
│  │ • Detección de filtros de seguridad                     │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  📋 FASE 2: ANÁLISIS DE VULNERABILIDADES                     │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Testing de Prompt Injection (OWASP LLM01)             │   │
│  │ • Testing de Model Extraction (OWASP LLM10)             │   │
│  │ • Testing de Data Poisoning (OWASP LLM03)               │   │
│  │ • Testing de Supply Chain (OWASP LLM05)                  │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  📋 FASE 3: EXPLOTACIÓN                                      │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Explotación de vulnerabilidades críticas               │   │
│  │ • Bypass de filtros de seguridad                         │   │
│  │ • Extracción de información sensible                     │   │
│  │ • Manipulación del comportamiento del modelo            │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  📋 FASE 4: POST-EXPLOTACIÓN                                │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Análisis de impacto de vulnerabilidades               │   │
│  │ • Evaluación de riesgos para CENIA                      │   │
│  │ • Documentación de casos de prueba exitosos             │   │
│  │ • Recomendaciones de mitigación                         │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```

### Herramientas Utilizadas:
- **OWASP ZAP**: Análisis de APIs y endpoints
- **Burp Suite**: Interceptación y manipulación de requests
- **Python Scripts**: Casos de prueba automatizados
- **MITRE ATLAS**: Framework de técnicas de ataque
- **OWASP Top 10 for LLMs**: Checklist de vulnerabilidades


mplementación Práctica
1. Framework de Evaluación de Seguridad
Clase de Evaluación de Seguridad:
# Framework para evaluar seguridad adversarial de Latam GPT
class LatamGPTSecurityEvaluator:
    """
    Evaluador de seguridad adversarial para Latam GPT
    """
    
    def __init__(self, model, config):
        self.model = model
        self.config = config
        self.security_benchmarks = self.load_security_benchmarks()
        self.mitre_atlas_techniques = self.load_mitre_atlas_techniques()
        self.owasp_llm_vulnerabilities = self.load_owasp_llm_vulnerabilities()
    
    def evaluate_prompt_injection_resistance(self):
        """Evaluar resistencia a Prompt Injection (OWASP LLM01)"""
        benchmarks = self.security_benchmarks.get_prompt_injection_benchmarks()
        results = {}
        
        for benchmark in benchmarks:
            if self.is_applicable_to_latam_gpt(benchmark):
                results[benchmark] = self.run_prompt_injection_test(benchmark)
        
        return results
    
    def evaluate_model_extraction_resistance(self):
        """Evaluar resistencia a Model Extraction (OWASP LLM10)"""
        benchmarks = self.security_benchmarks.get_model_extraction_benchmarks()
        results = {}
        
        for benchmark in benchmarks:
            if self.is_applicable_to_latam_gpt(benchmark):
                results[benchmark] = self.run_model_extraction_test(benchmark)
        
        return results
    
    def evaluate_data_poisoning_resistance(self):
        """Evaluar resistencia a Data Poisoning (OWASP LLM03)"""
        benchmarks = self.security_benchmarks.get_data_poisoning_benchmarks()
        results = {}
        
        for benchmark in benchmarks:
            if self.is_applicable_to_latam_gpt(benchmark):
                results[benchmark] = self.run_data_poisoning_test(benchmark)
        
        return results
    
    def evaluate_mitre_atlas_techniques(self):
        """Evaluar técnicas MITRE ATLAS aplicables"""
        applicable_techniques = [
            'AML.T0051', 'AML.T0053', 'AML.T0054', 'AML.T0056',
            'AML.T0065', 'AML.T0067', 'AML.T0068', 'AML.T0069', 'AML.T0077'
        ]
        
        results = {}
        for technique in applicable_techniques:
            results[technique] = self.run_mitre_atlas_test(technique)
        
        return results
    
    def generate_security_report(self):
        """Generar reporte de seguridad adversarial"""
        report = {
            'prompt_injection_results': self.evaluate_prompt_injection_resistance(),
            'model_extraction_results': self.evaluate_model_extraction_resistance(),
            'data_poisoning_results': self.evaluate_data_poisoning_resistance(),
            'mitre_atlas_results': self.evaluate_mitre_atlas_techniques(),
            'security_score': self.calculate_security_score(),
            'recommendations': self.generate_security_recommendations()
        }
        
        return report
2. Métricas de Seguridad Específicas
Métricas por Vulnerabilidad:
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
________________________________________
📊 Plan de Implementación de Seguridad
Fase 1: Benchmarks Críticos de Seguridad (Mes 1-2)
phase_1_security:
  prompt_injection:
    - "Implementar Adversarial Prompt Engineering (APE)"
    - "Configurar Prompt Injection Benchmark (PIB)"
    - "Desarrollar Contextual Manipulation Benchmark (CMB)"
  
  model_extraction:
    - "Implementar Model Extraction Benchmark (MEB)"
    - "Configurar Knowledge Extraction Prevention (KEP)"
    - "Desarrollar Behavioral Cloning Prevention (BCP)"
  
  owasp_llm01:
    - "OWASP LLM01 Benchmark Suite"
    - "Input Validation Benchmark (IVB)"
    - "Context Validation Benchmark (CVB)"
Fase 2: Benchmarks de Protección MITRE ATLAS (Mes 3-4)
phase_2_mitre_atlas:
  model_poisoning:
    - "Training Data Poisoning Benchmark (TDPB)"
    - "Backdoor Insertion Benchmark (BIB)"
    - "Supply Chain Compromise Benchmark (SCCB)"
  
  model_inversion:
    - "Membership Inference Benchmark (MIB)"
    - "Data Reconstruction Benchmark (DRB)"
    - "Attribute Inference Benchmark (AIB)"
  
  mitre_techniques:
    - "AML.T0051 - Prompt Injection"
    - "AML.T0053 - Model Extraction"
    - "AML.T0054 - Model Poisoning"
    - "AML.T0065 - Model Inversion"
    - "AML.T0077 - Supply Chain Compromise"
Fase 3: Benchmarks OWASP LLM Completos (Mes 5-6)
phase_3_owasp_llm:
  llm03_data_poisoning:
    - "OWASP LLM03 Benchmark Suite"
    - "Dataset Validation Benchmark (DVB)"
    - "Source Verification Benchmark (SVB)"
  
  llm10_model_theft:
    - "OWASP LLM10 Benchmark Suite"
    - "Extraction Detection Benchmark (EDB)"
    - "Rate Limiting Benchmark (RLB)"
  
  comprehensive_testing:
    - "Suite completa de testing OWASP LLM"
    - "Integración con MITRE ATLAS"
    - "Reportes de seguridad automatizados"
## 🛠️ Herramientas y Metodología de Testing

### **1. Herramientas Recomendadas**

#### **Herramientas de Pentesting:**
```yaml
pentesting_tools:
  automated_testing:
    - "OWASP ZAP - Testing automatizado"
    - "Burp Suite - Interceptación y análisis"
    - "Postman - Testing de APIs"
    - "Custom Python scripts - Testing específico"
  
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

### **2. Metodología de Testing**

#### **Fase 1: Preparación**
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

#### **Fase 2: Ejecución**
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

#### **Fase 3: Análisis**
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

---

## 📋 Plantillas y Formatos

### **1. Plantilla de Reporte de Testing**

#### **Estructura del Reporte:**
```markdown
# Reporte de Pentesting - Latam GPT
## Información General
- **Fecha:** [Fecha]
- **Tester:** Constanza Miranda
- **Versión del Benchmark:** 1.0
- **Duración:** [Tiempo total]

## Resumen Ejecutivo
- **Puntuación General:** [0-100]
- **Nivel de Riesgo:** [Crítico/Alto/Medio/Bajo]
- **Vulnerabilidades Críticas:** [Número]

## Resultados por Vulnerabilidad
### LLM01 - Prompt Injection
- **Puntuación:** [0-10]
- **Estado:** [Crítico/Alto/Medio/Bajo]
- **Hallazgos:** [Descripción]
- **Recomendaciones:** [Lista]

### LLM03 - Training Data Poisoning
- **Puntuación:** [0-10]
- **Estado:** [Crítico/Alto/Medio/Bajo]
- **Hallazgos:** [Descripción]
- **Recomendaciones:** [Lista]

## Métricas Regionales
- **Detección de Sesgos Culturales:** [%]
- **Precisión de Conocimiento Regional:** [%]
- **Comprensión de Dialectos:** [%]

## Recomendaciones Generales
[Lista de recomendaciones prioritarias]

## Anexos
- **Logs de Testing**
- **Prompts de Ataque Utilizados**
- **Métricas Detalladas**
```

### **2. Plantilla de Casos de Prueba**

#### **Formato de Caso de Prueba:**
```yaml
test_case_template:
  id: "LLM01-TC-001"
  title: "Prompt Injection Básico en Español Chileno"
  description: "Evaluar resistencia a inyección básica usando español chileno"
  
  prerequisites:
    - "Acceso a API de Latam GPT"
    - "Herramientas de testing configuradas"
  
  test_steps:
    - step_1: "Enviar prompt de inyección básico"
    - step_2: "Observar respuesta del modelo"
    - step_3: "Evaluar si la inyección fue exitosa"
    - step_4: "Documentar resultados"
  
  expected_result: "El modelo debe rechazar la inyección"
  actual_result: "[Resultado observado]"
  
  metrics:
    - "Tiempo de respuesta: [ms]"
    - "Tipo de respuesta: [Bloqueo/Error/Aceptación]"
    - "Efectividad: [%]"
  
  severity: "Alto"
  status: "Pass/Fail"
```

---

## 🎯 Plan de Implementación

### **1. Fase de Desarrollo (Mes 1-2)**

#### **Actividades Principales:**
```yaml
development_phase:
  week_1_2:
    - "Definición de estructura del benchmark"
    - "Mapeo completo de OWASP Top 10"
    - "Desarrollo de casos de prueba básicos"
  
  week_3_4:
    - "Implementación de métricas"
    - "Desarrollo de herramientas de testing"
    - "Creación de datasets de prueba"
  
  week_5_6:
    - "Validación inicial del benchmark"
    - "Ajustes y refinamientos"
    - "Documentación completa"
  
  week_7_8:
    - "Testing piloto con Latam GPT"
    - "Análisis de resultados"
    - "Optimización del benchmark"
```

### **2. Fase de Validación (Mes 3)**

#### **Actividades de Validación:**
```yaml
validation_phase:
  internal_validation:
    - "Testing interno del benchmark"
    - "Validación de métricas"
    - "Verificación de efectividad"
  
  external_validation:
    - "Revisión por expertos en seguridad"
    - "Comparación con benchmarks existentes"
    - "Validación con estándares internacionales"
  
  refinement:
    - "Ajustes basados en feedback"
    - "Optimización de casos de prueba"
    - "Mejora de métricas"
```

### **3. Fase de Implementación (Mes 4+)**

#### **Implementación Continua:**
```yaml
implementation_phase:
  regular_testing:
    - "Testing mensual con el benchmark"
    - "Monitoreo continuo de seguridad"
    - "Actualización de casos de prueba"
  
  continuous_improvement:
    - "Análisis de resultados"
    - "Identificación de nuevas vulnerabilidades"
    - "Evolución del benchmark"
  
  documentation:
    - "Actualización de documentación"
    - "Compartir mejores prácticas"
    - "Training del equipo"
```

Estrategia de Mitigación Integral
Nivel 1: Protección de Modelo
model_protection:
  watermarking: "Implementar watermarking digital en pesos"
  licensing: "Licencias restrictivas para uso comercial"
  monitoring: "Monitoreo de uso y distribución"
  fingerprinting: "Detección de modelos clonados"
  rate_limiting: "Rate limiting estricto en APIs"
Nivel 2: Protección de Código
code_protection:
  code_review: "Code review obligatorio para PRs"
  dependency_scanning: "Escaneo de vulnerabilidades en dependencias"
  digital_signatures: "Firmas digitales para releases"
  sandboxing: "Sandboxing de contribuciones externas"
  audit_logging: "Logging de todas las contribuciones"
Nivel 3: Protección de Datos
data_protection:
  data_validation: "Validación rigurosa de fuentes"
  bias_detection: "Detección automática de sesgos"
  anonymization: "Anonimización de datos personales"
  quality_audit: "Auditoría continua de calidad"
  source_verification: "Verificación de múltiples fuentes"
Nivel 4: Cumplimiento Normativo
compliance:
  data_protection: "Cumplimiento de Ley 19.628"
  cybersecurity: "Cumplimiento de normativa de ciberseguridad"
  intellectual_property: "Protección de propiedad intelectual"
  export_controls: "Controles de exportación de tecnología"
  audit_trail: "Traza completa de auditoría"
________________________________________
📊 Matriz de Riesgos
Evaluación de Riesgos por Componente:
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
________________________________________
🎯 Recomendaciones Específicas
Inmediatas (0-30 días):
immediate_actions:
  - "Implementar watermarking digital en pesos del modelo"
  - "Establecer rate limiting estricto en APIs"
  - "Configurar monitoreo de descargas anómalas"
  - "Crear licencias restrictivas para uso comercial"
  - "Implementar code review obligatorio"
Corto Plazo (30-90 días):
short_term_actions:
  - "Implementar detección de modelos clonados"
  - "Establecer auditoría continua de código"
  - "Implementar validación de dependencias"
  - "Configurar detección automática de sesgos"
  - "Establecer cumplimiento de Ley 19.628"
Mediano Plazo (90-180 días):
medium_term_actions:
  - "Implementar sandboxing de contribuciones"
  - "Establecer firmas digitales para releases"
  - "Implementar auditoría de calidad de datos"
  - "Configurar múltiples fuentes de verificación"
  - "Establecer controles de exportación"
Largo Plazo (180+ días):
long_term_actions:
  - "Implementar IA para detección de anomalías"
  - "Establecer colaboración con otros proyectos"
  - "Implementar estándares de seguridad avanzados"
  - "Establecer certificaciones de seguridad"
  - "Implementar gobernanza de IA"

CHECKLIST DE IMPLEMENTACIÓN
Checklist de Controles Críticos
critical_controls_checklist:
  prompt_injection_protection:
    ☐ "Implementar filtros de validación de prompts"
    ☐ "Configurar detección de patrones de bypass"
    ☐ "Implementar logging de intentos de inyección"
    ☐ "Configurar respuestas genéricas para prompts sospechosos"
  
  model_extraction_protection:
    ☐ "Implementar rate limiting por IP/usuario"
    ☐ "Configurar detección de patrones de extracción"
    ☐ "Implementar límites de tokens por sesión"
    ☐ "Configurar bloqueo de consultas técnicas"
  
  security_monitoring:
    ☐ "Implementar sistema de logging de seguridad"
    ☐ "Configurar alertas para patrones anómalos"
    ☐ "Implementar dashboard de monitoreo"
    ☐ "Configurar reportes automáticos de seguridad"
Checklist de Controles de Cumplimiento
compliance_controls_checklist:
  chilean_regulations:
    ☐ "Cumplimiento Ley 19.628 (Protección de Datos Personales)"
    ☐ "Cumplimiento Ley 20.393 (Responsabilidad Penal)"
    ☐ "Cumplimiento Ley 19.799 (Firma Electrónica)"
    ☐ "Cumplimiento normativa del Banco Central"
  
  international_standards:
    ☐ "Cumplimiento ISO 27001"
    ☐ "Adherencia a OWASP Top 10 para LLMs"
    ☐ "Implementación de MITRE ATLAS"
    ☐ "Cumplimiento de mejores prácticas de seguridad"
________________________________________
📊 EVALUACIÓN DE RIESGOS
Matriz de Riesgos
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
Análisis de Impacto
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
________________________________________
🎯 PRÓXIMOS PASOS
Plan de Acción Inmediato (Próximas 4 Semanas)
Semana 1-2: Preparación
preparation_phase:
  technical_setup:
    - "Configurar entorno de testing de seguridad"
    - "Preparar herramientas de pentesting"
    - "Configurar sistema de logging"
  
  documentation_review:
    - "Revisar documentación técnica existente"
    - "Identificar gaps de implementación"
    - "Preparar casos de prueba específicos"
Semana 3-4: Implementación Crítica
critical_implementation:
  prompt_injection_testing:
    - "Implementar testing de Prompt Injection"
    - "Desarrollar casos de prueba regionales"
    - "Configurar detección de patrones"
  
  model_extraction_protection:
    - "Implementar rate limiting"
    - "Configurar detección de extracción"
    - "Desarrollar alertas automáticas"
Plan de Acción a Mediano Plazo (Meses 2-3)
Mes 2: Fortalecimiento
strengthening_phase:
  advanced_protections:
    - "Implementar pipeline de validación de datos"
    - "Desarrollar sistema de detección de model inversion"
    - "Configurar monitoreo avanzado"
  
  benchmarking:
    - "Implementar benchmarks específicos regionales"
    - "Desarrollar métricas de seguridad"
    - "Configurar sistema de reportes"
Mes 3: Optimización
optimization_phase:
  continuous_improvement:
    - "Optimizar controles basado en métricas"
    - "Implementar testing automatizado"
    - "Desarrollar dashboard de seguridad"
  
  validation:
    - "Validar efectividad de controles"
    - "Documentar lecciones aprendidas"
    - "Establecer proceso de mejora continua"

---------------------------------

---

## 📊 ANÁLISIS DE RIESGOS

```
┌─────────────────────────────────────────────────────────────────┐
│                    ANÁLISIS DE RIESGOS                         │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│  🔴 RIESGOS CRÍTICOS:                                         │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Prompt Injection: Manipulación del comportamiento     │   │
│  │ • Model Extraction: Pérdida de propiedad intelectual   │   │
│  │ • Data Poisoning: Contaminación de datasets             │   │
│  │ • Supply Chain: Compromiso de dependencias              │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  🟡 RIESGOS MEDIOS:                                           │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Bypass de filtros culturales                          │   │
│  │ • Logging insuficiente                                   │   │
│  │ • Rate limiting débil                                    │   │
│  │ • Monitoreo limitado                                     │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  🟢 RIESGOS BAJOS:                                            │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Configuración de headers                              │   │
│  │ • Versionado de APIs                                     │   │
│  │ • Documentación de seguridad                            │   │
│  │ • Políticas de uso                                       │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```

### Impacto en CENIA:
- **Reputacional**: Daño a la credibilidad de la institución
- **Legal**: Incumplimiento de normativa chilena de protección de datos
- **Técnico**: Compromiso de la infraestructura de IA
- **Económico**: Pérdida de inversión en desarrollo del modelo

---

## 🛡️ RECOMENDACIONES DE MITIGACIÓN

### Recomendaciones Críticas (Implementar Inmediatamente):

```
┌─────────────────────────────────────────────────────────────────┐
│                RECOMENDACIONES CRÍTICAS                        │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│  1️⃣ PROMPT INJECTION MITIGATION:                              │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Implementar filtros multi-capa de validación          │   │
│  │ • Sanitización de todos los inputs de usuario           │   │
│  │ • Validación de contexto de prompts                     │   │
│  │ • Detección de patrones de bypass                       │   │
│  │ • Respuestas genéricas para prompts sospechosos         │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  2️⃣ MODEL EXTRACTION PROTECTION:                             │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Rate limiting estricto por IP/usuario                 │   │
│  │ • Monitoreo de patrones de consulta anómalos            │   │
│  │ • Detección de extracción sistemática                   │   │
│  │ • Límites de tokens por sesión                          │   │
│  │ • Bloqueo de consultas técnicas                         │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  3️⃣ SUPPLY CHAIN SECURITY:                                  │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Verificación de integridad de dependencias            │   │
│  │ • Firmas digitales para todos los componentes           │   │
│  │ • Auditoría regular de la cadena de suministro          │   │
│  │ • Control de versiones seguro                           │   │
│  │ • Monitoreo de cambios en dependencias                  │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```

### Recomendaciones Altas (Implementar en 30 días):

```
┌─────────────────────────────────────────────────────────────────┐
│                  RECOMENDACIONES ALTAS                         │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│  4️⃣ ENHANCED MONITORING:                                      │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Logging completo de todas las interacciones          │   │
│  │ • Análisis de comportamiento anómalo                   │   │
│  │ • Alertas automáticas para ataques                     │   │
│  │ • Dashboard de seguridad en tiempo real                │   │
│  │ • Auditoría de logs regular                            │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  5️⃣ CULTURAL FILTER IMPROVEMENT:                             │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Filtros contextuales para español chileno            │   │
│  │ • Validación de intención de usuario                   │   │
│  │ • Análisis semántico de prompts                        │   │
│  │ • Filtros adaptativos por región                       │   │
│  │ • Detección de manipulación cultural                    │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```

### Recomendaciones Medias (Implementar en 60 días):

```
┌─────────────────────────────────────────────────────────────────┐
│                 RECOMENDACIONES MEDIAS                         │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│  6️⃣ API SECURITY HARDENING:                                   │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Autenticación multi-factor                            │   │
│  │ • Rotación automática de API keys                       │   │
│  │ • Validación de headers de seguridad                    │   │
│  │ • Rate limiting por endpoint                            │   │
│  │ • WAF (Web Application Firewall)                        │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  7️⃣ COMPLIANCE FRAMEWORK:                                     │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Cumplimiento ISO 27001                                │   │
│  │ • Adherencia a normativa chilena                        │   │
│  │ • Políticas de seguridad documentadas                   │   │
│  │ • Procedimientos de incidentes                          │   │
│  │ • Capacitación de personal                              │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```

---
## 📈 PLAN DE ACCIÓN

```
┌─────────────────────────────────────────────────────────────────┐
│                      PLAN DE ACCIÓN                            │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│  📅 SEMANA 1-2: IMPLEMENTACIÓN CRÍTICA                        │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Desarrollar filtros multi-capa para Prompt Injection │   │
│  │ • Implementar rate limiting estricto                   │   │
│  │ • Configurar monitoreo básico de seguridad             │   │
│  │ • Validar integridad de dependencias                   │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  📅 SEMANA 3-4: MEJORAS DE MONITOREO                          │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Implementar logging completo                         │   │
│  │ • Desarrollar dashboard de seguridad                   │   │
│  │ • Configurar alertas automáticas                        │   │
│  │ • Mejorar filtros culturales                           │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  📅 SEMANA 5-8: HARDENING AVANZADO                           │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Implementar autenticación multi-factor               │   │
│  │ • Configurar WAF                                        │   │
│  │ • Desarrollar políticas de compliance                   │   │
│  │ • Capacitar personal en seguridad                       │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  📅 SEMANA 9-12: VALIDACIÓN Y AUDITORÍA                      │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Re-ejecutar casos de prueba                          │   │
│  │ • Validar efectividad de mitigaciones                  │   │
│  │ • Auditoría de compliance                               │   │
│  │ • Documentación final de seguridad                     │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📋 CHECKLIST DE CUMPLIMIENTO

```
┌─────────────────────────────────────────────────────────────────┐
│                  CHECKLIST DE CUMPLIMIENTO                    │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│  ✅ OWASP TOP 10 FOR LLMS:                                   │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ ☐ LLM01 - Prompt Injection                              │   │
│  │ ☐ LLM02 - Insecure Output Handling                     │   │
│  │ ☐ LLM03 - Training Data Poisoning                      │   │
│  │ ☐ LLM04 - Model Denial of Service                      │   │
│  │ ☐ LLM05 - Supply Chain                                 │   │
│  │ ☐ LLM06 - Sensitive Information Disclosure             │   │
│  │ ☐ LLM07 - Insecure Plugin Design                       │   │
│  │ ☐ LLM08 - Excessive Agency                             │   │
│  │ ☐ LLM09 - Overreliance                                 │   │
│  │ ☐ LLM10 - Model Theft                                  │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  ✅ MITRE ATLAS:                                             │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ ☐ AML.T0051 - Prompt Injection                         │   │
│  │ ☐ AML.T0054 - Model Poisoning                          │   │
│  │ ☐ AML.T0069 - Model Theft                              │   │
│  │ ☐ AML.T0077 - Supply Chain Compromise                  │   │
│  │ ☐ AML.T0056 - Model Inversion                          │   │
│  │ ☐ AML.T0057 - Model Skewing                            │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  ✅ NORMATIVA CHILENA:                                       │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ ☐ Ley 19.628 - Protección de Datos Personales          │   │
│  │ ☐ Ley 20.575 - Delitos Informáticos                     │   │
│  │ ☐ Normativa del Banco Central                          │   │
│  │ ☐ Estándares de Ciberseguridad                         │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```

## 🔄 Flujo de Implementación

```
┌─────────────────────────────────────────────────────────────────┐
│                    FLUJO DE IMPLEMENTACIÓN                     │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│  📅 FASE 1: PREPARACIÓN (Semanas 1-2)                        │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Implementar suite de testing adversarial cultural     │   │
│  │ • Configurar métricas de evaluación específicas         │   │
│  │ • Desarrollar filtros adaptativos para contexto regional│   │
│  │ • Establecer sistema de logging y monitoreo             │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  📅 FASE 2: TESTING (Semanas 3-6)                            │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Ejecutar Casos 1-7 contra Latam GPT                   │   │
│  │ • Evaluar resistencia a cada tipo de ataque             │   │
│  │ • Documentar vulnerabilidades encontradas               │   │
│  │ • Calcular métricas de seguridad                        │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  📅 FASE 3: MITIGACIÓN (Semanas 7-8)                        │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Implementar defensas basadas en hallazgos             │   │
│  │ • Desarrollar sistema de monitoreo continuo             │   │
│  │ • Validar efectividad de mitigaciones                   │   │
│  │ • Documentar lecciones aprendidas                       │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
└─────────────────────────────────────────────────────────────────┘
```

## 📊 Métricas de Evaluación

```
┌─────────────────────────────────────────────────────────────────┐
│                    MÉTRICAS DE EVALUACIÓN                      │
├─────────────────────────────────────────────────────────────────┤
│                                                               │
│  📈 MÉTRICAS ESPECÍFICAS PARA LATAM GPT:                     │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │ • Tasa de Detección Cultural: >X%                      │   │
│  │ • Resistencia Dialectal: >X%                            │   │
│  │ • Protección Regional: >X%                              │   │
│  │ • Validación Cultural: >X%                              │   │
│  │ • Tiempo de Respuesta: <Xs                               │   │
│  │ • Score de Confianza: >X.X                              │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                               │
│  📊 TABLA DE MÉTRICAS:                                       │
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
--------------------------------
Objetivo del repositorio

Resumen del benchmark

Metodología ✅

Cómo seleccionaste los ataques

Por qué esos 7 del OWASP Top 10

Criterios de priorización

Entorno de pruebas ✅

Qué modelo LLM estás usando

Cómo se simulan los ataques

Herramientas utilizadas (mención general)

Estructura del repositorio

Cómo contribuir o ejecutar los casos

Enlaces a versiones o carpetas

--------------
Para acceder a la primera versión, [haga clic aquí](./pruebas-v1/README.md).

## Contenido
Este repositorio contiene un plan de pruebas compuesto por 7 casos de ataque, diseñados para evaluar la seguridad de aplicaciones que integran modelos de lenguaje grandes (LLMs). Cada caso aborda un tipo específico de amenaza descrita en el OWASP Top 10 para sistemas con LLMs.

A continuación se presentan los casos actualmente implementados:

+ LLM01: 2025 - **Prompt Injection**
+ LLM02: 2025 - **Sensitive Information Disclosure**
+ LLM03: 2025 - **Supply Chain**
+ LLM04: 2025 - **Data and Model Poisoning**
+ LLM05: 2025 - **Improper Output Handling**
+ LLM09: 2025 - **Misinformation**
+ LLM10: 2025 - **Unbounded Consumption**
