# Casos-de-prueba-llm-owasp

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
