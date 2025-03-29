```md
# Capa

**Título do Projeto:** Freela Match - Plataforma de Conexão entre Freelancers e Empresas  
**Nome do Estudante:** Anna Beatriz Loz Silva e Souza 
**Curso:** Engenharia de Software  
**Data de Entrega:** 01/04/2025  

---

# Resumo

O presente documento descreve o projeto Freela Match, uma plataforma web voltada para conectar freelancers e empresas, permitindo cadastro, busca e interação entre ambos. O projeto visa oferecer um ambiente eficiente para negociações de serviços, gestão de propostas e avaliações de desempenho. Serão abordados aspectos técnicos da implementação, requisitos funcionais e não funcionais, bem como questões de segurança e design da aplicação.

---

# 1. Introdução

## 1.1 Contexto

Com o crescimento do trabalho autônomo e remoto, surgiu a necessidade de plataformas que facilitem a conexão entre freelancers e empresas. Muitas empresas precisam de profissionais qualificados para projetos específicos, enquanto freelancers buscam oportunidades compatíveis com suas habilidades.

## 1.2 Justificativa

O Freela Match se justifica pela necessidade de um sistema eficiente para facilitar essa conexão, garantindo transparência, segurança e facilidade de uso. Além disso, ao fornecer um sistema de propostas e avaliações, o projeto contribui para um ambiente profissional mais confiável.

## 1.3 Objetivos

**Objetivo Principal:** Desenvolver uma plataforma web para conectar freelancers e empresas.  
**Objetivos Secundários:**  
- Criar um sistema seguro de autenticação.  
- Implementar mecanismos eficientes de busca e filtragem.  
- Permitir a gestão de propostas de trabalho.  
- Fornecer um sistema de avaliações para melhorar a confiabilidade dos perfis.

---

# 2. Descrição do Projeto

## 2.1 Tema do Projeto

O projeto consiste em uma plataforma web para o cadastro e gerenciamento de freelancers e empresas, permitindo a interação entre eles para fechamento de contratos de prestação de serviços.

## 2.2 Problemas a Resolver

- Dificuldade em encontrar freelancers qualificados.
- Falta de transparência na contratação de serviços.
- Ausência de um sistema confiável de feedback e avaliações.

## 2.3 Limitações

- O sistema não realizará intermediação financeira.
- Não serão fornecidos serviços de resolução de disputas.
- Apenas freelancers e empresas poderão se cadastrar; clientes individuais não serão suportados inicialmente.

---

# 3. Especificação Técnica

## 3.1 Requisitos de Software

### Lista de Requisitos

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

- Aplicação baseada em arquitetura Cliente-Servidor.
- Camadas separadas: Front-end, Back-end e Banco de Dados.

### Padrões de Arquitetura

- Utilização do padrão MVC no back-end.
- Front-end baseado em SPA (Single Page Application).

### Modelos C4

O projeto será documentado utilizando os quatro níveis do modelo C4: Contexto, Contêineres, Componentes e Código.

## 3.3 Stack Tecnológica

### Linguagens de Programação
- Front-end: TypeScript (Angular 18)
- Back-end: C# (.NET 8)
- Banco de Dados: MySQL

### Frameworks e Bibliotecas
- Angular Material e Bootstrap para UI.
- Entity Framework Core para ORM.

### Ferramentas de Desenvolvimento e Gestão de Projeto
- GitHub para controle de versão.
- Azure DevOps para CI/CD.

## 3.4 Considerações de Segurança

- Proteção de senhas com hashing e salting.
- Controle de acesso baseado em JWT e Identity.
- Validação de entrada para prevenir injeções de SQL e XSS.

---

# 4. Próximos Passos

1. Implementação inicial da arquitetura.
2. Desenvolvimento dos módulos principais.
3. Testes unitários e integração.
4. Implantação e monitoramento.

---

# 5. Referências

[Listar frameworks, bibliotecas e artigos utilizados]

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

