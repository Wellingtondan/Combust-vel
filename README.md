## Documentação Fiscal – Compra de Combustível

🔍 **Visão Geral**

A aquisição de combustíveis como **óleo diesel, gasolina, etanol ou GNV**, diretamente em postos de combustíveis e utilizados **para consumo interno** da empresa (ex: abastecimento de veículos próprios), **não caracteriza revenda**, e sim **uso/consumo**. A escrituração correta evita autuações fiscais e inconsistências no SPED.

---------------

🧾 **Entradas de Combustível – Uso Interno**

🔹 **CFOP (Código Fiscal de Operações)**

| **CFOP**	| **Descrição**	| **Quando usar** |
|------------|-----------------|--------------|
| 1653 | Compra de combustível por consumidor final | ✅ Mais apropriado para empresas que abastecem em postos, com ICMS-ST já retido |
| 1556 |	Compra de combustíveis ou lubrificantes para consumo |Alternativa válida (uso genérico) |
| 2556 | Idem, porém para aquisições de fora do estado	| Uso raro em compras interestaduais |

>💡 **Recomendação:** O **CFOP 1653** é o mais indicado quando o combustível é adquirido diretamente em posto com NF sem destaque de ICMS.

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
  
- Em notas de compra, confira sempre o CFOP e CST utilizados.
  
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
| CFOP	| 1653 |
| CST ICMS	| 061 |
| CST PIS/COFINS	| 04 ou 70 |
| Crédito ICMS	| ❌ Não permitido |
| Crédito PIS/COFINS	| ✅ Permitido se insumo e regime não cumulativo |
| Finalidade	| Abastecimento de frota própria |

---------------------------

📌 **CFOP 1556 vs 1653 – Qual usar?**

| CFOP	| Descrição	Quando usar |
|------------|-----------------|
| 1556	| Compra de combustível para consumo	| Nota com ICMS-ST, uso interno |
| 1653	| Compra por consumidor final	| Mais preciso para consumo em frota própria |

> ✅ Ambos são aceitos, mas o **1653** é o mais **adequado e específico** para compra direta em posto.

---------------------

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

---------------------

✅ **Checklist para escrituração correta**

- ☑️Verificar CFOP da NF (preferência: 1653)

- ☑️Usar CST ICMS 060 ou 061

- ☑️Validar CST PIS/COFINS (geralmente 04, 70 ou 73)

- ☑️Classificar **como uso/consumo**

- ☑️Conferir se há direito a crédito de PIS/COFINS (caso insumo + regime não cumulativo)

- ☑️Não considerar ICMS como recuperável

------------------------

### Conclusão

A compra de combustível para uso interno (frota, geradores, empilhadeiras etc.) deve ser tratada como consumo, com CFOP 1653 e CST ICMS 060 ou 061. O crédito de PIS/COFINS é possível apenas em casos específicos (regime não cumulativo + insumo essencial). Evite o uso indevido de CST 50 e CFOPs de revenda. A correta escrituração fiscal é essencial para manter a conformidade e evitar passivos tributários.

🖊️***Elaborado pelo colaborador:*** Wellington Daniel
