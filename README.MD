# Zabbix Monitoramento - Infraestrutura

## Resumo do Projeto

Este projeto demonstra um ambiente de monitoramento robusto utilizando Zabbix, MySQL e Docker. O objetivo principal é fornecer uma solução escalável, fácil de implantar e gerenciar para o monitoramento de infraestruturas, permitindo a coleta e análise de dados em tempo real.  O projeto oferece uma base sólida para aprendizado e experimentação com o Zabbix.

## Estrutura do Projeto

O projeto é organizado em duas branches principais, cada uma destinada a um tipo específico de implantação:

*   **`infra-local`**: Contém a configuração para implantação local, ideal para desenvolvimento, testes e aprendizado.
*   **`oracle-cloud`**: Contém a configuração para implantação na Oracle Cloud (OCI).

## Implantação Local (Branch `infra-local`)

Se você deseja configurar o ambiente localmente para fins de aprendizado ou testes, siga as seguintes etapas:

1.  Clone a branch `infra-local`:
    ```bash
    git clone https://github.com/mizaelZuza/zabbix-monitoramento.git -b infra-local
    cd zabbix-monitoramento
    ```
2.  Siga as instruções de configuração detalhadas presentes no arquivo `README.md` dentro da branch `infra-local`.

## Implantação na Oracle Cloud (Branch `oracle-cloud`)

Se você pretende implantar o ambiente em um ambiente de nuvem, siga estas etapas:

1.  Clone a branch `oracle-cloud`:
    ```bash
    git clone https://github.com/mizaelZuza/zabbix-monitoramento.git -b oracle-cloud
    cd zabbix-monitoramento
    ```
2.  Consulte o arquivo `README.md` dentro da branch `oracle-cloud` para obter instruções específicas de configuração e deploy na nuvem OCI.


