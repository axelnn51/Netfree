# 🎬 Mi Netflix Casero (Stremio Docker)

Este proyecto despliega un servidor de streaming tipo Netflix usando Docker en Ubuntu Server. No requiere almacenamiento local ya que utiliza protocolos P2P y streaming directo.

## 🚀 Despliegue Rápido

1. Asegúrate de tener Docker y Docker Compose instalados en tu Ubuntu Server.
2. Sube estos archivos a tu servidor.
3. Ejecuta el comando:
   ```bash
   docker compose up -d
   ```

## ⚙️ Configuración Post-Instalación

1. Accede a `http://tu-ip-servidor:8081`.
2. Ve a la sección de **Addons** e instala **Torrentio** (si no lo tienes, puedes instalarlo desde https://torrentio.strem.fun).
3. ¡Listo! Ya puedes empezar a disfrutar de tu Netflix personal. La conexión entre la interfaz web y el servidor ya está preconfigurada automáticamente.

### 🌟 Recomendación para Idioma (Español)
Al configurar **Torrentio**, selecciona:
- **Priority foreign language**: Spanish.
- **Exclusion**: Deja marcados los formatos que no quieras (ej: 4K si tu internet es lento).

## 🛠️ Hardware Optimizado
- **CPU**: i5-8400T (Soporte QuickSync activado en el compose).
- **RAM**: 8GB DDR4.
- **Storage**: 128GB M.2.

---
Creado por Antigravity.
