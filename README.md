# Funcionalidades Principais

## Criptografia de Texto
- O usuário pode inserir um texto e criptografá-lo usando uma chave secreta.
- O texto criptografado é codificado em Base64.

## Descriptografia de Texto
- O usuário pode inserir um texto criptografado e descriptografá-lo usando a mesma chave secreta.
- O texto descriptografado é decodificado a partir de Base64.

## Interface Gráfica Amigável
- A interface é dividida em áreas para inserção de texto, chave secreta e botões para executar as operações.
- Design simples e intuitivo, com cores temáticas.

## Segurança Básica
- A chave secreta é fixa (`1234`), mas pode ser facilmente modificada no código para uso personalizado.
- Mensagens de erro são exibidas caso a chave esteja incorreta ou ausente.

## Botão de Reset
- Permite limpar os campos de texto e chave para uma nova operação.

# Como Funciona?
1. O texto inserido pelo usuário é codificado ou decodificado usando a biblioteca `base64` do Python.
2. A chave secreta é verificada antes de realizar qualquer operação.
3. O resultado da criptografia ou descriptografia é exibido em uma nova janela.

# Tecnologias Utilizadas
- **Python**: Linguagem de programação principal.
- **Tkinter**: Biblioteca para criação da interface gráfica.
- **Base64**: Algoritmo para codificação e decodificação de dados.
