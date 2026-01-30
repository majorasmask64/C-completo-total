# Parte 1 — A Linguagem C

A primeira parte deste livro apresenta uma discussão completa da linguagem de programação C.
O Capítulo 1 fornece uma rápida exposição da linguagem C — o programador mais experiente talvez queira passar diretamente para o Capítulo 2.
O Capítulo 2 examina os tipos de dados internos, variáveis, operadores e expressões.
O Capítulo 3 apresenta os comandos de controle do programa. O Capítulo 4 discute matrizes e strings.
O Capítulo 5 trabalha com ponteiros.
O Capítulo 6 discute funções.
O Capítulo 7 aborda estruturas, uniões e os tipos definidos pelo usuário.
O Capítulo 8 examina as E/S pelo console.
O Capítulo 9 aborda as E/S de arquivo e, finalmente, o Capítulo 10 discute o pré-processador e faz comentários. O assunto desta parte (e a maior parte do material deste livro) reflete o padrão ANSI para C. No entanto, o padrão original de C, oriundo do UNIX versão 5, também é focalizado, e as diferenças mais importantes são salientadas. O livro aborda tanto o C ANSI quanto o original como garantia de que você encontrará informações pertinentes ao seu ambiemte de programação em C.

## Uma visão Geral de C

A finalidade deste capítulo é apresentar uma visão geral da linguagem de programação C, suas origens, seus usos e sua filosofia. Este capítulo destina-se principalmente aos novatos em C.

### As Origens de C

A linguagem C foi inventada e implementada primeiramente por Dennis Ritchie em um DEC PDP-11 que utilizava o sistema operacional UNIX. C é o resultado de um processo de desenvolvimento que começou com uma linguagem mais antiga, chamada BCPL, que ainda está em uso, em sua forma original, na Europa. BCPL foi desenvolvida por Martin Richards e influenciou uma linguagem chamada B, inventada por Ken Thompson. Na década de 1970, B levou ao desenvolvimento de C.

Por muitos anos, de fato, o padrão para C foi a versão fornecida com o sistema operacional UNIX versão 5. Ele é descrito em _The C Programming Language_, de Brian Kernighan e Dennis Ritchie (Englewood Cliffs, N.J.: Prentice Hall, 1978). Com a popularidade dos microcomputadores, um grande número de implementações de C foi criado. Quase que por milagre, os códigos-fontes aceitos por essas implementações eram altamente compatíveis. (Isto é, um programa escrito com um deles podia normalmente ser compilado com sucesso usando-se um outro.) Porém, por não existir nenhum padrão, havia discrepâncias. Para remediar essa situação, o ANSI (American National Standards Institute) estabeleceu, no verão de 1983, um comitê para criar um padrão que definiria de uma vez por todas a linguagem C. No momento em que esta obra foi escrita, o comitê do padrão ANSI estava concluindo o processo formal de adoção. Todos os principais compiladores C já implementaram o padrão C ANSI. Este livro aborda totalmente o padrão ANSI e enfatiza-o. Ao mesmo tempo, ele contém informações sobre a antiga versão UNIX de C. Em outras palavras, independentemente do compilador que esteja usando, você encontrará assuntos aplicáveis aqui.

### C É uma Linguagem de Médio Nível

C é frequentemente chamada de linguagem de médio nível para computadores. Isso não significa que C seja menos poderosa, difícil de usar ou menos desenvolvida que uma linguagem de alto nível como BASIC e Pascal, tampouco implica que C seja similar à linguagem assembly e seus problemas correlatos aos usuários. C é tratada como uma linguagem de médio nível porque combina elementos de linguagens de alto nível com a funcionalidade da linguagem assembly. A Tabela 1.1 mostra como C se enquadra no espectro das linguagens de computador.

Tabela 1.1 A posição de C no mundo das linguagens.

| Nível                | Linguagem       |
|----------------------|-----------------|
| **Nível mais alto**  | Ada             |
|                      | Modula-2        |
|                      | Pascal          |
|                      | COBOL           |
|                      | FORTRAN         |
|                      | BASIC           |
| **Médio nível**      | C++             |
|                      | C               |
|                      | FORTH           |
| **Nível mais baixo** | Macro-assembler |
|                      | Assembler       |
