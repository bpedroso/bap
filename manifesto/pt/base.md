# I. BASE — Domínio, Fundação & Resiliência

[← Voltar ao manifesto](README.md)

Toda grande visão exige um solo firme. Sistemas de alta escala e disponibilidade não aceitam improvisos e nascem do entendimento profundo do negócio.

## Princípios

* **Compreensão do negócio como premissa:** Não existe arquitetura forte sem domínio do contexto. Entender os domínios de negócio que o software toca é o primeiro passo para determinar como ele deve ser desenhado e construído.
* **A estabilidade precede a inovação:** Nenhum algoritmo avançado substitui um alicerce frágil. A infraestrutura e a modelagem de dados devem ser projetadas para suportar alta carga, concorrência severa e crescimento exponencial.
* **Isolamento e previsibilidade:** Componentes devem ser autônomos e tolerantes a falhas. A infraestrutura de base deve ser estritamente determinística, observável e resiliente, garantindo que falhas pontuais jamais comprometam o ecossistema.
* **Arquitetura em todos os níveis:** Todo profissional de TI precisa conhecer arquitetura, em profundidades diferentes conforme a função. Do conhecimento mais raso ao mais profundo, cada camada amplia a qualidade das decisões.

## Arquitetura em todos os níveis

Arquitetura não é um ofício reservado a quem tem o cargo no crachá. É alfabetização: todo profissional de TI precisa dela, em graus distintos. Quem enxerga o sistema além da própria tarefa escolhe melhor, conversa melhor e erra menos.

A profundidade muda com a função. O que não muda é o efeito: mesmo um recorte raso já melhora a decisão; um recorte profundo torna a orientação possível.

## Insights

Dicas e reflexões sobre este pilar — situações do dia a dia que ajudam a ancorar o princípio.

**Domínio na base** — Toda equipe deve conseguir dizer o que o sistema faz, seu contexto e suas fronteiras. O conhecimento do domínio deve estar na BASE; se a equipe não sabe, o sistema se torna menos confiável em situações de falha.

**Observabilidade é alfabetização** — Logs, métricas e traces não são “trabalho de SRE depois”. São o mínimo para qualquer papel enxergar o sistema. Sem isso, arquitetura vira opinião.

**Security by design** — Segurança não entra no fim do projeto: nasce com o domínio. Identidade, dados sensíveis e quem pode ver ou alterar o quê são decisões de fundação. Quando a proteção é desenhada junto com o sistema, evita-se o ciclo eterno de “patch de segurança”.

### Por profundidade de função

**Desenvolvedor júnior** — querer saber como uma requisição chega (cliente → rede → API → serviço → dados) já localiza o próprio trabalho no sistema, seja back ou front. Esse mapa mínimo reduz o “código no vácuo”: a pessoa entende de onde vem o dado, para onde vai o erro e por que um contrato existe.

**Designer** — um pouco de arquitetura amplia ideias e possibilidades. Saber que existe latência, cache, estados de carregamento ou limites de um contrato de API muda o que vale desenhar — e o que vale defender. Sem esse recorte, o design compete com o sistema; com ele, o design usa o sistema.

**Profissional de arquitetura** — precisa de conhecimento muito mais profundo para decidir e orientar. Trade-offs, limites, evolução e risco não cabem em um diagrama de alto nível: exigem critério. Sem essa profundidade, a orientação vira opinião; com ela, vira responsabilidade.
