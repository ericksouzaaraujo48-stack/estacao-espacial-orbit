# 🚀 Missão Aurora Boreal-7

## Verificador de Suporte de Vida

Um script simples em Python que simula a verificação dos sistemas de suporte de vida de um módulo espacial, exibindo o status de oxigênio, pressão e reciclagem de água.

## 🌐 Camadas de Ambiente

O projeto segue o fluxo de três camadas de ambiente:

- **develop**: ambiente de desenvolvimento ativo, onde novas funcionalidades são implementadas e testadas localmente antes de qualquer integração.
- **stage**: ambiente de homologação, usado para validar as mudanças em condições semelhantes às de produção antes do lançamento oficial.
- **main**: ambiente de produção, contendo a versão estável e oficial do sistema de suporte de vida, em operação real na missão.

## 👨‍🚀 Tripulantes (Desenvolvedores)

- **Marina Castelo** — Engenheira de Software

## 📋 Descrição

Este projeto contém uma função que imprime no console o status atual de três sistemas críticos:

- **Oxigênio**: nível percentual disponível
- **Pressão do módulo**: estado de estabilidade
- **Sistemas de reciclagem de água**: status operacional

## 🚀 Como executar

Certifique-se de ter o Python 3 instalado. Depois, execute:

```bash
python verificar_suporte_de_vida.py
```

## 📄 Saída esperada

```
Oxigênio: 98%
Pressão do módulo: Estável
Sistemas de reciclagem de água: Operacionais
```

## 🛠️ Requisitos

- Python 3.x (não há dependências externas)

## 📁 Estrutura do projeto

```
.
├── verificar_suporte_de_vida.py
└── README.md
```

## 🔧 Possíveis melhorias futuras

- Substituir os valores fixos por leituras de sensores reais
- Adicionar tratamento de erros e alertas para níveis críticos
- Registrar logs com data/hora de cada verificação
- Criar testes automatizados para validar o comportamento da função

## 📝 Licença

Este projeto é de uso livre para fins educacionais e de demonstração.
