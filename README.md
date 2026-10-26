<p align="center">
<img src="assets/capa.png" alt="Git & GitHub" width="100%">
</p>

<h1 align="center">Git & GitHub</h1>
<p align="center"><i>Projeto de prática de versionamento do curso da DIO</i></p>

<p align="center">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/tipo-estudo-64748B?style=flat-square" alt="tipo: estudo">
</p>

## Sumário

- [Sobre](#sobre)
- [O que foi praticado](#o-que-foi-praticado)
- [Como visualizar](#como-visualizar)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Autor](#autor)

## Sobre

Projeto criado no **curso de Git e GitHub da DIO** para praticar controle de versão com um site simples: criar o repositório, registrar commits e publicar no GitHub.

## O que foi praticado

| Prática | Conceito |
| --- | --- |
| `git init` · `git clone` | Criar e copiar repositórios |
| `git add` · `git commit` | Registrar alterações |
| `git branch` · `git merge` | Trabalhar com ramificações |
| `git push` | Publicar no GitHub |
| `index.html` · `contato.html` | Site usado como base da prática |

```mermaid
gitGraph
    commit id: "git init"
    commit id: "index.html"
    branch contato
    checkout contato
    commit id: "contato.html"
    checkout main
    merge contato
    commit id: "git push"
```

## Como visualizar

```bash
git clone https://github.com/sauloprado/Projeto-Curso-Git.git
```

Abra o `index.html` no navegador.

## Estrutura do repositório

```text
Projeto-Curso-Git/
├── index.html
├── contato.html
└── assets/capa.png
```

## Autor

**Saulo Prado** · Analista de Sistemas · Gestão de Ativos de TI, orçamento, automação e dashboards

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saulo%20Prado-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saulo-prado-ab4a0b96/)
[![GitHub](https://img.shields.io/badge/GitHub-sauloprado-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sauloprado)
