🏦 Sistema de Gestión de Cuentas Bancarias

Una aplicación en Java que simula el núcleo de un sistema bancario, gestionando cuentas, clientes, transferencias y operaciones con un alto nivel de precisión y control.

✨ Características Principales

    Gestión Completa de Entidades: Creación y administración de Clientes, Cuentas Bancarias (Ahorro y Corriente) y Direcciones.

    Operaciones Bancarias Seguras: Depósitos, retiros y transferencias entre cuentas con validación de saldos y límites.

    Sistema de Historial: Registro detallado de todas las transacciones realizadas para auditoría y consulta.

    Modelo de Datos Sólido: Implementación robusta usando Programación Orientada a Objetos (POO), con herencia, encapsulación y polimorfismo.

    Persistencia de Datos: Los datos se mantienen en memoria durante la ejecución, ready para ser extendido a una base de datos.

🛠️ Tecnologías Utilizadas

    Lenguaje de Programación: Java 17

    Paradigma: Programación Orientada a Objetos (POO)

    Estructuras de Datos: ArrayList, HashMap

    Control de Versiones: Git

🧠 Diseño Orientado a Objetos

Este proyecto demuestra un uso avanzado de los pilares de la POO:

    Herencia: CuentaAhorro y CuentaCorriente heredan de la clase abstracta CuentaBancaria.

    Polimorfismo: Se trata a todas las cuentas como CuentaBancaria, invocando los métodos depositar() y retirar() de forma polimórfica.

    Encapsulación: Los atributos de las clases son privados y se accede a ellos through getters y setters.

💡 Funcionalidades Clave Implementadas

    Creación de Cuentas: Permite elegir entre cuenta de Ahorro o Corriente.

    Depósitos: Añadir fondos a una cuenta.

    Retiros: Retirar fondos, con validación de saldo disponible.

    Transferencias: Enviar dinero entre cuentas, con validación de saldo en la cuenta de origen.

    Consultas: Listar todos los clientes, cuentas y el historial completo de operaciones.

👨‍💻 ¿Qué Demuestra Este Proyecto?

Este proyecto es un ejemplo de mi capacidad para:

    Modelar dominios complejos del mundo real (como el sistema bancario) en código, utilizando relaciones entre clases.

    Aplicar conceptos avanzados de POO (Herencia, Polimorfismo, Encapsulación) para crear un diseño flexible y mantenible.

    Implementar lógica de negocio crítica con validaciones y reglas de integridad (ej: no permitir retiros sin saldo).

    Estructurar un proyecto en paquetes y clases de forma lógica y clara.

🚀 Próximos Pasos Posibles (Ideas para Escalar el Proyecto)

    Persistencia: Conectar el sistema a una base de datos MySQL para guardar los datos permanentemente.

    Interfaz Gráfica: Desarrollar una interfaz de usuario con JavaFX.

    API REST: Convertir la lógica en una API usando Spring Boot.

    Funcionalidades Adicionales: Añadir préstamos, tarjetas de crédito o un sistema de usuarios y autenticación.

📧 Contacto

Enrique Cala Rodríguez
[LinkedIn](https://www.linkedin.com/in/enrique-cala-rodr%C3%ADguez-21032491/)

Email: enriquecalar@gmail.com
