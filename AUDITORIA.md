# Auditoria da apresentação revisada

Revisão confrontada com Lista1_EconometriaII_2026.pdf. As perguntas seguem separadas das respostas; a tabela de 2(b) é uma única comparação continuada em três slides para preservar a leitura.

| Item | Slides | Conteúdo conferido |
|---|---|---|
| 1(a) | 1, 2, 3 | Seis gráficos separados; estatísticas completas de nível e 100 Δlog; unidades e comparação. |
| 1(b) | 4, 5, 6, 7 | FAC/FACP de h, s, Δlog h e Δlog s; FAC/FACP dos logs para discutir raízes; 48 defasagens e bandas. |
| 1(c) | 8, 9, 10, 11 | Dois seasonal subseries plots efetivos (12 painéis cada), perfil médio e comparação. |
| 2(a) | 12, 13 | d=1 em HOUST original, quatro candidatos não sazonais e justificativas FAC/FACP. |
| 2(b) | 14, 15, 16, 17 | Tabela comparativa de 12 modelos, continuada em três slides: coeficientes, EP, t, σ², AIC/BIC e amostra comum. |
| 2(c) | 18, 19 | Polinômios AR/MA e integração, raízes, círculo de raízes inversas, estacionariedade/invertibilidade e cancelamento. |
| 2(d) | 20, 21, 22 | FAC residual e quadrados; valores de Q(6,12,24), gl e p; ARCH-LM; caminho de 24 modelos e ressalvas. |
| 2(e) | 23, 24 | Seleção manual/automática, configurações, termos sazonais e interpretação cuidadosa da restrição. |
| 3(a) | 25, 26, 27, 28, 29, 30 | Identificação de p,q,P,Q; justificativas; estimativas e IC de quatro candidatos; FAC residual de cada um; Q(12,24,36) e ARCH; escolha. |
| 4(a) | 31, 32, 33 | 131 previsões de um passo, janela expansível, RMSE/MAE/MAPE e fórmulas. Ressalva explícita de seleção histórica. |
| 4(b) | 34, 35, 36 | Alvo comum, fórmula do fator estimado só no passado, gráficos 2025 com intervalos e limitações. |
| 4(c) | 37, 38 | Recomendação condicionada ao alvo bruto e às falhas residuais/limitações da avaliação. |
| 2ª parte (a) | 39, 40, 41 | Log-retornos, série temporal, distribuição descritiva, ARCH-LM em múltiplas defasagens e interpretação. |
| 2ª parte (b) | 42, 43, 44, 45, 46, 47 | Equação e características EGARCH; estimação; seleção manual/automática; FAC z/z²; Q/ARCH; Q-Q t; assimetria e sensibilidade. |
| 2ª parte (c) | 48, 49, 50, 51 | Vários GARCH, IC comuns, coeficientes/EP e comparação de persistência e meias-vidas em escalas diferentes. |
| 2ª parte (d) | 52, 53, 54 | Gráficos e tabela de 15 pregões, quantis, diferenças e recomendação operacional; divergência da esperança no EGARCH-t. |

## Limitações preservadas, sem mascarar resultados

- O ARIMA não passou no diagnóstico completo; nenhuma das 24 alternativas passou em todos os testes.
- O SARIMA melhora os testes Q pedidos, mas ainda apresenta ARCH e incerteza sobre diferenciação.
- A previsão recursiva usa ordens escolhidas até 2024. Os ajustes e fatores usam apenas o passado de cada origem, mas a seleção das ordens não é estritamente fora da amostra nas primeiras origens. O exercício é condicional às especificações selecionadas; não foi refeito como seleção recursiva histórica.
- As bases são revisadas, não vintages em tempo real; intervalos ignoram fontes de incerteza declaradas.
- Diagnósticos EGARCH não são aprovação irrestrita: cauda esquerda, variantes de assimetria e momentos futuros permanecem ressalvas.
- O PDF é uma apresentação. O enunciado também pede código e base na entrega; este repositório inclui um pacote dos materiais numéricos e scripts utilizados, separado do arquivo de slides.

## Alterações visuais

- Removido o rótulo dos lembretes de apresentação; o texto permanece discretamente no rodapé e foi ampliado moderadamente.
- Mantidas fontes Latin Modern, inclusive gráficos e tabelas.
- Acrescentados slides de resposta conforme necessidade; nenhum item do enunciado foi suprimido.
