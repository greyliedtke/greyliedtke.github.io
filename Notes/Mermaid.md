# Mermaid

A minimal language for creating diagrams and such

- Diagrams with [Mermaid](https://mermaid-js.github.io/mermaid/#/classDiagram?id=setting-the-direction-of-the-diagram)
  - [Lines](https://mermaid-js.github.io/mermaid/#/flowchart?id=links-between-nodes)
  - [Great Example](https://dompl.medium.com/produce-great-looking-flowcharts-in-seconds-7f3bea64f2e2)
  - linkStyle 1 stroke:#Red
    - Assign color to links
  - Node colors 
    -     %% Define classes
          classDef Red fill:Red;
          classDef Black fill:Black;
    -     %% Assigning styles to nodes
          class DC+ Red;
          class DC- Black;

## Examples
:::mermaid
