# Parqueate-Cerca-Valledupar

ParqueateCerca es una aplicación web diseñada para facilitar la gestión, 
búsqueda y registro de parqueaderos en Valledupar, permitiendo a los usuarios encontrar espacios disponibles de manera rápida,
así como administrar un historial de entradas y salidas mediante códigos QR.

El proyecto está desarrollado en Python con Django y utiliza MySQL como base de datos principal

# Objetivos del Proyecto

## Objetivo general

Desarrollar una aplicación web y móvil que indique la localización y la disponibilidad en 
tiempo real de los parqueaderos en la ciudad de Valledupar.

## Objetivos especificos

1. Analizar la información relacionada de los parqueaderos y usuarios viales para obtener datos 
que nos permitan una guía clara y precisa sobre las necesidades y problemáticas de los 
conductores de vehículos a la hora de localizar parqueaderos en la ciudad de Valledupar, 
generando informes de requerimientos funcionales y no funcionales.
2. Diseñar prototipos del aplicativo con el fin de mejorar la experiencia del usuario y de los 
administradores de los parqueaderos, mediante la implementación de interfaces intuitivas, 
funcionales y amigables.
3. Desarrollar un sistema de geolocalización preciso que permita a los usuarios visualizar en 
tiempo real los parqueaderos disponibles más cercanos, con información detallada sobre tarifas, 
horarios y características del estacionamiento.
4. Implementar tecnologías de Google Maps (API) para conocer la ubicación y disponibilidad de 
parqueaderos en tiempo real, optimizando la búsqueda y reduciendo el tiempo de circulación; 
realizando las pruebas del software pertinentes.

# Tecnologías Utilizadas

Python 3.x

Django (framework backend principal)

MySQL (base de datos relacional)

HTML5, CSS3, JavaScript

Django Templates para la interfaz

Git y GitHub para control de versiones

Bibliotecas para QR:

qrcode o segno

Pillow para manipulación de imágenes

API Google maps

# Roles del equipo

Líder técnico - Kevin Cuervo

Desarrollador Backend - Juan Velasquez

Desarrollador Frontend - Ángel Arias

Tester / QA - Dayan Martinez

Documentador - Karlo Molina

#Organización de ramas y Git Flow

## Ramas principales

main → Rama estable, código listo para producción.

develop → Rama donde se integra el desarrollo diario.

feature/ → Una rama por funcionalidad, ejemplo: feature/login.

hotfix/ → Corrección de errores urgentes.

release/ → Preparación de versiones finales.

# Flujo de Trabajo (Git Flow)

main → versión estable

develop → rama de desarrollo

feature/ → nuevas funcionalidades

release/ → preparación de versiones

hotfix/ → correcciones urgentes

Reglas del flujo de trabajo

Toda nueva funcionalidad se crea desde develop.

Los commits deben ser claros y descriptivos (PEP8 obligatorio).

Toda integración se realiza mediante Pull Requests.

El código debe ser revisado por otro integrante antes del merge.

# Flujo de trabajo

## Líder Técnico

Responsabilidades:

Dirigir las decisiones técnicas del proyecto.

Supervisar calidad del código y cumplimiento de PEP8.

Administrar el flujo de trabajo Git (ramas, merges, releases).

Coordinar integración entre backend, frontend y base de datos.

Resolver bloqueos técnicos del equipo.

## Desarrollador Backend

Responsabilidades:

Implementar la lógica de negocio en Django.

Construir las APIs para registro de usuarios, parqueaderos, historial y QR.

Gestionar la conexión y operaciones con MySQL.

Implementar autenticación, seguridad y validaciones.

Documentar endpoints de la API.

## Desarrollador Frontend

Responsabilidades:

Construir interfaces responsivas y funcionales.

Integrar vistas de Django (Django Templates).

Diseñar mapas, formularios, listas y pantallas de historial.

Conectar frontend con endpoints del backend.

Optimizar la experiencia de usuario (UX/UI).

## Encargado de Documentación

responsabilidades:

Elaborar documentación técnica del proyecto.

Mantener actualizado el README.md y los manuales.

Diseñar diagramas (clases, casos de uso, arquitectura).

Documentar decisiones técnicas y cambios importantes.

Apoyar en la elaboración del informe del proyecto final.

## Tester / QA (Aseguramiento de Calidad)

Responsabilidades:

Diseñar y ejecutar pruebas funcionales y no funcionales.

Validar flujo de registro, parqueaderos, historial, escaneo de QR, etc.

Reportar bugs y realizar seguimiento hasta su solución.

Crear casos de prueba y matrices de validación.

# Tipos permitidos

feat:	Nueva funcionalidad
fix:	Corrección de errores
docs:	Cambios en documentación
style:	Cambios de estilo (indentación, espacios; sin afectar lógica)
refactor:	Reestructuración de código sin cambiar funcionalidad
test:	Pruebas unitarias o de integración
chore:	Tareas generales (archivos de configuración, limpieza, etc.)

# Reglas para escribir commits

Un commit debe incluir solo una mejora o cambio (atómico).

Escribir mensajes cortos pero significativos (máx. 72 caracteres).

Evitar commits genéricos como "arreglo", "cambios", "update".

Siempre revisar que el código cumple con PEP8 antes de hacer commit.

# Revisión de Código (Code Review)

## Pasos obligatorios para revisión

1. El desarrollador crea una rama feature/.

2. Implementa la funcionalidad siguiendo PEP8.

3. Sube la rama y crea un Pull Request hacia develop.

4. Otro integrante del equipo debe revisar el PR.

5. El revisor valida:

Calidad del código.
Limpieza y claridad.
Buen uso de excepciones y validaciones.
Que no hayan vulnerabilidades evidentes.
Que la funcionalidad esté completa y probada.

6. Si todo está bien → se aprueba.

Si hay cambios → se solicita corrección.

#  Generacion de pull request 
## Reglas para crear un PR

El PR debe tener un título claro y un resumen detallado.

Incluir en la descripción:

El objetivo del cambio.

Funcionalidades agregadas o corregidas.

Evidencia (capturas, pruebas realizadas).

Checklist de tareas completadas.

Asociar el PR con el issue correspondiente.

El PR debe venir desde una rama feature/, hotfix/ o release/.

## Tamaño del PR

Debe ser pequeño y fácil de revisar.

Evitar PR gigantes con cambios no relacionados
