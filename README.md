# Econometria II — apresentação revisada

[Abrir o PDF](Apresentacao_Econometria_II.pdf) · [Fonte LaTeX](apresentacao.tex)

54 slides: 16 perguntas, seguidas das respostas com gráficos, tabelas e lembretes no rodapé. Fontes Latin Modern. Material de apoio para o grupo.

## Correções de setembro

- Slide 3: N, média, desvio-padrão, mínimo e máximo.
- Slides 5–7: identificação explícita de HOUSTNSA (h) e HOUST (s).
- Slides 9–10: seasonal subseries plots em faixa única; slide 11: perfil sazonal médio relativo.
- Slide 15: seis ordens ARIMA sem drift; observação sobre os testes com drift, que pioraram AIC/BIC. Slide 16: conferência da variância e dos critérios.
- Slide 17: círculo com apenas raízes inversas ARMA; a raiz de integração permanece no modelo, mas não no desenho.
- Slide 24: explicação do operador B.
- Slides 31–39: origem corrigida para 2025M1, reestimação expansível e previsões de um passo. Interpretando origem como último mês observado, são 11 alvos (fevereiro–dezembro). Para prever também janeiro, a primeira origem seria 2024M12.
- Slides 35–36: fórmula e exemplo numérico da ressazonalização com fatores históricos, sem usar fatores futuros.

No alvo bruto comum, RMSE de 9,06 para o ARIMA recomposto e 6,56 para o SARIMA direto. O ARIMA mantém falhas no diagnóstico; o SARIMA ainda apresenta efeitos ARCH. Os intervalos são condicionais, e os dados revisados não reproduzem perfeitamente a informação disponível em tempo real.

## Editar e compilar

O repositório contém apenas PDF, fonte LaTeX autocontido e este README. Os gráficos são vetoriais, com coordenadas no próprio fonte; não dependem de imagens externas ou bases de dados.

    tectonic apresentacao.tex

A saída é apresentacao.pdf. A primeira compilação pode baixar pacotes LaTeX. Os slides de pergunta podem servir como transições rápidas; ensaiar é necessário para ajustar a apresentação ao tempo disponível.

Fontes dos dados: FRED (HOUSTNSA e HOUST) e Yahoo Finance (^GSPC).