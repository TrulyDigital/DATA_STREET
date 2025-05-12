# SFTP Server

```mermaid
graph TD
    A[./server_sftp] -- To have --> B[./yahoo_finance]
    A -- Can have --> C[./other_folders]
    B --> D[./1_file_new]
    B --> E[./2_file_processed]
    B --> F[./3_errors]
```

## Otro

```mermaid
graph TD
    subgraph Contenedor_A [Linux Server]
        A1[&lt;&lt;folder&gt;&gt;\<br/> 📂 server_sftp]
        A2[&lt;&lt;sub_folder&gt;&gt;\<br/> 📂 yahoo_finance]
        A3[&lt;&lt;sub_folder&gt;&gt;\<br/> 📂 other_folder]
        A4[&lt;&lt;sub_folder&gt;&gt;\<br/> 📂 other_folder]
    end

    A1 --> A2
    A1 --> A3
    A1 --> A4
```

## Aprendiendo mermad

```mermaid
graph TB
    subgraph Contenedor_A [Contenedor A]
        A1[Servicio 1]
        A2[Servicio 2]
    end

    subgraph Contenedor_B [Contenedor B]
        B1[Servicio 3]
    end

    A1 --> B1
    A2 --> B1
```


