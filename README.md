# atv-uni-2-eng-soft
Este repositório pertence à atividade avaliativa da 2ª unidade da disciplina de Engenharia de Software.
O sistema em questão trata-se de uma API (Applicattion Programming Interface) do sistema WeGuide, de guias e viagens.

# StarTour: Transformando e Inovando Experiências Turísticas

A StarTour é uma empresa inovadora que busca revolucionar o setor de turismo. Nosso objetivo é proporcionar uma experiência única, promovendo uma conexão mais profunda entre guias de turismo e turistas. Vamos além do simples turismo, oferecendo experiências culturais, gastronômicas, econômicas e sociais que permitem aos viajantes mergulharem verdadeiramente na essência de cada destino.

## Nossa Missão

Queremos ser a principal plataforma de ligação entre turistas e guias de turismo locais, simplificando e agilizando o processo de conexão em qualquer lugar onde a internet alcance. Isso significa que, onde quer que você esteja, encontrar o guia perfeito será rápido e eficiente graças à StarTour.

<h1 align="center">Backlog do produto</h1>
<div align="center"><strong>Tabela 1 - Backlog do produto</strong>
  
| ID | Funcionalidade | Priorização de Implementação |
|:--:|:---------------|:-----------------------------|
| 01 | Cadastro de cliente no sistema | 1 |
| 02 | Cadastro de guia no sistema | 1 |
| 03 | Cadastro de orgão ou entidade de turismo no sistema | 1,2 |
| 04 | Criação de perfil de serviço por guia | 2 |
| 05 | Interação entre guia e cliente | 3 |
| 06 | Envio de mensagem do cliente ao guia | 3 |
| 07 | Troca de mensagens entre o cliente e o guia | 3,4 |
| 08 | Exibição de imagens de pontos turísticos na tela inicial | 4 |
| 09 | Seleção de guia com base no ponto turístico pelo cliente | 4 |

</div>

# Estórias|Histórias de Usuário e Cenários BDD

##  História de Usuário 1: Relação de Instituições com o Cadastro

### Como um órgão ou entidade de turismo,

Eu quero me cadastrar na plataforma,

Para que possa inserir o Cadastur e garantir a confiabilidade dos profissionais em minha colaboração com a plataforma.

### Cenário #1: Cadastro de Órgão do Governo com Cadastur

**Dado que** um órgão do governo deseja se cadastrar na plataforma,

- E este órgão possui o Cadastur em vigor,

**Quando** o órgão inicia o processo de cadastro,

**Então** o sistema permite que o órgão complete o cadastro com sucesso,

- E a plataforma registra o órgão como um novo usuário,

- E a confiabilidade do órgão é automaticamente confirmada devido à posse do Cadastur.

### Cenário #2: Cadastro de Entidade de Turismo sem Cadastur

**Dado que** uma entidade de turismo deseja se cadastrar na plataforma,

- E esta entidade não possui o Cadastur,

**Quando** a entidade inicia o processo de cadastro,

**Então** o sistema permite que a entidade complete o cadastro com sucesso,

- E a plataforma registra a entidade como um novo usuário,

- Mas a confiabilidade da entidade não é automaticamente confirmada devido à falta do Cadastur,

- E o sistema exibe uma mensagem informando à entidade que ela deve providenciar o Cadastur para garantir a confiabilidade de seus profissionais.

## História de Usuário 2: Criação de Perfil de Serviço por Guias

### Funcionalidade: Criação de perfil de serviço

Como um guia,

Eu quero poder criar um perfil de serviço,

Para que possa destacar minhas habilidades e qualificações, atraindo mais clientes interessados em meus serviços.

### Cenário #1: Guia Cria um Perfil de Serviço com Habilidades e Qualificações

**Dado que** um guia deseja criar um perfil de serviço na plataforma,

**Quando** o guia inicia o processo de criação de perfil,

**Então** o sistema permite que o guia insira suas habilidades e qualificações,

- E o guia completa o perfil com sucesso,

- E o sistema registra o perfil de serviço do guia na plataforma.

### Cenário #2: Guia Incompleto Deixa Campos em Branco no Perfil de Serviço

**Dado que** um guia deseja criar um perfil de serviço na plataforma,

- E o guia deixa campos obrigatórios em branco durante o processo de criação do perfil,

**Quando** o guia tenta salvar o perfil incompleto,

**Então** o sistema exibe uma mensagem de erro informando o guia sobre os campos em branco,

- E o sistema não permite que o perfil seja criado até que todos os campos obrigatórios sejam preenchidos.

## História de Usuário 3: Interação entre Guia e Turista

### Funcionalidade: Interação entre guias e clientes

Como um turista interessado em um guia,

Eu quero poder interagir com os guias na plataforma,

Para que possamos discutir minhas necessidades específicas e encontrar o guia adequado para atender às minhas expectativas.

### Cenário #1: Cliente Inicia uma Conversa com um Guia

**Dado que** um cliente está interessado em encontrar um guia na plataforma,

- E o cliente encontra um guia cujo perfil atende às suas necessidades,

**Quando** o cliente inicia uma conversa com o guia,

**Então** o sistema permite que o cliente envie uma mensagem ao guia,

- E o guia recebe a mensagem e pode responder à consulta do cliente.

### Cenário #2: Turista e Guia Discutem Detalhes do Serviço contratado

**Dado que** um turista está planejando uma viagem e iniciou uma conversa com um guia,

- E o guia recebeu a mensagem do cliente,

**Quando** o turista e o guia começam a discutir detalhes específicos do serviço, como itinerário, datas e preferências,

**Então** o sistema permite que a conversa prossiga e ajuda a facilitar a comunicação entre o cliente e o guia,

- E eles podem trocar informações relevantes para planejar a experiência de viagem.
