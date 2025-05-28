+++
title = 'Afinal, o que é DevX (ou DevEx)?'
date = 2025-05-10
draft = false
description = "Mas e DevX? Você já ouviu falar? E do que se trata?"
image = "/images/devx1.webp"
imageBig = "/images/devx1.webp"
categories = ["devops", "engenharia de software"]
authors = ["PalharesDev"]
avatar = "/images/avatar.webp"
+++

Hoje em dia, dentro do contexto da engenharia de software, é muito falado sobre a cultura DevOps, cultura essa de colaboração da parte de desenvolvimento com a parte de operações e uma série de práticas adotadas a partir dessa colaboração para a entrega e desenvolvimento contínuo. Mas e DevX? Você já ouviu falar? E do que se trata?

DevX trata-se de um termo que se refere a "Developer experience", ou em uma tradução direta (e óbvia rs) experiencia do desenvolvedor. Essa experiencia, pode ser comumente relacionada a UX (User experience), mas com um escopo limitado, para a área de engenharia de software, o que não é bem verdade, vejamos a seguir melhor ao que se refere essa tal experiencia do desenvolvedor segundo a literatura.

### Definição da experiência do desenvolvedor
Existem várias definições para a experiência do desenvolvedor, mas de forma geral, e a mais utilizada na literatura é:

> **A broader concept that captures how developers feel about, think about and value their work**. (Fagerholm and Munch, 2012)

Em uma tradução livre: "**Um conceito mais amplo que captura como os desenvolvedores se sentem, pensam e valorizam seu trabalho**"

Como a própria definição diz, é um conceito amplo, mas não significa que não possa ser mensurado, é o que faz, por exemplo, o framework DevEX (termo utilizado comumente no lugar de DevX), através de métricas próprias, e muito bem estabelecidas.

### Métricas chaves
Apesar de estabelecido e definido na literatura, não quer dizer que seja um conceito difundido na indústria. Por se tratar de uma abordagem mais recente, as métricas utilizadas para se definir essa experiencia do desenvolvedor é bem diversa na literatura, de forma que cada framework, empresa e implementações pontuais possam ter métricas diferentes e únicas para medir e avaliar a experiência de seus desenvolvedores. A fórmula GitHub, por exemplo, leva em consideração três pilares para avaliar a experiência de seus desenvolvedores: A produtividade, o impacto e a satisfação desses.

![Métricas chaves DevX da empresa github](/images/devx2.webp)

Já o framework DevEX, citado anteriormente, estabelece três pilares diferentes: Estado de fluxo (Flow State), Ciclo de feedbacks (Feedback Loops) e Carga cognitiva(Cognitive Load).

![Métricas chaves do framework DevEx](/images/devx3.webp)

No caso desse framework, cada um desses pilares pode ser medido individualmente, por percepções humanas (atitudes e opiniões) ou por sistemas e processos próprios, dando exemplo com cada um dos três:

### Flow State (Estado de fluxo)

Normalmente referido como "flow", Flow state normalmente se refere ao estado mental que um indivíduo está quando ele está completamente imerso na sua atividade (seja ela qual for), e normalmente é um estado que o indivíduo tem uma percepção de esforço menor realizando a tarefa e se sente mais realizado para continuar fazendo seu trabalho. Algumas métricas DevEx para mensurar esse fator:

- Capacidade autopercebida de se concentrar e evitar interrupções
- Satisfação com a clareza das metas da tarefa ou do projeto
- Percepção de rompimento ao estar em uma call (com alguém do time normalmente).
- Número de blocos de tempo (ou blocos de trabalho) sem reuniões ou interrupções.
- Frequência de tarefas ou solicitações não planejadas
- Frequência de incidentes que exigem interrupções das tarefas atuais e atenção da equipe


### Feedback Loops (Ciclo de feedbacks)

Os ciclos de feedback refletem a velocidade e a qualidade das respostas às ações tomadas. Para isso, temos as seguintes métricas:

- Satisfação com a velocidade e o resultado dos testes automatizados
- Satisfação com o tempo necessário para validar uma alteração local
- Satisfação com o tempo necessário para implementar uma alteração na produção
- Tempo necessário para gerar resultados de CI
- Tempo de resposta da revisão de código
- Tempo de implantação (tempo necessário para que uma alteração seja liberada para a produção)

### Cognitive Load (Carga cognitiva)

A carga cognitiva refere-se normalmente a quantidade de esforço mental exigido de um desenvolvedor para que ele execute uma determinada tarefa. Métricas DevEx para Cognitive Load:

- Complexidade da base de código
- Facilidade no "debbuging" dos sistemas de produção 
- Facilidade de compreensão da documentação
- Tempo necessário para obter respostas a perguntas técnicas
- Etapas manuais necessárias para implementar uma alteração desenvolvida
- Frequência de melhorias na documentação

### Como melhorar a experiência do desenvolvedor?

Bom, você não precisa ser um gênio para entender que, para melhorar a experiência do desenvolvedor, dado essas métricas, basta, trabalhar em cima delas, exemplos práticos como adotar políticas para diminuir a complexidade da base de código da empresa, facilitar  a compreensão da documentação (além de sempre incrementar a mesma), diminuir o tempo necessário para que uma alteração seja liberada para a produção, diminuir tempo de resposta para revisões de código, entre muitas outras já citadas anteriormente.

![Desenvolvedor sentado](/images/devx4.webp)

### Por que você deveria se preocupar com isso?

Descrito todo o conceito, as métricas chaves e algumas medidas que podem ser tomadas para impactar a experiência dos desenvolvedores, é muito comum desenvolvedores questionarem: por que saber tudo isso sobre esse assunto? Bom, desenvolvedores de forma geral podem até não ser os responsáveis pela implementação de políticas relacionadas a DevX, ou em saber o que pode influenciar nas métricas analisadas para medir a experiência, e acharem que são apenas um objeto de estudo, mas o ponto é que, as políticas implementadas podem (e em muitos casos devem) fazer uma total diferença em seu dia a dia e no comprimento de suas tarefas.  

DevX é comumente relacionado na literatura com o aumento da produtividade, entre outros benefícios. A difusão dessa cultura voltada para políticas de melhoria na experiência do desenvolvedor no ambiente de trabalho tende a melhorar cada vez mais a vida dos devs, então nada mais justo que ter noção da existência dela.

#### Redes sociais
X: [@palharesgab](https://x.com/palharesdev)<br>  
Youtube: [@palharesgab](https://www.youtube.com/@PalharesDev)<br>  
LinkedIn: [Gabriel Palhares](https://www.linkedin.com/in/gabriel-pizzani-palhares/)<br>  
<!-- Instagram: [@palharesdev](https://www.instagram.com/palharesdev/)<br>     -->