# Equipo 11 - Fundamentos de Diseño
### Carrera de Ingeniería Informática / Industrial  
**Universidad Peruana Cayetano Heredia**

---

## 🌍 Descripción del Equipo 
Somos el **Equipo 11** del curso **Fundamentos de Diseño 2026-2**, conformado por estudiantes de la carrera de Ingeniería Ambiental / Informática / Industrial.  
Nuestro objetivo es aplicar la metodología de diseño para generar soluciones innovadoras con impacto social, tecnológico y ambiental.  

Esperamos que se encuentre bien. A continuación, presentamos la propuesta formal de la idea de proyecto para el curso de Fundamentos del Diseño:

## Nombre del Proyecto
**AQUA-ALERT (Sistema Robótico e Inteligente de Monitoreo, Control de Calidad y Prevención de Fugas de Agua)**

Nos interesa trabajar en los siguientes **Objetivos de Desarrollo Sostenible (ODS):** 
- El ODS Principal: ODS 6 – Agua Limpia y Saneamiento (Garantiza la gestión sostenible, la calidad y el monitoreo del recurso hídrico).
- ODS 12 – Producción y Consumo Responsables (Evita el desperdicio mediante la detección y el corte mecánico automático de fugas).
- ODS 11 – Ciudades y Comunidades Sostenibles (Aporta resiliencia urbana frente a cortes y desabastecimiento hídrico en tanques/cisternas).

## Problemática a resolver:
Las fugas de agua que no son detectadas oportunamente pueden generar desperdicio del recurso hídrico y pérdidas económicas. El problema se vuelve especialmente relevante durante la noche, cuando los usuarios no se encuentran supervisando continuamente el consumo de agua.

Una dificultad importante es que no todo flujo de agua representa una fuga. Por ejemplo, una persona puede utilizar el inodoro, lavarse las manos o ducharse durante la madrugada. Por ello, el sistema no debe limitarse a detectar flujo, sino analizar sus características para distinguir entre un consumo esperado y un comportamiento compatible con una fuga.

AQUA-ALERT aborda esta problemática mediante la medición del flujo, el análisis de patrones de consumo, la estimación del volumen y la activación automática de alertas y corte de suministro cuando corresponde.

## Propuesta de solución:
El sistema se basa en cuatro funciones principales:

1. Medir el flujo de agua mediante el sensor YF-S201.
2. Analizar la duración, caudal y volumen de cada evento de consumo.
3. Comparar el evento con firmas de consumo conocidas, previamente registradas por el usuario.
4. Alertar y actuar ante una posible fuga, mediante un buzzer, LED y electroválvula.

## Funcionamiento nocturno:
El sistema puede trabajar dentro de una ventana de vigilancia configurable, inicialmente planteada entre las 00:00 y 05:00 horas.
Durante una etapa inicial de calibración, el usuario registra consumos habituales, como:
- Uso del inodoro
- Uso del lavamanos
- Uso de la ducha

Para cada evento se registra principalmente su duración y caudal promedio.
Durante la vigilancia, cada nuevo evento de flujo se compara con estas firmas de consumo.

* Si coincide con un patrón conocido -> se registra como consumo habitual.
* Si no coincide con los patrones conocidos y supera el tiempo establecido -> se clasifica como posible fuga.
* Ante una posible fuga -> se registra el evento, se estima el volumen perdido, se activa la alerta y se puede accionar la electroválvula para interrumpir el suministro.

---
## 📸 Fotografía del Equipo  
<p align="center">
<img width="1408" height="768" alt="imagen_alumnos_IA" src="https://github.com/SebastianLV9/FdD_Equipo_11/blob/main/Recursos/Im%C3%A1genes/Foto%20Grupal.jpeg" />
  <em>Figura 1. Fotografía del equipo 11</em>
</p>

---

## 👥 Integrantes del Equipo  

| Foto | Nombre | Rol | Intereses |
|------|--------|-----|-----------|
| <img src="/Recursos/Imágenes/Layme.jpeg" width="90"/> | **Sebastian Layme** | Líder del equipo | Innovación social, sostenibilidad |
| <img src="/Recursos/Imágenes/Daniel.jpeg" width="90"/> | **Daniel Oliva** | Responsable de investigación | Gestión ambiental, desarrollo comunitario|
| <img src="/Recursos/Imágenes/Jimena.png" width="90"/> | **Jimena Vega** | Diseñadora | Diseño de prototipos, creatividad aplicada |
| <img src="/Recursos/Imágenes/integrante2.jpg" width="90"/> | **Susan S Limascca** | Encargado/a de documentación | Comunicación científica, redacción técnica |
| <img src="/Recursos/Imágenes/Marlon.png" width="90"/> | **Sarmiento Montalvo Marlon Steeven** | Programador/a - Modelador/a | Programación, análisis de datos, simulación |

---

## 📌 Resumen Final  
Este README resume quiénes somos, qué nos motiva y en qué ODS queremos enfocar nuestro trabajo durante el curso.  
