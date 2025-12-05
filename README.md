<h1 align="center">AiLexa</h1>
![Python Badge](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

Uma assistente de áudio em protuguês que automatiza algumas tarefas. O programa foi testado com Python 3.11.7 num MacBook Air, com processador Apple M2, 8 Gb de memória e macOS Sequoia 15.7.2. 

## Dica
Antes de executar o arquivo ailexa.py deve-se instalar algumas bibliotecas com o comando:<br>
pip install PyAudio SpeechRecognition gTTS wikipedia

## Utilização
Quando o script é executado ele fica monitorando o microfone e os comandos reconhecidos:<br>
-lexa<br>
-aste<br>
-ailexa<br>
-sair<br><br>
Podendo usar qualquer um dos três primeiros para a assistente ficar ativa a reconhecer comandos e o último para finalizar a aplicação.
Quando a assistente estiver ativa ela é capaz de realizar as seguintes tarefas:
1. Abrir o navegador na página do Youtube, dizendo qualquer frase que contenha a palavra youtube;
2. Abrir o navegador na página do Uol, dizendo qualquer frase que contenha a palavra uol;
3. Abrir o programa VLC para reproduzir música, dizendo qualquer frase que contenha a palavra música;
4. Reproduzir em voz um resumo sobre algum tema da Wikipedia, dizendo a frase "procure na wipidia ASSUNTO", onde ASSUNTO é o tema desejado.
5. Voltar para o modo escuta se disser a palavra dormir, ou a palavra aguardar.
