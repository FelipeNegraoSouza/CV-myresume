# Felipe Negrão Souza

**Desenvolvedor Backend & DevOps**  
Aparecida do Taboado - MS | [felipe.ngsouza@gmail.com](mailto:felipe.ngsouza@gmail.com) | (67) 98111-351  
[LinkedIn](https://www.linkedin.com/in/felipenegraosouza) | [GitHub](https://github.com/FelipeNegraoSouza)

---

## 🚀 Resumo Profissional

Desenvolvedor Backend focado em escrita de código limpo, sustentável e de alta performance. Domínio em desenvolvimento de APIs assíncronas com Python (FastAPI, SQLAlchemy), processamento e manipulação de fluxos de dados com Pandas e integrações de sistemas. Prática e estudos contínuos focados em ecossistema DevOps, infraestrutura sob Linux, conteinerização (Docker), orquestração leve (K3s), IaC (Terraform) e Go (Golang) para arquitetura de microsserviços e sistemas distribuídos.

---

## 🛠️ Competências Técnicas

- **Linguagens:** Python, Go (Golang), SQL, TypeScript
- **Backend & Frameworks:** FastAPI, SQLAlchemy, Pydantic, REST APIs, Monolito Modular
- **Dados & Telemetria:** Pandas, Tratamento e Transformação de Dados, Mapeamento ORM
- **DevOps, Infraestrutura & Redes:** Linux (Arch/Void), Docker, K3s (Kubernetes), Terraform (IaC), Fundamentos de Redes
- **Ferramentas & Metodologias:** Git/GitHub, Zellij, Neovim/VS Code, Modelagem de Banco de Dados Relacional

---

## 🏗️ Projetos de Engenharia & Arquitetura

### Estudo de Caso: Arquitetura de Monolito Modular e Ingestão de Telemetria
*GitHub: [Repositorio em estruturação com estudo de caso real seguindo a LGPD]*

- Blueprint de arquitetura focado em ingestão, tratamento e processamento de dados industriais em tempo real.
- Concepção de APIs REST assíncronas com **FastAPI** e **Pydantic v2** para validação estrita de dados na camada de borda.
- Modelagem de camada de persistência com **SQLAlchemy 2.0 (Async)** e integração com ERP (TOTVS) como fonte da verdade.
- Aplicação de rotinas de análise e agregação de telemetria/métricas operacionais utilizando **Pandas**.
- Padronização de governança de código, versionamento com Git/GitHub e conteinerização completa da aplicação via **Docker Compose**.

### Homelab & Infraestrutura Cloud-Native
*GitHub: [github.com/FelipeNegraoSouza/HomelabServer-AcerE5](https://github.com/FelipeNegraoSouza/HomelabServer-AcerE5)*

#### 📌 Visão Geral & Filosofia
- **Objetivo:** Construir um servidor residencial autônomo, seguro e de baixo consumo para hospedar serviços, automações, projetos pessoais, e armazenamento.
- **Filosofia:** Priorizar **manual mastery, system autonomy e privacidade** (zero telemetria desnecessária, sem camadas de virtualização pesadas).
- **Hardware Servidor:** Acer E5 (Intel Core i5 de 5ª geração, 4GB de RAM, HDD 1TB).
- **Stack Tecnológica Base:** Debian Server (Headless), Docker, Tailscale, Go, Git, Terraform, K3s (Kubernetes), Jellyfin e File Browser.

#### ⚙️ Execução Técnica
- **Instalação e Configuração Minimalista:** Instalação limpa do **Debian Server** (*netinst*) via CLI em hardware dedicado (Core i5 5ª gen, 4GB RAM) com reserva de IP fixo na rede local.
- **Ajustes de Kernel & Hardening:** Parametrização do `systemd-logind` para operação contínua *headless* com tampa fechada, regras de firewall com **UFW** e hardening de acesso **SSH**.
- **Rede Privada Mesh:** Configuração e autenticação do **Tailscale** para gerenciamento de acesso remoto criptografado via VPN mesh sem exposição de portas públicas.
- **Runtime Docker & Persistência:** Instalação da engine do **Docker** e **Docker Compose**, estruturando o padrão de volumes e ambientes isolados em `/opt/services`.
- **Implantação de Serviços & Mídia:** Deployment e orquestração de ecossistema de mídias e gestão de arquivos utilizando **Jellyfin** e **File Browser**, incluindo configuração de montagem de volumes e permissões de escrita/leitura no sistema de arquivos local.
- **Manutenção Contínua & Lifecycle:** Gestão do ciclo de vida dos serviços, automação de backups de configurações, monitoramento de saúde do sistema e atualizações contínuas de containers e do SO.

---

## 🎓 Formação Acadêmica

- **Bacharelado em Sistemas de Informação**  
  Universidade Federal de Mato Grosso do Sul (UFMS) | *Em andamento*
