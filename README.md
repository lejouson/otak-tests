# otak-tests
Tests for the otak mini server

## 2025-11-7

- [x] Ejecutar [caddy](./caddy/compose.yaml) fuera de Portainer
  - Sí monta el fichero
  - Igualmente no puedo acceder por https `https://127.0.0.1:8443`
  - En VS Code la pestaña ports de Codespace saca una URL rara para el puerto
  - No hace lo mismo para el resto de puertos
- [x] Ejecutar caddy dentro de Portainer
  - No monta el fichero
- [x] Montar el fichero en otra imagen
  - Uso redis
  - Dentro de Portainer no funciona
  - Fuera de Portainer sí
- Pruebas adicionales
  - Poner portainer detrás de caddy