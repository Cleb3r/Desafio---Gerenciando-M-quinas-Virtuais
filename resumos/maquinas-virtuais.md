# Máquinas Virtuais (VMs) no Azure
As máquinas virtuais (VMs) no Azure são um dos recursos mais populares da plataforma. Elas permitem que você execute sistemas operacionais e aplicativos em uma infraestrutura totalmente gerenciada, escalável e altamente disponível.

## Principais Conceitos
* Provisionamento sob demanda: Você pode criar VMs rapidamente usando o portal Azure, linha de comando (CLI), ou templates de automação.

* Imagens de SO: Azure oferece imagens pré-configuradas de Windows, Linux, além de permitir a criação de imagens personalizadas.

* Tamanhos e tipos de VM: Variam conforme a necessidade — desde instâncias básicas para testes até máquinas otimizadas para processamento gráfico ou banco de dados.

## Casos de uso comuns
* Ambientes de desenvolvimento e teste

* Execução de aplicações legadas

* Hospedagem de sites e APIs

* Processamento de dados e workloads intensivos

## Componentes Essenciais
* Disco do sistema operacional (geralmente SSD gerenciado)

* Discos de dados adicionais (opcional)

* Grupos de segurança de rede (NSG) para controle de tráfego

* Endereço IP público ou privado conforme necessidade

## Dicas práticas
* Sempre utilize etiquetas (tags) para organização e controle de custos.

* Habilite a autenticação baseada em chave SSH para VMs Linux.

* Use Auto-shutdown para evitar custos com VMs ociosas.

* Faça snapshots periódicos para backup rápido.
