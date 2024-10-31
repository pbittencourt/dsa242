# MBA Data Science & Analytics — Turma 242

Repositório contendo os estudos de Pedro P. Bittencourt durante o
[MBA Data Science e Analytics](https://mbauspesalq.com/cursos/mba-em-data-science-e-analytics),
turma 242 (outubro 2024), oferecido pela **USP/Esalq**.

## Estrutura geral

Cada diretório, nomeado no padrão `modulo-NN`, corresponde a um módulo do
curso. Neles, é possível encontrar os arquivos fornecidos pelos professores
para o acompanhamento das aulas. Nesse sentido, não há uma estrutura comum,
pois depende da abordagem de cada professor.

O diretório `notes`, entretanto, corresponde a meu "caderno de anotações", e
segue uma estrutura similar ao apresentado:

```
.
├── graphics
│   ├── *.pdf
│   ├── *.pdf_tex
│   └── *.svg
├── modulo-01
│   ├── aula_01.tex
│   ├── aula_02.tex
│   ├── aula_03.tex
│   ├── aula_NN.tex
│   └── exercicios.tex
├── modulo-02
│   ├── notes.ipynb
│   └── notes.md
├── modulo-NN
│   ├── aula_01.tex
│   ├── aula_02.tex
│   ├── aula_03.tex
│   ├── aula_NN.tex
│   ├── exercicios.tex
│   ├── notes.ipynb
│   └── notes.md
├── notes.pdf
├── notes.tex
├── preamble.tex
├── references.bib
├── symbols.tex
└── tree.md
```

Por conta dos estilos diferentes das aulas, as anotações são redigidas em
diferentes formatos: temas mais técnicos e concentuais em Latex, conteúdos mais
focados em código em markdown e jupyter notebook. Dessa forma, no diretório de
cada módulo poderemos ter misturas desses arquivos. Quando fornecido pelo
professor, teremos também um documento `exercicios.tex`, com atividades
complementares, resolvidas e extensivamente comentadas.

O diretório `graphics` contém todas as imagens de apoio que fizemos ao longo do
curso. Utilizamos, para isso, o [Inkscape](https://www.inkscape.org), um
excelente software open-source para construção de imagens vetoriais. De modo a
embutir os desenhos em arquivos Latex, temos três documentos para cada imagem:
o arquivo `*.svg`, correspondente à imagem, em si; um arquivo `*.pdf`, que
corresponde à exportação dessa imagem em documento de texto; e, por fim, um
arquivo `*.pdf_tex`, uma versão do documento na qual os textos escritos em
notação Latex são removidos, de forma a serem renderizados no próprio arquivo
Latex.

## Conteúdo programático

* Módulo 01: Fundamentos de estatística — Prof. Wilson Tarantin Junior
* Módulo 02: Introdução à programação com python — Prof. Wilson Tarantin Junior
* Módulo 03: Data Wrangling — Prof. Wilson Tarantin Junior

--

Atualizado em 2024-10-31 09:00 por Pedro P. Bittencourt
