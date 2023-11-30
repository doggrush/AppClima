# Clima - Software de Clima Mobile

### Resumo
O aplicativo de previsão do tempo proposto visa fornecer aos usuários informações sobre as condições climáticas em suas áreas de interesse.
Essa ferramenta é projetada para ser fácil de usar e acessível a todos, ajudando as pessoas a se prepararem para as mudanças climáticas e tomarem decisões informadas em seu dia a dia.

### Problema
O acesso a informações meteorológicas é fundamental para planejar atividades diárias, eventos ao ar livre, viagens e até mesmo a segurança pessoal.
Atualmente, muitos aplicativos de previsão do tempo existentes podem ser complexos ou inacessíveis a certas comunidades. Este projeto visa resolver esses problemas, fornecendo uma solução confiável, precisa, acessível e simples.

### Solução
A solução prevista para o usuário é um aplicativo mobile que irá requisitar a cidade que o usuário deseja verificar as informações de clima, com o input do usuário, o aplicativo requisita da API OpenWeather as informações da cidade, depois o aplicativo exibe as informações (temperatura atual, uma imagem representando o clima, a data atual, a sensação térmica, a umidade e a visibilidade), após exibi-las, o usuário pode voltar para a tela inicial e requisitar outra cidade.

### Objetivo do Software
O objetivo principal deste aplicativo de previsão do tempo é:
Fornecer previsões meteorológicas para locais específicos.
Apresentar informações de forma clara e intuitiva para facilitar o entendimento.
Ser acessível e fácil de usar para pessoas de todas as idades e níveis de habilidade.
Manter os dados meteorológicos constantemente atualizados por meio de fontes confiáveis.

### Impactos esperados
Facilitação do planejamento diário dos usuários.
Melhora na segurança pessoal e nas atividades ao ar livre.
Redução de impactos negativos de eventos climáticos imprevistos

### Telas presentes no software
1. Tela Inicial - É nesta tela onde o usuário ira digitar a cidade desejada.
2. Tela de Resultados - É nesta tela onde os resultados da API são exibidos.

### Requisitos Funcionais
O sistema permite que o usuário pesquise o clima de qualquer cidade do mundo. \
O sistema reconhece quando uma cidade não existe e avisa o usuário.

### Requisitos Não Funcionais
Versão mínima API Android 29/Android 10. \
Desenvolvido no Android Studio. \
Linguagem utilizada: Java. \
Uso da API [OpenWeather](https://openweathermap.org/). \
O software tem um tempo de resposta que não deve exceder 5000ms. 
