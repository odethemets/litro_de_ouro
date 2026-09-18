1. Resumo

O software Litro de Ouro é um aplicativo mobile que permite aos usuários localizar postos de combustíveis e eletropostos próximos, consultar os preços dos diferentes tipos de abastecimento e encontrar rotas até o local escolhido. O aplicativo utiliza a localização do usuário e recursos de mapas para apresentar as opções disponíveis na região.

Além de exibir a distância até os postos, o sistema considera os preços informados para auxiliar o usuário na escolha de uma opção, permitindo comparar o custo do combustível com a distância a ser percorrida.

2. Clientes

O Litro de Ouro é destinado a motoristas que desejam encontrar opções de abastecimento próximas e comparar preços de combustíveis e carregamento elétrico antes de se deslocarem até um posto ou eletroposto.

O aplicativo também permite que os próprios usuários contribuam com informações, cadastrando e atualizando os preços encontrados nos estabelecimentos.

3. Problema

3.1. Preços dos combustíveis

Os preços dos combustíveis podem variar entre diferentes postos e também podem sofrer alterações frequentes. Muitas vezes, o motorista precisa consultar diversos estabelecimentos ou se deslocar até eles para descobrir qual possui um preço mais adequado.

O Litro de Ouro busca centralizar essas informações em um único aplicativo, permitindo que o usuário visualize os preços cadastrados pelos demais usuários e encontre postos próximos.

3.2. Distância e custo do deslocamento

Escolher o posto apenas pelo menor preço nem sempre representa a opção mais econômica, pois um posto mais barato pode estar muito distante do usuário.

Por isso, o aplicativo considera tanto o preço do abastecimento quanto a distância até o estabelecimento, apresentando opções de rota para auxiliar o usuário na decisão.

3.3. Eletropostos

Usuários de veículos elétricos também podem encontrar dificuldades para localizar pontos de carregamento e verificar informações sobre eles.

O Litro de Ouro permite localizar eletropostos, visualizar informações disponíveis sobre os carregadores, preços por kWh, disponibilidade e tipos de carregadores.

4. Escopo

4.1. O Litro de Ouro é…

- Um aplicativo mobile para localização e comparação de postos de combustíveis e eletropostos.
- Um sistema que utiliza a localização do usuário para apresentar estabelecimentos próximos.
- Um aplicativo que permite consultar preços de diferentes tipos de abastecimento.
- Um sistema que permite aos usuários cadastrar e atualizar preços.
- Um aplicativo que calcula rotas até os estabelecimentos.
- Um sistema que considera distância e preço para auxiliar na escolha do posto.
- Um aplicativo que permite avaliar e informar a situação dos preços apresentados.
- Um sistema integrado a recursos de mapas, utilizando a API do Google Maps.

4.2. O Litro de Ouro não é…

- Um sistema responsável pela venda de combustíveis.
- Um sistema responsável pelo abastecimento do veículo.
- Um sistema responsável por definir os preços praticados pelos postos.
- Um sistema que garante que os preços cadastrados pelos usuários estejam sempre atualizados.
- Um aplicativo de pagamento de combustível ou carregamento elétrico, salvo se essa funcionalidade for adicionada posteriormente.

4.3. O Litro de Ouro faz…

- Cadastro e autenticação de usuários.
- Localização de postos próximos.
- Localização de eletropostos próximos.
- Exibição dos preços cadastrados pelos usuários.
- Cadastro e atualização de preços pelos usuários.
- Consulta de diferentes tipos de combustíveis e formas de abastecimento.
- Exibição da distância entre o usuário e os estabelecimentos.
- Cálculo e apresentação de rotas.
- Comparação entre preço e distância.
- Exibição de informações dos eletropostos, como preço por kWh, disponibilidade e tipo de carregador, quando essas informações estiverem disponíveis.
- Avaliação dos postos e das informações apresentadas.
- Utilização de mapas e serviços de localização por meio da API do Google Maps.

4.4. O Litro de Ouro não faz…

- Controla os preços praticados pelos postos.
- Garante a veracidade das informações cadastradas pelos usuários.
- Realiza o abastecimento dos veículos.
- Realiza diretamente a manutenção dos postos.
- Define os preços dos combustíveis ou da recarga elétrica.
- Garante a disponibilidade de combustível ou carregadores no momento da chegada do usuário.

5. Usuários

5.1. Motoristas

Utilizam o aplicativo para localizar postos de combustíveis e eletropostos próximos, consultar preços, comparar as opções disponíveis e traçar rotas até o estabelecimento escolhido.

Também podem cadastrar e atualizar preços encontrados nos postos e realizar avaliações para contribuir com as informações disponíveis no aplicativo.

5.2. Usuários de veículos elétricos

Utilizam o aplicativo para localizar eletropostos, consultar informações sobre carregadores, preços por kWh, disponibilidade e tipos de carregadores, quando disponíveis.

Também podem contribuir com a atualização dessas informações.

6. Requisitos funcionais

[RF1] Gerenciar usuários – permitir cadastro, login e gerenciamento das informações da conta.

[RF2] Localizar postos – apresentar postos de combustíveis próximos à localização atual do usuário.

[RF3] Localizar eletropostos – apresentar eletropostos próximos à localização atual do usuário.

[RF4] Consultar preços – permitir visualizar os preços cadastrados para os diferentes tipos de abastecimento.

[RF5] Cadastrar preços – permitir que usuários cadastrados informem os preços encontrados nos estabelecimentos.

[RF6] Atualizar preços – permitir que os usuários atualizem informações de preços já cadastradas.

[RF7] Comparar opções – apresentar informações que permitam ao usuário comparar preço e distância dos estabelecimentos.

[RF8] Calcular rotas – calcular e apresentar uma rota entre a localização do usuário e o estabelecimento selecionado.

[RF9] Gerenciar informações de eletropostos – apresentar informações como preço por kWh, disponibilidade e tipo de carregador, quando disponíveis.

[RF10] Avaliar estabelecimentos – permitir que os usuários realizem avaliações dos postos e das informações apresentadas.

[RF11] Utilizar localização – obter a localização do usuário para apresentar estabelecimentos próximos e calcular rotas.

[RF12] Exibir mapa – apresentar postos, eletropostos e rotas em um mapa utilizando serviços do Google Maps.

7. Requisitos não-funcionais

- O sistema deve ser desenvolvido para dispositivos móveis.
- O sistema deve possuir autenticação para acesso às funcionalidades que exigem cadastro.
- O sistema deve utilizar serviços de localização para identificar a posição do usuário.
- O sistema deve utilizar a API do Google Maps para mapas e rotas.
- O sistema deve apresentar as informações de forma simples e intuitiva.
- O sistema deve permitir atualização das informações de preços pelos usuários.
- Os dados dos usuários devem ser protegidos por mecanismos de autenticação e segurança.
- O sistema deve apresentar as informações de localização e preços de maneira rápida e adequada para dispositivos móveis.
- O sistema deve ser capaz de trabalhar com diferentes tipos de combustíveis e formas de abastecimento.

8. Regras de negócio

[RN1] Para utilizar as funcionalidades que dependem de uma conta, o usuário deve realizar cadastro no aplicativo.

[RN2] Os preços exibidos no aplicativo são informados e atualizados pelos próprios usuários.

[RN3] O usuário deve informar o estabelecimento e o tipo de abastecimento ao cadastrar um preço.

[RN4] Os preços cadastrados podem sofrer alterações e podem não representar o preço praticado no estabelecimento no momento da chegada do usuário.

[RN5] O aplicativo deve utilizar a localização atual do usuário para identificar estabelecimentos próximos.

[RN6] O aplicativo deve permitir que o usuário selecione um posto ou eletroposto para visualizar suas informações e traçar uma rota.

[RN7] A rota deve considerar a localização do usuário e a localização do estabelecimento selecionado.

[RN8] A comparação das opções deve considerar as informações de preço e distância disponíveis no sistema.

[RN9] Os eletropostos devem apresentar, quando disponíveis, informações sobre preço por kWh, disponibilidade e tipo de carregador.

[RN10] O usuário pode avaliar os estabelecimentos e contribuir para a atualização das informações disponíveis.

[RN11] As informações cadastradas pelos usuários estão sujeitas a alterações e podem apresentar divergências em relação às informações reais do estabelecimento.

[RN12] O sistema deve permitir a utilização de diferentes tipos de abastecimento, incluindo combustíveis e carregamento de veículos elétricos.

