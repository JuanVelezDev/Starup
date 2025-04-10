# 🌄 Que chimba de parche

> **¿Indeciso? ¿Necesitas cambiar de aires? ¿Vacaciones?**  
> *Que chimba de parche* es tu guía cultural, emocional y visual para reconectar con la esencia de Medellín.  
> Rompamos juntos el estigma del turismo tradicional y démosle paso al verdadero encanto de esta tierra:  
> **sus historias, su gente, sus charcos, sus platos, y su alma.**

---

## 🧑‍🤝‍🧑 Público objetivo

- Jóvenes entre 18 y 35 años interesados en explorar Medellín de forma alternativa.
- Turistas nacionales e internacionales que desean evitar el turismo comercial o estigmatizante.
- Grupos de amigos o parejas que buscan planes culturales y económicos.
---





## 🧩 Problema que resuelve

El turismo en Medellín ha sido opacado por narrativas que reducen la ciudad a prostitución y narcotráfico.  
Nosotros proponemos una alternativa **más real, más humana, más nuestra**:


> **De la violencia a la vivencia.**

Museos, pueblos, historia, charcos, arte callejero, naturaleza, gastronomía y anécdotas.  
Todo reunido en una plataforma hecha con el corazón, para mostrarle al mundo que **Medellín es mucho más**.


---






## ✨ Funcionalidades

- 📸 Galería de fotos y videos auténticos de los destinos.
- 📍 Reseñas reales de viajeros y locales.
- 💰 Presupuestos pensados para todos los bolsillos.
- 🍛 Recomendaciones de platos típicos y dónde encontrarlos.
- 🗺️ Consejos de viaje, cultura local y datos curiosos.
- 👫 Planes para hacer en pareja, con amigos o en solitario.
- 🌈 Espacios culturales, naturales y tradicionales.
- 🔍 Búsqueda por tipo de experiencia: aventura, relajación, cultura, comida.



---

Análisis funcional y técnico

| Funcionalidad             | Tareas específicas                                                                      | Dificultad | Restricciones                   |
|--------------------------|------------------------------------------------------------------------------------------|------------|----------------------------------|
| Explorador de parches     | Base de datos de lugares, filtros por tipo de plan (aventura, cultural, comida)         | Media      | Acceso a contenido georreferenciado |
| Planificador de viaje     | Crear sistema de presupuesto, lista de lugares por presupuesto, tiempo y transporte     | Alta       | UX debe ser simple               |
| Comunidad viajera         | Sistema de reseñas, puntuación y consejos, autenticación opcional                      | Media      | Moderación de contenido          |


## 🧠 Filosofía del sitio

**Que chimba de parche** no es solo una guía turística.  
Es una declaración: *"Queremos volver a sentirnos orgullosos de lo nuestro."*

Creamos este espacio para mostrarte que Medellín tiene alma, historia y lugares mágicos escondidos entre montañas.  
Y lo hacemos desde una perspectiva local, honesta y cultural.



---



## 🔧 Arquitectura del sistema

### Pantallas clave

1. **Inicio / Explora un parche**: Muestra los destinos destacados, filtros por categoría, acceso a presupuesto.
2. **Detalle del destino**: Galería de fotos/videos, descripción, mapa, reseñas, tips y platos recomendados.



---



### Diagrama de flujo de usuario

[Inicio]
   ↓
[Explora parches]
   ↓
[Selecciona destino]
   ↓
[Detalle del destino]
   ↓
[Agrega al planificador]
   ↓
[Consulta presupuesto y tips]

---
## 📄 Pseudocódigo – Que chimba de parche

```pseudocode
Definir destino Como Cadena

Escribir "Bienvenido a Que chimba de parche!"
Escribir "Pulsa ENTER para comenzar..."
Leer destino

Escribir "Explorando parches disponibles..."
Escribir "Opciones: Comuna 13, Parque Arví, Museo de Antioquia"

Escribir "Escribe el nombre del destino que te interesa:"
Leer destino

Escribir "Mostrando detalles de: ", destino

Escribir "Agregando ", destino, " al planificador..."

Escribir "Presupuesto estimado: $50.000"
Escribir "Tip: Lleva ropa cómoda y disfruta al máximo."

Escribir "Gracias por usar Que chimba de parche ¡Buen viaje!"
FinProceso


```


## 🖼️ Vista previa del sitio y opciones de precios

### 1. Comparativa de precios de actividades

![Tabla de precios de actividades en Medellín](./ruta-a-tu-imagen/Captura%20desde%202025-04-10%2000-22-19.png)

Esta tabla permite al usuario comparar entre los distintos paquetes turísticos ofrecidos. Desde la opción básica hasta la experiencia total, se detallan los servicios incluidos como guía, transporte, entradas y actividades personalizadas, ayudando al usuario a elegir según su presupuesto.

---

### 2. Página de inicio – “Descubre Medellín como nunca antes”

![Portada del sitio Que chimba de parche](./ruta-a-tu-imagen/Captura%20desde%202025-04-10%2000-24-04.png)

La página principal da la bienvenida al usuario con una imagen llamativa y un mensaje inspirador. Se invita a explorar lugares únicos en Medellín, resaltando experiencias auténticas, cultura y naturaleza.

---
















# Casos de Prueba ✅

## Buscar y filtrar destinos
- **Entrada:** `“charcos”`
- **Esperado:** Mostrar todos los charcos con imágenes y descripción.

## Presupuesto personalizado
- **Entrada:** 
  - **Tiempo:** `2 días`
  - **Presupuesto:** `$150,000`
- **Esperado:** Mostrar lista de lugares y comida dentro del rango.

## Sistema de reseñas
- **Entrada:** Usuario escribe una reseña y califica.
- **Esperado:** La reseña se publica y se actualiza la puntuación promedio.

---

# 🐛 Posibles Errores Comunes

- Problemas de carga de contenido por mala conexión.
- Mal cálculo de presupuestos por datos desactualizados.

---





# 🚀 Estrategia de despliegue

- Base de datos en **Firebase Firestore**.
- Despliegue vía **Firebase Hosting**.
- Dominio personalizado opcional (ej. `quechimbadeparche.co`).
- Monitorización con **Google Analytics** y **Sentry** (errores).

---

# 💡 Futuras mejoras

- Integración con **WhatsApp** para reservas automáticas.
- Sistema de **gamificación** para usuarios frecuentes (insignias, premios o descuentos)
- 




























