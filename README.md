# Linux

## Por que é importante entender alguns conceitos de Linux para aprender Docker?

Aprender Docker e conceitos sobre Linux estão fortemente interligados por várias razões. Aqui estão os principais motivos pelos quais entender Linux pode ser crucial para trabalhar eficientemente com Docker:

### 1. Ambiente Baseado em Linux

Docker usa o kernel do Linux para criar e gerenciar containers. Portanto, muitos dos comandos e conceitos usados no Docker são derivados do Linux.

### 2. Sistema de Arquivos

Docker containers são construídos em cima de sistemas de arquivos Linux, como o OverlayFS. Conhecer o funcionamento desses sistemas pode ajudar a entender como os containers gerenciam arquivos e diretórios.

### 3. Permissões e Usuários
   
Linux possui um sistema robusto de permissões e gerenciamento de usuários. Entender esses conceitos é importante, especialmente ao configurar containers com diferentes níveis de acesso e ao garantir a segurança do ambiente.

### 4. Rede e Networking
   
O Docker cria redes virtuais para os containers e manipula interfaces de rede Linux para isso. Conhecer os fundamentos de redes no Linux, como interfaces de rede, roteamento, e iptables, é essencial para configurar corretamente a comunicação entre containers e entre containers e o mundo externo.

### 5. Gerenciamento de Processos

Cada container Docker é essencialmente um processo isolado rodando no Linux. Conhecer como o Linux gerencia processos (usando comandos como ps, top, kill) pode ajudar a monitorar e solucionar problemas nos containers.

### 6. Comandos Básicos do Linux
   
Muitos comandos básicos usados para interagir com containers, como ls, cd, cp, mv, chmod, chown, e muitos outros, são comandos Linux. Familiaridade com esses comandos é essencial para manipular arquivos e diretórios dentro dos containers.

### 7. Scripts e Automação
   
Scripts shell (bash, sh, etc.) são frequentemente usados para automatizar tarefas no Docker, como construir e configurar containers. Conhecimento em scripting no Linux pode aumentar significativamente a eficiência na criação e gestão de ambientes Docker.

### 8. Resolução de Problemas
   
Muitos problemas que surgem ao usar Docker podem estar relacionados a configurações do sistema operacional subjacente. Conhecimento em Linux permite identificar e resolver esses problemas de forma mais eficaz.

## Exemplo Prático
- Volumes: Docker utiliza volumes para persistência de dados. Saber como funcionam os sistemas de arquivos no Linux pode ajudar a entender melhor onde e como esses volumes são armazenados.
- Rede: Configurar um container para expor portas ou se conectar a outras redes pode exigir comandos e conceitos de rede do Linux.

### Conclusão

Embora não seja estritamente necessário ser um especialista em Linux para começar a usar Docker, ter um conhecimento básico do sistema operacional subjacente é extremamente benéfico. Isso pode facilitar a resolução de problemas, a otimização de configurações e a automação de tarefas, tornando o uso do Docker mais eficaz e menos frustrante.

## Linux quais são suas principais distribuições?


Linux é um sistema operacional de código aberto que possui várias distribuições (ou "distros") adaptadas para diferentes necessidades e preferências. Aqui estão algumas das principais distribuições de Linux:

### 1. Ubuntu:

- Descrição: Uma das distribuições mais populares, especialmente entre iniciantes. É conhecida por sua facilidade de uso e grande suporte da comunidade.
- Base: Debian
- Ambiente de Desktop: GNOME (padrão), mas também possui variantes como Kubuntu (KDE), Xubuntu (XFCE), e Lubuntu (LXQt).

### 2. Debian:

- Descrição: Uma distribuição muito estável e respeitada, conhecida por sua robustez e políticas de software livre.
- Base: Nativa
- Ambiente de Desktop: Diversos (GNOME, KDE, XFCE, LXDE, etc.).

### 3. Fedora:

- Descrição: Focado em oferecer as últimas inovações em software livre. Usado frequentemente por desenvolvedores e para testes de novas tecnologias.
- Base: Red Hat
- Ambiente de Desktop: GNOME (padrão), mas possui spins com KDE, XFCE, LXQt, e outros.

### 4. CentOS/Rocky Linux/AlmaLinux:

- Descrição: Distribuições derivadas do código-fonte do Red Hat Enterprise Linux (RHEL), fornecendo uma alternativa gratuita com foco em estabilidade e suporte de longo prazo.
- Base: Red Hat
- Ambiente de Desktop: Diversos (geralmente usado mais em servidores sem ambiente gráfico).

### 5. openSUSE:

- Descrição: Conhecida por sua ferramenta de administração YaST, oferece versões estáveis (Leap) e de ponta (Tumbleweed).
- Base: SUSE
- Ambiente de Desktop: KDE (padrão), GNOME, e outros.

Cada distribuição tem suas particularidades, com diferentes níveis de suporte, foco em diferentes tipos de usuários (de iniciantes a avançados), e variações no ambiente de desktop e pacotes de software incluídos. A escolha da distribuição ideal depende das necessidades específicas do usuário e do ambiente em que será utilizada.

## Praticando alguns comandos do Linux

- Para isso vamos utilizar uma imagem do hub docker com linux
- Acessar hub.docker.com / ubuntu

  
https://github.com/JosiTubaroski/Linux/blob/main/Ubuntu/ubuntu.png

