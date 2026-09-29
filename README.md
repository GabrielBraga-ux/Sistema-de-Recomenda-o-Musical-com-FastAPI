Atividade prática — implementada em Python com o dataset Top 50 Music de 2010 a 2019.

Este notebook segue os requisitos do PDF e apresenta cinco APIs de recomendação: por características musicais, por gênero/artista, filtro colaborativo simulado, híbrida e popularidade/ano. Inclui exploração dos dados, documentação dos endpoints, exemplos e testes locais com TestClient.
O CSV contém músicas populares e características musicais, mas não contém histórico real de usuários. Por isso, o endpoint colaborativo usa interações simuladas e determinísticas, agrupando faixas reais por gêneros para demonstrar co-ocorrências. Não se deve interpretar essa parte como comportamento real de ouvintes.
