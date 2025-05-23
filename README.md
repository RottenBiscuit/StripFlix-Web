# 📺 Web de Gestión de Series - Frontend Angular

Esta es una aplicación web desarrollada con Angular que permite a los usuarios **ver, registrar y gestionar sus propias series favoritas**. Su diseño modular y responsivo, apoyado por Angular Material y Bootstrap, ofrece una experiencia de usuario moderna, clara e intuitiva.

---

## 🎯 ¿Qué puedes hacer con esta app?

- ✅ Visualizar una lista de series registradas
- ➕ Añadir nuevas series a tu colección
- 📝 Editar información de series ya registradas
- ❌ Eliminar series que ya no te interesen
- 🔍 Posiblemente buscar y filtrar series por nombre, categoría u otros criterios (basado en las rutas e infraestructura)

---

## 🛠️ Tecnologías Utilizadas

- **Angular 17**: Framework principal de desarrollo
- **TypeScript**: Lenguaje de programación
- **Angular Material & Bootstrap**: Componentes UI modernos
- **FontAwesome**: Íconos decorativos
- **RxJS**: Programación reactiva
- **Router Angular**: Para navegación entre vistas

---

## 📁 Estructura y Componentes

La aplicación sigue una arquitectura modular. El componente principal `AppComponent` actúa como contenedor general y usa `<router-outlet>` para renderizar vistas dinámicamente según las rutas configuradas.

```html
<router-outlet></router-outlet>
```

Esto significa que diferentes pantallas (como la lista de series o formularios de registro) se cargan dinámicamente según la navegación.

### Estructura del Proyecto:

- `src/app/`: Contiene los módulos y componentes de la app
- `app.component.ts`: Componente principal
- `app.component.html`: Contenedor con enrutamiento dinámico
- `angular.json`: Configuración global de la app
- `package.json`: Dependencias y scripts
- `styles.css` + `custom-theme.scss`: Estilos personalizados

---

## 🚀 Instalación y Puesta en Marcha

### Requisitos:

- Node.js (LTS)
- Angular CLI

### Pasos:

1. Clona este repositorio:
   ```bash
   git clone <url-del-repositorio>
   cd Frontend
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Inicia la app:
   ```bash
   ng serve
   ```

4. Abre en tu navegador:
   ```
   http://localhost:4200/
   ```

---

## 📦 Scripts disponibles

- `npm start` o `ng serve` → Servidor en desarrollo
- `ng build` → Compilar para producción
- `ng test` → Ejecutar pruebas unitarias
- `ng lint` → Verificar calidad del código

---

## 🔐 Backend (suponiendo integración)

Esta aplicación se conecta con un backend que maneja datos de series. Si estás desarrollando el backend también, asegúrate de que la API esté disponible y configurada correctamente (por ejemplo en `environment.ts`).

---

## 🎨 Estilo y Experiencia de Usuario

La app está diseñada para ser:
- Responsiva (compatible con móvil y escritorio)
- Clara e intuitiva
- Accesible visualmente gracias a Angular Material

---

## 👩‍💻 Autora

Este proyecto ha sido creado por **Sofía Millán** como parte de su aprendizaje y desarrollo profesional en tecnologías frontend modernas.

---

## 📄 Licencia

Uso libre para fines educativos o personales. Para uso comercial o distribución, consulta a la autora.

