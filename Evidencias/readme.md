# Introdução
> Utilizamos o serviço DHCP do roteador para distribuir automaticamente os endereços IP aos dispositivos da rede. O roteador também forneceu a máscara de sub-rede e o gateway padrão, facilitando a configuração dos equipamentos e evitando conflitos de endereçamento entre os clientes DHCP.
>
> Os testes de conectividade foram realizados no Cisco Packet Tracer seguindo estas etapas:
>
> 1. No **PC1**, acessamos **Desktop → Command Prompt**.
>
> 2. Digitamos `ping 192.168.0.1` para verificar a comunicação com o roteador, responsável pelo gateway da rede.
>
> 3. Executamos `ping 192.168.0.100` para testar a comunicação com o **PC2**.
>
> 4. Executamos `ping 192.168.0.102` para testar a comunicação com o **PC3**.
>
> 5. Por fim, digitamos `ping 192.168.0.103` para verificar a comunicação com a **câmera de segurança**.
>
> Todos os testes apresentaram quatro pacotes enviados e quatro recebidos, com **0% de perda**, confirmando a comunicação 
> com os destinos testados. Como os endereços são atribuídos por DHCP, é necessário conferir os IPs atuais antes de >
> repetir os comandos.
