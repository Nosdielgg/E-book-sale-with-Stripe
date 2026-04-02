📚 Venda de E-book com Stripe + Envio Automático por Email

Este projeto é uma aplicação web desenvolvida com Flask que permite vender um e-book utilizando o Stripe Checkout e enviar automaticamente o arquivo para o cliente por e-mail após a confirmação do pagamento.

🚀 Funcionalidades
💳 Pagamento online com Stripe
📩 Envio automático do e-book por e-mail
🔗 Link de download via Google Drive
⚡ Webhook para confirmação de pagamento
🌐 Interface simples de compra

O funcionamento é assim: o usuário acessa a página, clica no botão de compra e é levado para a página de pagamento do Stripe. Quando o pagamento é aprovado, ele volta para uma página de sucesso. Ao mesmo tempo, o sistema recebe uma confirmação (webhook) e pega o e-mail da pessoa que comprou. Em seguida, envia automaticamente uma mensagem com o link para baixar o e-book, que está hospedado no Google Drive.

O projeto usa algumas ferramentas importantes: Flask para criar o site, Stripe para processar o pagamento e o Gmail (SMTP) para enviar o e-mail. Também tem uma estrutura simples com arquivos organizados, incluindo o código principal, uma página de confirmação e um arquivo responsável pelo envio do e-mail.

Para rodar o projeto, você precisa configurar algumas informações em um arquivo chamado .env, como as chaves do Stripe e os dados do seu e-mail. Depois disso, é só instalar as dependências e executar o sistema.

Esse tipo de projeto é ótimo para quem quer vender produtos digitais, como e-books ou cursos, de forma automática. No futuro, dá pra melhorar adicionando mais produtos, criando uma área para usuários ou deixando o visual mais bonito.


