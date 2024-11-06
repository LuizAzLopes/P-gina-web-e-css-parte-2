<!DOCTYPE html>

<html lang="pt-br">
    <head>
        <title>Barbearia do Luizão - Contatos</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width">
        <link rel="stylesheet" href="dependencias/reset.css">
        <link rel="stylesheet" href="dependencias/contatos.css">
        <link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <div>
                <h1><img src="imagens/logo.png" alt="Logo da Barbearia Luizão"></h1>

                <nav>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos</a></li>
                        <li><a class="select" href="contatos.html">Contatos</a></li>
                    </ul>
                </nav>
            </div>
        </header>
        
        <main>
            <form>
                <label for="nomesobrenome">Nome e sobrenome</label>
                <input type="text" id="nomesobrenome" class="input_padrao" required placeholder="Nome completo">

                <label for="email">Email</label>
                <input type="email" id="email" class="input_padrao" required placeholder="seuemail@dominio.com">

                <label for="telefone">Telefone</label>
                <input type="tel" id="telefone" class="input_padrao" required placeholder="(xx) xxxxx-xxxx">

                <label for="mensagem">Mensagem</label>
                <textarea cols="70" rows="10" id="mensagem" class="input_padrao" required placeholder="(Insira sua mensagem aqui!)"></textarea>

                <fieldset>
                    <legend>Como prefere o nosso contato?</legend>

                    <label for="radio_email"><input type="radio" name="contato" value="email" id="radio_email">Email</label>
                    <label for="radio_telefone"><input type="radio" name="contato" value="telefone" id="radio_telefone">Telefone</label>
                    <label for="radio_whatsApp"><input type="radio" name="contato" value="WhatsApp" id="radio_whatsApp" checked>WhatsApp</label>
                </fieldset>

                <fieldset>
                    <legend>Qual horário prefere ser atendido:</legend>
                    <select>
                        <option >Manhã</option>
                        <option>Tarde</option>
                        <option>Noite</option>
                    </select>
                </fieldset>

                <label class="checkbox"><input id="check" type="checkbox" checked>Gostaria de receber nossas novidades por email?</label>
                
                <input type="submit" value="Enviar formulário" class="enviar">
            </form>

            <table>
                <thead>
                    <tr>
                        <th>Dia</th>
                        <th>Horário</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Segunda</td>
                        <td>8h ~ 20h</td>
                    </tr>
                    <tr>
                        <td>Quarta</td>
                        <td>8h ~ 20h</td>
                    </tr>
                    <tr>
                        <td>Sexta</td>
                        <td>8h ~ 20h</td>
                    </tr>
                </tbody>
            </table>
        </main>

        <footer>
            <img src="imagens/logo-branco.png" alt="Logo da Barbearia do Luizão">
            <p>&copy; Copyright Barbearia Luizão - 2024</p>
        </footer>
    </body>
</html>
