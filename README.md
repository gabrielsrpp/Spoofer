# Spoofer

# 🌀 Insane Spoofer

**Insane Spoofer** é uma ferramenta desenvolvida para fins educacionais e experimentais, com foco em anonimização e mascaramento de identificadores de hardware (HWID). Ideal para testes de segurança, análise de fingerprinting e desenvolvimento de sistemas com base em autenticação por hardware.

---

## 🖼️ Interface

![Interface do Spoofer](<img width="564" height="406" alt="image" src="https://github.com/user-attachments/assets/49e93762-cd51-417a-a6da-86bbf8b076d4" />
)

---

## ⚙️ Funcionalidades

### 🔹 HWID Spoofer  
Altera identificadores como Machine GUID, SMBIOS, Volume ID, entre outros.  
Esses dados são amplamente utilizados para autenticação e rastreamento por softwares.

### 🔹 EFI Spoofer  
Modifica informações do firmware UEFI/BIOS, simulando outra placa ou fabricante.  
Importante para burlar verificações em baixo nível.

### 🔹 Reset TPM  
Efetua a reinicialização do Trusted Platform Module, limpando chaves associadas ao dispositivo.  
Útil para desfazer vínculos criptográficos com o hardware original.

### 🔹 New MAC  
Gera um novo endereço MAC aleatório para a interface de rede.  
Evita rastreamento por rede física.

### 🔹 Kernel Mode (VIP)  
Ativa modo avançado com permissões em nível de kernel.  
Permite spoofing profundo, com acesso a áreas protegidas do sistema.

---

## 🔘 Ações do Sistema

- **Instalar Warp**  
  Instalação do WARP (Cloudflare) para roteamento seguro e proteção de IP.

- **Verificar Sistema**  
  Analisa o sistema atual para validar compatibilidade com o spoofing.

- **Spoof Sistema**  
  Executa o processo completo com base nas opções ativadas.  
  > ⚠️ **Reinicie o computador após o spoofing para aplicar todas as alterações.**

---

## 🧠 Observações Importantes

- O software não está disponível publicamente nem possui código-fonte aberto.
- Este repositório é apenas para fins de documentação e portfólio.
- O uso indevido é de responsabilidade do usuário.

---

## 📝 Licença

Este repositório está licenciado sob a [Creative Commons BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).

