# Econometria II — apresentação

[**Abrir apresentação em PDF (32 slides)**](Apresentacao_Econometria_II.pdf)

Material de apoio para apresentação do trabalho de Econometria II sobre previsão da construção residencial americana com ARIMA/SARIMA e volatilidade do S&P 500 com GARCH/EGARCH.

Os slides estão organizados em 16 pares de pergunta e resposta. Cada pergunta tem um resumo; cada resposta inclui uma breve sugestão de fala no rodapé. A tipografia utiliza Latin Modern, da família tradicional do LaTeX.

## Arquivos

- `Apresentacao_Econometria_II.pdf`: apresentação final.
- `apresentacao.tex`: fonte LaTeX completo, com gráficos vetoriais e tabelas.
- `roteiro.json`: resumos das perguntas e sugestões de fala.

## Compilar

Com Tectonic instalado, execute:

```sh
tectonic apresentacao.tex
```

O resultado será `apresentacao.pdf`. O fonte contém os dados utilizados nos gráficos e não depende de imagens externas. A primeira compilação pode precisar de acesso à internet para baixar pacotes LaTeX.

## Escopo

Esta é uma apresentação acadêmica resumida, destinada à discussão em grupo. As ressalvas metodológicas e limitações dos modelos constam dos slides e do roteiro. O repositório contém o material de apresentação; não inclui o pipeline completo de estimação.

