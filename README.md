# Práctica CSS. Módulo LMSGI

## Introducción

En esta práctica he desarrollado un sitio web con la finalidad de aprender las características de CSS. El objetivo era diseñar un sitio "responsive" adaptable a distintos tamaños de pantalla.

## Objetivos

1. Definir reglas CSS usando diferentes selectores.
2. Usar variables y funciones en CSS.
3. Comprender y modificar el modelo de cajas.
4. Utilizar unidades de medida absolutas y relativas.
5. Implementar transformaciones, transiciones y animaciones.
6. Establecer diferentes diseños para distintos tamaños de pantalla.

## Preparando el entorno

- La práctica se realizó en parejas.
- Se permitió la selección libre del IDE.
- Creé un repositorio en GitHub y añadí como colaboradores a mi compañero/a, rgmf (Román Martínez) y pasantiagosantig (Pedro Antonio).
- La entrega se realizó en Aules para LMSGI y en GitHub para ED en la fecha indicada.

## Enunciado

Nos pidieron crear un pequeño sitio web para una empresa de vídeo bajo demanda. El sitio debía tener un diseño adaptable a distintos tamaños de pantalla y proporcionar una experiencia de usuario agradable.

## Estructura de directorios

Tal y como se vio en el tema anterior, la carpeta del sitio tiene la siguiente estructura:

- Carpeta `css`: Contiene los archivos CSS.
- Carpeta `img`: Contiene las imágenes del sitio.
- Carpeta `js`: Contiene los archivos JS.
- Ficheros `index.html`, `detalle.html` y `configuracion.html`.

## Estructura de la web

El sitio web se ve correctamente en 4 tipos de dispositivos:

1. **Compactos**: Ancho de pantalla máximo de 480px (móviles).
2. **Normal**: Ancho de pantalla máximo de 768px (tablets verticales).
3. **Mediano**: Ancho de pantalla hasta 1024px (tablets en horizontal).
4. **Grande**: Ancho de pantalla mayor de 1024px (monitor).

### Página principal

La página principal contiene tres grupos de tarjetas:

1. Estrenos
2. Series
3. Películas

Cada tarjeta muestra:

- Imagen
- Título
- Duración y año
- Puntuación (con iconos de 0 a 5)

### Página detalle

En la página detalle de cada película se encuentra la información de la misma:

- Título
- Imagen (con una barra simulando los botones de reproducción y pausa en la parte inferior)
- Duración
- Puntuación
- Sinopsis
- Comentarios (numerados de forma automática usando contadores CSS)

### Página de perfil

La página de perfil contiene un formulario con los datos del usuario:

- Nombre
- Email
- Dirección
- Teléfono
- Contraseña
- Confirmar contraseña

Además, cuenta con botones de enviar y cancelar.

## Variables y colores

Definí una gama de colores en variables para facilitar futuros cambios en el diseño. Usé herramientas como Coolors y Colorhunt.co para definir los colores principales, secundarios y complementarios.
