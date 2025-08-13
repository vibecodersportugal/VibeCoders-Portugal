# 1. Autenticação e Controlo de Acesso

- [ ] Implementar MFA com **fatores de categoria diferente** (saber/ter/ser).  
- [ ] Utilizar protocolos seguros (OAuth 2.0, OpenID Connect, SAML 2.0).  
- [ ] Políticas de passwords:
  - [ ] Mínimo 12 caracteres (preferencialmente 14+).
  - [ ] Maiúsculas/minúsculas, números e símbolos.
  - [ ] Bloquear passwords comuns/reutilizadas ([Have I Been Pwned](https://haveibeenpwned.com/Passwords)).
  - [ ] Incentivar *passphrases* e gestores de passwords.
- [ ] Bloqueio de conta:
  - [ ] Bloqueio temporário após 5 falhas.
  - [ ] Desbloqueio só com verificação adicional (link seguro/MFA).
  - [ ] Proteção contra força bruta e *credential stuffing*.
- [ ] Sessões:
  - [ ] Expiram após inatividade (≤ 15 min para dados sensíveis).
  - [ ] Tempo máximo por sessão (ex.: 8 h).
  - [ ] Regenerar ID após login; terminar no *logout* ou atividade suspeita.
  - [ ] Cookies `Secure`, `HttpOnly`, `SameSite=Strict`.
- [ ] APIs:
  - [ ] Tokens JWT/OAuth com TTL curto e revogação.
- [ ] Autorização:
  - [ ] RBAC/ABAC com mínimo privilégio e revisão periódica.
  - [ ] Evitar perfis administrativos por defeito.
- [ ] Registos:
  - [ ] Guardar data/hora, IP, resultado; alertar padrões anómalos.
- [ ] Desativação automática de contas inativas.

---

**VibeCoders Portugal**
