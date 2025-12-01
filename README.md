# bruteforce
Projeto de Simulação de Ataques de Força Bruta
1. Visão Geral do Projeto
Este projeto demonstra, em ambiente controlado, técnicas de força bruta, password spraying e
automação de tentativas utilizando Kali Linux, Medusa, Metasploitable 2 e DVWA.
2. Arquitetura do Ambiente
- Kali Linux como atacante
- Metasploitable 2 como alvo vulnerável
- DVWA (Damn Vulnerable Web Application)
- VirtualBox com rede Host-Only
3. Configuração do Ambiente
Ambas as VMs configuradas com adaptador Host-Only, permitindo comunicação isolada e segura.
4. Ferramentas Utilizadas
- Medusa (ataques de força bruta)
- DVWA (plataforma web vulnerável)
- Nmap (mapeamento de portas e serviços)
- Wordlists simples criadas manualmente
5. Testes Realizados
Força Bruta em FTP: Compreensão do comportamento do serviço frente a tentativas repetidas.
Ataques Web no DVWA: Testes de brute force em formulários web conforme níveis de segurança.
Password Spraying em SMB: Simulação do impacto de senhas fracas e políticas de autenticação.
6. Wordlists
Wordlists pequenas foram criadas apenas para fins educacionais, demonstrando como o tamanho
influencia o tempo dos ataques.
7. Medidas de Mitigação
- Políticas de senha forte
- MFA
- Captcha em formulários
- Limite de tentativas de login
- Hardening de serviços (desativar FTP/SMB inseguros)
- Monitoramento e análise de logs
8. Conclusão
O projeto proporcionou entendimento prático sobre técnicas ofensivas e, principalmente, sobre como
preveni-las em ambientes reais.
