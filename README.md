# exercicio 01

# Como funciona a internet?
<div style="text-align: justify">

## O que é a Internet?
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Para compreendermos como a Internet chega na sua casa vamos imaginar que ela é uma pequena rede conectada a outras redes (maiores) de computadores. Sendo assim, não há um dono da Internet, nem uma empresa que a controle, mas sim um grupo de várias redes interligadas. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Quando conectamos um computador a outro, ou quando ligamos vários computadores uns aos outros, criamos uma rede local. Mas desta forma, os computadores só se comunicam uns com os outros, sem acesso a outros computadores fora da sua casa ou empresa, sem acesso a outros servidores, como é possível quando há acesso à Internet.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Este acesso externo ocorre quando a sua rede local se conecta a uma outra rede maior - no caso, o seu provedor de Internet - por meio da tecnologia TCP/IP, um modo de comunicação baseado no endereço de IP (Internet Protocol). Este IP é o endereço de cada um dos pontos de uma rede, e cada ponto da rede consiste em um computador que, por sua vez, se interliga a outros computadores, formando uma verdadeira “teia de redes”.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Já os sites e serviços acessados pela Internet são - de maneira simplificada - aplicativos disponíveis em servidores. E esses servidores são formados por grandes computadores conectados à rede mundial de Internet, cada um deles também identificado por um endereço de IP.
#### O Caminho da Internet
Este caminho passa por quatro passos principais, sempre identificados por um endereço de IP:
 - backbone
 - provedor de acesso
 - provedor de serviço 
 - usuário final.


### Backbone
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Estes backbones são pontos das redes que compõem o núcleo das redes de Internet. São pontos-chave da Internet que distribuem pelas redes as informações baseadas na tecnologia TCP/IP. Existem poucos backbones espalhados pelo mundo, e estes são os responsáveis por distribuir o acesso mundial para a rede de Internet.

### Provedor de acesso
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A partir dos backbones, a Internet passa para uma nova etapa, quando o seu sinal chega aos provedores de acesso - as empresas que contratam o sinal de backbones para distribuir aos seus usuários. Os provedores de acesso são, em geral, empresas ligadas ao setor de telecomunicações, ou até mesmo as próprias companhias telefônicas, que fornecem o acesso à Internet por meio de planos acordados com seus usuários.

### Provedor de serviço
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Estes dados de Internet que trafegarão na rede necessitam de um meio para o seu transporte até os usuários, e são as empresas provedoras de serviço as responsáveis por este papel. Estas empresas recebem os dados do provedor de acesso e distribuem aos usuários por variados meios, seja por linha telefônica, fibra ótica ou via rádio (por tecnologia sem fio).
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Estas empresas devem sempre ser regulamentadas pela Anatel e podem ser prestadores de serviço de rede, companhias telefônicas e empresas de telecomunicações.

### Usuário final
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Este pode parecer o passo final do caminho percorrido pela Internet, mas na verdade não é. Ao chegar no usuário final o sinal de Internet passa a repetir todo o caminho novamente, porém na forma inversa, já que você, como usuário final, também envia sinais - com as suas requisições - para a Internet.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os dados enviados pelos usuários são transportados pelo provedor de serviço, enviados para o provedor de acesso e chegam novamente ao backbone. A partir do backbone, o processo segue novamente o mesmo caminho inicial até o próximo destino, que pode ser, por exemplo, o arquivo do CD que você está querendo fazer download, lá na Espanha.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ao acessar o site do CD desejado, entretanto, ninguém obviamente sabe o endereço IP completo da máquina que hospeda esses arquivos ou sites. O que conhecemos é o endereço “www”. Estes endereços de sites são baseados na tecnologia DNS, que basicamente cria atalhos entre os endereços “www” à endereços IP. Assim, não é necessário que você navegue decorando endereços do tipo "192.168.200.45" para acessar o seu site preferido. Basta conhecer o endereço “www”.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Após acessar o site, por DNS, o endereço “www” te jogará para o endereço IP onde ele está hospedado. Feito isso o site receberá o seu sinal pedindo para baixar o arquivo do CD, e este sinal será transportado pelo seu provedor de serviço para o provedor de acesso, que o levará até o backbone. Chegando no backbone contratado, o sinal deve alcançar o servidor espanhol onde estão os arquivos do CD que você quer baixar, então o backbone do seu provedor enviará um sinal para o backbone do provedor do site espanhol do CD, que fará o mesmo caminho. Ao fim, o arquivo finalmente será transferido de lá para o seu computador.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Vamos apenas lembrar que nestes processos podem existir outros servidores intermediários com seus respectivos endereços IP, já que um provedor de acesso ou um backbone pode distribuir o sinal por três servidores diferentes, por exemplo.

### Outros caminhos possíveis
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Existem outros serviços baseados na Internet que não seguem exatamente este mesmo caminho, como por exemplo a telefonia VoIP (Voz sobre IP) e o compartilhamento de arquivos P2P (ponto à ponto).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os serviços de VoIP, que possibilitam o tráfego de voz sobre a rede de Internet, permitem que você faça ligações para outros usuários do serviço e também para usuários da telefonia convencional.
Em uma ligação entre usuários de VoIP, cada usuário utilizando um computador equipado com software específico ou um aparelho telefônico especial se conecta ao provedor VoIP que intermedia a comunicação. Já em uma ligação entre um usuário de VoIP com um telefone convencional, celular ou fixo, o usuário VoIP se conecta ao provedor VoIP que efetua uma ligação para o telefone convencional desejado.
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Já no compartilhamento de arquivos P2P, os usuários compartilham arquivos de forma ponto à ponto - ou seja: cada usuário decide compartilhar alguns dos seus arquivos com uma determinada rede P2P (Kazaa, Emule, Ares, BitTorrent, etc). Com isso, estes arquivos ficam disponíveis para todos usuários que utilizam o software pertencente à rede de P2P.
</div> 