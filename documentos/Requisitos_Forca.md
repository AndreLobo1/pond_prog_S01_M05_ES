# Requisitos Funcionais - Jogo da Forca Online  

| RFXX  | Título                                     | Regra de Negócio |
|-------|--------------------------------------------|------------------|
| RF01  | Cadastro de Usuário                        | O sistema deve permitir que novos usuários realizem o cadastro, inserindo suas informações pessoais na tela "Entrar". Esses dados serão utilizados para exibição no ranking geral e para identificação pelos adversários. |
| RF02  | Login de Usuário                           | O usuário já cadastrado deve ser capaz de acessar sua conta na tela de "Entrar" ao fornecer suas credenciais, evitando a necessidade de um novo cadastro e facilitando o acesso ao jogo. |
| RF03  | Armazenamento de Informações dos Usuários  | O sistema deve armazenar as informações fornecidas pelos jogadores em um banco de dados, garantindo a persistência dos dados associados à conta de cada usuário. |
| RF04  | Pareamento de Jogadores                    | O sistema deve parear automaticamente dois jogadores aleatórios, designando um como prisioneiro e outro como detentor, para iniciarem uma partida após pressionarem o botão "Começar" na tela inicial. |
| RF05  | Definição da Palavra pelo Detentor         | O sistema deve permitir que o detentor insira livremente a palavra de sua escolha para validação e inicio do jogo. |
| RF06  | Validação da Palavra Escolhida             | Antes do início do jogo, o sistema deve validar se a palavra digitada pelo detentor está presente no banco de palavras permitidas para impedir o uso de termos inexistentes, ofensivos ou inválidos. |
| RF07  | Escolha de Letras pelo Prisioneiro         | Após o início da partida, o prisioneiro deve ser capaz de selecionar letras exibidas na tela para tentar adivinhar a palavra. As letras devem ser clicáveis para o prisioneiro e apenas visíveis para o detentor. |
| RF08  | Omissão de Letras Já Escolhidas            | O sistema deve ocultar automaticamente as letras já selecionadas pelo prisioneiro para ambos os jogadores, evitando tentativas repetidas. |
| RF09  | Emissão de Sons                            | O sistema deve reproduzir diferentes efeitos sonoros dentro da interface do jogo para ambos os jogadores a fim de indicar eventos distintos, como acertos, erros e encerramento da partida. |
| RF10  | Exibição de Animações                      | O sistema deve exibir animações para ambos os jogadores representando eventos do jogo, como a escolha de letras, erros do prisioneiro, enforcamento e derrota do detentor. |
| RF11  | Cálculo do Limite de Tentativas            | O sistema deve calcular automaticamente o limite de tentativas do prisioneiro com base no tamanho da palavra escolhida pelo detentor, garantindo equilíbrio na dificuldade do jogo. |
| RF12  | Encerramento Automático da Partida         | O sistema deve encerrar automaticamente a partida e desconectar os jogadores quando um deles vencer. |
| RF13  | Atualização de Pontuação                   | O sistema deve atualizar a pontuação do jogador vencedor ao final de cada rodada, refletindo essa alteração no ranking geral. |
| RF14  | Exibição do Ranking Geral                  | O sistema deve exibir um ranking geral com os jogadores melhor classificados, organizados em ordem decrescente de pontuação, em uma tela específica denominada "Ranking Geral". |
