# Terminal — releases

Este repositorio **solo publica** los instaladores firmados del Terminal (MSI de Windows), su firma (`.msi.sig`) y `latest.json`, el archivo que la app instalada consulta para actualizarse sola.

- **Aquí no hay código.** El código fuente es privado.
- Cada versión está firmada con la clave del updater de Tauri; la app verifica la firma antes de instalar nada.
- Instalación limpia: descargar el `.msi` del último release. Las copias ya instaladas se actualizan solas.
- Las ramas de este repositorio están bloqueadas (ruleset `solo-releases`): nadie puede empujar código aquí por accidente.
