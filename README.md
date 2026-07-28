# Estilo CSL ABNT NBR 10520:2023 e NBR 6023:2025

## Sistema autor-data sem número de página nas citações

Este repositório contém um estilo **Citation Style Language — CSL**, em português do Brasil, desenvolvido para uso no **Mendeley** e em outros processadores compatíveis com CSL 1.0.

O estilo foi elaborado com base nas seguintes normas:

* **ABNT NBR 10520:2023** — Informação e documentação — Citações em documentos — Apresentação;
* **ABNT NBR 6023:2025** — Informação e documentação — Referências — Elaboração.

A presente variante utiliza o sistema **autor-data** e foi configurada para **não exibir número de página, seção, capítulo ou outro localizador nas citações inseridas no corpo do texto**.

> A supressão do localizador ocorre somente nas citações. A paginação bibliográfica de artigos, capítulos e outros documentos continua sendo apresentada normalmente na lista de referências.

---

## Arquivo principal

```text
abnt-nbr-10520-2023-nbr-6023-2025-julio-andreo-sem-pagina.csl
```

Identificador interno do estilo:

```text
http://www.zotero.org/styles/abnt-nbr-10520-2023-nbr-6023-2025-julio-andreo-sem-pagina
```

---

## Autoria e responsabilidades

* **Autoria e responsabilidade pelo estilo:** Julio Andreo;
* **E-mail:** [julio.andreo@ufu.br](mailto:julio.andreo@ufu.br);
* **Elaboração do código CSL:** OpenAI;
* **Revisão normativa e técnica:** Julio Andreo;
* **Data de elaboração:** 28 de julho de 2026;
* **Idioma:** português do Brasil (`pt-BR`).

---

## Formato das citações

### Citação parentética

```text
(Silva, 2024)
```

### Citação narrativa

```text
Silva (2024)
```

Para produzir a forma narrativa no Mendeley:

1. escreva o nome do autor no texto;
2. insira a citação imediatamente depois;
3. utilize a opção **Suprimir autor** na citação.

Exemplo:

```text
Silva + citação com autor suprimido = Silva (2024)
```

Não deve ser digitada vírgula depois do nome do autor. A forma abaixo está incorreta:

```text
Silva, (2024)
```

O estilo não acrescenta vírgula ou espaços indevidos entre o autor digitado no texto e o ano entre parênteses.

### Citação com localizador informado

Mesmo que uma página seja preenchida no Mendeley, esta variante produzirá:

```text
Silva (2024)
```

em vez de:

```text
Silva (2024, p. 25)
```

### Dois autores

```text
(Silva; Souza, 2024)
```

### Quatro ou mais autores

```text
(Silva et al., 2024)
```

### Autor institucional

```text
(IBGE, 2022)
```

### Obras do mesmo autor e ano

```text
(Silva, 2024a, 2024b)
```

---

## Formatação da lista de referências

Entre as principais regras implementadas estão:

* ordenação alfabética pelo autor;
* sobrenomes em letras maiúsculas nas referências;
* prenomes abreviados por iniciais;
* indicação de todos os autores quando houver até três;
* indicação do primeiro autor seguido de *et al.* quando houver quatro ou mais autores;
* diferenciação de obras do mesmo autor e ano por letras `a`, `b`, `c`;
* títulos principais de livros, teses, relatórios e páginas eletrônicas em negrito;
* títulos de periódicos e documentos de eventos em negrito;
* abreviaturas dos meses em português do Brasil;
* apresentação de DOI, endereço eletrônico e data de acesso quando disponíveis;
* uso de `[S. l.]`, `[s. n.]` e `[s. d.]` para dados editoriais ausentes;
* espaçamento simples, com separação entre as referências.

Exemplo de referência institucional:

```text
IBGE. Censo Brasileiro 2022: Resultados Preliminares. Instituto Brasileiro de Geografia e Estatística (IBGE), 2022.
```

O código utiliza ponto seguido de espaço entre o título e a instituição. Portanto, não deve ocorrer a junção incorreta:

```text
Resultados Preliminares.Instituto
```

---

## Tipos documentais contemplados

O estilo possui tratamento específico para:

* livros e folhetos;
* capítulos de livros;
* verbetes de dicionários e enciclopédias;
* artigos de periódicos e revistas;
* artigos de jornais;
* trabalhos publicados em eventos;
* teses e dissertações;
* relatórios e manuscritos;
* páginas eletrônicas, blogs e publicações online;
* legislação, projetos de lei, tratados e decisões judiciais;
* patentes;
* entrevistas, discursos, músicas e documentos audiovisuais;
* mapas, bases de dados, imagens, figuras e partituras;
* comunicações pessoais;
* outros documentos processados por um modelo bibliográfico genérico.

---

## Instalação no Mendeley

1. Baixe o arquivo `.csl` deste repositório.
2. Abra o [Mendeley CSL Editor](https://csl.mendeley.com/visualEditor/).
3. Acesse o editor de código do estilo.
4. Substitua o conteúdo existente pelo conteúdo integral do arquivo `.csl`.
5. Salve o estilo com um nome próprio.
6. No Mendeley ou no Mendeley Cite, selecione o estilo salvo.
7. Atualize as citações e a bibliografia do documento.

Caso uma versão anterior continue sendo aplicada, remova o estilo antigo, reinstale o arquivo atualizado e reinicie o Mendeley Cite.

O uso de um identificador interno próprio reduz conflitos com estilos anteriormente armazenados em cache.

---

## Recomendações para preenchimento no Mendeley

### DOI

Preencha somente o identificador:

```text
10.1590/0102-311X00030519
```

Não inclua `https://doi.org/` no campo DOI.

### Edição

Preencha somente o número:

```text
2
```

Deixe o campo vazio para a primeira edição.

### Autor institucional

Cadastre a instituição como autor institucional em um único campo, evitando a separação automática em nome e sobrenome.

### Sobrenomes compostos

Registre o sobrenome completo no campo de sobrenome, por exemplo:

```text
Assaf Neto
García Márquez
Grisard Filho
```

### Data de acesso

Informe a data de acesso para documentos consultados online.

### Eventos

Quando o sistema não separar adequadamente o nome e o número do evento, registre a informação completa no campo correspondente:

```text
CONGRESSO BRASILEIRO DE URBANISMO, 5.
```

### Organizadores

O campo `editor` é apresentado como `(org.)`.

O CSL e o Mendeley nem sempre conseguem distinguir automaticamente editor, organizador e coordenador. Por isso, os registros desse tipo devem ser conferidos individualmente.

---

## Diferença desta variante

Esta versão foi criada especificamente para produzir citações sem localizador:

```text
(Silva, 2024)
```

Ela não apresenta:

```text
(Silva, 2024, p. 25)
```

A escolha desta variante deve considerar as exigências do trabalho, da instituição, do periódico ou do evento.

Quando a indicação da página ou de outro localizador for necessária, deve ser utilizada uma versão do estilo que preserve o campo `locator` nas citações.

---

## Limitações

O CSL não resolve automaticamente:

* recuo, tamanho da fonte e espaçamento de citações diretas longas;
* distinção entre citação direta e indireta;
* inserção automática de `apud`;
* expressões como “grifo nosso” e “tradução nossa”;
* escolha automática entre chamada narrativa e parentética;
* correção de dados bibliográficos ausentes ou cadastrados em campos inadequados;
* todas as particularidades dos documentos jurídicos, cartográficos, audiovisuais e normativos previstos pela ABNT;
* diferenças de interpretação ou exigências editoriais específicas de universidades, revistas e eventos.

A qualidade da referência final depende também do preenchimento correto dos metadados no Mendeley.

---

## Verificações realizadas

O arquivo foi submetido às seguintes verificações:

* análise de XML bem-formado;
* carregamento por processador CSL;
* teste de citações parentéticas;
* teste de citações com autor suprimido;
* teste com localizador informado, confirmando sua omissão;
* teste de referências de livros, artigos, capítulos, eventos, dissertações, legislação e páginas eletrônicas;
* verificação de ponto e espaço entre título e instituição;
* verificação da ausência de vírgula indevida em `Autor (ano)`.

Recomenda-se testar o estilo com registros reais da biblioteca antes de sua adoção definitiva, especialmente em referências jurídicas, institucionais, cartográficas e de eventos.

---

## Referências técnicas

* ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 10520:2023: informação e documentação — citações em documentos — apresentação**. Rio de Janeiro: ABNT, 2023.
* ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 6023:2025: informação e documentação — referências — elaboração**. Rio de Janeiro: ABNT, 2025.
* [Citation Style Language](https://citationstyles.org/).
* [Mendeley CSL Editor](https://csl.mendeley.com/).
* [CSL Specification](https://docs.citationstyles.org/).
* [Estilo ABNT UFRGS com iniciais](http://www.zotero.org/styles/associacao-brasileira-de-normas-tecnicas-ufrgs-initials).
* [Estilo Universidade Federal de Uberlândia](https://csl.mendeley.com/styles/560229411/universidade-federal-uberlandia).


---

## Aviso

Este é um estilo independente, desenvolvido com base nas normas indicadas.

O arquivo não constitui publicação oficial da Associação Brasileira de Normas Técnicas, da Universidade Federal de Uberlândia, do Mendeley, do Zotero ou da OpenAI.

A conferência final das citações e referências permanece sob responsabilidade do autor do trabalho acadêmico.

---

## Instalação

No Mendeley Cite, no Word, em Citation Settings > Change citation style > Add a custom style , e use um dos dois links abaixo:

Para Citações com página Autor (Data, Página), use o link:

https://raw.githubusercontent.com/julioandreo/Mendeley_ABNT/main/abnt-nbr-10520-2023-nbr-6023-2025-julio-andreo.csl

Para Citações sem página Autor (Data), use o link:

https://raw.githubusercontent.com/julioandreo/Mendeley_ABNT/main/abnt-nbr-10520-2023-nbr-6023-2025-julio-andreo-sem-pagina.csl
