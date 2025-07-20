# Monitoramento de infraestrutura com Zabbix

---

## Resumo do projeto

Este projeto demonstra um ambiente de monitoramento robusto utilizando Zabbix, MySQL e Docker. O objetivo principal é fornecer uma solução escalável, fácil de implantar e gerenciar, para o monitoramento de infraestruturas, permitindo a coleta e análise de dados em tempo real.  
O projeto oferece uma base sólida para aprendizado e experimentação com o Zabbix.

---

## Estrutura do projeto

O projeto é organizado em duas branches principais, cada uma destinada a um tipo específico de implantação:

*   **`infra-local`**: Contém a configuração para implantação local, ideal para desenvolvimento, testes e aprendizado. No `README.md` desta branch `infra-local` temos exemplos de cadastro e monitoramento por icmp de 3 hosts Google, Github e Cloudflare.
---

*   **`oracle-cloud`**: Contém a configuração para implantação na Oracle Cloud (OCI). No `README.md` desta branch `oracle-cloud` temos exemplos de cadastro e monitoramento por icmp de 3 hosts Google, Github e Cloudflare, além de monitoramento por zabbix agent de um host Linux, o host que hospeda os containeres Docker.

---

## Implantação local (Branch `infra-local`)

Se você deseja configurar o ambiente localmente para fins de aprendizado ou testes, siga as seguintes etapas:

1.  Clone a branch `infra-local`:
    ```bash
    git clone https://github.com/mizaelZuza/zabbix-monitoramento.git -b infra-local
    cd zabbix-monitoramento
    ```
2.  Siga as instruções de configuração detalhadas presentes no arquivo `README.md` dentro da branch `infra-local`.

**Pré-requisitos:**

*   Docker instalado e em execução.
*   Conhecimento básico de linha de comando.

## Implantação na Oracle cloud (Branch `oracle-cloud`)

Se você pretende implantar o ambiente em um ambiente de nuvem, siga estas etapas:

1.  Clone a branch `oracle-cloud`:
    ```bash
    git clone https://github.com/mizaelZuza/zabbix-monitoramento.git -b oracle-cloud
    cd zabbix-monitoramento
    ```
2.  Consulte o arquivo `README.md` dentro da branch `oracle-cloud` para obter instruções específicas de configuração e deploy na Oracle cloud OCI.

**Pré-requisitos:**

*   Conta Oracle Cloud Infrastructure (OCI) ativa com acesso à criação de recursos.
*   Conhecimento básico de rede e segurança na OCI.
*   VM Linux na OCI com Docker e Docker composeinstalado e em execução.

---

## Recursos úteis

*   **Documentação zabbix:** [https://www.zabbix.com/documentation](https://www.zabbix.com/documentation)
*   **Documentação Oracle cloud infrastructure (OCI):** [https://docs.oracle.com/](https://docs.oracle.com/)
*   **Documentação Docker:** [https://docs.docker.com/](https://docs.docker.com/)

---