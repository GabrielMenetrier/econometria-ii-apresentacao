# Econometria II — apresentação revisada

[**Abrir a apresentação em PDF**](Apresentacao_Econometria_II.pdf)

54 slides: 16 perguntas, seguidas pelas respostas com gráficos, tabelas e lembretes discretos no rodapé. Fontes Latin Modern, da família tradicional do LaTeX.

## O que foi corrigido

- Inclusão de seasonal subseries plots de HOUSTNSA e HOUST: 12 painéis por série, com observações de cada mês ao longo dos anos e sua média.
- Estatísticas descritivas das duas séries em nível e primeira diferença do log.
- FAC/FACP de todas as transformações pedidas, com 48 defasagens e bandas de referência.
- Comparação completa de 12 ARIMA, incluindo coeficientes, erros-padrão, estatísticas t, variância e AIC/BIC; a tabela continua em três slides.
- Estatísticas Q e ARCH, caminho de reidentificação, identificação SARIMA e diagnósticos dos candidatos.
- Equações, estimação, seleção e etapas de diagnóstico EGARCH/GARCH; tabela dos 15 pregões previstos.
- Remoção do rótulo dos lembretes de apresentação e ampliação moderada do texto.

## Arquivos

- [PDF](Apresentacao_Econometria_II.pdf): versão atual da apresentação.
- [LaTeX](apresentacao.tex): fonte autocontido, com gráficos vetoriais e tabelas.
- [Roteiro](roteiro.json): lembretes por slide.
- [Auditoria por item](AUDITORIA.md): mapa das questões, slides e ressalvas metodológicas.
- [Códigos, bases e resultados](Materiais_Econometria.zip): cópia dos dados utilizados, scripts analíticos e resultados numéricos para conferência.

## Compilar o PDF

```sh
tectonic apresentacao.tex
```

O resultado é `apresentacao.pdf`. O fonte contém os dados dos gráficos e não depende de imagens externas. A primeira compilação pode baixar pacotes LaTeX.

## Como apresentar

Os slides de pergunta servem como transições rápidas. Nas tabelas continuadas e de apoio, destacar o resultado principal em vez de ler cada linha. A inclusão do material necessário aumentou o número de slides; o tempo depende do ensaio e da seleção dos detalhes a comentar.

## Limitações importantes

O ARIMA permanece um benchmark com falhas residuais; o SARIMA ainda apresenta ARCH. A avaliação recursiva é condicional às ordens escolhidas com dados até 2024 e não representa seleção histórica estritamente fora da amostra nas primeiras origens. Os intervalos e o EGARCH-t têm limitações explicitadas na apresentação e na auditoria. Incluir resultados adicionais não elimina essas limitações.

Fontes: FRED (HOUSTNSA e HOUST) e Yahoo Finance (^GSPC). Material acadêmico de apoio à apresentação.
