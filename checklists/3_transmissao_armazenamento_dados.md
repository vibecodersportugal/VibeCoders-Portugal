# 3. Segurança na Transmissão e Armazenamento de Dados

- [ ] TLS 1.2+ (ideal 1.3); desativar SSL/TLS antigos; PFS (ECDHE); cifras fortes.  
- [ ] Forçar HTTPS + HSTS; redireciono automático HTTP→HTTPS.  
- [ ] Certificados:
  - [ ] CA de confiança; renovação atempada; *pinning* em apps móveis/clients.
- [ ] Cifra em repouso:
  - [ ] AES-256 para dados; RSA-4096/ECC para troca de chaves.
  - [ ] Chaves em HSM/KMS seguro.
- [ ] *Hashing* de passwords:
  - [ ] Argon2id/bcrypt/scrypt com *salt* único e custo adequado.
- [ ] Pseudo/anonimização de dados pessoais; separação de identificadores.  
- [ ] Minimização e retenção: recolher só o necessário; eliminar no prazo.  
- [ ] Backups cifrados; local seguro; testes regulares de recuperação.  
- [ ] Evitar exposição: nada de dados sensíveis em URLs/logs/erros; mascaramento.  
- [ ] Bases de dados:
  - [ ] Menor privilégio por utilizador/serviço; registar *queries* críticas.

---

**VibeCoders Portugal**
