# CRUD TELEGRAM EM MYSQL
🤤ESSE É UM BOT DO TELEGRAM DE CRUD EM MYSQL!

<img src="./IMAGENS/FOTO_1.png" align="center" width="400"> <br>
<img src="./IMAGENS/FOTO_2.png" align="center" width="400"> <br>

## DESCRIÇÃO:
Este bot do Telegram oferece uma variedade de recursos para gerenciar uma lista de usuários de forma eficiente e conveniente. Aqui estão os principais recursos:

1. **Adicionar Usuário**: Os usuários podem adicionar novos usuários à lista fornecendo seus nomes e idades. O bot guia por meio de uma série de mensagens interativas, solicitando o nome e a idade do novo usuário a ser adicionado.

2. **Listar Usuários**: O bot permite que as pessoas visualizem todos os usuários cadastrados na lista. Ao selecionar essa opção no menu, ele exibe uma lista detalhada de todos os usuários, incluindo seus nomes e idades.

3. **Atualizar Usuário**: Os usuários têm a capacidade de atualizar as informações de um usuário existente na lista. O bot solicita o nome do usuário a ser atualizado, seguido pelo novo nome e idade a serem atualizados. Isso permite que as pessoas mantenham a lista de usuários atualizada com as informações mais recentes.

4. **Excluir Usuário**: O bot permite que as pessoas excluam um usuário específico da lista. Ao selecionar essa opção no menu e fornecer o nome do usuário a ser excluído, o bot remove o usuário da lista, garantindo que apenas usuários válidos sejam mantidos na lista.

5. **Interface Amigável**: O bot oferece uma interface de usuário amigável, apresentando um menu inicial com botões inline que facilitam a navegação e a interação. Os usuários podem acessar facilmente as diferentes opções do bot e seguir as instruções fornecidas para realizar as operações desejadas.

6. **Feedback de Ações**: O bot fornece feedback claro e informativo após a conclusão de cada ação. Os usuários recebem mensagens de confirmação ou feedback de erro, garantindo uma experiência de usuário suave e sem problemas.

7. **Operações CRUD**: Este bot segue o paradigma CRUD (Create, Read, Update, Delete), permitindo que as pessoas realizem todas as operações básicas de manipulação de dados em uma lista de usuários diretamente do Telegram.

## EXECUTANDO O PROJETO:
1. **Configuração do Banco de Dados:**
   - Antes de executar o bot, é necessário importar o arquivo `./CODIGO/DATABASE.sql`.

2. **Colocar suas Credenciais:**
   - Certifique-se de substituir `seu_token`, `localhost`, `seu_usuario`, e `sua_senha` pelos valores corretos no arquivo `./CODIGO/.env`. O arquivo `.env` deve conter as seguintes variáveis de ambiente:

     ```env
     # Token do bot do Telegram
     TELEGRAM_TOKEN=seu_token

     # Configurações do banco de dados MySQL
     DB_HOST=localhost
     DB_USER=seu_usuario
     DB_PASSWORD=sua_senha
     DB_NAME=cadastro
     ```

3. **Instalando as dependências:**
   - Antes de executar o bot, certifique-se de instalar todas as dependências necessárias. No terminal, execute o seguinte comando para instalar as dependências listadas no arquivo `requirements.txt` em `CODIGO`:
   ```bash
   pip install -r requirements.txt
   ```

4. **Inicie o Bot:**
   - Execute o bot do Telegram em Python iniciando-o com o seguinte comando em `CODIGO`:
   ```bash
   python CODIGO.py
   ```

   - Inicie o bot enviando o comando `/start`. Receba uma mensagem de boas-vindas e clique no botão inline.

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens e tecnologias relacionadas, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos alguns subsidios:
* [VEJA A DOCUMENTAÇÃO](https://python-telegram-bot.org/)
* [CURSO DE PYTHON](https://github.com/VILHALVA/CURSO-DE-PYTHON)
* [CURSO DE MYSQL](https://github.com/VILHALVA/CURSO-DE-MYSQL)
* [CURSO SUGERIDO](https://github.com/VILHALVA/CURSO-DE-TELEBOT)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)


