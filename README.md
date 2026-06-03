# Ejercicio 8 - DrawerLayout y NavigationView en Android

Implementación de un menú lateral de navegación utilizando **DrawerLayout**, **NavigationView** y **MaterialToolbar** en Android Studio con Kotlin.

## Descripción

Este laboratorio tiene como objetivo aprender el uso de componentes de navegación de Android para crear una interfaz moderna basada en Material Design.

La aplicación implementa:

* Barra superior personalizada (**MaterialToolbar**).
* Menú lateral desplegable (**Navigation Drawer**).
* Encabezado personalizado dentro del menú.
* Gestión de eventos de navegación.
* Personalización de temas y colores.
* Uso de recursos gráficos e íconos vectoriales.

---

## Tecnologías Utilizadas

* Kotlin
* Android Studio
* Material Design Components
* DrawerLayout
* NavigationView
* MaterialToolbar
* Android SDK 26+
* View System (XML)

---

## Estructura del Proyecto

```text
Laboratorio_8/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/mx/unam/
│   │   │   │   ├── ui/theme/
│   │   │   │   │   └── Color.kt
│   │   │   │   └── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── drawable/
│   │   │   │   ├── layout/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   ├── bar_main.xml
│   │   │   │   │   └── header_main.xml
│   │   │   │   ├── menu/
│   │   │   │   │   └── activity_main_menu.xml
│   │   │   │   └── values/
│   │   │   │       ├── colors.xml
│   │   │   │       └── themes.xml
│   │   │   └── AndroidManifest.xml
│   │   ├── test/
│   │   └── androidTest/
│   ├── build.gradle.kts
│   └── proguard-rules.pro
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
├── gradle.properties
└── gradlew
```

---

<img width="433" height="994" alt="image" src="https://github.com/user-attachments/assets/0556b43c-9fe0-449b-b511-1838bfae7240" />


## Componentes Implementados

### MainActivity

Se encarga de:

* Inicializar la barra de herramientas.
* Configurar el DrawerLayout.
* Gestionar la apertura y cierre del menú lateral.
* Registrar eventos de navegación.
* Cargar dinámicamente el encabezado del menú.

### activity_main.xml

Contiene:

* DrawerLayout principal.
* Imagen principal de la aplicación.
* Inclusión de la barra superior.
* NavigationView para el menú lateral.

### bar_main.xml

Define:

* AppBarLayout.
* MaterialToolbar.
* Título de la aplicación.

### header_main.xml

Diseña el encabezado del menú lateral:

* Imagen de fondo.
* Logo institucional.
* CardView para resaltar el logo.

### activity_main_menu.xml

Define los elementos de navegación:

* Grupo de opciones.
* Submenús.
* Íconos vectoriales.
* Elementos seleccionables.

---

## Personalización Visual

### Colores utilizados

| Nombre      | Valor     |
| ----------- | --------- |
| fondo_color | #E92DBAFA |
| menu_color  | #D88FC8E3 |
| purple_700  | #FF3700B3 |
| white       | #FFFFFFFF |

### Tema

```xml
Theme.Movil.NoActionBar
```

Permite ocultar la barra de acción nativa para utilizar una Toolbar personalizada.

---

## Interfaz de Usuario

La aplicación muestra:

1. Imagen principal en pantalla.
2. Barra superior personalizada.
3. Menú lateral deslizable.
4. Encabezado personalizado con logotipo.
5. Opciones de navegación mediante Material Design.

---

## Ejecución

### Requisitos

* Android Studio
* JDK 17 o superior
* Android SDK API 26+
* Emulador Pixel 2 API 33 o dispositivo físico

### Pasos

```bash
git clone https://github.com/usuario/Laboratorio_8.git
```

Abrir el proyecto en Android Studio y ejecutar:

```bash
Run > Run 'app'
```

---

## Conceptos Aprendidos

* DrawerLayout
* NavigationView
* MaterialToolbar
* ActionBarDrawerToggle
* Navigation Drawer
* CardView
* Temas personalizados
* Recursos XML
* Material Design
* Manejo de eventos de navegación

---


