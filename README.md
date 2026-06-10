# 🚀 LiveOnSpace — Global Solution 2026
> **1º Ano de Engenharia de Software (Presencial) — FIAP** > *Plataforma Inteligente de Monitoramento Ambiental com Apoio de Tecnologias Espaciais.*

---

## 👥 Integrantes do Grupo
* **Kaick Lima Silva** (RM: 574060)
* **Gustavo Basso** (RM: 572623)
* **Guilherme Sales** (RM: 572933)
* **Pedro Feltrin Geraldes** (RM: 569038)
* **Guilherme Kozikoski Failla** (RM: 571611)

---

## 🌍 O que é o LiveOnSpace?

Imagine que florestas estão queimando ou cidades estão sofrendo com mudanças climáticas extremas, mas os bombeiros, fiscais e moradores só descobrem o problema quando já é tarde demais. Isso acontece porque os dados ambientais hoje são espalhados, lentos e difíceis de acessar.

O **LiveOnSpace** resolve isso criando uma "ponte" inteligente. Nós juntamos duas coisas poderosas:
1. **Sensores na Terra:** Dispositivos instalados no chão (usando placas Arduino) que medem a temperatura, a umidade e a qualidade do ar do local em tempo real.
2. **Dados do Espaço:** Informações atualizadas vindas direto de satélites de agências espaciais como a **NASA** e o **INPE**.

Nossa plataforma web recebe esses dois tipos de dados, calcula os riscos de desastres (como incêndios) antes que eles fiquem fora de controle e envia alertas automáticos para o celular das autoridades e moradores.

---

## 🎯 Objetivo Principal

Desenvolver uma plataforma digital centralizada que monitora o clima e o ambiente em tempo real. O foco é detectar focos de incêndio de forma antecipada, gerar alertas automáticos de perigo e exibir mapas interativos para ajudar governos, agricultores e comunidades a tomarem decisões rápidas para salvar vidas e proteger a natureza.

---

## 🛠️ Como o Sistema foi Construído?

O projeto foi dividido em quatro camadas principais de tecnologia:

* **A Interface do Usuário (Front-End):** A página web que o usuário acessa, construída de forma leve e rápida usando HTML5, CSS3 e JavaScript puro, integrada a mapas digitais interativos.
* **O Cérebro do Sistema (Back-End):** Programação em Python utilizada para organizar os dados e gerar relatórios automáticos.
* **O Hardware (Internet das Coisas - IoT):** Circuitos físicos com Arduino que funcionam como pequenas estações meteorológicas de campo.
* **A Conexão Espacial:** Sistemas que buscam e consomem dados oficiais das APIs públicas da NASA, ESA e INPE.

---

## 🕹️ Simulador do Circuito Técnico

Para demonstrar o funcionamento dos sensores e das placas de circuito sem precisar de peças físicas, o grupo construiu um protótipo digital completo da parte eletrônica.

* **Onde testar:** Através do simulador virtual Wokwi.
* **Link de Acesso:** [Clique aqui para abrir o simulador do circuito interativo](https://wokwi.com/projects/466193340014837761)

---

## 📊 Organização dos Arquivos no Repositório

A estrutura de pastas foi planejada para manter o código limpo, separado e fácil de dar manutenção:

```text
├── assets/
│   ├── css/
│   │   └── style.css            # Código de estilo, cores e visual da página
│   └── img/
│       ├── logo.png             # Logotipo oficial
│       └── ...                  # Imagens explicativas das seções do projeto
├── index.html                   # Página principal estruturada com as 6 seções
├── integrantes.txt              # Identificação oficial dos alunos do grupo
└── link_github.txt              # Arquivo de entrega com o link do repositório
