# atv-uni-2-eng-soft
Este repositório pertence à atividade avaliativa da 2ª unidade da disciplina de Engenharia de Software.
O sistema em questão trata-se de uma API (Applicattion Programming Interface) do sistema WeGuide, de guias e viagens.

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

<h1 align="center">Estórias de usuário e cenários BDD</h1>

<h3>ESTÓRIA 01</h3>
<strong>Como um</strong> órgão ou entidade de turismo,<br>
<strong>Eu quero</strong> cadastrar-me na plataforma,<br>
<strong>Para que</strong> possa inserir o Cadastur e garantir a confiabilidade dos profissionais em minha colaboração com a plataforma.

<h4>Cenário #1: Cadastro de Órgão do Governo com Cadastur</h4>

<strong>Dado que</strong> um órgão do governo deseja se cadastrar na plataforma,<br>
ㅤㅤ​​ㅤㅤE este órgão possui o Cadastur em vigor,<br>
<strong>Quando</strong> o órgão inicia o processo de cadastro,<br>
<strong>Então</strong> o sistema permite que o órgão complete o cadastro com sucesso,<br>
E a plataforma registra o órgão como um novo usuário,<br>
E a confiabilidade do órgão é automaticamente confirmada devido à posse do Cadastur.

