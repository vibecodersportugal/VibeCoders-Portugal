# 5. Configuração Segura de Infraestrutura

- [ ] *Hardening* do SO: desativar serviços/módulos desnecessários; permissões corretas; partições `/var`, `/tmp`, `/home` com `noexec`, `nosuid`, `nodev`.  
- [ ] Firewalls: regras explícitas entrada/saída; só tráfego essencial; portas não usadas bloqueadas.  
- [ ] Acessos administrativos:
  - [ ] SSH por chaves, não por password; IPs autorizados; MFA em contas privilegiadas.
- [ ] Serviços expostos sempre autenticados; *admin APIs* apenas em redes privadas.  
- [ ] Isolar *dev/test/prod*; nunca usar dados reais em teste.  
- [ ] IaC:
  - [ ] Repositórios privados; *security review* antes de *deploy*; Checkov/Terrascan.
- [ ] Segmentação de rede entre app/DB/admin; mínimo de comunicações.  
- [ ] Containers:
  - [ ] Imagens oficiais/assinadas; *rootless*; *vulnerability scan* antes de publicar.
- [ ] Cloud:
  - [ ] Sem endpoints públicos desnecessários; permissões restritas em *buckets*; cifra em trânsito/repouso.
- [ ] Monitorização de configuração/integridade: OSSEC/Wazuh/Tripwire; alertas imediatos.  
- [ ] *Patching* regular; testes antes de produção.

---

**VibeCoders Portugal**
