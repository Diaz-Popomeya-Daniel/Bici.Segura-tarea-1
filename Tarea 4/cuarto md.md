### 1. Diseño de Interfaz

Escritorio: Pantalla dividida (Mapa + Lista) para ver todo a la vez.

Móvil: Pestañas abajo (como una app nativa) para no amontonar el mapa.

Animación: Al hacer clic en la lista, el mapa se mueve suavemente (FlyTo) hacia el lugar.

### 2. Lista de Mejoras de Accesibilidad

Lectores de Pantalla: Agregué aria-label="Acercar mapa" y aria-label="Alejar mapa" a los botones de zoom para que las personas con discapacidad visual sepan qué hacen.

Contraste Visual: Elegí marcadores azules porque se distinguen bien tanto sobre el gris de las calles como sobre el verde de los parques.

Facilidad de Uso: Aumenté el tamaño de los botones a 44px para que sean fáciles de tocar en pantallas táctiles.

### Prompts

Modifica la interfaz para tener dos columnas (o pestañas en móvil): 'Mapa' y 'Lista de Lugares'. Cuando se agregue un marcador en el mapa, debe aparecer también como un texto descriptivo en la sección de Lista (ej. 'Punto en Lat: X, Long: Y'). Asegúrate de que los botones del mapa tengan atributos 'aria-label' como 'Acercar mapa' o 'Alejar mapa'.

Ok ahora quiero que pongas un boton que me deje hacer rutas osea que yo ponga un punto y luego otro y que los vaya juntando con una linea