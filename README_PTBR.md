# Portuguese README - Sorteio Bot

Este bot implementa um bot Discord para realizar sorteios interativos. O bot permite que os usuários participem de um sorteio clicando em um botão e sorteará um vencedor quando o tempo do sorteio terminar.

## Descrição
Este bot Discord permite criar sorteios para sua comunidade, com um prêmio definido. Os usuários podem entrar no sorteio clicando em um botão, e o bot sorteará um vencedor quando o tempo do sorteio terminar.

## Características Principais

1. **Criação de Sorteios**: Os administradores podem iniciar sorteios especificando o prêmio, o tempo do sorteio em minutos, uma URL de imagem do prêmio e o preço do jogo (opcional).

2. **Participação no Sorteio**: Os usuários podem participar do sorteio clicando no botão "Entrar no Sorteio" enquanto o sorteio estiver ativo.

3. **Sorteio Automático**: Quando o tempo do sorteio expirar, o bot escolherá aleatoriamente um vencedor entre os participantes e o anunciará no canal.

4. **Atualização do Tempo Restante**: O bot atualiza regularmente o tempo restante no sorteio, exibindo-o no título da mensagem do sorteio.

## Como Usar

1. Quando o bot estiver online, um administrador pode iniciar um sorteio usando o comando `!iniciar` seguido de quatro argumentos:
   - Prêmio: Descrição do prêmio.
   - Tempo em Minutos: A duração do sorteio em minutos.
   - URL da Imagem: A URL da imagem que representa o prêmio.
   - Preço do Jogo (opcional): O preço do jogo associado ao prêmio.

   Por exemplo: `!iniciar Xbox Series X 60 https://example.com/xbox.jpg 499`

2. Uma mensagem do sorteio será criada com um botão "Entrar no Sorteio". Os usuários podem participar clicando nesse botão enquanto o sorteio estiver ativo.

3. O bot atualizará regularmente o tempo restante no sorteio. Quando o tempo acabar, ele escolherá um vencedor aleatório entre os participantes e o anunciará no canal.

## Personalização
Você pode personalizar o código ajustando os comandos, mensagens e aparência do bot para atender às necessidades da sua comunidade.

## Nota Importante
Este bot utiliza a biblioteca Discord.py e requer uma configuração adequada, incluindo o token do bot, para funcionar no seu servidor do Discord. Certifique-se de substituir `'TOKEN'` pelo token do seu bot na última linha do código.

---

Se você tiver alguma dúvida específica sobre como executar ou personalizar o bot, sinta-se à vontade para perguntar!
