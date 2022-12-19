The OWL is only designed to be compatible with free open-source licenses.  This graph shows how a license is chosen to be either OWL-compatible or not.

```mermaid
graph TD
    B[License is PD] --> C[Yes]
    C --> D[Compatible with the OWL]
    Q --> Yes --> D
    B --> X[No] --> Q[License provides permissions to modify and distribute for any purpose - including commercially]
    Q --> X2[No]
    X2 --> E[Incompatible with the OWL - proprietary]
```

This graph is completely made with **Mermaid**, a graph renderer. The source code of this document contains the graph code. It can help you with Mermaid graphing ;)
