# AluraBooks

AluraBooks é um projeto de catálogo de livros desenvolvido em **JavaScript, HTML e CSS**, criado como parte dos estudos na plataforma **Alura**. O projeto consome dados de uma API externa e permite funcionalidades como:

- Filtrar livros por categoria (Front-end, Back-end, Dados)
- Filtrar livros disponíveis
- Ordenar livros por preço
- Aplicar desconto automático nos livros
- Visualizar o valor total dos livros disponíveis

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API para consumir dados externos
- Métodos JavaScript: `forEach`, `map`, `filter`, `reduce`, `sort`

  ## Funcionalidades

1. **Exibir livros na tela**  
   Todos os livros carregados da API são exibidos com título, autor, preço, imagem e categoria.

2. **Aplicar desconto**  
   Um desconto fixo de 30% é aplicado aos livros automaticamente usando `map`.

3. **Filtrar livros**  
   - Por categoria (`front-end`, `back-end`, `dados`)  
   - Apenas livros disponíveis (`quantidade > 0`)

4. **Ordenar livros por preço**  
   Os livros podem ser ordenados do menor para o maior preço.

5. **Calcular valor total de livros disponíveis**  
   Exibe o valor total de todos os livros disponíveis usando `reduce`.

## Veja o vídeo da interface

[Veja o vídeo da interface](demo.mp4)

## Como executar

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/AluraBooks.git
