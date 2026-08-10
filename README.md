# 📊 Análise de Vendas — BrightMart Retail Co.

## Por que eu fiz esse projeto?

Eu queria responder uma pergunta simples:
**"Onde está o dinheiro que essa empresa está deixando na mesa?"**

Pegar um dataset bruto de varejo e transformar em decisões acionáveis —
sem relatório bonito, sem gráfico decorativo. Só resposta para quem decide.

---

## Como eu pensei o problema

Antes de abrir o Excel, me fiz três perguntas:

1. **O que está vendendo mais — e o que está dando mais lucro?** (nem sempre é a mesma coisa)
2. **Existe alguma região ou loja que destoa das outras?**
3. **Tem algum padrão nos pedidos cancelados ou devolvidos?**

Essas três perguntas guiaram todas as métricas que escolhi construir.
Não fui pelo caminho de "vou criar todos os gráficos possíveis".
Fui pelo caminho de "o que eu precisaria saber se fosse o gerente dessa rede?"

---

## O que os dados disseram

> 6.000 transações · $1,86M em vendas · Margem de 39,9%

**Electronics domina — mas com armadilha.**
A categoria representa 50% do faturamento total ($935K), muito à frente de
Home & Kitchen ($327K) e Sports & Outdoors ($283K).
O problema: Electronics também concentra os tickets mais altos e,
proporcionalmente, mais devoluções. Faturamento alto ≠ lucro garantido.

**A região Midwest é o ponto de atenção.**
Northeast lidera em vendas ($547K), seguido por West ($504K) e South ($455K).
O Midwest ficou em $355K — quase $200K abaixo do líder, com a mesma
quantidade de lojas proporcionalmente. Isso não é azar. É um problema
operacional ou de mix de produto que merece investigação.

**8,5% dos pedidos nunca viraram receita.**
510 devoluções + 303 cancelamentos = 813 pedidos que consumiram custo
operacional e não geraram retorno. Em $1,86M de vendas, isso representa
um vazamento silencioso que nenhum dashboard de vendas sozinho captura.

**Nenhum método de pagamento domina.**
Cash (1.233), Debit Card (1.229), Credit Card (1.208), Bank Transfer (1.173)
e Digital Wallet (1.157) ficaram todos muito próximos. Isso sugere que
a base de clientes é diversa — e que campanhas segmentadas por
comportamento de pagamento podem ter baixo retorno.

---

## O que eu errei (e aprendi)

No início, comecei analisando vendas brutas por categoria e achei que
Electronics era imbatível. Esqueci de cruzar com margem e status dos pedidos.
Quando fiz esse cruzamento, a história mudou — e eu tive que refazer
parte da análise.

Também não separei devoluções de cancelamentos logo de cara,
o que distorceu minha leitura de taxa de conversão por algumas horas.
Detalhe simples, erro caro.

---

## O que eu faria diferente hoje

- Cruzaria **devoluções por categoria e por loja** desde o início —
  é onde mora o insight mais acionável
- Incluiria uma análise de **cohort por membership tier** (Bronze/Silver/Gold)
  para entender se clientes mais engajados têm ticket médio e margem maiores
- Adicionaria **sazonalidade mensal** para identificar picos e vales de demanda

---

## Ferramentas

`Microsoft Excel` — tratamento de dados, tabelas dinâmicas, indicadores e dashboard

---

## Dataset

Dados fictícios gerados para fins de portfólio.
Estrutura baseada em cenários reais de varejo multicanal.
