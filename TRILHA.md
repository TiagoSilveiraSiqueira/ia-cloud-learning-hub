# Oito entregas para praticar IA aplicada à TI

Cada etapa usa um projeto público e termina com uma entrega que pode ser revisada. O tempo sugerido serve apenas para organizar sua prática.

## 1. Executar e interpretar

Abra o início rápido do [Operations Lab](https://github.com/TiagoSilveiraSiqueira/azure-ai-operations-lab), execute o modo demo e leia `uses_llm`, `mode_used` e as evidências citadas.

**Entrega:** uma nota dizendo como a saída foi produzida, qual sintoma foi classificado e o que a entrada não confirma.

**Revisão:** a nota diferencia classificação de sintoma, hipótese e causa raiz; o modo descrito corresponde à saída.

## 2. Organizar uma passagem de contexto

Aplique a [skill de triagem](https://github.com/TiagoSilveiraSiqueira/skills-para-times-de-ti) a um exemplo fictício. Peça fatos, impacto declarado, lacunas e próximos passos.

**Entrega:** uma triagem que outra pessoa consiga continuar.

**Revisão:** métricas mantêm unidade e janela; a prioridade usa uma política fornecida ou permanece a confirmar.

## 3. Separar conhecimento inicial e posterior

Faça o exercício A de um [caso público de prompts](https://github.com/TiagoSilveiraSiqueira/engenharia-de-prompts-na-pratica/tree/main/casos-publicos). Depois leia a análise posterior e faça o exercício B.

**Entrega:** duas atualizações e uma explicação de qual conclusão só se tornou possível depois.

**Revisão:** a primeira atualização preserva a incerteza; a segunda identifica as fontes do conhecimento adicional.

## 4. Conferir uma recuperação de documentos

No [RAG Runbooks Lab](https://github.com/TiagoSilveiraSiqueira/rag-runbooks-lab), faça uma pergunta relacionada ao corpus. Confira os fragmentos e suas fontes. Em seguida, faça uma pergunta fora do conteúdo.

**Entrega:** pergunta pertinente, resultado recuperado e exemplo de falta de evidência.

**Revisão:** a entrega diferencia recuperação lexical, resposta extrativa e modo de modelo local; nenhuma citação é tratada como prova automática de toda a resposta.

## 5. Ler métricas de avaliação

Execute os exemplos do [AI Evaluation Lab](https://github.com/TiagoSilveiraSiqueira/ai-evaluation-lab). Compare as fixtures e leia o critério de cada falha.

**Entrega:** uma tabela com a métrica, seu denominador e um caso que justifica o resultado.

**Revisão:** os números são atribuídos às fixtures avaliadas, sem anunciar uma melhora comprovada de um LLM real.

## 6. Criar um caso de regressão

Escolha uma falha documentada no avaliador ou um cenário de entrada que o laboratório permite alterar. Crie uma variação fictícia com comportamento esperado e execute o teste correspondente.

**Entrega:** entrada, resultado observado e critério esperado.

**Revisão:** o critério verifica uma propriedade útil, como referência válida ou rejeição de dado inválido, sem depender apenas da redação exata de uma frase.

## 7. Comparar custos com premissas

Use o [Cloud FinOps Toolkit](https://github.com/TiagoSilveiraSiqueira/cloud-finops-toolkit) para comparar os cenários incluídos. Confira moeda, unidade, preço consultado, quantidade e horas de utilização.

**Entrega:** estimativa base, alternativa e diferença, com as exclusões do cálculo.

**Revisão:** a diferença é descrita como potencial sob as mesmas premissas; o snapshot público não é apresentado como uma fatura real ou um preço garantido no futuro.

## 8. Preparar uma decisão revisável

Combine a triagem, as fontes consultadas, a avaliação e as premissas de custo em uma proposta de laboratório. Use a skill de runbook para documentar a continuidade.

**Entrega:** proposta de uma página e um procedimento de revisão.

**Revisão:** cada resultado tem evidência; alternativas e pendências estão explícitas; ações que dependem de ambiente, acesso ou orçamento permanecem propostas para decisão humana.
