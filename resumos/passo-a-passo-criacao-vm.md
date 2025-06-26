# 🚀 Passo a Passo: Criar uma Máquina Virtual no Portal Azure
Este guia prático mostra como criar uma máquina virtual (VM) usando o portal do Azure com uma interface gráfica fácil de navegar.

## 1. Acessar o Portal Azure
  1. Vá até <https://portal.azure.com>

  2. Faça login com sua conta Microsoft

## 2. Criar uma nova VM
  1. No menu lateral, clique em **"Máquinas Virtuais"**

  2. Clique em **"Criar" > "Máquina Virtual"**


## 3. Preencher informações básicas
  * **Assinatura:** Selecione sua assinatura Azure ativa

  * **Grupo de Recursos:** Crie um novo ou escolha um existente

  * **Nome da VM:** Ex: minhaVM-teste

  * **Região:** Escolha a mais próxima para menor latência

  * **Imagem:** Escolha o sistema operacional (ex: Windows Server 2022)

  * **Tamanho:** Selecione uma opção baseada em seu orçamento e uso

## 4. Configurações de Acesso
  * Crie um **nome de usuário e senha** (para Windows) ou chave SSH (Linux)

  * Permita as portas necessárias, como **RDP (3389)** para Windows ou **SSH (22)** para Linux

## 5. Disco e Rede
  * Escolha disco SSD padrão (custo-benefício) ou premium

  * Aceite as configurações padrão de rede virtual e endereço IP

## 6. Revisar e Criar
  * Clique em **"Revisar + Criar"**

  * Após a validação, clique em **"Criar"**

  * Aguarde a implantação finalizar

## 7. Conectar-se à VM
  * Vá para a VM implantada no portal

  * Clique em **"Conectar"**

  * Siga as instruções (Área de Trabalho Remota para Windows, SSH para Linux)
