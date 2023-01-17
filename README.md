# Corretor_Provas
(logo)
#Home
Esse código é um sistema de correção de provas automatizado que utiliza a biblioteca OpenCV para processar imagens. Ele usa uma câmera conectada ao computador para ler a imagem da prova, extrai o gabarito da prova, identifica as respostas marcadas pelo aluno e compara com as respostas corretas pré-definidas. Ele desenha retângulos em volta das respostas marcadas e mostra a pontuação final com base no número de acertos e erros.

#Motivação
O desenvolvimento de software de correção automatizada de provas é uma boa escolha pois, a correção de provas é uma tarefa cansativa e demorada, especialmente quando se trata de grandes quantidades de provas. Além disso, a correção manual pode ser suscetível a erros humanos e imprecisões. Com o uso de tecnologia, é possível automatizar esse processo e melhorar a precisão e velocidade da correção, além de diminuir a carga de trabalho para professores.Além disso, a correção automatizada também pode ajudar a garantir a isonomia na correção de provas, o que é fundamental para garantir que todos os alunos sejam avaliados de forma justa e imparcial.

(prints código)

#Metodologia
A metodologia de desenvolvimento de software utilizada no processo de desenvolvimento do sistema de correção de provas pode variar dependendo das necessidades e objetivos específicos do projeto, mas geralmente inclui as seguintes etapas:

Análise de requisitos: nesta etapa, os requisitos para o sistema são coletados e documentados, incluindo as necessidades funcionais e não funcionais, bem como as restrições e limitações do sistema.

Projeto: nesta etapa, o sistema é projetado, incluindo a arquitetura do sistema, a escolha de tecnologias e ferramentas, a definição de interfaces e a identificação de casos de uso.

Implementação: nesta etapa, o código é escrito e testado para garantir que ele atenda aos requisitos especificados.

Teste: nesta etapa, o sistema é testado para garantir que ele funcione corretamente e atenda aos requisitos especificados.

Implantação: nesta etapa, o sistema é implantado em um ambiente de produção e é colocado em operação.

Manutenção: nesta etapa, o sistema é monitorado e mantido para garantir que ele continue funcionando corretamente e atenda às necessidades dos usuários.

Esse processo foi adaptado de acordo com a necessidade e escolha de metodologias ágeis.

#Integrantes
No meu caso em específico eu trabalhei sozinho atuando em todas as areas, Scrum Master, Product Owner etc...

(Sprints)

Por conta do horário e certa falta de organização do backlog, encontrei uma certo transbordo, precisando realizar muitas tarefas em pouco tempo que me disponibilizei


#Backlog inicial
Analisar os requisitos do sistema: entender as necessidades e objetivos do projeto, incluindo as necessidades funcionais e não funcionais, bem como as restrições e limitações do sistema.

Projetar a arquitetura do sistema: escolher as tecnologias e ferramentas a serem usadas, definir as interfaces e identificar os casos de uso.

Implementar a captura de imagem: escrever o código para capturar a imagem da prova usando uma câmera conectada ao computador.

Implementar a extração do gabarito: escrever o código para extrair o gabarito da prova a partir da imagem capturada.

Implementar a identificação de respostas: escrever o código para identificar as respostas marcadas pelo aluno.

Implementar a comparação de respostas: escrever o código para comparar as respostas marcadas pelo aluno com as respostas corretas pré-definidas.

Testar e depurar o sistema: testar o sistema para garantir que ele funcione corretamente e atenda aos requisitos especificados.

Documentação: documentar o projeto para futuras referências.

#Backlog final
Testar e depurar o sistema: testar o sistema para garantir que ele funcione corretamente e atenda aos requisitos especificados.

Implementar a funcionalidade de exibição de resultados: escrever o código para exibir os resultados da correção da prova na tela.

Finalizar a documentação: finalizar a documentação do projeto para futuras referências.

Fazer ajustes finais: fazer quaisquer ajustes finais necessários para garantir que o sistema esteja pronto para uso.

Treinar usuários: Treinar os usuários finais do sistema sobre como usar e manter o sistema.

Implantação: implantar o sistema em um ambiente de produção e colocá-lo em operação.

Monitorar o desempenho: Monitorar o desempenho do sistema e tomar medidas para corrigir quaisquer problemas ou otimizar o desempenho.

#Análise e Projeto do Software
Projeto Arquitetural em Camadas:

Camada de captura de imagem: essa camada é responsável por capturar a imagem da prova usando uma câmera conectada ao computador. Ela pode incluir bibliotecas de visão computacional para processar a imagem e extrair informações relevantes.

Camada de processamento de imagem: essa camada é responsável por processar a imagem capturada e compará-la com o modelo do gabarito fornecido. Ela pode incluir técnicas de processamento de imagem, como limiarização, segmentação e reconhecimento de formas, para extrair o gabarito da prova e compará-lo com o modelo.

Camada de identificação de respostas: essa camada é responsável por identificar as respostas marcadas pelo aluno na prova. Ela pode incluir técnicas de reconhecimento óptico de caracteres para ler as respostas marcadas e compará-las com as respostas corretas pré-definidas. Essa camada também pode usar o arquivo excel com as posições do gabarito para localizar as respostas marcadas na prova.

Camada de lógica de negócios: essa camada é responsável por aplicar as regras de negócios e lógicas para avaliar as respostas marcadas e determinar se elas estão corretas ou incorretas.

Camada de exibição de resultados: essa camada é responsável por exibir os resultados da correção da prova na tela, incluindo a contagem de acertos e erros, e a pontuação final. Ela pode incluir bibliotecas de interface gráfica do usuário para desenhar a interface e exibir os resultados.

#Projeto de Componentes
Módulo de captura de imagem: esse módulo é responsável por capturar a imagem da prova usando uma câmera conectada ao computador e fornecer a imagem para o próximo módulo de processamento de imagem.

Módulo de processamento de imagem: esse módulo é responsável por processar a imagem capturada e compará-la com o modelo do gabarito fornecido. Ele usa técnicas de processamento de imagem, como limiarização, segmentação e reconhecimento de formas, para extrair o gabarito da prova e compará-lo com o modelo.

Módulo de identificação de respostas: esse módulo é responsável por identificar as respostas marcadas pelo aluno na prova. Ele usa técnicas de reconhecimento óptico de caracteres para ler as respostas marcadas e compará-las com as respostas corretas pré-definidas. Ele também usa o arquivo excel com as posições do gabarito para localizar as respostas marcadas na prova.

Módulo de lógica de negócios: esse módulo é responsável por aplicar as regras de negócios e lógicas para avaliar as respostas marcadas e determinar se elas estão corretas ou incorretas.

Módulo de exibição de resultados: esse módulo é responsável por exibir os resultados da correção da prova na tela, incluindo a contagem de acertos e erros, e a pontuação final. Ele usa bibliotecas de interface gráfica do usuário para desenhar a interface e exibir os resultados.

#Propriedades e Princípios do Projeto
Abstração: O sistema é dividido em camadas e módulos, cada um com uma responsabilidade específica, permitindo que o sistema seja facilmente compreendido e modificado.

Encapsulamento: Cada camada ou módulo possui sua própria interface de comunicação, o que esconde os detalhes de implementação das outras camadas ou módulos. Isso permite que o sistema seja mais fácil de ser mantido e modificado.

Herança: As técnicas de processamento de imagem e reconhecimento óptico de caracteres são herdadas de bibliotecas externas, evitando a necessidade de reescrever esses componentes do zero

#Métricas do Código Fonte
#Tamanho
Para medir o tamanho do código-fonte do sistema pelo LOC (Linhas de Código), é possível usar uma ferramenta de contagem de linhas de código, como o CLOC (Count Lines of Code) ou o SLOCCount. Essas ferramentas podem ser executadas a partir da linha de comando e fornecerão uma contagem precisa do número de linhas de código no seu projeto.

Ao usar essa ferramenta, você pode especificar os arquivos ou diretórios que deseja incluir na contagem, bem como as extensões de arquivo que deseja incluir. Por exemplo, para contar somente as linhas de código em arquivos Python, você pode executar o comando:

cloc --include-ext=.py path/to/your/project

Ou usando o sloccount:

sloccount path/to/your/project

Isso irá produzir uma saída com a contagem de linhas de código, comentários e linhas em branco, assim como o número de arquivos e outras estatísticas.


 
