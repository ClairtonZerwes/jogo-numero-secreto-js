Desenvolvido com HTML, CSS e JavaScript, jogo para adivinhar o número secreto em um intervalor pré-selecionado precisando só alterar as variáveis minNumeroSecreto e maxNumeroSecreto o jogo começa com no máximo 3 tentativas que também pode ser alterado o valor na variável maximoTentativas no arquivo app.js. Outra funcionalidade e adicionar o uso de voz de IA para isso é preciso alterar o arquivo index.html,   <!-- EXEMPLO "<script src="https://code.responsivevoice.org/responsivevoice.js?key=CopieSuaChaveKeyAqui"></script>"
        O jogo executa normal sem voz de IA para alterar você precisa criar uma conta no site "https://code.responsivevoice.org/responsivevoice.js"
        e criar uma chave API e copiar o link gerado com a chave de autorização trocando na linha abaixo, fica como o exemplo acima.
    -->
    <script src="https://code.responsivevoice.org/responsivevoice.js"></script>. E no arquivo app.js descomentar está linha "// responsiveVoice.speak(texto, 'Brazilian Portuguese Female', {1:2}); // descomentar esta linha para usar a voz de IA. ".
