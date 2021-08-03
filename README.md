# UIPATH TEMPLATE

1. Preencher Excel Config (dentro da pasta Data) com vars locais, Assets, Credential e Queues. O robot ira popular a informação toda para dentro de um dicionário.

2. Obrigatorio Asset de Maquina definido como "empty". Este asset é usado para a possibilidade de existir mais que uma maquina a correr o processo de forma autonoma. A primeira maquina a correr o processo, altera o valor do asset e assim as outras percebem que são maquinas aux. No fim a maquina principal volta a por o asset a "empty"

3. Para carregar uma Queue é pedida uma datatable de input.

4. No final da execução é enviado um e-mail com o resumo da execução (tempo decorrido, nr de transações, nr de sucesso, nr, insucessos, etc) com a possibilidade de anexarmos 2 ficheiros.

