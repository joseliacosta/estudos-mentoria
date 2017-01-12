##Article

Quando começamos a marcar documentos na web, muito herdamos do ambiente gráfico.
Partindo disso podemos definir um artigo como um escopo que trata sobre algum assunto ou finalidade.
A tag `<article>` surgiu a partir da especificação do `HTML5`. Seu principal objetivo é fornecer valor semântico ao agrupar informações de mesma finalidade.
Em um exemplo pratico, vamos considerar um post com textão na linha do tempo do _Facebook_. Podemos pensar no conteúdo dentro da tag `<article>`, já que um post pode (ou não) ser um texto corrido sobre um ou mais assuntos. Mas em geral é sobre um assunto qualquer tratado como texto. Logo, pensando na linguagem de marcação, é mais rico fornecer ao _browser_ essa informação por meio da tag correta :)

A tag `article` é muito flexivel, havendo diversas aplicações dentro do documento. Ela pode ser filha e irmã de qualquer elemento do tipo  (https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#flow_content" flow-content")mas, de acordo com a MDN e a W3C há uma ressalva: *NÃo* use a tag `article` dentro de uma tag `address`.