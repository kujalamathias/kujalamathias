<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mermaid Diagram with Background Images</title>
    <style>
        .node-bg {
            background-image: url('https://raw.githubusercontent.com/kujalamathias/kujalamathias/main/image.gif');
            background-size: cover;
            display: inline-block;
            padding: 10px;
            color: #000;
        }
    </style>
</head>
<body>
    <div class="mermaid">
    %%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#fff'}}}%%
    graph TD;
        style A fill:#fff,stroke:#000,stroke-width:2px;
        style B fill:#fff,stroke:#000,stroke-width:2px;
        style C fill:#fff,stroke:#000,stroke-width:2px;
        style D fill:#fff,stroke:#000,stroke-width:2px;
        style E fill:#fff,stroke:#000,stroke-width:2px;
        
        A[<div class="node-bg">Node 1</div>]
        B[<div class="node-bg">Node 2</div>]
        C[<div class="node-bg">Circular Node</div>]
        D[<div class="node-bg">Node 3</div>]
        E[<div class="node-bg">Node 4</div>]
        
        A --> B
        B --> C
        C --> D
        D --> E
    </div>

    <script type="module">
        import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@9/dist/mermaid.esm.min.mjs';
        mermaid.initialize({ startOnLoad: true });
    </script>
</body>
</html>
