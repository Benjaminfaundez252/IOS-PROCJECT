Spansh 

Miniket 🐾

Miniket es una aplicación diseñada para dueños de mascotas y veterinarios, con el objetivo de gestionar la información de las mascotas, recetas, recordatorios de medicación  vacunas y llevar un registro de animales.

Actualmente la app funciona, pero hay problemas que limitan su uso diario y su adopción general.

🚨 Problemas actuales

Datos no persistentes: la app pierde toda la información al cerrarse.

Configuración temporal: ajustes de idioma y preferencias se reinician al reiniciar la app.

Funciones incompletas: algunos apartados, como recordatorios de medicamentos o historial de recetas, no están totalmente implementados.

Interfaz monolingüe: actualmente solo funciona en un idioma, limitando su alcance.

Requisitos no funcionales pendientes: la app necesita mejorar en usabilidad, confiabilidad y facilidad de acceso para dueños y veterinarios.

✅ Funcionalidades planeadas

Gestión de mascotas: agregar, editar y eliminar mascotas.

Registro de recetas: registrar medicamentos, dosis y fechas asociadas a cada mascota.

Recordatorios de medicación: alertas configurables para cada mascota.

Sección de animales fallecidos: mantener un historial respetuoso de mascotas que ya no están.

Persistencia de datos: guardar información permanentemente usando CoreData o JSON local.

Soporte multilenguaje: cambiar el idioma de la interfaz según preferencia del usuario.

Usabilidad optimizada: navegación clara y rápida, accesible para usuarios de todas las edades.

⚙️ Requisitos no funcionales

Persistencia y confiabilidad: los datos no deben perderse al cerrar la app.

Seguridad y privacidad: la información de mascotas y dueños debe ser segura.

Rendimiento: la app debe ser rápida y ligera, incluso con muchas mascotas y recordatorios.

Compatibilidad: soportar múltiples versiones de iOS y diferentes tamaños de pantalla.

Escalabilidad: fácil de mantener, agregar funciones futuras y adaptar para uso comercial.

🛠 Archivos y estructura sugerida

Models.swift → Definición de mascotas, recetas y recordatorios.

Persistence.swift → Manejo de persistencia de datos (CoreData o JSON).

Views/ → Pantallas principales de la app.

Localizable.strings → Traducciones de la interfaz.

DataController.swift → Configuración de CoreData y métodos CRUD.

🎯 Objetivo

Crear una aplicación fácil de usar, confiable y útil para dueños y veterinarios, que permita gestionar la salud de las mascotas de manera organizada y accesible, con funciones completas y persistentes, y con soporte multilingüe.





English 


Miniket 🐾

Miniket is an app designed for pet owners and veterinarians to manage pets’ information, prescriptions, medication reminders, and keep a respectful record of deceased animals.

Currently, the app works, but there are issues that limit daily use and broader adoption.

🚨 Current Issues

Non-persistent data: the app loses all information when closed.

Temporary settings: language and preference settings reset on restart.

Incomplete features: some sections, like medication reminders or prescription history, are not fully implemented.

Monolingual interface: currently only available in one language.

Pending non-functional requirements: usability, reliability, and accessibility need improvement for both owners and veterinarians.

✅ Planned Features

Pet management: add, edit, and remove pets.

Prescription tracking: record medications, doses, and dates for each pet.

Medication reminders: configurable alerts for each pet.

Deceased pets section: maintain a respectful history of pets no longer alive.

Data persistence: permanent storage using CoreData or local JSON.

Multilingual support: allow users to switch the interface language.

Optimized usability: clear and fast navigation, accessible to all user levels.

⚙️ Non-Functional Requirements

Persistence and reliability: data must not be lost when the app closes.

Security and privacy: sensitive pet and owner information must be secure.

Performance: the app should be fast and lightweight, even with many pets and reminders.

Compatibility: support multiple iOS versions and screen sizes.

Scalability: easy to maintain, expand, and adapt for commercial use.

🛠 Suggested Files & Structure

Models.swift → Define pets, prescriptions, and reminders.

Persistence.swift → Handle data persistence (CoreData or JSON).

Views/ → Main app screens.

Localizable.strings → Interface translations.

DataController.swift → CoreData setup and CRUD methods.

🎯 Goal

To create an easy-to-use, reliable, and useful app for pet owners and veterinarians, enabling organized pet health management with complete, persistent features and multilingual support.
