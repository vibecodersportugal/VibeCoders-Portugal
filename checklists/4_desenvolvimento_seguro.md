# 4. Desenvolvimento Seguro

- [ ] Validação de entrada no servidor; *whitelists*; limites de tamanho/formato.  
- [ ] Prevenir injeções:
  - [ ] *Prepared statements*/queries parametrizadas.
  - [ ] Escapar dados dinâmicos (HTML/JS/XML/JSON).
  - [ ] ORMs com mecanismos anti-injeção.
- [ ] *Output encoding* por contexto (HTML/JS/CSS/URL); prevenir XSS refletido/armazenado/DOM.  
- [ ] CSRF:
  - [ ] *Tokens* por sessão/formulário; cookies `SameSite=Lax/Strict`.
- [ ] Não expor detalhes internos:
  - [ ] Erros genéricos; *stack traces* só em logs internos.
- [ ] APIs/microserviços:
  - [ ] OAuth2/JWT TTL curto; *rate limiting*; validação por esquema (JSON/XML).
- [ ] Menor privilégio entre componentes; evitar *exec* de comandos do SO.  
- [ ] SAST em CI/CD (SonarQube, Semgrep, Bandit); corrigir antes de *merge*.  
- [ ] DAST em *runtime* para falhas lógicas não captadas estaticamente.  
- [ ] Testes de segurança automatizados (unitários + regressão).  
- [ ] Eliminar código/bibliotecas obsoletas; substituir APIs depreciadas.

---

**VibeCoders Portugal**
