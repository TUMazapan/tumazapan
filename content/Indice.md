---
title: Hub Epistemológico
tipo: sistema
area: filosofia
estado: publicado
publish: false
---

> "La virtud no reside en la contemplación de la idea, sino en la precisión de su ejecución."

Bienvenido. Este no es un blog, es un grafo de conocimiento estructurado en tres niveles de análisis. 

---

### 1. Nodos de Tesis (Premisas y Debates)
*Afirmaciones estructurales diseñadas para someterse a escrutinio.*

```dataview
TABLE date as "Fecha", area as "Disciplina"
FROM "_Praxis"
WHERE contains(tipo, "tesis") AND contains(publish, "true")
SORT date desc
LIMIT 10
```

### 2. Nodos de Sistemas (Modelos y Teoría)

_Análisis objetivo, decodificación de estándares y mecánica de sistemas._

Fragmento de código

```dataview
TABLE date as "Fecha", area as "Disciplina"
FROM "_Sistema"
WHERE contains(tipo, "sistema") AND contains(publish, "true")
SORT date desc
LIMIT 10
```

### 3. Nodos de Praxis (Ejecución)

_El puente hacia el mundo físico. Guías, código y documentación operativa._

Fragmento de código

```dataview
TABLE date as "Fecha", area as "Disciplina"
FROM "_Praxis"
WHERE contains(tipo, "praxis") AND contains(publish, "true")
SORT date desc
LIMIT 10
```
### 3. El Tejido Conectivo (Uso de Enlaces)

Con este sistema, la navegación de tu audiencia será orgánica. 

Imagina que estás escribiendo un nodo de Tesis titulado: *"El crecimiento económico sostenido es matemáticamente incompatible con una demanda de dinero pasiva"*. 

Dentro de esa nota, no tienes que explicar desde cero la teoría económica. Simplemente haces esto:
> "Para entender por qué ocurre esto, debemos revisar la mecánica de los desplazamientos en el [[Modelo IS-LM]], donde se observa que..."

Ese enlace `[[Modelo IS-LM]]` conectará directamente con una nota clasificada como `sistema`, creando el puente entre tu argumento (Tesis) y el modelo riguroso que lo sustenta (Sistema).

Atajo de GIT Obsidian
Ctrl + Shift + P