# Prova_1_IA
Repositório com os códigos da prova de IA

# Alunos
Hugo de Abreu Biella

Pedro Augusto Borges Assis

# Tema
Diagnóstico de procastinação utilizando lógica Fuzzy, com parâmetros definidos para:

baixo(low = 0),

baixo-médio(low-medium = 0.25),

médio(medium=0.5),

médio-alto(medium-high=0.75),

alto(high=1);

O sistema fuzzy é implementado no código apresentado para avaliar o nível de procrastinação usando cinco variáveis linguísticas:
"produtividade", "uso de celular", "uso de jogos elétricos", "ansiedade" e "organização".
Utilizamos as funções de pertinência e inferência para realizar o diagnóstico.

# Função de Pertinência
A função de pertinência (Linhas 71 a 89 do código) foi implementada com o uso de 'Maps'(Linhas 1 a 39 do código) onde as chaves correspondem às strings:
("low", "low-medium", "medium", "medium-high" e "high"), esses valores ("0","0.25","0.5","0.75","1"), respectivamente, sãos os graus de pertinência
que serão usados para o processo da inferência.

OBS: os dados do usuãrio são coletados a partir da função cosnt answers: Answer ={} (Linhas 91 a 97 do código).

# Função de Inferência
Com base nos valores de pertinência, é processado as informações fornecidas (Linhas 49 a 69 do código) e é gerado um resultado e uma conclusão final,
que é dada dentros do parêmtros de ("baixo", "médio" e "alto").
