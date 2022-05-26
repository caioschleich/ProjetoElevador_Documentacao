// Introdução
. Este programa foi desenvolvido como parte do trabalho final para o curso "Formação MS-DEV - Aprendendo a programar em C#", oferecido pela Samsung Ocean, em parceria com a Universidade do Estado do Amazonas (UEA), Universidade Estadual de Campinas (Unicamp) e Universidade de São Paulo (USP).

// Objetivo
. O objetivo deste programa foi praticar os conhecimentos adquiridos em Lógica de Programação, Resolução de Problemas e Linguagem C# para o desenvolvimento de uma interação simulada de um usuário de elevador. Para este programa em particular, o autor criou a interação com base no trabalho do ascensorista, profissional responsável pela operação, manobras e cuidados com o elevador em edifícios públicos. Trata-se de um profissional raro, porém muito presente e importante em muitos edifícios das grandes metrópoles.

// Sobre o autor
. Este programa foi desenvolvido pelo aluno Caio Varlei Righi Schleich, graduado em Arquitetura e Urbanismo e pós-graduado em Gerenciamento de Projetos, atualmente busca o desenvolvimento de plataformas e sistemas inteligentes em edifícios para o benefício de seus moradores e usuários. É estudante de IA, Machine Learning e IoT.

// Como funciona?

// Utilização do programa
. Ao iniciar o programa, a tela inicial apresenta uma mensagem de boas vindas baseada na hora do sistema do usuário e em seguida pergunta o nome do condomínio onde o elevador irá operar.

. O programa solicita que o usuário insira informações padrão para a operação do elevador, como o número de andares do condomínio.

. Em seguida, solicita a informação de qual a capacidade máxima de passageiros que podem utilizar o elevador simultaneamente. Tal como com a quantidade de andares, o programa informa um número padrão inicial.

. Após a configuração inicial, é exibida uma mensagem de boas-vindas ao usuário do programa (Olá Ascensorista!) e as informações do estado atual do elevador (se está vazio, ou ocupado com determinado número de pessoas, e em qual andar se encontra).

. Tal como uma rotina padrão de um elevador comum, o usuário deve informar nesta ordem: quantas pessoas vão entrar no elevador, para qual andar o elevador irá, e quantas pessoas sairão do elevador no andar de destino:

. Após a operação de entrada, viagem e saída de pessoas, o programa informa novamente o estado do elevador, desta vez em caráter informativo e apresentando o nome do condomínio. Com essa operação concluída, o usuário pode escolher se prefere continuar operando novas viagens ou se deseja sair do programa.

. Caso deseje sair ao escolher a opção "s", uma mensagem de despedida é exibida.

// Mensagens de erro
. O programa foi elaborado com recursos para negar a entrada de dados que sejam inadequados para o seu funcionamento correto com base nas informações padrão determinadas pelo próprio usuário. O primeiro caso é a quantidade de pessoas que podem entrar no elevador ser, no máximo, a quantidade informada. Caso o elevador já esteja ocupado, o programa calculará a quantidade atual e, ao somar com a nova entrada, também apresentará mensagem de erro caso a soma ultrapasse a capacidade máxima permitida:</p>

. O programa também nega a entrada de dados para qual andar o usuário deseja viajar com base na informação inicial apresentada.

. Outro recurso de segurança é impedir a saída de mais pessoas do que a quantidade que existe dentro do elevador, garantindo cálculos matemáticos válidos.
