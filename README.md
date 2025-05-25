# 🧠 Resumo Geral: Serviços de Computação e Rede no Azure

Este material aborda os principais serviços de **computação e rede** da plataforma **Microsoft Azure**, com foco em suas **ofertas, funcionalidades e aplicações práticas**.

---

## 🖥️ Computação no Azure

O Azure oferece diferentes modelos de computação para atender a diversas necessidades, desde soluções com maior controle (como VMs) até plataformas totalmente gerenciadas (como Functions):

- **Máquinas Virtuais (VMs)**: Computadores virtuais completos com controle total. Ideal para aplicações legadas ou migração lift-and-shift.
- **Conjuntos de Dimensionamento**: Permite escalar automaticamente várias VMs com balanceamento de carga.
- **Conjuntos de Disponibilidade**: Garantem alta disponibilidade ao distribuir VMs entre domínios de falha e de atualização.
- **Área de Trabalho Virtual**: Fornece um ambiente de desktop virtual escalável e seguro baseado na nuvem.
- **Contêineres (ACI, AKS, App Containers)**: Oferecem ambientes leves e isolados para aplicações baseadas em microsserviços, com suporte a orquestração e escalabilidade.
- **Azure Functions**: Computação serverless orientada a eventos, onde o código é executado sob demanda sem gerenciamento de servidores.
- **Serviços de Aplicativo**: Plataforma gerenciada para construir e hospedar APIs e aplicações web com suporte a diversas linguagens (.NET, Node.js, Java, Python, PHP).

---

## 🌐 Rede no Azure

A conectividade segura e eficiente entre recursos é viabilizada por meio de uma variedade de serviços de rede:

- **Rede Virtual (VNet)**: Estrutura fundamental para comunicação entre recursos no Azure.
- **Pontos de Extremidade**: Públicos (acesso externo) e privados (acesso interno apenas).
- **Sub-redes e Emparelhamento de Redes**: Segmentam e conectam redes de forma segura.
- **Gateway de VPN**: Conexão criptografada entre Azure e redes locais via internet.
- **ExpressRoute**: Conexão privada de alta performance entre o Azure e a infraestrutura local.
- **DNS do Azure**: Gerenciamento de nomes de domínio confiável e seguro com suporte a nomes personalizados e registros de alias.

---
