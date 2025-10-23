SELECT
[T0].[TransId] AS [ID_Lancamento],
[T0].[RefDate] AS [Data_Lancamento],
[T0].[Memo] AS [Descricao_Cabecalho],
[T1].[Account] AS [Conta_Contabil],
[T1].[Debit] AS [Valor_Debito],
[T1].[Credit] AS [Valor_Credito],
[T1].[LineMemo] AS [Descricao_Linha],
[T1].[ShortName] AS [Codigo_PN]
FROM [OJDT] AS [T0]
INNER JOIN [JDT1] AS [T1] ON [T0].[TransId] = [T1].[TransId]
WHERE [T0].[RefDate] >= '2023-01-01'; -- Exemplo de filtro por data, ajuste conforme necessário
