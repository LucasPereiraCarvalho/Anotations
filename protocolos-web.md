Oque é um serviço web?

# Protocolos
Um acordo/padrão que segue e define regras conhecidas pelas duas partes da comunicação (cliente e servidor).

- HTTP (Hypertext Transfer Protocol) 
    - Documento que contem referencias para outros documentos. Protocolo que define regras para outros documentos.

- FTP (File Transfer Protocol) 
    - Protocolo dedicado para trasnferencia de arquivos

- SMTP (Simple Mail Trasnfer Protocol) 
    - Protocolo dedicado para transferencia de mensagens de email

- TCP (Transmission Control Protocol)
    - Error Recovery: Se um pedaço da informação não chegar na outra ponta, este erro seja indentificado e corrigido até que toda a informação seja entregue corretamente
    - Desvantagem: Deixa a transmição de dados mais devagar.

- UDP (User Datagram Protocol)
    - Cada pacote enviado é auto-suficiente e não depende de uma negociação ou conferencia entre as partes envolvidas. 
    - Diferença UDP e TCP: [HTML5 Games - UDP vs TCP](https://www.youtube.com/watch?v=ZEEBsq3eQmg&ab_channel=Yannick%28yandeu%29)

## Procoloco consegue ser montado um "em cima do outro"
HTTP - TCP - IP
- HTTP: Define como as informações web serao trocadas entre um cliente e servidor
    - TCP: Transmite as informações e garante que serão transitadas corretamente
        - IP:  Garante que as informações serão enviadas para os locais corretos na internet.