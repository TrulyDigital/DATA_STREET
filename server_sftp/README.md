# SFTP Server

```mermaid
graph TD
    A[$PROJECT_PATH/server_sftp] --> B{¿Decisión?}
    B -- Sí --> C[Haz esto]
    B -- No --> D[Haz otra cosa]
    C --> E[Fin]
    D --> E
