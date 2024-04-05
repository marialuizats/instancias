# Instâncias - Mestrado

---

Os arquivos aqui encontrados foram os utilizados na execução de testes para a defesa de Mestrado.

Ao todo, são apresentadas cinco instâncias com 1000 **clientes (endereços)** diferentes, onde cada **cliente** tem o seu respectivo pedido, com os produtos que deverão ser entregues. Além disso, temos os estoques dos ***fulfillment centers*** para cada produto disponível, sendo 20 no total.

As informações contidas no arquivo ***Sample.zip*** são detalhadas abaixo. Para todas as pastas informadas, cada arquivo corresponde a uma instância diferente.

### Pastas:

- Endereços:
    - O conteúdo dos arquivos é explicados como segue:
        - Cada linha se refere a um **cliente**;
        - A primeira coluna se refere a **latitude** do endereço do **cliente** informado.
        - A segunda coluna se refere a **longitude** do endereço do **cliente** informado.
        - A terceira coluna se refere ao ***service center*** específico do cliente, caso os cenários 1 e 2 sejam utilizados para execução da instância, conforme explicado na dissertação de mestrado e no relatório final.
        - A quarta coluna informa se o cliente específico se encontra na intersecção dos dois ***service centers***, caso o cenário 2 seja utilizado para execução da instância. Caso o cliente esteja na intersecção, a célula terá o valor “Limbo”; caso o cliente não faça parte da intersecção, a célula terá o valor “No”.
- Estoque:
    - O conteúdo dos arquivos é explicados como segue:
        - Cada linha corresponde a um ***fulfillment center**, onde* a matriz indica a quantidade de itens de cada produto, dado pela posição (índice) da matriz, disponível no ***fulfillment center*** indicado.
- Pedidos:
    - O conteúdo dos arquivos é explicados como segue:
        - Cada linha corresponde a um **cliente**, onde a matriz indica a quantidade de itens de cada produto, dado pela posição (índice) da matriz, solicitados no pedido do **cliente** indicado.
- Pesos:
    - Pedidos:
        - Cada linha corresponde ao volume do **pedido** do **cliente** indicado.
    - Produtos:
        - Cada linha corresponde ao volume do **produto** indicado.

Desenvolvedora: Maria Luíza Teixeira Santos.
