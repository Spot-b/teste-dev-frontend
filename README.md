# Teste Dev Front End - Bernoulli

O intuito deste teste é analisar a capacidade de responder ao desafio abaixo com uma solução criativa. Entendemos que no início da carreira, muitas vezes, não temos experiência ou conhecimentos sobre tecnologias específicas. Por isso nesse teste você terá a chance de mostrar a capacidade de **pesquisar e propor** uma solução simples e funcional.

Quando finalizar o teste, publique tudo no seu [Github](https://github.com/) (_Instruções no final do teste_).

> Para facilitar você pode fazer um fork desse repositório, assim você utiliza as imagens (fundo e logo) da pasta assets. :)


### O que nós gostaríamos :thumbsup:
- Código organizado
- Instruções de uso e configuração de seus projetos
- Commits explicando o processo de construção do projeto

### O que nós não gostaríamos :thumbsdown:
- Descobrir que não foi você quem fez seu teste.
- Ver commits gigantes, sem mensagens ou com `-m` sem pé nem cabeça.

> **ATENÇÃO**: Os bônus não são obrigatórios, priorize os requisitos básicos. Entretanto os mesmos nos ajudam a avaliar a qualidade de sua entrega com relação aos demais candidatos.

# Missão

Desenvolver um projeto para a interface de usuário em **javascript** utilizando **Vue.js** (Vue 3)  para viabilizar o login e a seleção utilizando autenticação com API Rest.

Apesar do tamanho do projeto, queremos ver como você trabalha com
Single File Componentes. Por isso fique atento às dicas.

### Bônus
* Crie um projeto novo que possa ser executado via `yarn serve` :star: :star:
* Crie seu projeto no github já no início do desenvolvimento, sempre fazendo commits incrementais para simular a prática real :star:
* Não utilize frameworks (exemplo: vuetify, material ui) :star:

## Login

Essa tela deverá conter os campos:
* e-mail
* senha
* toggle de ‘permanecer conectado’
* Feedback
* botão de envio de formulário

As seguintes situações devem ser previstas:

1. O preenchimento de todos os campos é obrigatório.
2. O input de e-mail deve possuir validação.
3. Em cada um dos casos de erro na requisição mostrar mensagem
personalizada através do componente Feedback


> **Request URL**: https://meu-bernoulli-api-dev.azurewebsites.net/api/prova/login
>
> **Action**: POST
>
> **Parâmetros**
>   * email: teste@bernoulli.com.br
>   * password: #Teste@2021

Abaixo uma sugestão de layout:

![Tela de Login](https://github.com/Spot-b/teste-dev-frontend/raw/main/assets/exemplo-login.png)

### Bônus
* Seguir o layout (estrutura) sugerido. :star: (As imagens de fundo e logo estão na pasta assets desse repositório)
* **Divir os componenentes da tela (inputs, botões, etc) em componentes individuais**. :star: :star: :star:

## Seleção de Perfil

Estando conectado ao sistema, essa tela deve permitir ao usuário fazer a
seleção de um perfil por meio do componente select. Os perfis disponíveis
poderão ser acessados através de requisição GET. (Rota logo abaixo).

O Select deve possibilitar filtrar as opções por meio de busca de caracteres.

> **Request URL**: https://meu-bernoulli-api-dev.azurewebsites.net/api/prova/perfis
>
> **Action**: GET
>
> **Observações**
>   Envie o token obtido no passo anterior no head da solicitação com o nome `token`.

Abaixo uma sugestão de layout:

![Tela de seleção de perfil](https://github.com/Spot-b/teste-dev-frontend/raw/main/assets/exemplo-perfil.png)

### Bônus
* Seguir o layout (estrutura) sugerido. :star: (As imagens de fundo e logo estão na pasta assets desse repositório)
* **Divir os componenentes da tela em componentes individuais**. :star: :star: :star:

## Finalização

Quando finalizar o teste:
1. Grave um vídeo apresentando a plataforma, as principais características
da aplicação e principalmente mostrando o código e como ele foi desenvolvido pensando em resolver os problemas apresentados aqui no teste.  O aplicativo loom pode ser utilizado como opção
para gravação e compartilhamento https://www.loom.com
2. Envie um e-mail com o título `[Teste Dev Front End] Dúvidas` para [alexandre.resende@bernoulli.com.br](mailto:alexandre.resende@bernoulli.com.br) com o endereço para seu repositório com o projeto finalizado e o link para o vídeo.

## Dúvidas

Em caso de dúvidas envie um e-mail com o título `[Teste Dev] Dúvidas` para [alexandre.resende@bernoulli.com.br](mailto:alexandre.resende@bernoulli.com.br).

## Disclaimer (Considerações legais)

O presente exame tem por objetivo a seleção de candidatos para a vaga
Developer Front End (Desenvolvedor Front End), anunciada pelo Grupo
Bernoulli.

A execução deste exame caracteriza apenas uma das fases do processo seletivo
realizado pelo candidato e não gera, por tanto, nenhum vinculo trabalhista ou
obrigação financeira de qualquer natureza por sua realização.

Os produtos resultantes deste exame possuem finalidade exclusiva de avaliação
e seleção dos candidatos e não serão, sob nenhuma hipótese, utilizados para
outros propósitos.
