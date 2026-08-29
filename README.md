# 📋 Sistema de Gestión de Reservas Deportivas

## 📝 Descripción

Aplicación web desarrollada con Django para la gestión y alquiler de canchas deportivas. Este proyecto resuelve la problemática de la desorganización en agendas manuales y permite consultar disponibilidad, registrar turnos, calcular costos y realizar consultas de forma sencilla. Forma parte del laboratorio del curso de **Desarrollo de Aplicaciones Empresariales**.

## 💬 Prompt y Consigna del Laboratorio

### Consigna Oficial
Desarrollar una aplicación web en Django que permita resolver una problemática real mediante un CRUD con datos estáticos en memoria (sin migraciones ni base de datos física SQL).

### Prompts Utilizados en la Asistencia
1. **Prompt General:** "Construir una App Django (`reservas`) sin base de datos SQL, usando listas estáticas (`RESERVAS_DB`) en `models.py`, `forms.Form` plano, vistas con redirigido `POST` y Bootstrap 5 heredando de `core/base.html` para cumplir 10 requisitos funcionales de reservas deportivas."
2. **Prompt de Estructuración:** "Adaptar el código y la documentación MVT para alinearlos con los entregables del laboratorio y generar las respuestas para el informe final."

## 🚀 Características

* **Gestión de Reservas:** Registro, consulta y cancelación de turnos para canchas deportivas.
* **Modelo en Memoria:** Manejo de datos estáticos en `models.py` (`RESERVAS_DB`) sin base de datos SQL.
* **Filtros por Deporte y Precio:** Búsqueda rápida de canchas según los requerimientos del usuario.
* **Cálculo Automático de Costo:** Multiplicación de la tarifa por hora según la duración seleccionada.
* **Validación de Horarios:** Control de disponibilidad para evitar cruces en la misma cancha y fecha.
* **Formulario de Consultas:** Sección para que los clientes dejen sus mensajes y comentarios.
* **Diseño Responsive con Bootstrap 5:** Interfaz adaptada a diferentes dispositivos.

## 📋 Requisitos Funcionales

1. Registrar canchas deportivas con sus características.
2. Mostrar el listado general de canchas reservadas.
3. Permitir realizar nuevas reservas mediante un formulario web.
4. Validar disponibilidad de horario para evitar doble reserva.
5. Permitir la cancelación de reservas activas.
6. Proporcionar un formulario de contacto y consultas.
7. Filtrar reservas por deporte y precio máximo por hora.
8. Calcular automáticamente el costo total de la reserva.
9. Mostrar la información detallada de una reserva específica.
   
## 💬 Prompt
"Diseña y construye una aplicación web modular en Django llamada reservas para la gestión de canchas deportivas, orientada a cumplir 10 requisitos bajo la arquitectura MVT. La solución debe operar estrictamente con una lista estática de diccionarios en memoria (RESERVAS_DB) dentro de models.py como única fuente de datos (sin ORM, base de datos SQL ni migraciones), utilizar formularios planos derivados de forms.Form sin ModelForm, y procesar peticiones GET y POST con redireccionamientos estándar. Asimismo, las vistas deben implementar la lógica de negocio necesaria para listar, registrar con cálculo automático de costo (duración por tarifa) y validación de doble reserva en el mismo horario, cancelar turnos activos, mostrar detalles individuales por ID, filtrar por deporte o precio, almacenar consultas de contacto y renderizar las plantillas HTML heredando de la interfaz base con Bootstrap 5."

## 🛠️ Guía de Ejecución

1. Activar el entorno virtual:
   .\venv\Scripts\Activate.ps1
