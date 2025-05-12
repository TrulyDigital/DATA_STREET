# SFTP Server

```mermaid
graph TD
    A[./server_sftp] --> B{¿Decisión?}
    B -- Sí --> C[Haz esto]
    B -- No --> D[Haz otra cosa]
    C --> E[Fin]
    D --> E

    NoteA[/"Este nodo representa la ruta del servidor SFTP"/]
    A -.-> NoteA
