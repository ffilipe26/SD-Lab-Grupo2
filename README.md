# SD-Lab-Grupo2

Laboratório de Sistemas Distribuídos – Comunicação entre Nós, Serviços e Investigação de Falhas  
Fatec Ferraz de Vasconcelos – Análise e Desenvolvimento de Sistemas

## Integrantes

| Nome completo | RA |
|---|---|
| Alecsander Torres | 2920482421030 |
| Filipe Acierno | 2920482421034 |
| Guilherme Souza | 2920482421020 |
| Michael Coutinho | 2920482421031 |
| Yago Nunes da Silva | 2920482421021 |

## Descrição da atividade

Montagem, no Cisco Packet Tracer, de um cluster didático com três nós (1 Manager e 2 Workers) ligados a um switch, mais um cliente de testes, na rede 192.168.10.0/24. Os workers oferecem o serviço HTTP (portal interno) e o Manager representa o papel de gerência.

Foram realizados testes de conectividade (ping), acesso aos serviços pelo navegador, observação dos protocolos ARP, ICMP, TCP e HTTP no Simulation Mode e testes de falha: queda do Worker-1, queda do Manager e, como teste extra, desativação das portas do switch.

## Vídeo da execução dos testes

https://youtu.be/YaCgVxN6itU

## Endereçamento

| Dispositivo | Função | IP |
|---|---|---|
| Manager | Gerência (conceitual) | 192.168.10.10 |
| Worker-1 | Serviço HTTP | 192.168.10.11 |
| Worker-2 | Serviço HTTP | 192.168.10.12 |
| Cliente-01 | Cliente de testes | 192.168.10.100 |

Máscara: 255.255.255.0 (/24), sem gateway.

## Conteúdo do repositório

- `SD_Lab_Grupo2.pkt` – arquivo do Packet Tracer com a topologia final funcionando
- `Relatorio_SD_Grupo2.pdf` – relatório técnico
- `evidencias/` – capturas de tela E1 a E13

