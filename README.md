# Watson Assistant Tutorial

Este tutorial tiene el objetivo de mostrar como hacer un asistente virtual desde cero para una ordenar pizzas y posteriormente integrarlo a una página de Facebook.

## Pre requisitos

- Tener una cuenta de IBM Cloud
- De preferencia tener una página de facebook

## Tutorial

### Paso 1: Crear una instancia de Watson Assistant

1. Ingresar a IBM Cloud 
2. En el dashboard principal buscar **"Watson Assistant"** y seleccionarlo.
3. Seleccionar una región, eligir el plan gratuito **"Lite"** y asignar un nombre y descripción (opcional) al asistente.
4. Dar click en **"Launch Watson Assistant"**
5. Dar click en **"Create Assistant**
6. Dar un nombre y una descripción (opcional) y da click en **"Crear Asistente"**

### Paso 2: Agregar un Skill

1. Dar click en **"Add dialog skill"**
2. En la página de Skill, dar click en la pestaña **"Create a Skill"**. 
3. Dar un nombre, despcrición (opcional) y seleccionar el lenguaje de tu asistente.Dar click en **"Create Dialog Skill"**

### Paso 3: Agregar intents

Es momento de agregar intents a nuestro asistente. Si tienes dudas de qué es un intent, puedes checar la presentación o **la documentación oficial** . Se agregarán 3 intents: #orden, #ayuda y #saludo.

1. Seleccionar "Skill" del lado derecho, después seleccionar "Intents" y dar click en **Create Intent**.
2. Poner el nombre del intent, en este caso **"Orden"** y dar una descripción (opcional). Crick en **Create Intent**
3. Agregar ejemplos del intent, en este caso pondremos todas las formas posibles en que las personas piden una pizza. **Se deben agregar mínimo 5 ejemplos para tener mejores resultados**.
4. Regresaremos a la página principal y crearemos el intent **Ayuda**. Repetiremos lo mismo que en el intent anterior.
5. Finalmente agregaremos el intent de **Saludo** y repetiremos los pasos que hicimos con los intent anteriores.

### Paso 4: Agregar entities

Es momento de agregar entities a nuestro asistente. Si tienes dudas de qué es una entity, puedes checar la presentación o **la documentación oficial** . Se agregarán 3 entities: @pizza_tipo, @pizza_ingredientes, @pizza_tamano e @ingredientes_extra.

1. Seleccionar "Entities" del lado derecho y dar click en **Create entity +**.
2. Agregar la entidad **pizza_tipo**. Asignar un nombre a la entidad, en este caso: **pizza_tipo**. Iremos agregando los valores de esta entidad junto con sinónimos para que se tengan mejores resultados.
3. Agregar la entidad **pizza_tamano** para los tamaños de pizza. Realizar los mismos pasos que en la entidad anterior.
4. Agregar la entidad **pizza_ingredientes** para los ingredientes extra. Realizar los mismos pasos que en la entidad anterior.
5. Agregar la entidad **ingredientes_extra** para confirmar si va a querer o no clientes extra. Realizar los mismos pasos que en la entidad anterior.

