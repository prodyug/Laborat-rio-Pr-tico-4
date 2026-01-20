# Laboratório Prático 4 – Protegendo o Acesso Remoto com SSH

**Aluno:** Hugo de Lima Santos  
**Professor:** Cefras Mandú  

---

## Objetivo
Instalar e configurar o serviço OpenSSH no Ubuntu Server, realizar acesso remoto inicial e aplicar configurações básicas de segurança no servidor.

---

## Atividades Executadas

### Instalação do OpenSSH Server

sudo apt-get update
sudo apt-get install openssh-server

1) Verificação do serviço:

<img width="967" height="498" alt="Screenshot from 2026-01-20 03-14-51" src="https://github.com/user-attachments/assets/2754bd58-f07d-42b4-9918-9cf8a5b24aa3" />

2) Acesso Inicial via SSH

Confirmação da autenticidade do host
Autenticação com senha do usuário

<img width="953" height="546" alt="Screenshot from 2026-01-20 03-27-16" src="https://github.com/user-attachments/assets/cac9e020-6f47-4c2c-8ba4-ef56ab33936c" />
<img width="954" height="305" alt="Screenshot from 2026-01-20 03-27-32" src="https://github.com/user-attachments/assets/36bb5e01-41aa-404b-9bb5-e3e640040e26" />

3) Backup do Arquivo de Configuração

<img width="935" height="338" alt="Screenshot from 2026-01-20 03-29-30" src="https://github.com/user-attachments/assets/74a52094-be80-433c-879f-3341634b4244" />

4) Configuração de Segurança do SSH

Alterações realizadas:

Porta padrão alterada para 2244

<img width="944" height="559" alt="Screenshot from 2026-01-20 03-30-34" src="https://github.com/user-attachments/assets/1c738a5c-67ef-4595-9df7-1fd80adf243c" />

Login do usuário root desabilitado

<img width="944" height="559" alt="Screenshot from 2026-01-20 03-31-28" src="https://github.com/user-attachments/assets/573ce75b-120b-459e-9fee-3a80d259ff20" />

5) Reinicialização do Serviço SSH

<img width="921" height="111" alt="Screenshot from 2026-01-20 03-33-28" src="https://github.com/user-attachments/assets/ab19ae36-b2e6-4fdf-b7e7-cde7de329009" />

6) Teste de Acesso na Nova Porta

<img width="890" height="151" alt="Screenshot from 2026-01-20 03-34-40" src="https://github.com/user-attachments/assets/387e72f2-d7d3-4ec3-831d-93d2879296ea" />

7) Teste de Acesso na Nova Porta
   
<img width="904" height="185" alt="Screenshot from 2026-01-20 03-35-25" src="https://github.com/user-attachments/assets/b645a13e-d3ab-4935-b954-05ed96e5da39" />


