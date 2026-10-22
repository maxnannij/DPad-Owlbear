# D-Pad para Owlbear Rodeo

Extensión experimental con cuatro flechas para mover los tokens seleccionados.

## Funciones
- D-Pad visual con flechas arriba, abajo, izquierda y derecha.
- Distancia configurable por pulsación (por defecto 50 píxeles del mapa).
- Permite mover varios tokens seleccionados a la vez.

## Publicar con GitHub Pages
1. Creá un repositorio público en GitHub, por ejemplo `owlbear-dpad`.
2. Subí a la raíz del repositorio `manifest.json`, `index.html` e `icon.svg`.
3. En **Settings → Pages**, elegí **Deploy from a branch**, seleccioná `main` y `/ (root)`.
4. Esperá a que GitHub Pages publique la web.
5. Comprobá que abra `https://TU-USUARIO.github.io/owlbear-dpad/manifest.json`.
6. En Owlbear Rodeo, abrí el administrador de extensiones y elegí **Add Custom Extension**. Pegá esa URL del manifest.
7. Habilitá la extensión en tu sala y abrí el botón **D-Pad**.

## Uso
1. Seleccioná un token que tengas permiso para mover en el mapa.
2. Abrí el D-Pad.
3. Pulsá una flecha. Ajustá la distancia si el movimiento es demasiado grande o pequeño.

## Importante
Es una primera versión comunitaria, no verificada por Owlbear Rodeo. Probala en una sala de prueba antes de usarla en una partida. La API de selección y movimiento puede estar sujeta a permisos del token y cambios del SDK. El movimiento usa píxeles del mapa, no casilleros de grilla; como punto de partida, probá con 50 y ajustá según el tamaño de tu mapa.
