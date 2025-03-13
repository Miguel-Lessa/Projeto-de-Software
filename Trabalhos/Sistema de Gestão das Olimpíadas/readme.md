# Projeto de Sistema de Gestão das Olimpíadas

Este projeto foi desenvolvido para a matéria de Projetos de Software, do curso de Engenharia de Software da Pontifícia Universidade Católica de Minas Gerais. Se tratando do desenvolvimento de um sistema de gerênciamento de eventos olímpicos informatizado

---

## Diagrama de casos de uso

| <img src="Trabalhos/Sistema de Gestão das Olimpíadas/casoDeUso.png" alt="use case"/> |
|:---------------------:|
| Diagrama de casos de uso |

## Diagrama de classes 
| <img src="Trabalhos/Sistema de Gestão das Olimpíadas/diagramaClassesPacotes.png" alt="use case"/> |
|:---------------------:|
| Diagrama de classes |

## Diagrama de componentes 
| <img src="Trabalhos/Sistema de Gestão das Olimpíadas/diagramaComponentes.png" alt="use case"/> |
|:---------------------:|
| Diagrama de componentes |

## Diagrama de implantação
| <img src="Trabalhos/Sistema de Gestão das Olimpíadas/diagramaImplantacao.png" alt="use case"/> |
|:---------------------:|
| Diagrama de componentes |

## Histórias de Usuário

| Usuário        | Necessidade                         | A fim de                              |
|---------------|-----------------------------------|--------------------------------------|
| Administrador | Cadastrar eventos esportivos     | Possibilitar a inscrição de atletas |
| Administrador | Validar inscrição de atletas     | Garantir que apenas atletas elegíveis participem |
| Administrador | Gerenciar dados do evento        | Manter informações atualizadas sobre competições |
| Administrador | Registrar resultados             | Atualizar o desempenho dos atletas  |
| Administrador | Gerar relatório de medalhas      | Disponibilizar dados sobre vencedores |
| Administrador | Visualizar relatórios de resultados | Analisar o desempenho dos atletas |
| Atleta        | Realizar inscrição em eventos    | Participar de competições esportivas |
| Federação    | Gerenciar atletas associados     | Acompanhar seus desempenhos |
| Federação    | Visualizar dados do evento       | Obter informações sobre as competições |
| Federação    | Gerar relatório de medalhas de atletas | Analisar o número de premiações |

## Estrutura de Pacotes

A estrutura do projeto foi organizada em pacotes para melhor separação de responsabilidades:

```
com.sgo
│-- Gerencia de competição e eventos
│   ├── Medalha
│   ├── Evento
│   ├── Competição 
│-- Gerencia atletas
│   ├── Federação
│   ├── Atleta
```

