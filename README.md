# Primeiro exercicio da semana 2 parte 1
https://github.com/Italo-C-TI/SQS-Desafio-semana-2-sender
# Primeiro exercicio da semana 2 parte 2
https://github.com/Italo-C-TI/SQS-Desafio-semana-2-consomer
# Segundo exercicio da semana 2
Compare e descreva as diferenças e o objetivo entre a Amazon SQS e a Amazon SNS:

    O Amazon SQS e o Amazon SNS são serviços de filas e de tópicos
    altamente escaláveis, O Amazon SNS permite que aplicativos 
    enviem mensagens críticas em termos de tempo para vários assinantes 
    através de um mecanismo de “push”, eliminando a necessidade de verificar 
    periodicamente ou “pesquisar” por atualizações. O Amazon SQS é um serviço 
    de fila de mensagens usado por aplicativos distribuídos para trocar mensagens 
    através de um modelo de sondagem e pode ser usado para desacoplar 
    componentes de envio e recebimento. Dito isso o SBS é um bom sistemas 
    de compartilhamento de mensagens para os usuarios inscritos no seu serviço 
    enquanto o SQS é melhor utilizado no compartilhamento de mensagens entre sistemas
    sendo simples de usar e não exige a configuração de agentes de mensagens.
