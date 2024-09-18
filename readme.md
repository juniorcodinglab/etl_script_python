
### DESAFIO 1

Avançamos significativamente no projeto e construímos um pipeline seguindo as boas práticas da programação. No entanto, sempre há espaço para melhorias. Na orientação a objetos existe o conceito do Encapsulamento, que, de maneira simplificada, informa que nem todos os métodos e atributos devem ser acessíveis pelo usuário da classe.

Considerando que nós decidimos esses acessos mencionados acima através dos métodos e atributos públicos ou privados, volte na nossa classe e reflita quais métodos e atributos devem ser públicos e quais serão utilizados apenas internamente por ela.

Realizar as tarefas propostas é essencial para consolidar o conhecimento, aplicar conceitos na prática e promover o engajamento de suas habilidades. Fortaleça o processo de sua aprendizagem e permita uma compreensão mais profunda do conteúdo. Compartilhe conhecimento! Estou ansioso para ver sua solução, bom desafio.

OBS: Essa atividade é um próximo passo nos seus estudos de engenharia de dados, então fique tranquilo se não conseguir resolver agora e analise a solução proposta.

### DESAFIO 2

Nosso projeto encontrou um desafio quando fomos adaptar a função de join para se tornar um método da classe Dados. O desafio foi que a função recebia duas listas de listas e retornava uma lista para lidar com a união desses dados. Na solução orientada a objetos, nossos dados agora são objetos da classe Dados.

Então, fica o questionamento: Como fazer a função join receber um objeto e retornar um objeto ?

Na aula, nossa solução foi criar um novo modo de leitura de dados para dados que não estão no arquivo, mas sim em memória. Essa solução resolve nosso problema e agora o método join recebe duas classes, acessa os dados e cria um novo objeto da Classe dados.

Contudo, mesmo com o problema resolvido existe espaço para melhoria. É possível refatorar nosso código e transformar as funções de leitura em métodos estáticos. Isso fará com que nosso método construtor receba, por padrão, dados e não mais o caminho para os dados.

Para resolver esse desafio sugiro que pesquise sobre classmethod, um tipo de método estático que é capaz de instanciar nosso objeto da classe.

Estou ansioso para ver sua solução, bom desafio.
