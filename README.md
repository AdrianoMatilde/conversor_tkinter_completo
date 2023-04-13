# conversor_tkinter_completo
 Conversor de temperaturas
---
Este código é um exemplo de um conversor de temperatura feito em tkinter, uma biblioteca de interface gráfica para Python.
Ele tem uma interface gráfica com?
 1.	três menus suspensos para selecionar as unidades de temperatura,
 2.	três botões de opção para escolher o tipo de conversão e,
 3.	uma entrada para o valor da temperatura a ser convertido.

Quando o usuário clica no botão "Converter", o valor da temperatura é convertido e exibido em um rótulo abaixo do botão.
O código usa uma variável do tipo StringVar() para armazenar a unidade de entrada e saída selecionada pelos usuários nos menus suspensos. Ele também usa uma variável do tipo IntVar() para armazenar a opção de conversão selecionada pelos usuários nos botões de opção.

A função converter_temperatura() é chamada quando o usuário clica no botão "Converter". Ele converte o valor da temperatura com base nas unidades selecionadas e na opção de conversão. O resultado da conversão é exibido em um rótulo abaixo do botão. O resultado é formatado usando f-strings.
A janela principal é criada usando a classe Tk() e todos os outros elementos gráficos são adicionados à janela usando os métodos grid() e pack().
As unidades de temperatura são armazenadas em um dicionário para facilitar o acesso aos símbolos das unidades.

A janela é executada com o método mainloop().

---
Espero que tenha gostado!
