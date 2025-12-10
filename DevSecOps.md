1. O que é DevSecOps e qual sua importância?
2. Integração da segurança no ciclo de desenvolvimento.
3. Automação de testes de segurança.
4. Controles de segurança em pipelines (CI/CD)
5. Ferramentas e práticas recomendadas

## O que é DevSecOps?
<p align="center">
<img width="412" height="539" alt="image" src="https://github.com/user-attachments/assets/906663ca-377a-4e5c-8d18-984077db9865" />
</p>

DevSecOps = Development + Security + Operations

Prática de incluir segurança desde o início do desenvolvimento, e não apenas no final. Ajuda a identificar falhas de segurança mais cedo, reduz custos e evita incidentes. Integra equipes: desenvolvedores, operações e segurança trabalhando juntos. Cultura de responsabilidade compartilhada pela segurança. 
São as atividades de segurança que os profissionais de segurança de aplicações realizam, a fim de garantir a segurança dos sistemas criados pelas práticas de DevOps. É a mesma coisa que os profissionais da AppSec sempre fizeram, agora com uma nova abordagem e em novos ambientes. 


## O que é DevOps?

<p align="center"> 
  <img width="865" height="423" alt="image" src="https://github.com/user-attachments/assets/175c114b-7a97-459c-b475-ea1b55c23f61" />

</p>
União de pessoas, processos e tecnologigas para fornecer continuamente valor aos clientes, permitindo que funções anteriormente isoladas, tais como: desenvolvimento, operações de TI, engenharia da qualidade e segurança. Atuando de forma coordenada e colaborativa para gerar produtos melhores e mais confiáveis. As equipes ganham a capacidade de responder melhor às necesssidades dos clientes, aumentar a confiança nos aplicativos que constroem e cumprir as metas empresariais mais rapidamente.

## Por que DevSecOps?

Aumento de ataques cibernéticos direcionados ao software. Ciclos de desenvolvimento cada vez mais rápido com DevOps --> risco de "pular segurança". Vazamentos de dados e incidentes custam caro e afetam reputação. DevSecOps garante agilidade com segurança. Segurança passa a ser parte natural do processo, não um bloqueio. 

## Controles DevSecOps

<p align="center">
<img width="904" height="380" alt="image" src="https://github.com/user-attachments/assets/72d2293d-9e6c-47c9-979d-6caee9267c86" />
</p>

Desenvolvimento - Desenvolvimento contínuo e  centrado no usuário e feedback.

Operação - Implantação contínua usando infraestrutura como código. 

Segurança - Segurança proativa e reativa mensurando desde o aplicativo até a infraestrutura. 

Garantia de qualidade - Testes automatizados e monitoramento contínuo. 

## DevSecOps - Nomenclatura 
* Rugged DevOps
* SecDevOps
* DevOpsSec
* Agile Security
* Agile SDLC
* DevOPs Security

## Shift Security Left 

Segurança começa na fase de planejamento. Ameaças e riscos são avaliados desde o design da aplicação.

Segurança inserida em cada etapa:
* Planejamento
* Desenvolvimento
* Testes
* Build e deploy
* Operações e monitoramento

O objetivo é prevenir, não apenas corrigir no fnal. 

* Shifting Security Left - Traduzindo seria algo como trazer a segurança para a esquerda.
* Nos permite lidar com problemas de segurança com antecedência e com frequência.
* Se deixarmos as práticas de segurança para o fim, acabaremos com defeitos de segurança na produção.
* Portanto, Shifting Security reduz o risco e os custos de corrigir problemas de segurança.
* Como vimos anteriormente, encontrar e corrigir bugs de segurança mais cedo leva a menos erros e menos compromentimentos.

<p align="center">
  <img width="778" height="382" alt="image" src="https://github.com/user-attachments/assets/cfc61323-88f5-4212-b88e-461942dac044" />
</p>

## Automação de Testes de Segurança 

Por que automatizar?
* Para acompanhar a velocidade dos times DevOps.
* Reduz erros humanos e garante verificações consistentes.

Principais testes automatizados:
* SAST (Static Application Security Testing): analisa o código-fonte.
* SCA (Software Composition Analysis): verifica vulnerabilidades em bibliotecas e dependências.
* DAST (Dynamic Application Security Testing): testa a aplicação em execução.
* IAST (Interactive Application Security Testing): combina análise estática e dinâmica.
* Scanning de contêineres e imagens para vulnerabilidades.
* Controle de permissões e segregação de funções.

Segurança contínua: cada commit é analisado.








