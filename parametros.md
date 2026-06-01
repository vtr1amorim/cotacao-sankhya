# Parâmetros — Módulo Cotação Sankhya

Planilha de controle. Preencha **Valor atual** consultando *Preferências/Parâmetros do Sistema* no Sankhya Om, defina o **Valor desejado** com a área de Compras e marque o status ao concluir.

| # | Chave | Descrição | Valor atual | Valor desejado | Status | Responsável | Data | Observações |
|---|---|---|---|---|---|---|---|---|
| 1 | `USAMODCABCOT` | Utiliza Cotação no Modo Cabeçalho | | Ligado | ☐ | | | Define modo da tela e do Portal |
| 2 | `ALERTRESPMINCOT` | Mínimo de respostas p/ sugestão de resultado | | 3 | ☐ | | | Item vira "Precificada" ao atingir |
| 3 | `RESPCOTCOMPR` | Responsável pela cotação tem que ser comprador? | | Ligado | ☐ | | | Restringe lançamento |
| 4 | `TRABMOECOT` | Trabalhar com moedas na cotação | | Desligado | ☐ | | | Ligar só se houver fornecedor estrangeiro |
| 5 | `INFMOTCANCOT` | Informar motivo de cancelamento | | Ligado | ☐ | | | Exige cadastro de motivos |
| 6 | `COTDESAPPEDGER` | Permite desaprovar produto com pedido gerado | | Desligado | ☐ | | | Cuidado: pode gerar inconsistência |
| 7 | `CODPRODGENCOT` | Produto genérico que pode repetir | | 0 | ☐ | | | -1=todos, 0=nenhum, >0=apenas o código |
| 8 | `DECVLRIMPUNTCOT` | Decimais p/ impostos unitários | | 2 | ☐ | | | Precisão dos impostos |

## Marcações em *Cotação → Outras Opções → Preferências*

| Marcação | Aplicar? | Observação |
|---|---|---|
| Calcular custos e preço | ☐ | Requer Modelo de Nota |
| Calcular ICMS, ST e IPI | ☐ | Desconsidera valores manuais de imposto |
| Exibir último valor unitário da compra | ☐ | Útil para histórico |
| Modelo de Nota padrão | ☐ | Informar código do modelo |
