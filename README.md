![Alt text](https://g.gravizo.com/source/svg/c1?https%3A%2F%2Fraw.githubusercontent.com%2FGreyWayfarer%2FNewRep%2Fmaster%2FREADME.md)
<details> 
<summary></summary>
c1
  digraph G {
    END -> A [label="A-Z, a-z, 0-9"];
    END -> B [label="space"];
    A -> S [label="A-Z, a-z, _"];
    S -> B [label="space"];
    B -> A [label="A-Z, a-z, 0-9"];
    A -> A [label="A-Z, a-z, 0-9"];
  }
c1
</details>
