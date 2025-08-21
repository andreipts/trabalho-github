# 🚀 Workflow de Desenvolvimento

Este documento define o fluxo de trabalho adotado no projeto, boas práticas de versionamento e política de revisões.

---

## Modelos de Workflow

### 1. Git Flow
- Branches principais:  
  - `main` → versão estável em produção  
  - `develop` → integra novas features antes do release  
- Branches auxiliares:  
  - `feature/*` → novas funcionalidades  
  - `release/*` → preparação para entrega  
  - `hotfix/*` → correções urgentes em produção  

### 2. GitHub Flow
- Fluxo:
  1. Cria branch a partir de `main`
  2. Faz commit/push da feature
  3. Abre Pull Request (PR)
  4. Revisão + merge na `main`

### 3. GitLab Flow
- Fluxo comum:
  - `main` → produção  
  - `feature/*` → desenvolvimento  
  - `release/*` → staging/testes  

---

## Nomeação de Branches
- `feature/nome-da-feature` → novas funcionalidades  
- `fix/nome-do-bug` → correções  
- `hotfix/nome-do-hotfix` → correções críticas em produção  
- `docs/nome` → documentação  
- `test/nome` → testes  


