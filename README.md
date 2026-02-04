# Variedades García - Tienda en Línea

![Variedades García](imagen/Logo1.jpg)

Una tienda en línea moderna y completa para la gestión de productos, inventario y ventas. Construida con tecnologías web modernas y Firebase para almacenamiento en la nube.

## 🌟 Características

### Para Clientes
- **Catálogo de Productos**: Visualización atractiva de todos los productos disponibles
- **Compra Directa**: Integración con WhatsApp para pedidos instantáneos
- **Interfaz Responsiva**: Funciona perfectamente en móviles, tablets y computadoras
- **Productos de Calidad**: Todos los productos son de alta calidad y extraídos de USA 🇺🇸

### Para Administradores
- **Panel de Administración**: Gestión completa de productos con contraseña segura
- **Subida de Imágenes**: Soporte para múltiples imágenes por producto
- **Gestión de Inventario**: Control de stock en tiempo real
- **Edición y Eliminación**: Modificar productos existentes fácilmente
- **Seguimiento de Ventas**: Registro automático de todas las transacciones
- **Almacenamiento Híbrido**: Firebase + localStorage para máxima compatibilidad

## 🛠️ Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Firebase Firestore
- **Estilos**: CSS Grid, Flexbox, Animaciones CSS
- **Almacenamiento**: Firebase + localStorage (fallback)
- **Hosting**: GitHub Pages

## 🚀 Instalación y Configuración

### Prerrequisitos
- Navegador web moderno
- Conexión a internet (para Firebase)
- Cuenta de Firebase (opcional para desarrollo local)

### Instalación

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/variedades-garcia.git
   cd variedades-garcia
   ```

2. **Configura Firebase (opcional para desarrollo local):**
   - Crea un proyecto en [Firebase Console](https://console.firebase.google.com/)
   - Habilita Firestore Database
   - Copia tu configuración en `index.html` (líneas 418-426)

3. **Abre en tu navegador:**
   - Abre `index.html` directamente en tu navegador
   - O usa un servidor local: `python -m http.server 8000`

## 📱 Uso

### Para Clientes
1. Navega por el catálogo de productos
2. Haz clic en "Comprar" en cualquier producto
3. Se abrirá WhatsApp automáticamente con el mensaje de pedido

### Para Administradores
1. Haz clic en "Modo Admin"
2. Ingresa la contraseña: `admin2026`
3. Accede al panel de administración:
   - **Subir Productos**: Agrega nuevos productos con imágenes
   - **Editar Productos**: Modifica nombre, precio o cantidad
   - **Eliminar Productos**: Remueve productos del catálogo
   - **Ver Inventario**: Controla el stock disponible
   - **Ver Ventas**: Revisa el historial de transacciones

## 🎨 Características de Diseño

- **Interfaz Moderna**: Gradientes suaves y sombras elegantes
- **Botones Interactivos**: Efectos hover con animaciones suaves
- **Colores Consistentes**: Paleta de colores profesional
- **Tipografía Elegante**: Fuentes serif para el branding
- **Responsive Design**: Adaptable a todos los dispositivos

## 🔧 Estructura del Proyecto

```
variedades-garcia/
├── index.html          # Archivo principal de la aplicación
├── imagen/            # Directorio de imágenes
│   └── Logo1.jpg      # Logo de la tienda
└── README.md          # Este archivo
```

## 🌐 Despliegue

Este proyecto está configurado para desplegarse automáticamente en GitHub Pages:

1. Sube tu código a un repositorio de GitHub
2. Ve a Settings > Pages
3. Selecciona "Deploy from a branch"
4. Elige la rama `main` y carpeta `/ (root)`
5. ¡Tu tienda estará online!

**URL de ejemplo:** `https://tu-usuario.github.io/variedades-garcia/`

## 🔒 Seguridad

- **Contraseña de Admin**: Cambia la contraseña por defecto en el código
- **Validación de Datos**: Verificación de entradas antes de guardar
- **Firebase Security**: Reglas de seguridad configuradas para acceso controlado

## 🤝 Contribución

¡Las contribuciones son bienvenidas! Para contribuir:

1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📞 Contacto

**Variedades García**
- WhatsApp: [+502 4496-9900](https://wa.me/44969900)
- Email: info@variedadesgarcia.com

---

⭐ **¡Si te gusta este proyecto, dale una estrella en GitHub!**

Desarrollado con ❤️ para emprendedores que quieren vender online.
