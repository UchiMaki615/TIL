```
I trying mermaid addon for create the flowchart.
I am troubled for managing the documents.
Even if created, may not be easily updated.
I'm trying to make the creation and updating process easier.
```


```mermaid
graph TD;
    A(Start Process)-->B[Check Request]
    B-->C{Check Results}
    C-->|OK| D[Registration User]
    C-->|NG| E[Display Error]
    E-->F(End Process)
    D-.->|Reference| H[(Users Table)]
    D-->G(Redirect Top)
```