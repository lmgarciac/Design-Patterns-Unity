# Design Patterns – (Unity)

Aplicación interactiva desarrollada en **Unity** para explorar y estudiar los **24 patrones de diseño GoF** de forma visual y práctica.

El proyecto permite, para cada patrón:
- leer su **descripción**
- visualizar el **diagrama del patrón**
- interactuar con un **ejemplo funcional**
- inspeccionar el **código de ejemplo**

> **Repositorio principal (código fuente e historial completo):**  
> GitLab: https://gitlab.com/luism.garciac/design-patterns-quark

---

## Qué muestra este proyecto

- Implementación práctica de los **patrones creacionales, estructurales y de comportamiento**
- Separación clara entre:
  - presentación visual
  - lógica del patrón
  - código de ejemplo
- Uso de **Unity como entorno interactivo**, no solo como motor gráfico
- Enfoque didáctico: el objetivo es **comprender el patrón**, no optimizar para producción

---

## Patrones incluidos

### Creacionales
- Abstract Factory  
- Factory Method  
- Singleton  
- Prototype  
- Builder  

### Estructurales
- Adapter  
- Bridge  
- Composite  
- Facade  
- Flyweight  
- Proxy  
- Decorator  

### Comportamiento
- Chain of Responsibility  
- Command  
- Interpreter  
- Iterator  
- Mediator  
- Memento  
- Observer  
- State  
- Strategy  
- Template Method  
- Visitor  
---

## Cómo ejecutar el proyecto

1. Clonar el repositorio principal desde GitLab
2. Abrir el proyecto en Unity (versión LTS recomendada)
3. Instalar la dependencia necesaria: `com.unity.nuget.newtonsoft-json`
4. Abrir la escena: `Assets/Scenes/DesignPatterns.unity`

<img width="2188" height="1208" alt="imagen" src="https://github.com/user-attachments/assets/5d0a917f-ace0-441b-b804-70f2631f39b8" />


## Estructura del código

Los archivos fuente de los patrones se encuentran en:
Assets/Sources/Patrones

Cada patrón está implementado de forma independiente para facilitar su lectura, análisis y comparación.

## Notas sobre el alcance

- Este proyecto no busca ser un framework ni código de producción
- El foco está puesto en:
  - claridad conceptual
  - visualización
  - aprendizaje

Algunas decisiones priorizan simplicidad y didáctica por sobre “best practices” de producto final.

Proyecto educativo desarrollado como material de estudio y referencia.

## Autor:
Luis Garcia
