# lab-medusa-kali-basic
Repositório estudante — laboratório básico: Kali + Metasploitable2 (força bruta FTP com Medusa)

# Laboratório Básico: Força Bruta FTP com Medusa
Aluno: Samuel Rodriguez
Alvo (Metasploitable2): 192.168.128.2

## Objetivo
Projeto simples para demonstrar conceito de força bruta em serviço FTP usando Medusa em ambiente controlado (Kali → Metasploitable2). 

## Pré-requisitos
- Virtualbox/UTM com duas VMs: Kali Linux (atacante) e Metasploitable2 (alvo).
- Rede: Host-only entre as VMs.

## Como usar
1. Coloque os arquivos deste repositório numa pasta no Kali.
2. Dê permissão de execução ao script:
```bash
chmod +x run_simple_ftp.sh
