# CEI - Checklist de entrega

Este checklist tem como objetivo o auxílio das equipes de desenvolvimento e testes na execução de testes básicos, aumentando assim a qualidade das entregas.

> A equipe de desenvolvimento deverá garantir o funcionamento correto dos itens presentes nesse checklist.

Ao executar os testes, caso alguma falha seja encontrada e esteja relacionada a algum item deste checklist, o código do mesmo será informado no registro da falha. Este registro possibilitará a medição da qualidade da equipe de desenvolvimento.

## CEI01 - Elementos de interface

### CEI01-01 - Elementos visuais

|   Código    | Descrição                                                                                                                                                      | Testado? | Observações |
| :---------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI01-01.01 | Verificar o formato de apresentação da tela, conferindo se as cores, estilo, tipo e tamanho de fonte estão de acordo com a especificação ou padrão do sistema. |          |             |
| CEI01-01.02 | Verificar o correto posicionamento e alinhamento dos campos e objetos da tela, conferindo se estão de acordo com a especificação ou padrão do sistema.         |          |             |
| CEI01-01.03 | Testar o foco inicial ao abrir a tela, e a tab order, conferindo se estão de acordo com a especificação.                                                       |          |             |
| CEI01-01.04 | Testar o funcionamento correto de telas modais, ou seja, a tela chamadora não pode ser editada equanto a tela modal estiver aberta.                            |          |             |
| CEI01-01.05 | Verificar a correta posição e tamanho das telas do tipo pop-up, conferindo se estão de acordo com a especificação ou padrão do sistema.                        |          |             |
| CEI01-01.06 | Verificar se a indicação visual na interface que indica campos de preenchimento obrigatório (ex.: asterisco, negrito) está presente.                           |          |             |
| CEI01-01.07 | Verificar a correta posição e tamanho das telas do tipo pop-up, conferindo se estão de acordo com a especificação ou padrão do sistema.                        |          |             |
| CEI01-01.08 | Testar se os links presentes na tela não estão quebrados e estão apontando corretamente para o destino.                                                        |          |             |

### CEI01-02 - Ortografia

|   Código    | Descrição                                                                                                                                        | Testado? | Observações |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ----------- |
| CEI01-02.01 | Verificar a correta ortografia de todos os textos presentes: labels (botões, campos, informações), títulos, links, tooltiptext, mensagens etc.   |          |             |
| CEI01-02.02 | Verificar as iniciais maiúsculas ou minúsculas dos labels, menus e títulos de acordo com a especificação ou padrão do sistema.                   |          |             |
| CEI01-02.03 | Verificar o texto explicativo (tooltiptext) de todos os botões e campos, conferindo se estão de acordo com a especificação ou padrão do sistema. |          |             |

### CEI01-03 Mensagens

|   Código    | Descrição                                                                                                                                                                | Testado? | Observações |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ----------- |
| CEI01-03.01 | Verificar se todas as mensagens presentes na especificação foram implementadas. Verificar na especificação ou Plano de Testes os casos de testes relativos às mensagens. |          |             |
| CEI01-03.02 | Verificar se todas as mensagens implementadas na aplicação estão iguais às descritas na especificação.                                                                   |          |             |

### CEI01-04 Habilitação / Desabilitação 

|   Código    | Descrição                                                                                                                                              | Testado? | Observações |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ----------- |
| CEI01-04.01 | Testar a habilitação/desabilitação dos objetos da tela (botões, campos, links, ícones), conferindo se estão de acordo com a especificação.             |          |             |
| CEI01-04.02 | Testar a visibilidade/invisibilidade dos objetos da tela (botões, campos, links, ícones e imagens), conferindo se estão de acordo com a especificação. |          |             |

### CEI01-05 Tabelas

|   Código    | Descrição                                                                                                                                                                                             | Testado? | Observações |
| :---------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI01-05.01 | Verificar se o cabeçalho da tabela está conforme descrito na especificação.                                                                                                                           |          |             |
| CEI01-05.02 | Verificar se as colunas da tabela estão ordenadas conforme descrito na especificação.                                                                                                                 |          |             |
| CEI01-05.03 | Verificar se a reordenação das colunas está presente e se comporta conforme está descrito na especificação                                                                                            |          |             |
| CEI01-05.04 | Verificar se todas as células exibem valor correto conforme está descrito na especificação.                                                                                                           |          |             |
| CEI01-05.05 | Verificar marcação e desmarcação de todos os registros da tabela através da marcação de um CheckBox "Marcar/Desmarcar todos".                                                                         |          |             |
| CEI01-05.06 | Verificar o comportamento do sistema caso seja necessário selecionar algum registro antes de acionar algum comando, e nenhum registro tenha sido selecionado. Ver especificação ou padrão do sistema. |          |             |

### CEI01-06 Páginação

|   Código    | Descrição                                                                                                                                                                                                                | Testado? | Observações |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ----------- |
| CEI01-06.01 | Verificar se paginação se encontra no padrão do sistema, conferindo a especificação do sistema.                                                                                                                          |          |             |
| CEI01-06.02 | Testar o correto funcionamento da paginação: Navegar para frente e para trás, primeiro e último, página "X" e campo "Ir para". Obs.: para isto é necessário possuir mais de uma página                                   |          |             |
| CEI01-06.03 | Verificar a habilitação/desabilitação dos comandos de navegação (ex.: na última página, o comando "próximo" deverá estar desabilitado).                                                                                  |          |             |
| CEI01-06.04 | Verificar o número máximo de registros por páginas. Ver especificação ou padrão do sistema.                                                                                                                              |          |             |
| CEI01-06.05 | Verificar a mudança do número máximo de registros por página. Ver espeficiação ou padrão do sistema.                                                                                                                     |          |             |
| CEI01-06.06 | Testar o campo "Ir para", colocando um valor inválido (uma letra, por exemplo). Verificar o tratamento. Obs.: testar, também, copiando algum texto e colando (Ctrl-C/Crtl-V e Utilizando o botão direito do mouse).      |          |             |
| CEI01-06.07 | Testar o campo "Ir para", colocando um valor acima do limite de páginas encontradas. Verificar o tratamento. Obs.: testar, também, copiando algum texto e colando (Ctrl-C/Crtl-V e Utilizando o botão direito do mouse). |          |             |
| CEI01-06.08 | Verificar se os comandos da tabela(paginação, navegadores, editar, excluir ...) continuam funcionando após paginação.                                                                                                    |          |             |

## CEI02 Campos de entrada de dados

### CEI02-01 Campos em geral

|   Código    | Descrição                                                                                                                                                                                                                                                                                                                                                                                                   | Testado? | Observações |
| :---------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI02-01.01 | Verificar se os nomes do campos existentes na aplicação estão conforme o descrito na especificação.                                                                                                                                                                                                                                                                                                         |          |             |
| CEI02-01.02 | Testar se o campo não-editável realmente não permite a edição. Obs.: testar, também, copiando algum texto e colando (Ctrl-C/Crtl-V e Utilizando o botão direito do mouse).                                                                                                                                                                                                                                  |          |             |
| CEI02-01.03 | Testar o tamanho mínimo/máximo permitido pelo campo, verificando se está de acordo com a especifcação. Obs.: testar, também, copiando algum texto com tamanho menor/maior que permitido e colando (Ctrl-C/Crtl-V e Utilizando o botão direito do mouse).                                                                                                                                                    |          |             |
| CEI02-01.04 | Testar se as máscaras (CPF, CNPJ, CEP, datas etc) estão funcionando e se estão de acordo com a especificação ou padrão do sistema. Obs.: testar, também, copiando algum texto e colando (Ctrl-C/Crtl-V e Utilizando o botão direito do mouse).                                                                                                                                                              |          |             |
| CEI02-01.05 | Testar o domínio de todos os campos (ex.: alfanuméricos, numéricos, limites etc), conferindo se o comportamento e o tratamento estão de acordo com a especificação ou padrão do sistema. Obs.: Para campos que não permitem a entrada de caracteres fora do domínio, testar, também, copiando algum texto com caracteres fora do domínio e colando (Ctrl-C / Crtl-V e Utilizando o botão direito do mouse). |          |             |
| CEI02-01.06 | Verificar o preenchimento do campo com o correto valor default, conferindo se está de acordo com a especificação.                                                                                                                                                                                                                                                                                           |          |             |
| CEI02-01.07 | Testar a inclusão de espaços em branco antes e depois do texto, e o excesso deles no meio do texto, para os campos de texto do tipo TextField e TextArea. Obs.: Normalmente, para o primeiro tipo, os espaços devem ser removidos. Para o segundo tipo, não. Ver comportamento na especificação ou no padrão do sistema.                                                                                    |          |             |
| CEI02-01.08 | Testar a inclusão de espaços em branco antes e depois do texto, e o excesso deles no meio do texto, para os campos de texto do tipo TextField e TextArea. Obs.: Normalmente, para o primeiro tipo, os espaços devem ser removidos. Para o segundo tipo, não. Ver comportamento na especificação ou no padrão do sistema.                                                                                    |          |             |
| CEI02-01.09 | Testar os campos que apresentam resultado de cálculos, conferindo a corretude dos cálculos.                                                                                                                                                                                                                                                                                                                 |          |             |

### CEI02-02 Campos do tipo alfanumérico

| Código | Descrição | Testado? | Observações |
| :----: | --------- | -------- | ----------- |

### CEI02-03 Campos do tipo numérico

| Código | Descrição | Testado? | Observações |
| :----: | --------- | -------- | ----------- |

### CEI02-04 Campos do tipo e-mail

| Código | Descrição | Testado? | Observações |
| :----: | --------- | -------- | ----------- |

### CEI02-05 Campos do tipo url

| Código | Descrição | Testado? | Observações |
| :----: | --------- | -------- | ----------- |

### CEI02-06 Campos do tipo data

|   Código    | Descrição                                                                                                                                         | Testado? | Observações |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI02-06.01 | Testar datas inexistentes (ex.: 32/01/2008, 20/13/2008);                                                                                          |          |             |
| CEI02-06.02 | Testar formatos incorretos de datas (ex.: 01/01/08, 12122008). Ver formato do campo data na especificação.                                        |          |             |
| CEI02-06.03 | Testar ano bissexto (ex.: 29/02/2008);                                                                                                            |          |             |
| CEI02-06.04 | Em períodos (De - Até), testar se o sistema realiza verificação caso a data do campo "De:" seja posterior à data do campo "Até:".                 |          |             |
| CEI02-06.05 | Em períodos (De - Até), testar a mesma data nos dois campos, conforme especificação                                                               |          |             |
| CEI02-06.06 | Em períodos (De - Até), testar apenas primeira data "De:", deixando a outra em branco, e vice-versa. Ver comportamento descrito na especificação. |          |             |
| CEI02-06.07 | Mesmos testes para campos de hora e minutos.                                                                                                      |          |             |

### CEI02-07 Campos do tipo checkbox

|   Código    | Descrição                                                                         | Testado? | Observações |
| :---------: | --------------------------------------------------------------------------------- | -------- | ----------- |
| CEI02-07.01 | Verificar se o valor default é estar marcado ou não.                              |          |             |
| CEI02-07.02 | Testar a atualização das opções do Checkbox que dependem do valor de outro campo. |          |             |

### CEI02-08 Campos do tipo radio buttons

|   Código    | Descrição                                                                                                                                                                                      | Testado? | Observações |
| :---------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI02-08.01 | Verificar se os RadiosButton de um grupo são exclusivos, ou seja, ao selecionar um deles, o que estava selecionado anteriormente deixa de estar selecionado.                                   |          |             |
| CEI02-08.02 | Verificar se o valor default é estar selecionado ou não. E no caso de grupos, verificar se algum deverá estar selecionado e qual deverá estar selecionado. Ver comportamento na especificação. |          |             |
| CEI02-08.03 | Testar a atualização das opções do Radio que dependem do valor de outro campo.                                                                                                                 |          |             |

### CEI02-09 Campos do tipo textarea

|   Código    | Descrição                                                                                                      | Testado? | Observações |
| :---------: | -------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI02-09.01 | Verificar se a informações de caracteres restantes está presente. Ver comportamento descrito na especificação. |          |             |
| CEI02-09.02 | Verificar se ao redimensionar não esta atrapalhando o layout.                                                  |          |             |

### CEI02-10 Campos do tipo select

|   Código    | Descrição                                                                                                                                                 | Testado? | Observações |
| :---------: | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI02-10.01 | Verificar valor default, conferindo se está de acordo com a especificação ou padrão do sistema (ex.: vazio, traços “-----", "Selecione", ou algum valor). |          |             |
| CEI02-10.02 | Verificar se o Select está sendo populado com as opções conforme descrito na especificação.                                                               |          |             |
| CEI02-10.03 | Testar a atualização das opções do ComboBox que dependem do valor de outro campo.                                                                         |          |             |
| CEI02-10.04 | Verificar se a ordenação das opções está conforme descrito na especificação.                                                                              |          |             |
| CEI02-10.05 | Verificar se o Select aceita múltipla seleção (caso esteja descrito na especificação), e testá-la.                                                        |          |             |

### CEI02-11 Campos do tipo seleção de opções de uma lista para outra

|   Código    | Descrição                                                                                             | Testado? | Observações |
| :---------: | ----------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI02-11.01 | Testar a transferência de apenas um elemento da lista de origem para lista de destino, e vice-versa.  |          |             |
| CEI02-11.02 | Testar a transferência de multiplos elementos da lista de origem para lista de destino, e vice-versa. |          |             |
| CEI02-11.03 | Testar a transferência de todos os elementos da lista de origem para lista de destino, e vice-versa.  |          |             |
| CEI02-11.04 | Verificar se a ordenação dos dados em ambas as listas está conforme especificação.                    |          |             |

### CEI02-12 Campos do tipo input file

|   Código    | Descrição                                                                                                                                                    | Testado? | Observações |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ----------- |
| CEI02-12.01 | Verificar se o campo é editável ou se o seu preenchimento só é possível através da seleção do arquivo (normalmente comando 'Selecionar'). Ver especificação. |          |             |
| CEI02-12.02 | Verificar se o campo permite selecionar somente o tipo de **arquivo** permitido. Ver comportamento na especificação.                                         |          |             |
| CEI02-12.03 | Se o campo for editável, testar se, ao submeter o formulário com um caminho/arquivo inexistente, o sistema informa o usuário. Ver especificação.             |          |             |
| CEI02-12.04 | Testar o tamanho máximo de arquivo que pode ser selecionado. Ex.: Testar acima do limite também. Ver comportamento esperado na especificação.                |          |             |
| CEI02-12.05 | Verificar se o sistema informa ao usuário caso o arquivo esteja vazio (0 bytes). Ver comportamento esperado na especificação.                                |          |             |
| CEI02-12.06 | Selecionar um arquivo válido e antes de submeter o formulário, remover o arquivo do diretório. Ver comportamento esperado na especificação.                  |          |             |

### CEI02-13 Campos do tipo input color

| Código | Descrição | Testado? | Observações |
| :----: | --------- | -------- | ----------- |

### CEI02-14 Campos do tipo input editor de texto wysiwyg

| Código | Descrição | Testado? | Observações |
| :----: | --------- | -------- | ----------- |


### CEI02-15 Campos do tipo input editor de código fonte

| Código | Descrição | Testado? | Observações |
| :----: | --------- | -------- | ----------- |

## CEI03 - Teste função padrão e acesso a dados

### CEI03-01 Pesquisa e listagem

|   Código    | Descrição                                                                                                                                                                                                   | Testado? | Observações |
| :---------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI03-01.01 | Verificar se todos os campos do formulário de pesquisa estão prentes. Ver especificação.                                                                                                                    |          |             |
| CEI03-01.02 | Testar uma pesquisa que não retorne nenhum registro. Ver mensagem esperada na especificação.                                                                                                                |          |             |
| CEI03-01.03 | Testar uma pesquisa que retorne um único registro, verificando que está correto.                                                                                                                            |          |             |
| CEI03-01.04 | Testar uma pesquisa que retorne vários registros, verificando se estão corretos.                                                                                                                            |          |             |
| CEI03-01.05 | Testar uma pesquisa sem preencher nenhum parâmetro. Ver comportamento esperado na especificação.                                                                                                            |          |             |
| CEI03-01.06 | Testar todos os filtros permitidos na tela, testando cada um separadamente e depois alguns conjuntos.                                                                                                       |          |             |
| CEI03-01.07 | Testar a obrigatoriedade do campos e verificar se a mensagem e o tratamento estão de acordo com a especificação ou padrão do sistema. Obs.: testar, também, inserindo apenas espaços em branco e tabulação. |          |             |
| CEI03-01.08 | Verificar se os campos exibidos no resultado da pesquisa/listagem estão de acordo com a especificação.                                                                                                      |          |             |
| CEI03-01.09 | Testar o comando "Limpar", verificando se os campos estão realmente sendo limpos ou restaurando o valor default.                                                                                            |          |             |

### CEI03-02 Detalhamento

| Código | Descrição | Testado? | Observações |
| :----: | --------- | -------- | ----------- |


### CEI03-03 Inclusão

|   Código    | Descrição                                                                                                                                                                                                   | Testado? | Observações |
| :---------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI03-03.01 | Testar a inclusão de todos os registros preenchidos com tamanho máximo.                                                                                                                                     |          |             |
| CEI03-03.02 | Testar a inclusão de uma entidade que já existe cadastrada (com mesmo identificador).                                                                                                                       |          |             |
| CEI03-03.03 | Testar a obrigatoriedade do campos e verificar se a mensagem e o tratamento estão de acordo com a especificação ou padrão do sistema. Obs.: testar, também, inserindo apenas espaços em branco e tabulação. |          |             |
| CEI03-03.04 | Testar o comando "Limpar", verificando se os campos estão realmente sendo limpos ou restaurando o valor default.                                                                                            |          |             |

### CEI03-04 Alteração

|   Código    | Descrição                                                                                                                                                                                                   | Testado? | Observações |
| :---------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI03-04.01 | Verificar se os campos que devem estar desabilitados estão realmente desabilitados. Ver especificação.                                                                                                      |          |             |
| CEI03-04.02 | Testar a alteração de um registro alterando todos campos obrigatórios e opcionais.                                                                                                                          |          |             |
| CEI03-04.03 | Testar a alteração de uma entidade para uma que já existe cadastrada (com mesmo identificador).                                                                                                             |          |             |
| CEI03-04.04 | Verificar se os campos são carregados na tela de alteração com os valores já existentes para alteração.                                                                                                     |          |             |
| CEI03-04.05 | Testar a obrigatoriedade do campos e verificar se a mensagem e o tratamento estão de acordo com a especificação ou padrão do sistema. Obs.: testar, também, inserindo apenas espaços em branco e tabulação. |          |             |
| CEI03-04.06 | Testar o comando "Limpar", verificando se os campos estão realmente sendo limpos ou restaurando o valor default.                                                                                            |          |             |

### CEI03-05 Exclusão

|   Código    | Descrição                                                                                                                                          | Testado? | Observações |
| :---------: | -------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI03-05.01 | Testar a exclusão de um registro que não possui entidades dependentes.                                                                             |          |             |
| CEI03-05.02 | Testar a exclusão de um registro que possui entidades dependentes. Ver comportamento esperado na especificação.                                    |          |             |
| CEI03-05.03 | Testar a exclusão de múltiplos registros.                                                                                                          |          |             |
| CEI03-05.04 | Testar a exclusão de múltiplos registros contendo um ou mais registros que não podem ser excluídos. Verificar se o comportamento na especificação. |          |             |
| CEI03-05.05 | Verificar se existe mensagem de confirmação na exclusão de um registro, testando também o botão de cancelamento.                                   |          |             |

### CEI03-06 Concorrência

|   Código    | Descrição                                                                                                                                                                                                                                                                                                                                                               | Testado? | Observações |
| :---------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI03-06.01 | Testar exclusão de registro excluído: abrir duas instâncias do sistema e aplicar a mesma consulta em ambas. Excluir o registro em uma delas. Tentar excluir o mesmo registro na outra. Verificar se o comportamento está de acordo com o padrão definido pelo sistema. Obs.: Testar na execução do comando excluir, e na confirmação da exclusão.                       |          |             |
| CEI03-06.02 | Testar alteração de registro excluído: abrir duas instâncias do sistema e aplicar a mesma consulta em ambas. Excluir o registro em uma delas. Tentar editar o mesmo registro na outra. Verificar se o comportamento está de acordo com o padrão definido pelo sistema. Obs.: Testar na execução do comando alterar, e na confirmação da alteração.                      |          |             |
| CEI03-06.03 | Testar alguma ação que não seja permitida devido ao estado atual de uma entidade: abrir duas instâncias do sistema e aplicar a mesma consulta em ambas. Alterar o estado de uma entidade em uma delas. Tentar executar a ação não mais permitida no mesmo registro, na outra instância. Verificar se o comportamento está de acordo com o padrão definido pelo sistema. |          |             |


### CEI03-07 Relatórios

|   Código    | Descrição                                                                                                                                                             | Testado? | Observações |
| :---------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI03-07.01 | Verificar se o relatório se encontra no padrão do sistema, conferindo a especificação do sistema.                                                                     |          |             |
| CEI03-07.02 | Verificar se cabeçalho, rodapé e data/hora do relatório estão corretos.                                                                                               |          |             |
| CEI03-07.03 | Verificar se o relatório gerado apresenta todos os dados conforme especificação.                                                                                      |          |             |
| CEI03-07.04 | Verificar se os valores apresentados nas colunas das tabelas estão coerentes com os títulos correspondentes.                                                          |          |             |
| CEI03-07.05 | Verificar se a ordenação dos dados está correta, conforme especificação.                                                                                              |          |             |
| CEI03-07.06 | Verificar nos relatórios com mais de uma página se não há perda de dados de uma página para outra.                                                                    |          |             |
| CEI03-07.07 | Verificar nos relatórios com mais de uma página se o cabeçalho e/ou rodapé do relatório deve ou não ser duplicado. Ver na especificação.                              |          |             |
| CEI03-07.08 | Verificar nos relatórios com mais de uma página a correta numeração. Ver na especificação.                                                                            |          |             |
| CEI03-07.09 | Verificar se relatório exibe os campos corretamente quando os mesmos estão preenchidos com tamanho máximo,ou seja, os valores não foram cortados.                     |          |             |
| CEI03-07.10 | Testar todos os cálculos existentes no relatório (somatório, totalizador, agrupamentos, etc..).                                                                       |          |             |
| CEI03-07.11 | Testar o relatório quando não existe dados a serem exibidos.                                                                                                          |          |             |
| CEI03-07.12 | Verificar se os campos não obrigatórios de um relatório deverão aparecer em branco, ou se os labels nem deverão ser exibidos. Ver especificação ou padrão do sistema. |          |             |
| CEI03-07.13 | Verificar a correta impressão do relatório (Margens, cabeçalho, rodapé, numeração, fontes, layout em geral, etc...).                                                  |          |             |
| CEI03-07.14 | Verificar se a configuração de filtros utilizada para geração do relatório está sendo informada no relatório. Ver especificação.                                      |          |             |

### CEI03-08 Relatórios em excel

|   Código    | Descrição                                                                                         | Testado? | Observações |
| :---------: | ------------------------------------------------------------------------------------------------- | -------- | ----------- |
| CEI03-08.01 | Verificar se os campos exibidos no Excel possuem largura coerente com o campo. Ver especificação. |          |             |


## Dicas 

Template para registrar uma falha
```
Código: 
Mensagem:
Passo a passo para reproduzir:
```

### Como testar cópiar e colar
 
Copie algum texto (ctrl + c) e cole utilizando os seguintes casos
  - crtl + v;
  - shift + insert;
  - Utilizando o botão direito do mouse.
