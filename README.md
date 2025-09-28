# resumo-do-lab

Computação em nuvem é a entrega de serviços de computação (como servidores, armazenamento e bancos de dados) pela internet, sem precisar instalar nada fisicamente. Em vez de manter tudo em um computador local, você acessa recursos online, de forma escalável e sob demanda — pagando apenas pelo que usa. A plataforma de nuvem da Microsoft, oferece uma interface inicial intuitiva, onde você pode gerenciar todos os seus recursos. No painel principal, você encontra atalhos para criar serviços, visualizar gastos, acessar máquinas virtuais, bancos de dados e acompanhar o status geral da sua infraestrutura em tempo real.


2-Desafio 

Como faz — passos principais

- Acessar o Portal do Azure 
- Ir pra “Máquinas virtuais” → Criar uma nova máquina virtual 
- Preencher os dados básicos da VM, como:
- Nome da VM (ex: “myVM”) 
- Escolher imagem: Windows Server 2022 Datacenter Gen‑2 
- Nome de usuário administrador + senha (com requisitos de segurança) 
- Configurar portas de entrada (network): liberar RDP (porta 3389) para acesso remoto e HTTP (porta 80) se quiser hospedar serviço web. 
- Revisar e criar (“Examinar + criar” → “Criar”)

SLA (Acordo de Nível de Serviço) é o compromisso da Microsoft com a disponibilidade e confiabilidade dos serviços do Azure.
Ele define o tempo mínimo garantido que um serviço ficará no ar (sem falhas) em determinado período.

Por exemplo:
Uma VM no Azure com alta disponibilidade (usando zonas ou conjuntos de disponibilidade) pode ter um SLA de 99,99%.
Isso significa que, em teoria, o serviço pode ficar fora do ar por menos de 5 minutos por mês.
Se a Microsoft não cumprir esse SLA, você pode solicitar créditos financeiros na fatura.

Armazenamento no Azure

O Azure Storage é um conjunto de serviços de armazenamento em nuvem seguro, escalável e durável, usado para armazenar diferentes tipos de dados e atender a diferentes necessidades de aplicações.
Tipos de Armazenamento:
- Blobs (Binary Large Objects)

Armazenamento de arquivos não estruturados: imagens, vídeos, documentos.
Tipos: Block Blob, Append Blob e Page Blob.
Files (Azure File Storage)

Compartilhamento de arquivos via SMB ou NFS, acessível como um disco de rede.
Queues (Filas)

Armazenamento de mensagens para comunicação assíncrona entre aplicativos.
Tables (Tabelas)

Banco de dados NoSQL para dados estruturados e semi-estruturados, leve e rápido.
Disks (Discos)

Armazenamento de discos para máquinas virtuais (VHDs).
Principais Características

Escalabilidade: cresce conforme a demanda sem precisar de hardware físico.
Durabilidade: dados replicados local ou geograficamente para alta disponibilidade.
Segurança: criptografia automática e controle de acesso via Azure AD e RBAC.
Acessibilidade: via REST APIs, SDKs ou portal do Azure.
