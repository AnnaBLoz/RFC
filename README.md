# Capa

**Título do Projeto:** Freela Match - Plataforma de Conexão entre Freelancers e Empresas  
**Nome do Estudante:** Anna Beatriz Loz Silva e Souza 
**Curso:** Engenharia de Software  
**Data de Entrega:** 01/04/2025  

---

# Resumo

O presente documento apresenta o desenvolvimento do Freela Match, uma plataforma web voltada para conectar freelancers e empresas, com o objetivo de facilitar a intermediação de serviços autônomos por meio de um ambiente digital dinâmico e seguro. A aplicação permite o cadastro de perfis profissionais e empresariais, a busca por oportunidades de trabalho, o envio e o gerenciamento de propostas, bem como a comunicação entre as partes e a avaliação mútua de desempenho.

O projeto foi estruturado com base em requisitos funcionais e não funcionais cuidadosamente definidos, visando garantir usabilidade, desempenho e escalabilidade. A solução foi implementada utilizando Angular 18 no front-end, .NET 8 no back-end e MySQL como sistema gerenciador de banco de dados, com hospedagem na plataforma Microsoft Azure. O desenvolvimento considerou ainda aspectos relacionados à segurança da informação, arquitetura de software, design responsivo e experiência do usuário (UX/UI).

Além de propor uma solução prática para a conexão entre profissionais autônomos e contratantes, este trabalho contribui para a modernização dos processos de contratação e gestão de serviços no contexto digital, oferecendo uma alternativa eficiente e alinhada às demandas do mercado de trabalho contemporâneo.

---

# 1. Introdução

## 1.1 Contexto

Nas últimas décadas, o mercado de trabalho passou por transformações significativas impulsionadas pelo avanço da tecnologia e pela popularização do modelo remoto e autônomo de prestação de serviços. Esse cenário favoreceu o crescimento expressivo do número de freelancers, profissionais independentes que atuam em projetos temporários ou sob demanda, atendendo às necessidades específicas de empresas dos mais diversos setores. Paralelamente, organizações de pequeno, médio e grande porte têm recorrido cada vez mais a esse modelo como uma alternativa viável para suprir demandas pontuais, reduzir custos operacionais e obter maior flexibilidade nos processos de contratação.

Diante desse contexto, observa-se uma crescente demanda por plataformas digitais que atuem como pontes entre empresas e freelancers, permitindo o encontro entre oferta e demanda de forma eficiente, segura e transparente. No entanto, muitas das soluções disponíveis atualmente apresentam limitações em termos de usabilidade, confiabilidade ou personalização, dificultando o processo de intermediação e comprometendo a experiência dos usuários.

## 1.2 Justificativa

A criação da plataforma Freela Match justifica-se pela necessidade de uma solução tecnológica que vá além das funcionalidades básicas de cadastro e busca, oferecendo um ambiente integrado que permita não apenas a conexão entre profissionais e contratantes, mas também o gerenciamento de propostas, negociações, comunicações e avaliações de desempenho. Ao priorizar aspectos como segurança, facilidade de uso e transparência, o projeto busca fomentar relações profissionais mais confiáveis, eficientes e alinhadas às exigências do mercado atual.

Adicionalmente, o desenvolvimento da plataforma representa uma oportunidade relevante de aplicação prática dos conhecimentos adquiridos ao longo da formação acadêmica, envolvendo o uso de tecnologias modernas e boas práticas de engenharia de software. O projeto visa ainda contribuir com o ecossistema de soluções digitais voltadas ao trabalho freelance, apresentando uma proposta inovadora e com potencial de escalabilidade.

## 1.3 Objetivos

**Objetivo Principal:** Desenvolver uma plataforma web que promova a conexão entre freelancers e empresas, facilitando a intermediação de serviços autônomos por meio de recursos que garantam segurança, usabilidade e eficiência.  
**Objetivos Secundários:**  
- Implementar um sistema de autenticação seguro, com diferentes perfis de acesso (freelancer e empresa).  
- Desenvolver mecanismos de busca e filtragem avançados para a localização de oportunidades e profissionais.  
- Permitir o envio, recebimento e gerenciamento de propostas de trabalho dentro da própria plataforma.  
- Integrar um sistema de avaliações e feedbacks para promover a confiança entre os usuários.
- Garantir uma experiência de usuário intuitiva, com foco em design responsivo e acessibilidade.

---

# 2. Descrição do Projeto

## 2.1 Tema do Projeto

O presente projeto propõe o desenvolvimento de uma plataforma web para gerenciamento e intermediação de serviços freelance, denominada Freela Match. A aplicação tem como objetivo principal permitir o cadastro e a interação entre freelancers e empresas contratantes, oferecendo um ambiente virtual propício para o estabelecimento de relações profissionais, negociação de propostas e formalização de acordos de prestação de serviços. Por meio de funcionalidades específicas, busca-se facilitar o processo de contratação temporária de profissionais qualificados, promovendo maior organização, agilidade e segurança na comunicação entre as partes.

## 2.2 Problemas a Resolver

O desenvolvimento do Freela Match parte da identificação de lacunas recorrentes no cenário atual da contratação de freelancers, as quais comprometem a eficiência e a confiança nas relações profissionais estabelecidas por meios digitais. Os principais problemas que o projeto busca mitigar são:
- Dificuldade na identificação de profissionais qualificados: muitas empresas enfrentam desafios na hora de encontrar freelancers que atendam aos critérios técnicos e comportamentais exigidos por um projeto específico.
- Falta de transparência nos processos de contratação: a ausência de informações claras sobre histórico, reputação e qualidade dos serviços prestados dificulta a tomada de decisão e aumenta os riscos para ambas as partes.
- Inexistência de um sistema estruturado de feedback: a falta de avaliações consistentes compromete a construção de confiança entre usuários e prejudica a seleção de candidatos adequados para futuras oportunidades.

Ao atacar diretamente esses pontos, a plataforma visa proporcionar um ambiente digital mais confiável e eficiente, contribuindo para a profissionalização do mercado freelance.

## 2.3 Limitações

Embora o projeto proponha uma solução completa em termos de conexão e gestão de oportunidades entre freelancers e empresas, algumas limitações foram definidas para escopo e viabilidade técnica durante o desenvolvimento:
- Não haverá intermediação financeira direta pela plataforma: pagamentos e transações entre as partes deverão ocorrer fora do ambiente da aplicação, sendo de responsabilidade dos próprios usuários.
- Ausência de mecanismos formais de resolução de disputas: o sistema não oferecerá recursos jurídicos ou administrativos para mediar conflitos entre freelancers e contratantes.
- Cadastro restrito a empresas e profissionais autônomos: nesta versão inicial, o sistema não contemplará usuários com perfis de cliente pessoa física, restringindo-se a interações B2B (empresa-empresa) e B2F (empresa-freelancer).

Tais restrições foram adotadas com o intuito de focar nos principais objetivos do projeto e garantir sua implementação dentro dos prazos e recursos disponíveis.

---

# 3. Especificação Técnica

## 3.1 Requisitos de Software

### Lista de Requisitos

Nesta seção são apresentados os requisitos que orientam o desenvolvimento do sistema Freela Match, divididos em requisitos funcionais, que definem o comportamento esperado da aplicação, e requisitos não funcionais, que estabelecem critérios de qualidade e restrições técnicas.

**Requisitos Funcionais (RF)**
1. RF01 - O usuário deve poder criar uma conta e fazer login.
2. RF02 - Empresas devem poder cadastrar propostas de trabalho.
3. RF03 - Freelancers devem poder visualizar, aceitar ou recusar propostas.
4. RF04 - O sistema deve permitir avaliações mútuas entre freelancers e empresas.
5. RF05 - Deve ser possível realizar buscas e filtros avançados de perfis.
6. RF06 - O sistema deve permitir a edição de perfis por freelancers e empresas.
7. RF07 - Empresas devem poder visualizar o histórico de propostas enviadas e seu status.
8. RF08 - Freelancers devem poder visualizar o histórico de propostas recebidas e seu status.
9. RF09 - O sistema deve enviar notificações para freelancers e empresas sobre novas propostas e atualizações.
10. RF10 - Administradores devem poder gerenciar usuários e propostas indevidas.

**Requisitos Não Funcionais (RNF)**
1. RNF01 - O sistema deve suportar autenticação via JWT.
2. RNF02 - O tempo de resposta para buscas deve ser inferior a 2 segundos.
3. RNF03 - O banco de dados deve garantir integridade referencial entre entidades.
4. RNF04 - O sistema deve ser responsivo e acessível em dispositivos móveis e desktops.

### Representação dos Requisitos

Um Diagrama de Casos de Uso será desenvolvido para ilustrar os principais fluxos do sistema.

## 3.2 Considerações de Design

### Visão Inicial da Arquitetura

A aplicação será estruturada segundo o modelo cliente-servidor, com divisão clara entre as camadas de apresentação (front-end), lógica de negócios (back-end) e persistência de dados (banco de dados). Essa abordagem favorece a separação de responsabilidades, facilita a manutenção do sistema e permite escalabilidade futura.

### Padrões de Arquitetura

- Back-end: Utilização do padrão MVC (Model-View-Controller) para organizar a lógica da aplicação de forma modular e reutilizável.
- Front-end: Arquitetura baseada em SPA (Single Page Application), visando uma experiência fluida e responsiva ao usuário, sem recarregamento de páginas.

### Modelos C4

O projeto será documentado utilizando os quatro níveis do modelo C4: Contexto, Contêineres, Componentes e Código.

## 3.3 Stack Tecnológica

### Linguagens de Programação
- Front-end: TypeScript, utilizando o framework Angular 18.
- Back-end: C#, por meio da plataforma .NET 8.
- Banco de Dados: MySQL, para armazenamento estruturado e relacional.

### Frameworks e Bibliotecas
- Interface de Usuário (UI): Angular Material e Bootstrap, visando um design moderno e responsivo.
- Persistência de Dados: Entity Framework Core, atuando como ORM (Object-Relational Mapper).

### Ferramentas de Desenvolvimento e Gestão de Projeto
- Controle de Versão: GitHub, para versionamento colaborativo do código-fonte.
- Integração e Entrega Contínua (CI/CD): Azure DevOps, automatizando testes e deploys durante o ciclo de vida do projeto.

## 3.4 Considerações de Segurança

A segurança da informação é um aspecto central na arquitetura do Freela Match. Para mitigar riscos e proteger os dados dos usuários, serão adotadas as seguintes práticas:
- Armazenamento seguro de senhas, com uso de técnicas de hashing e salting.
- Controle de acesso baseado em autenticação via JWT e gerenciamento de permissões com Identity.
- Validação de entradas para prevenir ataques de injeção de SQL e cross-site scripting (XSS).

Essas medidas visam garantir a integridade, a confidencialidade e a disponibilidade das informações dentro do sistema.

---

# 4. Próximos Passos

Com o levantamento de requisitos, definição da arquitetura e especificação das tecnologias a serem utilizadas, os próximos passos do projeto Freela Match seguem uma abordagem incremental, alinhada a boas práticas de engenharia de software. O processo de desenvolvimento será dividido em etapas sequenciais e iterativas, conforme descrito a seguir:

1. Implementação Inicial da Arquitetura

Nesta fase será estruturada a base do sistema, incluindo a configuração dos ambientes de desenvolvimento, integração das camadas de front-end, back-end e banco de dados, e definição de rotas, entidades e modelos iniciais. Serão implementadas também as primeiras interfaces e funcionalidades essenciais de autenticação.
2. Desenvolvimento dos Módulos Principais

Após a fundação da arquitetura, será dado início ao desenvolvimento dos principais módulos funcionais, como cadastro e edição de perfis, criação e gerenciamento de propostas, sistema de busca com filtros, painel administrativo e mecanismo de avaliações mútuas entre freelancers e empresas.
3. Testes Unitários e de Integração

Serão aplicadas práticas de Test-Driven Development (TDD) e integração contínua, com foco na cobertura de testes unitários e testes de integração entre os componentes críticos do sistema. Essa etapa visa garantir a qualidade, estabilidade e confiabilidade do software em execução.
4. Implantação e Monitoramento

Após a validação das funcionalidades por meio de testes, será realizada a implantação do sistema em ambiente de produção. Ferramentas de monitoramento e logging serão configuradas para acompanhar o desempenho da aplicação, detectar falhas e apoiar a manutenção evolutiva.
Esses passos serão gerenciados por meio de ferramentas de versionamento e automação, com o auxílio do Azure DevOps, permitindo um controle eficiente sobre o progresso do projeto e seus ciclos de entrega.

---

# 5. Referências

A seguir, será apresentada a lista de materiais utilizados como base para o desenvolvimento do projeto, incluindo bibliotecas, frameworks, ferramentas e publicações técnicas ou acadêmicas. As referências serão organizadas conforme as normas da ABNT:

MICROSOFT. Documentação oficial do .NET 8. Disponível em: https://learn.microsoft.com/.

ANGULAR. Angular 18 Documentation. Disponível em: https://angular.io/docs

ROBERT C. MARTIN. Clean Architecture: A Craftsman's Guide to Software Structure and Design. Prentice Hall, 2017.

ERICH GAMMA et al. Design Patterns: Elements of Reusable Object-Oriented Software. Addison-Wesley, 1994.

FOWLER, Martin. Patterns of Enterprise Application Architecture. Addison-Wesley, 2002.

---

# 6. Apêndices (Opcionais)

[Adicionar informações complementares]

---

# 7. Avaliações de Professores

### Considerações Professor/a:

---

### Considerações Professor/a:

---

### Considerações Professor/a:
```

