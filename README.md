🛡️ Vaultwarden Zero Trust: Gestão de Credenciais Segura

Este projeto apresenta a implementação de um cofre de senhas corporativo utilizando Vaultwarden, operando sob uma rede Zero Trust via Tailscale. O objetivo é eliminar o compartilhamento inseguro de senhas e garantir a custódia dos dados sensíveis pela TI.🚀 

Diferenciais da Arquitetura
Superfície de Ataque Zero: O servidor não possui portas expostas para a internet pública.
Conectividade Privada: Acesso restrito a dispositivos autorizados via malha VPN WireGuard (Tailscale).
Governança Corporativa: Implementação da política "Cofre Pessoal Zero", garantindo que as senhas da empresa pertençam à empresa.

🛠️ Tecnologias Utilizadas
 Vaultwarden: Servidor compatível com Bitwarden em Rust (leve e seguro).
 Tailscale: Orquestração de rede Zero Trust.
 Docker & Docker Compose: Containerização e facilidade de deploy.
 Ubuntu Server: Sistema operacional base.

📊 Funcionalidades Implementadas
 Segmentação por Departamentos: Criação de coleções para DP, RH, Financeiro e Instrumentação.
 Controle de Acesso (RBAC): Permissões granulares por usuário e grupo.
 HTTPS Automático: Criptografia de ponta a ponta garantida pelo provedor de rede.
 Painel de Auditoria: Rastreabilidade de acessos e modificações.
