# FYKOS reusable workflows

Znovupoužitelné workflows pro Github actions

## Variables & Secrets

V rámci definice `workflow_call` může workflow požadovat nadefinování vstupů.
Na uložení těchto proměnných je dobré použít `Secrets and variables` na Githubu
a nedefinovat je přímo v action souborech.

> [!CAUTION]
> Tajné tokeny NESMÍ být definované přímo v souborech a mělo by být využito
> secrets, aby byly bezpečně uloženy.
