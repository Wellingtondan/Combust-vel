## Documentação Fiscal – Compra de Combustível

🔍 **Visão Geral**

A aquisição de combustíveis como **óleo diesel, gasolina, etanol ou GNV** diretamente em postos de combustíveis, e utilizados **para consumo interno** da empresa (ex: abastecimento de veículos próprios), **não é operação de revenda**, mas sim de **consumo**, e deve ser corretamente classificada para evitar falhas fiscais.

---------------

🧾 **Entradas de Combustível – Uso Interno**

🔹 **CFOP (Código Fiscal de Operações)**

| **CFOP**	| **Descrição**	| **Quando usar** |
|------------|-----------------|--------------|
| 1556 |	Compra de combustíveis ou lubrificantes para consumo |	Quando adquirido dentro do estado |
| 2556 | Idem, porém para aquisições de fora do estado	| Interestadual (raro em postos) |

🔹 **CST ICMS (Regime Normal)**

| **CST**	 | **Descrição** |
|------------|-----------------|
| 060	| ICMS cobrado anteriormente por substituição tributária (ICMS-ST) |
| 061	| Idem, variação comum em alguns sistemas |

> ⚠️ Não use CST 041 – o combustível é tributado por ST, e não isento.

🔹 **CST PIS/COFINS**

| CST	| Descrição Resumida	| Uso em Combustíveis|
|------------|------------|-----------------|
| 04	| Monofásico com revenda a alíquota zero	| ✅ Entrada de produto monofásico |
| 49	| Outras operações de saída	| ✅ Saída sem crédito (revenda) |
| 70	| Aquisição sem direito a crédito	| ✅ Entrada sem crédito |
| 73	| Aquisição com alíquota zero	| ✅ Entrada com alíquota zero sem direito a crédito |
| 50	| Com direito a crédito (⚠️ não usar em combustíveis)	| ⚠️ Alerta de uso indevido |
| 98/99	| Outras operações de entrada/saída	| ⚠️ Só usar com embasamento técnico |

🔹 **Destaques na NF-e**

- **ICMS:** Já retido por substituição tributária (não há destaque).

- **PIS/COFINS:** Pode ou não estar destacado — depende da operação e NCM.
----------------

🧾 **Observações importantes**

- A empresa **não pode se creditar de ICMS**, mesmo que a nota venha com o ICMS ST embutido.

- Se a empresa estiver no **regime não cumulativo**, poderá **tomar crédito de PIS/COFINS se o combustível for insumo vinculado à atividade-fim** (ex: transportadora, construção pesada).

- O combustível **deve ser lançado como consumo**, e não como mercadoria para revenda.
---------------

📤 **Saídas – Quando aplicável**

Normalmente, **não há saída fiscal** para consumo próprio. Mas se houver ajustes (ex: perda, baixa, transferência interna):

| **CFOP**	| **Descrição** |
|------------|-----------------|
| **5949**	| Outras saídas de mercadorias não especificadas |
| **6949**	| Idem, para fora do estado (se aplicável) |

- **CST ICMS:** 060 ou 061 (mantém ST)

- **Sem destaque de ICMS ou PIS/COFINS**
---------------

🧾 **Exemplo prático – Compra de Diesel em posto**

| **Campo** |	**Valor** |
|------------|-----------------|
| Produto	| Óleo Diesel S10 |
| NCM	| 2710.19.21 |
| CFOP	| 1556 |
| CST ICMS	| 060 |
| CST PIS/COFINS	| 01 |
| Crédito ICMS	| ❌ Não permitido |
| Crédito PIS/COFINS	| ✅ Permitido se insumo e regime não cumulativo |
| Finalidade	| Abastecimento de frota própria |

📜 **Base legal**

- **ICMS-ST:**
  -  Convênio ICMS 110/2007 – Anexo II (lista de combustíveis com ST)
  -  RICMS do estado (ex: Art. 313-W em SP)

- **PIS/COFINS:**
  - Lei 10.637/2002 (PIS) e Lei 10.833/2003 (COFINS)
  - Art. 3º: possibilidade de crédito quando insumo essencial
  - IN RFB 1.110/2010 (regula PIS/COFINS monofásico sobre combustíveis)

- **Lei Kandir – LC 87/96:**
  - Art. 20, §1º: veda crédito de ICMS sobre bens e serviços de uso ou consumo

✅ **Checklist para escrituração correta**

- ☑️Verificar se a NF vem com CFOP 5656 (remessa) ou 5556 (venda direta)

- ☑️Lançar com CFOP 1556 no SPED Fiscal

- ☑️Usar CST ICMS 060 ou 061

- ☑️Validar se há crédito de PIS/COFINS (regime não cumulativo)

- ☑️Não considerar ICMS como recuperável

### Conclusão

A compra de combustível em posto para uso interno deve ser lançada com CFOP 1556, CST ICMS 060 ou 061 (ICMS-ST), sem direito a crédito de ICMS. O crédito de PIS/COFINS pode ser permitido se a empresa estiver no regime não cumulativo e o combustível for considerado insumo essencial à atividade. A correta classificação evita autuações e garante conformidade fiscal.

🖊️***Elaborado pelo colaborador:*** Wellington Daniel
