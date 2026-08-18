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

### Exemplos por profundidade

**Desenvolvedor júnior** — querer saber como uma requisição chega (cliente → rede → API → serviço → dados) já localiza o próprio trabalho no sistema, seja back ou front. Esse mapa mínimo reduz o “código no vácuo”: a pessoa entende de onde vem o dado, para onde vai o erro e por que um contrato existe.

**Designer** — um pouco de arquitetura amplia ideias e possibilidades. Saber que existe latência, cache, estados de carregamento ou limites de um contrato de API muda o que vale desenhar — e o que vale defender. Sem esse recorte, o design compete com o sistema; com ele, o design usa o sistema.

**Profissional de arquitetura** — precisa de conhecimento muito mais profundo para decidir e orientar. Trade-offs, limites, evolução e risco não cabem em um diagrama de alto nível: exigem critério. Sem essa profundidade, a orientação vira opinião; com ela, vira responsabilidade.
