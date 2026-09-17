# Identificação de Stakeholders e Matriz de Impacto × Influência

## Histórico de Revisões

| Data | Versão | Descrição | Autores |
| :--: | :----: | :-------- | :------ |
| 11/09/2026 | 1.0 | Criação do artefato | Equipe SAGE / 2WW |

## 1. Objetivo

Este documento identifica as partes interessadas (*stakeholders*) do SAGE — plataforma web para divulgação, inscrições e gerenciamento de eventos do IFRN — e define a estratégia de relacionamento com cada grupo conforme seu impacto e sua influência no projeto.

### Escala de avaliação

| Valor | Impacto | Influência |
| :---: | :------- | :--------- |
| 1 | Muito baixo | Muito baixa |
| 2 | Baixo | Baixa |
| 3 | Médio | Média |
| 4 | Alto | Alta |
| 5 | Muito alto | Muito alta |

- **Impacto:** grau em que o stakeholder é afetado pelo funcionamento, sucesso ou falha do SAGE.
- **Influência:** capacidade de orientar decisões, priorizar requisitos, aprovar mudanças ou afetar a adoção do sistema.

## 2. Stakeholders identificados

| Stakeholder | Tipo | Interesses e necessidades principais | Impacto | Influência |
| :---------- | :--- | :---------------------------------- | :-----: | :--------: |
| Participantes e alunos | Primário externo | Encontrar eventos e atividades, realizar inscrições, consultar programação, acompanhar certificados e histórico. | 5 | 3 |
| Organizadores de eventos | Primário interno | Criar e atualizar eventos e atividades, acompanhar inscritos, registrar presença e emitir certificados. | 5 | 5 |
| Administradores do sistema | Primário interno | Controlar permissões, promover usuários a organizadores e preservar a integridade da operação. | 5 | 5 |
| Coordenação/Direção do IFRN | Patrocinador institucional | Garantir que a solução esteja alinhada aos eventos institucionais, à imagem do IFRN e às regras da instituição. | 4 | 5 |
| Palestrantes e ministrantes de minicursos | Externo | Ter informações corretas sobre horário, local, tema e público das atividades que conduzem. | 3 | 2 |
| Equipe de desenvolvimento SAGE / 2WW | Interno | Implementar, testar, manter a plataforma e transformar requisitos em funcionalidades viáveis. | 4 | 4 |
| Setor de TI e infraestrutura do IFRN | Interno de apoio | Disponibilidade, segurança, integração técnica, suporte e conformidade do ambiente. | 4 | 4 |
| Visitantes não autenticados | Externo | Consultar a divulgação e os detalhes públicos dos eventos de maneira rápida e acessível. | 3 | 1 |

## 3. Matriz de Impacto × Influência

|  | **Influência baixa (1–2)** | **Influência alta (3–5)** |
| :-- | :-- | :-- |
| **Impacto alto (4–5)** | **Manter informados**<br>Participantes e alunos | **Gerenciar de perto**<br>Organizadores de eventos; Administradores do sistema; Coordenação/Direção do IFRN; Equipe de desenvolvimento; Setor de TI e infraestrutura |
| **Impacto baixo ou médio (1–3)** | **Monitorar**<br>Visitantes não autenticados | **Manter satisfeitos**<br>Palestrantes e ministrantes de minicursos |

### Representação resumida

```text
                         INFLUÊNCIA
                    Baixa                 Alta
IMPACTO  Alto   Participantes          Organizadores
                                     Administradores
                                     Coordenação/Direção
                                     Equipe SAGE / 2WW
                                     TI e infraestrutura

          Baixo  Visitantes            Palestrantes e
                                        ministrantes
```

## 4. Estratégia de engajamento

| Grupo da matriz | Stakeholders | Estratégia de relacionamento | Canal e frequência sugeridos |
| :-------------- | :----------- | :--------------------------- | :--------------------------- |
| Gerenciar de perto | Organizadores, administradores, coordenação/direção, equipe de desenvolvimento e TI | Envolver na validação de requisitos, nas decisões de prioridade, nos testes de aceitação e na aprovação de mudanças relevantes. | Reuniões de acompanhamento; canal da equipe; revisões a cada entrega ou mudança crítica. |
| Manter informados | Participantes e alunos | Comunicar lançamentos, alterações de programação, abertura/encerramento de inscrições e instruções de uso. Coletar sugestões e problemas de usabilidade. | Avisos na plataforma, e-mail e redes sociais dos eventos; sempre que houver alteração e após eventos. |
| Manter satisfeitos | Palestrantes e ministrantes | Confirmar dados publicados, horários, locais e quantidade de inscritos sem sobrecarregar o grupo com detalhes técnicos. | Contato do organizador por e-mail ou mensagem; antes de publicação e em caso de alteração. |
| Monitorar | Visitantes não autenticados | Acompanhar acessos, buscas e conversões para cadastro/inscrição, mantendo a área pública clara e acessível. | Métricas de uso e formulário de contato; análise periódica. |

## 5. Matriz de Poder × Interesse

Embora a matriz de Impacto × Influência apresente uma visão semelhante, esta matriz considera especificamente o **poder** de decisão do stakeholder e seu **interesse** no sucesso do SAGE.

|  | **Interesse baixo (1–2)** | **Interesse alto (3–5)** |
| :-- | :-- | :-- |
| **Poder alto (3–5)** | **Manter satisfeitos**<br>Coordenação/Direção do IFRN; Setor de TI e infraestrutura | **Gerenciar de perto**<br>Organizadores de eventos; Administradores do sistema; Equipe de desenvolvimento SAGE / 2WW |
| **Poder baixo (1–2)** | **Monitorar**<br>Visitantes não autenticados | **Manter informados**<br>Participantes e alunos; Palestrantes e ministrantes de minicursos |

| Stakeholder | Poder | Interesse | Estratégia |
| :---------- | :---: | :-------: | :--------- |
| Participantes e alunos | 2 | 5 | Manter informados |
| Organizadores de eventos | 5 | 5 | Gerenciar de perto |
| Administradores do sistema | 5 | 5 | Gerenciar de perto |
| Coordenação/Direção do IFRN | 5 | 3 | Manter satisfeitos |
| Palestrantes e ministrantes | 2 | 4 | Manter informados |
| Equipe de desenvolvimento SAGE (Samuel Oliveira, Samuel Almeida, Lukas de Lima, Gabriel Gomez, João Gabriel, Caio Rodrigo) / 2WW | 4 | 5 | Gerenciar de perto |
| Visitantes não autenticados | 1 | 2 | Monitorar |

## 6. Responsabilidades por stakeholder

| Stakeholder | Principais responsabilidades no contexto do SAGE |
| :---------- | :----------------------------------------------- |
| Participantes e alunos | Manter dados cadastrais corretos, realizar inscrições dentro das regras e registrar eventuais problemas de uso. |
| Organizadores de eventos | Cadastrar e manter atualizadas as informações de eventos, atividades, vagas, programação e presença. |
| Administradores do sistema | Gerenciar perfis e permissões, garantindo que apenas usuários autorizados recebam privilégios de organização. |
| Coordenação/Direção do IFRN | Validar o uso institucional da solução, apoiar sua adoção e orientar prioridades institucionais. |
| Palestrantes e ministrantes | Fornecer e confirmar informações de suas atividades. |
| Equipe de desenvolvimento SAGE / 2WW | Desenvolver, testar, documentar e corrigir a plataforma conforme os requisitos priorizados. |
| Setor de TI e infraestrutura do IFRN | Apoiar hospedagem, disponibilidade, segurança e suporte técnico quando aplicável. |

## 7. Premissas e revisão

1. A prioridade dos stakeholders pode mudar conforme a fase do projeto, especialmente durante a realização de grandes eventos.
2. Novos parceiros institucionais ou serviços integrados devem ser avaliados e incluídos nesta matriz antes de sua adoção.
3. A matriz deve ser revisada a cada nova versão relevante do SAGE ou após a realização de um evento.
