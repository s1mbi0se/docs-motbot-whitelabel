---
hide:
  - toc
---

# Adição do novo cliente à lista de tenants

## Esse passo, assim como o anterior, também deve ser feito manualmente ainda, mas futuramente imagina-se uma interface gráfica para o mesmo.

1. Abra um terminal dentro da pasta do projeto, e rode os seguintes comandos
    ```bash linenums="1"
    pipenv shell
    pipenv install
    make migrate
    ```

2. Feito isso, as migrações do cliente estão prontas, e já pode ser levantado um front-end para ele!
