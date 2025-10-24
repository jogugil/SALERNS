# SALERNS
{SALERNS} (Satellite Emergency LoRa Network System)
# SALERNS: Satellite Emergency LoRa Network System

## Descripción del Proyecto
SALERNS es un sistema de comunicaciones de emergencia que integra tecnologías LoRa modificadas con infraestructura satelital, diseñado específicamente para escenarios de desastres naturales donde las infraestructuras terrestres convencionales están dañadas o inoperativas.

## Objetivo Principal
Desarrollar protocolos de comunicación resilientes que permitan establecer enlaces de comunicación confiables entre dispositivos IoT terrestres y satélites LEO, manteniendo la baja complejidad y consumo energético característicos de LoRa mientras superamos sus limitaciones de alcance y movilidad.

## Características Técnicas

### 🛰️ Módulo Satelital Adaptado
- Protocolos LoRa modificados para enlaces satélite-tierra
- Compensación avanzada de efecto Doppler
- Mecanismos de sincronización robustos para movilidad orbital

### 🔄 Protocolos Híbridos ARQ
- Esquemas de retransmisión adaptativa para condiciones de canal variables
- Codificación rateless para recuperación eficiente de errores
- Transiciones suaves entre modos de operación basadas en SNR

### 📡 Gestión Dinámica de Recursos
- Algoritmos semi-autónomos para asignación espectral
- Políticas de exploración/explotación adaptativas
- Optimización multi-objetivo: eficiencia vs consumo energético

## Estructura del Proyecto
```text
SALERNS/
├── simulations/ # Simulaciones de canal y protocolos
├── firmware/ # Implementación para dispositivos embebidos
├── protocols/ # Especificaciones de protocolos modificados
├── docs/ # Documentación técnica y artículos
├── tests/ # Suite de pruebas y validación
└── hardware/ # Diseños de referencia (opcional)
```

## Estado del Desarrollo

### 🔬 Fase Actual: Investigación y Simulación
- Modelado matemático de enlaces LoRa-satélite
- Desarrollo de algoritmos de compensación de Doppler
- Simulación de desempeño en escenarios de desastre

### 🎯 Próximos Hitios
- Prototipo de simulación funcional
- Implementación de stack protocolar básico
- Validación con SDR (Software Defined Radio)
- Pruebas de campo en entorno controlado

## Licencia
Licencia Combinada: **Creative Commons BY-NC-ND 4.0 + Restricciones Académicas + Inspiración en Apache/GPLv3**

### PARTE 1: Creative Commons BY-NC-ND 4.0
- **Atribución (BY):** Debes dar crédito apropiado
- **No Comercial (NC):** No puedes usar el material con fines comerciales
- **Sin Obras Derivadas (ND):** No puedes redistribuir material modificado

### PARTE 2: Restricciones Académicas Adicionales
Copyright (c) 2024 [Tu Nombre] - SALERNS Project
RESERVADOS TODOS LOS DERECHOS.

Se prohíbe expresamente sin autorización por escrito del autor:

El uso de este trabajo, ideas, algoritmos o metodologías en:

Proyectos de investigación externos

Trabajos Fin de Grado (TFG)

Trabajos Fin de Máster (TFM)

Tesis doctorales

Publicaciones académicas o científicas

Proyectos comerciales o empresariales

La creación de obras derivadas basadas en:

Los protocolos modificados propuestos

Los algoritmos de compensación de Doppler

Los esquemas ARQ híbridos

La gestión dinámica de recursos

La redistribución del código, documentación o ideas:

En cualquier formato

Con cualquier modificación

Para cualquier propósito

EXCEPCIONES:

Colaboradores directos del proyecto SALERNS

Instituciones académicas con acuerdo de colaboración

Investigadores con permiso explícito por escrito

Para solicitar permisos de uso, contactar con: [tu.email@dominio.com]

EL SOFTWARE Y LA DOCUMENTACIÓN SE PROPORCIONAN "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO.

## Contribuciones
- Política de Contribuciones Restringida:
  - Solo se aceptan contribuciones de colaboradores autorizados
  - Todos los colaboradores deben firmar un acuerdo de confidencialidad
  - Las contribuciones pasan a ser propiedad del proyecto SALERNS
  - No se aceptan pull requests públicos sin revisión previa

## Cómo Citarlo
Si tienes permiso para usar este trabajo en tu investigación, debes citar:
@software{salerns2025,
title = {SALERNS: Satellite Emergency LoRa Network System},
author = {Tu Nombre},
year = {2025},
url = {https://github.com/tu-usuario/SALERNS}
,
note = {Protocolos LoRa modificados para comunicaciones de emergencia vía satélite - Uso restringido}
}
## Contacto
- Coordinador del Proyecto: [Tu Nombre]  
- Email: [tu.email@dominio.com]  
- Repositorio: https://github.com/tu-usuario/SALERNS  

**Para solicitudes de colaboración o permisos de uso:**
- Enviar solicitud formal por email
- Especificar el propósito del uso solicitado
- Incluir afiliación institucional
- Describir el alcance del uso previsto

## Agradecimientos
Este proyecto de investigación se desarrolla como parte de [tu universidad/instituto] y cuenta con la colaboración de [entidades colaboradoras].

⚠️ **ADVERTENCIA LEGAL:** Este proyecto está protegido por derechos de autor y restricciones académicas. Cualquier uso no autorizado puede constituir una violación de la propiedad intelectual.
