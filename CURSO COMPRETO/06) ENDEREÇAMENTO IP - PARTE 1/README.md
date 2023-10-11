# ENDEREÇAMENTO IP (PARTE 1)
## CONCEITO:
**O que é um Número IP:**
- Um endereço IP (Internet Protocol) é um número exclusivo atribuído a cada dispositivo em uma rede para identificá-lo e permitir a comunicação. Os dispositivos usam endereços IP para rotear dados pela rede e saber para onde enviá-los.

**Classes de Endereços IP:**
- Os endereços IP são divididos em classes para alocar diferentes faixas de valores a redes de tamanhos variados. As classes mais comuns são:
   - **Classe A:** Começa com um número entre 1 e 126. Exemplo: 10.0.0.1. Usada para redes muito grandes.
   - **Classe B:** Começa com um número entre 128 e 191. Exemplo: 172.16.0.1. Usada para redes de tamanho médio.
   - **Classe C:** Começa com um número entre 192 e 223. Exemplo: 192.168.1.1. Usada para redes pequenas.
   - **Classe D:** Começa com um número entre 224 e 239. Reservada para multicasting.
   - **Classe E:** Começa com um número entre 240 e 255. Reservada para uso futuro e pesquisa.

**Faixas de Valores para Classes de Endereços IP:**
- Cada classe de endereço IP tem faixas específicas de valores. Aqui estão as faixas de valores típicas para as classes A, B e C:
   - Classe A: 1.0.0.0 a 126.255.255.255
   - Classe B: 128.0.0.0 a 191.255.255.255
   - Classe C: 192.0.0.0 a 223.255.255.255

**Descobrindo Seu Endereço IP:**
- Para descobrir qual é o seu endereço IP, você pode usar comandos específicos do sistema operacional ou visitar um site de verificação de IP. Aqui estão algumas maneiras de fazê-lo:
   - No Windows: Abra o Prompt de Comando e digite "ipconfig" e procure pelo endereço IPv4 na saída.
   - No macOS: Abra o Terminal e digite "ifconfig" ou "ipconfig getifaddr en0" para encontrar o endereço IP da interface de rede en0.
   - Em sistemas Unix/Linux: Use o comando "ifconfig" ou "ip a" para listar as informações da interface de rede.
   - Você também pode visitar um site como "https://www.whatismyip.com/" em um navegador para verificar seu endereço IP público.

O endereçamento IP é essencial para a comunicação na Internet e em redes locais, permitindo que os dispositivos se identifiquem e se comuniquem entre si de maneira eficiente. O entendimento das classes de endereços IP e a capacidade de encontrar o seu próprio IP são habilidades importantes para quem trabalha com redes e tecnologia da informação.

## IP É BINÁRIO:
O endereço IP, que é uma parte fundamental do Protocolo da Internet (IP), é representado em sua forma mais básica como um número binário. Isso ocorre porque as redes de computadores, incluindo a Internet, operam em níveis inferiores com base em comunicação digital, que é representada em formato binário (composto por 0s e 1s). No entanto, na maioria das aplicações práticas, os endereços IP são representados em notação decimal (formato de pontos), que é mais fácil de ler e entender para os seres humanos.

Aqui estão algumas informações sobre o endereço IP ser representado em formato binário:

1. **Formato Binário Puro:** Em sua forma mais fundamental, um endereço IP é composto por 32 bits para IPv4 (por exemplo, 11000000.10101000.00000001.00001010) ou 128 bits para IPv6 (um formato muito mais longo e complexo).

2. **Notação Decimal:** Para facilitar a leitura e a comunicação entre humanos, os endereços IP são frequentemente convertidos em notação decimal com quatro grupos de números separados por pontos. Por exemplo, o endereço IP "11000000.10101000.00000001.00001010" é representado como "192.168.1.10" em notação decimal.

3. **Conversão entre Formatos:** A conversão entre formato binário e decimal é direta. Cada grupo de 8 bits em formato binário é representado como um número decimal. Por exemplo, "11000000" em binário é igual a "192" em decimal.

4. **IPv6:** O IPv6, uma versão mais recente do Protocolo de Internet, usa endereços IP de 128 bits. Isso resulta em endereços IP extremamente longos se representados em formato binário puro. No entanto, mesmo para o IPv6, a notação decimal é usada para simplificar a compreensão.

5. **Endereços Subdivididos:** Os endereços IP também podem ser divididos em partes, como o endereço da rede e o endereço do host. Isso é comum em redes e é usado para rotear o tráfego com eficiência.

6. **Máscaras de Sub-rede:** Para gerenciar efetivamente os endereços IP, as máscaras de sub-rede são usadas para determinar quais bits em um endereço IP pertencem à parte da rede e quais pertencem à parte do host.

Em resumo, o endereço IP é representado em formato binário, mas é convertido em notação decimal para facilitar a compreensão humana e a comunicação. Essa representação decimal é amplamente utilizada em configurações de redes.