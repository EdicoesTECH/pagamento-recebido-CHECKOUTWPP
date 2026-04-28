# Página de redirecionamento - PagBank

Esta página é usada como URL de redirecionamento após o cliente concluir a etapa de pagamento no Checkout PagBank.

Ela apenas orienta o cliente a aguardar a confirmação do pagamento pelo WhatsApp.

A confirmação real do pagamento é feita por webhook no n8n, por meio da URL configurada em `payment_notification_urls` na requisição de criação do checkout PagBank.

## Arquivos

- `index.html`: página exibida ao cliente após o redirecionamento do PagBank.
