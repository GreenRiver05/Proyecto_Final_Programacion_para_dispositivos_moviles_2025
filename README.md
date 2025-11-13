### 📄 Presentación del proyecto - Movil 📱 [📂 Ver presentación en Google Drive](https://docs.google.com/document/d/18vUTro5xtIRiF_IcdjO7v2bznBYRF6DLGNsHZgV4cC4/edit?usp=sharing)
### 📄 Presentación del proyecto - Web 🛍️ [📂 Ver presentación en Google Drive](https://docs.google.com/document/d/1q6TZyCuTYKILoUcFNR_0_dcI8NxfvsNRRzU2FIbEa-A/edit?usp=sharing)


# 📱 App Móvil de Gestión Interna para Emprendimiento Personal

Este proyecto corresponde a una **aplicación móvil Android** desarrollada para complementar la [plataforma web de ventas](https://github.com/GreenRiver05/Proyecto_Final_Laboratorio_De_Programacion_II_2025.git
). Está orientada a los **usuarios internos del negocio** (empleados y administradores), permitiendo gestionar productos, pedidos, usuarios y consultas desde el celular, sin depender de una computadora. La app se conecta a la misma API REST utilizada por el sistema web, respetando roles y permisos.

---

## 🚀 Objetivos del sistema

- Facilitar la gestión operativa desde dispositivos móviles.  
- Optimizar el trabajo de empleados y administradores en tiempo real.  
- Mantener la coherencia funcional con la plataforma web.  
- Aplicar arquitectura MVVM estricta para garantizar mantenibilidad y escalabilidad.

---

## 🧩 Entidades principales

| Entidad           | Descripción funcional |
|-------------------|-----------------------|
| **Usuario**        | Persona que accede al sistema. Puede tener rol de empleado o administrador. Gestiona su perfil y participa en acciones según permisos. |
| **Producto**       | Artículo disponible para la venta. Incluye información comercial, estado de disponibilidad y stock. |
| **Categoría**      | Agrupación lógica de productos por tipo o uso. Facilita la navegación y organización del catálogo. |
| **Pedido**         | Transacción de compra realizada por un cliente. Registra fecha, estado, total y productos involucrados. |
| **DetallePedido**  | Componentes individuales de un pedido. Relaciona productos con cantidades y precios unitarios. |
| **Consulta**       | Mensaje enviado por un cliente con dudas o comentarios. Puede ser respondido por el equipo del negocio. |
| **Auditoría**      | Registro de acciones realizadas por usuarios sobre entidades del sistema. Visible solo para administradores. |


📌 Diagrama de clases incluido en `/docs/diagramas/DiagramaDeClases_App.jpg`

---

## 🔐 Roles y permisos

| Rol             | Permisos principales |
|-----------------|----------------------|
| **Administrador** | Accede a todas las funciones: productos, pedidos, usuarios y consultas. |
| **Empleado**      | Visualiza y actualiza pedidos, responde consultas, gestiona productos. |

📌 Diagrama de casos de uso incluido en `/docs/diagramas/CasosDeUso_App.jpg`

---

## ⚙️ Funcionalidades clave

### Para empleados y administradores
- 🔐 Iniciar sesión con credenciales  
- 📦 Visualizar pedidos y cambiar su estado  
- 🧰 Consultar, Crear y editar productos  
- 📬 Ver y responder consultas  
- 👥 Gestionar usuarios internos (solo administrador)

---

## 📊 Informes y listados

- Listar pedidos por estado (pendiente, enviado, cancelado)  
- Listar productos activos con filtros  
- Listar consultas por estado (respondida/no respondida)  
- Listar productos con stock bajo

---

## 🧪 Requisitos técnicos

- 📱 App nativa en **Kotlin**  
- 🧠 Arquitectura **MVVM estricta**  
- 🔗 Consumo de **API REST** con **Retrofit**  
- 🔐 Autenticación con **JWT**  
- 📦 Persistencia local con `SharedPreferences`  
- 🧭 Navegación con **Navigation Component**  
- 🧪 Pruebas con Postman y colección compartida

---

## 🎨 Prototipos y diseño visual

[🔗 Figma – Interfaz móvil](https://www.figma.com/design/FxERwK9Gtcta0wfh0eEVrK/Trabajo-Pr%C3%A1ctico-Final---DGD?node-id=1-4973&t=YZqz93cKnT1d67Vm-1)

---




