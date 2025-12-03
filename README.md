# 📅 Plataforma Web para la Administración de Citas  

Aplicación web construida para facilitar la organización, registro y gestión de citas mediante una interfaz moderna, fluida y altamente automatizada. El sistema integra calendario interactivo, manejo avanzado de datos, validaciones internas y herramientas inteligentes para generar citas de prueba.

Este proyecto combina frontend, backend y lógica de estado en un solo entorno, ofreciendo una experiencia completa para la programación de citas con proveedores y servicios.

---

## 📝 Descripción General  

La plataforma fue diseñada para centralizar todo el proceso de administración de citas. Desde la vista del calendario hasta la creación, consulta y cancelación, todo el flujo se realiza de forma intuitiva.

### Funcionalidades clave:
- **Calendario interactivo**: Visualización de citas en un calendario mensual.
- **Creación de citas**: Los usuarios pueden seleccionar un horario disponible y crear citas.
- **Detalles de citas**: Consultar detalles completos de citas existentes.
- **Cancelación de citas**: Cancelar citas mediante un proceso seguro con confirmación.
- **Generación de citas automáticas**: Citas aleatorias con validación de horarios disponibles.
- **Población rápida de calendarios**: Llenado automático de un mes con citas para pruebas de carga.

La plataforma fue construida sobre tecnologías modernas que permiten rapidez, modularidad y fácil escalabilidad.

---

## 🧩 Tecnologías Implementadas  

### **Frontend**
- **Next.js 14**  
- **React 18**
- **TypeScript**
- **Tailwind CSS**
- **React Big Calendar**
- **Day.js**

### **Gestión y Consumo de Datos**
- **TanStack React Query**
- Hooks personalizados para manejo de:  
  - Citas  
  - Proveedores  
  - Servicios  

### **Backend / API Interna**
- Rutas REST internas integradas en Next.js  
- Validación estricta de datos con **Zod**  
- Modelos tipados completamente con TypeScript  

### **Funciones Auxiliares**
- Generador inteligente de citas aleatorias  
- Verificador automático de disponibilidad  
- Formularios dinámicos y modales reutilizables  
- Herramientas para llenar meses completos para pruebas masivas  

---

## ⚙️ Funcionamiento General del Sistema  

### **1. Vista del Calendario**  
El calendario muestra todas las citas provenientes del backend.  
Permite:  
- Navegación por meses  
- Selección de fechas vacías para crear una cita  
- Clic en citas existentes para ver detalles  
- Actualización automática sin recargar la página  

### **2. Registro de Citas**  
Al elegir un espacio disponible:  
- Se abre un formulario con fecha y hora predefinidas  
- El usuario selecciona cliente, proveedor y servicio  
- La API verifica disponibilidad antes de confirmar la creación  

### **3. Información de una Cita**  
Al abrir una cita existente se despliega un modal que muestra:  
- Datos completos del cliente  
- Proveedor asignado  
- Servicio solicitado  
- Fecha y hora exactas  
- Botón para cancelar la cita con confirmación  

### **4. Generación Automática**  
El sistema cuenta con una sección especializada que permite:  
- Crear citas con datos aleatorios realistas  
- Seleccionar proveedores y servicios al azar  
- Verificar horarios disponibles de forma automatizada  
- Generar decenas o cientos de citas para pruebas visuales y de carga  
- Llenar un mes completo con citas entre 7 AM y 8 PM  

---

## ⭐ Características Principales  
- **Gestión integral de citas** desde un solo panel  
- **Interfaz moderna y responsiva**  
- **API interna** con validaciones robustas  
- **Automatización avanzada** para pruebas y demostraciones  
- **Componentes organizados** y reutilizables  
- **Código limpio** y fácil de mantener  

---

