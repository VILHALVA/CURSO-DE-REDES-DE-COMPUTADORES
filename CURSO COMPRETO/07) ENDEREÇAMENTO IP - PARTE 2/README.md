# ENDEREÇAMENTO IP (PARTE 2)
**IPs Restritos e Privados:**

- **IPs Restritos:** Alguns endereços IP são reservados para fins especiais e não podem ser usados na Internet pública. Por exemplo, o endereço IP 127.0.0.1 é reservado para a interface de loopback, usado para testar a conectividade de rede local. Outro exemplo é o endereço IP 0.0.0.0, que é usado para representar uma rede desconhecida ou indefinida.

- **IPs Privados:** Os endereços IP privados são reservados para uso em redes locais, como intranets, e não são roteados na Internet pública. As faixas de endereços IP privados mais comuns incluem:
   - Faixa Classe A Privada: 10.0.0.0 a 10.255.255.255
   - Faixa Classe B Privada: 172.16.0.0 a 172.31.255.255
   - Faixa Classe C Privada: 192.168.0.0 a 192.168.255.255

**CIDR (Classless Inter-Domain Routing):**

- CIDR é um sistema de notação que permite uma representação mais flexível do espaço de endereçamento IP. Em vez de depender das classes tradicionais (A, B, C, etc.), o CIDR permite a definição de prefixos de sub-rede mais precisos, usando uma notação como "192.168.1.0/24", onde "/24" especifica o número de bits para a parte da rede.

**APIPA (Automatic Private IP Addressing):**

- A APIPA é um recurso em sistemas operacionais que permite a atribuição automática de endereços IP quando um dispositivo não pode obter um endereço IP de um servidor DHCP (Dynamic Host Configuration Protocol). Esses endereços APIPA são geralmente da faixa 169.254.0.0 a 169.254.255.255.

**Distribuição de IPs:**

- Os endereços IP são distribuídos por várias organizações, como a Internet Assigned Numbers Authority (IANA) e os Registros Regionais da Internet (RIRs). Os RIRs distribuem blocos de endereços IP para ISPs (Provedores de Serviços de Internet) e outras organizações, que, por sua vez, distribuem os endereços para seus clientes e redes locais.

**Máscaras de Sub-rede:**

- As máscaras de sub-rede são usadas para determinar quais bits de um endereço IP pertencem à parte da rede e quais pertencem à parte do host. Elas são representadas por uma sequência de bits "1" seguidos por uma sequência de bits "0". Por exemplo, a máscara de sub-rede "255.255.255.0" (ou "/24" em notação CIDR) significa que os primeiros 24 bits do endereço IP são dedicados à parte da rede, e os últimos 8 bits são para identificar dispositivos na rede.

**Diferença entre Rede, Host e Broadcast:**

- **Rede:** É o endereço da rede, que identifica a própria rede. Os dispositivos com o mesmo endereço de rede estão na mesma rede e podem se comunicar diretamente.

- **Host:** É o endereço usado para identificar dispositivos específicos em uma rede. A parte do host varia de um dispositivo para outro, permitindo a diferenciação entre eles na mesma rede.

- **Broadcast:** É um endereço especial usado para enviar dados para todos os dispositivos na mesma rede. Por exemplo, o endereço de broadcast em uma rede com máscara "/24" seria o último endereço disponível, como "192.168.1.255". Quando os dados são enviados para esse endereço, todos os dispositivos na rede o recebem.

Esses conceitos são fundamentais para a compreensão e configuração de redes de computadores, pois ajudam a organizar e identificar dispositivos em uma rede e a rotear o tráfego de maneira eficiente.