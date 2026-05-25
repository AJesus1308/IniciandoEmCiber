# 🛡️ Cybersecurity Roadmap & Labs
 🧑‍💻 Criado em mantido por Alex Jesus (@ojesus_tech)

[![Year: 2026](https://img.shields.io/badge/Year-2026-blueviolet.svg)](#)
[![Contributions: Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](#contributing)

Bem-vindo ao repositório central de estudos, laboratórios e documentações voltados para **Cibersegurança (Foco em Defesa & Security Operations)**. Este espaço foi projetado para consolidar roteiros de aprendizado estruturados, scripts de automação, relatórios de vulnerabilidades (write-ups) e boas práticas de infraestrutura.

O objetivo principal deste repositório é servir como portfólio técnico e guia prático para profissionais que buscam construir uma base sólida, resiliente e focada nas demandas reais do mercado.

---

## 🗺️ Roteiro de Entrada Definitivo (2026)

O esqueleto inicial deste repositório baseia-se no **Guia de Entrada Definitivo em Cibersegurança**, um roadmap sem atalhos focado em autonomia técnica profissional. O plano macro de evolução está dividido em três grandes fases:

| Fase | Foco Técnico Principal | Conteúdos Inclusos |
| :--- | :--- | :--- |
| **Nível 1: Fundações** | Infraestrutura Core, Redes, Linux e Windows Internals. | Protocolos, CLI, Regedit, Processos. |
| **Nível 2: Segurança Core** | Triângulo CIA, Criptografia, SIEM e Análise de Tráfego. | Logs, Wireshark, Regras de Firewall. |
| **Nível 3: Autonomia** | Laboratórios Práticos, Desafios Realistas e Portfólio. | Write-ups, Blue Labs, Automação. |

> 📁 **Acesse o Guia Completo:** O arquivo formatado e editável deste plano pode ser encontrado na raiz deste repositório sob o nome [`Roteiro_Ciberseguranca_Iniciante_2026.pdf`](./Roteiro_Ciberseguranca_Iniciante_2026.docx)[cite: 1].

---

## 🗂️ Estrutura do Repositório

O repositório está organizado de forma modular para facilitar a navegação e o consumo dos materiais:

```text
├── .github/               # Templates de Issue e Pull Requests
├── roadmap/               # Cronogramas, planos de estudo e trilhas de certificações
├── fundacoes/             # Resumos técnicos e comandos práticos
│   ├── redes/             # Análises de pacotes (Wireshark) e topologias de rede
│   ├── linux/             # Shell scripting, gerenciamento de permissões e processos
│   └── windows/           # Sysinternals, Active Directory e persistência no Registry
├── labs/                  # Ambientes virtuais e simulações de incidentes
│   ├── writeups/          # Relatórios de resolução de salas (TryHackMe / HackTheBox)
│   └── configs/           # Arquivos de hardening e isolamento de redes (Host-Only)
└── scripts/               # Ferramentas e automações autorais
    ├── python/            # Parsers de log, port scanners e scripts de automação
    └── bash/              # Automação de coleta de evidências e análise forense rápida
