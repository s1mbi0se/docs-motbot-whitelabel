---
hide:
  - toc
---

# Adição do novo cliente à lista de tenants

## Esse passo, assim como o anterior, também deve ser feito manualmente ainda, mas futuramente imagina-se uma interface gráfica para o mesmo.

1. Abra o banco no schema Common (default=whitelabel_common)
2. Abra a tabela tenants_control e adicione uma nova linha.
3. Preencha adicionando um Nome (Não tem nenhum impacto final, é para facil identificação)
4. Adicione o Host, note que não deve ser adicionado subdomínio, e sim o domínio principal do host, por exemplo: `meutime.dev.br`
5. Adicione o Schema que acabou de criar para esse host (Importante: Não faça nenhuma alteração manual nesse schema adicionando tabelas ou outras configurações!)

#### **Agora sim! Com nosso cliente Criado e seu Schema devidamente vinculado a ele, partimos para as migrações.**
