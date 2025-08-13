# 2. Gestão e Segurança de Dependências (Supply Chain)

- [ ] Usar versões **suportadas e atualizadas**; evitar betas em produção.  
- [ ] Validar integridade/autenticidade:
  - [ ] *Hashes* (SHA256/512) e assinaturas (PGP/GPG).
- [ ] Repositórios **oficiais** (npm, PyPI, Maven Central, RubyGems).  
- [ ] Análise automática de vulnerabilidades:
  - [ ] `npm audit`, `pip-audit`, Snyk, Dependabot, OWASP Dependency-Check em CI/CD.
- [ ] Reduzir superfície de ataque:
  - [ ] *Minimal viable dependencies*; remover pacotes obsoletos.
- [ ] Fixar versões e prevenir **dependency confusion**:
  - [ ] *Locks* (package-lock.json, requirements.txt); vigiar *typosquatting*.
- [ ] Isolamento:
  - [ ] *venv*, nvm; imagens de containers imutáveis.
- [ ] Monitorização contínua da supply chain:
  - [ ] Alertas e relatórios integrados na gestão de risco.
- [ ] Auditoria de dependências críticas:
  - [ ] Rever código quando possível; reputação/manutenção do autor.
- [ ] Pós-atualização:
  - [ ] Testes unitários, integração e segurança automatizados.

---

**VibeCoders Portugal**
