## Instruções para Uso do Programa

Para executar o programa, siga as instruções abaixo para instanciar os objetos nas respectivas classes:

### 1. Classe `Filme`
Crie objetos da classe `Filme` passando os seguintes parâmetros no construtor, na ordem correta:
- `título` (String): O título do filme.
- `gênero` (String): O gênero do filme.
- `ano de lançamento` (int): O ano em que o filme foi lançado.
- `lista de atores` (List<String>): Uma lista com os nomes dos atores do filme.
- `nota` (double): A avaliação do filme.

### 2. Classe `Usuario`
Crie objetos da classe `Usuario` com os seguintes parâmetros no construtor:
- `nome` (String): O nome do usuário.
- `idade` (int): A idade do usuário.

Após instanciar o usuário, utilize o método `assistirFilme()` para registrar os filmes assistidos por ele.

### 3. Classe `Grafo`
Instancie a classe `Grafo` utilizando o construtor padrão. Depois, utilize os métodos a seguir:
- `adicionarUsuario(Usuario usuario)`: Adiciona um usuário ao grafo.
- `adicionarRelacao(Usuario usuario1, Usuario usuario2, double peso)`: Cria uma relação ponderada entre dois usuários.
- `obterIndicacao(Usuario usuario)`: Gera recomendações de filmes para o usuário especificado com base nas relações do grafo.

### 4. Impressão das Indicações
Para imprimir as indicações de filmes para um usuário, utilize o método `obterIndicacao()` e exiba os resultados.

---
### 5. Para executar este arquivo sem modificações
Para executar este arquivo sem realizar nenhuma modificação, basta rodar o algoritmo conforme o sistema operacional ou ambiente de terminal em que você está trabalhando. Certifique-se de que todas as dependências e configurações estejam devidamente ajustadas para garantir uma execução correta e eficiente do programa.

