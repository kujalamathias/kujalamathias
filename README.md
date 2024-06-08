## Hi there 👋

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#fff'}, 'flowchart': {'htmlLabels': false}}}%%
<style>
  .node-background {
    background-image: url("https://raw.githubusercontent.com/kujalamathias/kujalamathias/main/image.gif");
    background-size: cover;
  }
</style>

graph TD;
    A[Node with background]:::node-background
    B[Another node]:::node-background
    C((Circular Node)):::node-background
    D[Node 1] --> E[Node 2]

    class D node-background;
    class E node-background;
