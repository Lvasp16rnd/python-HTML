# Plano Inicial

O Chatbot Otis foi pensado funcionar inicialmente com uso da lógica semelhante a biblioteca Chatterbot do Python, ferramenta bastante utilizada pra a
criação de Bots de alto nivél de usabilidade, por fatores de curto tempo para desenvolvimento e não termos o conhecimento adequado para construirmos 
algo robusto e dentro do prazo optamos por somente utilizarmos a costrução inícial do banco de dados.

Organizamos os dados entre perguntas e respostas que faziam sentido no MySQL e importamos via JSON para o Firebase (ferramenta da google para serviços via cloud)
o que futuramente só nos gerou problemas...

# Problemas

Para utilizarmos o realtime database do firebase é necessário alguns conhecimentos...

1° Conhecimento mínimo de desenvolvimento Web (HTML e CSS)
2° Conhecimento da ferramenta firebase
3° Um bom nível de conhecimento de JavaScript
4° Uso de um Framework JS (ex: Node.Js ou React)
5° Uso de um bundler de módulo (ex: Webpack ou Rollup)

Em resumo, só tinhamos o conhecimento dos dois primeiros itens, o que nos impediu fazer algum progresso com a ferramenta e o responsável pelo back-end (Eu)
teve que correr atrás do JavaScript enquanto o site estava sendo feito pelo o membro Pedro; Passou se tempos e o conhecimento não era atingido para continuarmos
o projeto então veio a solução.

# Solução

Após pensar bastante em equipe foi resolvido passarmos o projeto para um framework do Python para desenvolvimento Web, o Django, que em suas vantagens são:

1° Aplicabilidade em conjunto do Python (linguagem que dominamos)
2° Organização lógica e simplificada
3° Escopagem de projeto de alto nível
4° Uso de ferramentas Web de forma simples (HTML, CSS e JS)
5° Debug em tempo real em conjunto com o host

Passamos toda as páginas do Otis para o Framework com os devidos ajustes e fomos para a ultima etapa

# Implementar o Chat

Nesse ultimo passo já sabiamos de duas coisas, não sabemos javascript o suficiente e não tinha como aplicar um código py no HTML, logo tinhamos que recorrer
a uma solução simples de aplicar e fácil, foi aí que descobrimos o DialogFlow da Google que é básicamente um serviço de cloud para criação e aplicação de bots,
em outras palavras reconstruimos o nosso chat usando o banco já existente (aquele do Chatterbot) e aplicamos no chat.

Problema resolvido
