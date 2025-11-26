## 🧾 Receipts Module

O módulo de **Receipts** é responsável pela emissão e consulta de documentos fiscais ou recibos vinculados a pedidos de venda.  
Ele garante que cada transação registrada no sistema possa gerar um comprovante oficial, assegurando conformidade legal e transparência para o cliente.  

### Principais responsabilidades:
- Emitir notas fiscais ou recibos associados a pedidos de venda.
- Disponibilizar consulta de documentos fiscais já emitidos.
- Integrar com o módulo de **Sales** para vincular pedidos e pagamentos.
- Garantir rastreabilidade e integridade dos documentos fiscais.

---

## 🔹 Endpoints

- **POST /receipt/orders/{id}/invoice** → Gera uma nota fiscal ou recibo vinculado a um pedido específico, incluindo informações de cliente, itens e valores.  

- **GET /receipt/orders/{id}/invoice** →  Consulta a nota fiscal ou recibo já emitido para um pedido específico, retornando detalhes como número do documento, data e status.  
