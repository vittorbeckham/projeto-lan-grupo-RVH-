# Projeto LAN  - Bragato Mix

## Redes de Computadores Trabalho 2
> curso de Análise e Desenvolvimento de Sistemas.
## Introdução 
> Para o desenvolvimento desta atividade, utilizamos como referência um estabelecimento comercial real, o **Bragato Mix**, adaptando sua infraestrutura para uma representação no Cisco Packet Tracer. O projeto tem como objetivo demonstrar a organização da rede local e a conexão dos equipamentos utilizados nas atividades do comércio e no monitoramento de segurança.
>
> A infraestrutura considerada é composta por **1 roteador, 1 switch principal, 3 computadores, 3 impressoras, 20 câmeras de segurança, 1 repetidor e 2 gravadores DVR**. O roteador atua como gateway da rede e fornece endereços IPv4 automaticamente aos dispositivos configurados como clientes DHCP. O switch principal interliga os equipamentos cabeados, enquanto o repetidor amplia a cobertura da rede sem fio. Os computadores atendem às atividades operacionais do estabelecimento, e as impressoras dão suporte à impressão de documentos utilizados na rotina comercial.
>
> As 20 câmeras são destinadas ao monitoramento do estabelecimento, com as imagens encaminhadas aos dois DVRs responsáveis pela gravação no cenário real. Na topologia elaborada no Cisco Packet Tracer, **foram utilizados dois switches adicionais para representar visualmente esses gravadores**. Essa adaptação permite ilustrar a organização das conexões das câmeras, mas não reproduz as funções de gravação e armazenamento de vídeo de um DVR.
>
> Assim, a simulação contém três switches: um utilizado na distribuição da rede e dois empregados na representação dos gravadores. A validação da conectividade foi realizada por meio de testes de ping do PC1 para o gateway, o PC2, o PC3 e uma câmera de segurança. Os quatro destinos responderam sem perda de pacotes, demonstrando a comunicação IP entre os equipamentos testados.
## Integrantes:
> *Rai Gil Pedrosa*
> 
> *José Vitor Santos da Silva*
> 
> *Henry Gabriel Lopes Leda*
> 
> *Hiago Gabriel de Oliveira Ferreira*
### como abrir e testar
> * 1.Abrir uma versão compatível do Cisco Packet Tracer.
> 
> * 2.Selecionar File > Open e abrir projeto-lan.pkt.
> 
> * 3.Aguardar a inicialização dos enlaces.
> 
> * 4.No PC1, acessar Desktop > IP Configuration e conferir DHCP, IPv4, máscara e gateway.
> 
> * 5.Conferir os IPs atuais dos destinos, pois o DHCP pode atribuir outros endereços.
> 
> * 6.Abrir Desktop > Command Prompt e executar ipconfig
> 
> * 7.Executar o ping ao gateway e aos IPs atuais de PC2, PC3 e câmera.
> 
