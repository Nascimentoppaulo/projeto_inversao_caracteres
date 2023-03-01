# projeto_inversao_caracteres

**DESCRIÇÃO**

Este programa inverte os caracteres de uma string fornecida pelo usuário. Ele lê a string de entrada e, em seguida, cria uma nova string com os caracteres invertidos. O programa utiliza um laço for para percorrer a string original e adicionar cada caractere à nova string em ordem inversa. Por fim, o programa exibe a nova string na tela.

**USO**

Para usar este programa, basta executá-lo em qualquer ambiente Python compatível, como um console interativo ou um arquivo Python. Ao executar o programa, ele solicitará ao usuário uma string de entrada. Depois que a string for fornecida, o programa exibirá a nova string com os caracteres invertidos.

**Exemplo**

Um exemplo de uso do programa é:

\# solicitar ao usuário uma string de entrada
entrada = input('Digite uma string para inverter: ')

\# criar uma nova string com os caracteres invertidos
inversa = ''
for i in range(len(entrada) - 1, -1, -1):
    inversa += entrada[i]

\# exibir a nova string na tela
print(f'A string invertida é: {inversa}')
Se o usuário fornecer a string "hello", o programa exibirá a nova string "olleh".

**DOCUMENTAÇÃO**

O código está documentado com comentários que explicam a lógica, as variáveis e o fluxo de controle. Os comentários seguem as melhores práticas de documentação de código, incluindo uma descrição geral do código, descrições de variáveis e funções, e explicações de fluxo de controle.
 
