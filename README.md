--como passar dados de uma table para outra no SQL--
INSERT INTO tabela_destino (coluna1, coluna2, ...)
SELECT coluna1, coluna2, ...
FROM tabela_origem
WHERE condição;  -- Se você quiser transferir apenas alguns registros
