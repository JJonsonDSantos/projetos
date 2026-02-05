# ESCOPO E PREMISSAS DO PROJETO

## 1. Visão Geral
Este documento define o escopo e as premissas para o desenvolvimento de um **Sistema de Gestão de Atividades de Engenharia**, destinado ao controle, acompanhamento e análise das atividades executadas por equipes de engenharia.

---

## 2. Objetivo do Sistema
O sistema tem como objetivo:
- Gerenciar atividades de engenharia ao longo de todo o seu ciclo de vida;
- Controlar documentos, dados técnicos e prazos associados às atividades;
- Monitorar indicadores de performance e qualidade;
- Fornecer informações consolidadas para apoio à tomada de decisão.

---

## 3. Premissas
- O sistema será acessado via interface web;
- O controle de acesso será baseado em perfis de usuário;
- Todas as operações relevantes deverão ser auditáveis;
- Os dados deverão ser armazenados de forma estruturada e segura.

---

## 4. Perfis de Usuário e Funcionalidades

### 4.1 Usuário de Aplicação
Funcionalidades permitidas:
- Criar novas atividades de engenharia;
- Inserir e atualizar dados, documentos e prazos previstos associados às atividades;
- Cancelar atividades que ainda não tenham sido iniciadas;
- Atualizar parcialmente atividades em andamento, respeitando regras de negócio;
- Encerrar atividades iniciadas;
- Visualizar indicadores individuais de performance e qualidade.

---

### 4.2 Usuário Master
Inclui todas as funcionalidades do Usuário de Aplicação, além de:
- Alterar e excluir dados, documentos e prazos de atividades;
- Alterar ou excluir atividades em qualquer estado;
- Visualizar e emitir relatórios consolidados de performance e qualidade por usuário, grupo ou período;
- Cadastrar e gerenciar usuários do sistema, incluindo definição parcial de permissões.

---

### 4.3 Administrador do Sistema
Inclui todas as funcionalidades do Usuário Master, além de:
- Gerenciar a infraestrutura do sistema (back-end, front-end e banco de dados);
- Realizar manutenção evolutiva e corretiva do código-fonte;
- Gerenciar políticas de segurança da informação e cibersegurança;
- Garantir disponibilidade, integridade, confidencialidade e confiabilidade dos dados;
- Executar rotinas de backup, recuperação e monitoramento do sistema.

---

## 5. Requisitos Não Funcionais
- O sistema deverá garantir controle de acesso baseado em perfis;
- Todas as operações críticas deverão ser registradas em logs de auditoria;
- O sistema deverá possuir mecanismos de backup e recuperação de dados;
- As informações deverão ser protegidas contra acesso não autorizado;
- O sistema deverá suportar crescimento gradual do volume de dados e usuários.

---

## 6. Fora de Escopo
- Integrações com sistemas externos (a serem definidas em fase futura);
- Automação de processos fora das atividades de engenharia;
- Suporte a dispositivos móveis (caso não previsto inicialmente).
