# Sistemas_Embarcados

# Funcionamento

## Retificador

Um retificador é um circuito eletrônico usado para converter corrente alternada (AC) em corrente contínua (DC). Na maioria dos casos, isso é feito removendo as partes negativas da forma de onda AC, resultando em uma saída que flui apenas em uma direção.

## Componentes

O componente principal em um retificador é o diodo semicondutor. Os diodos permitem que a corrente flua em uma direção enquanto bloqueiam o fluxo em outra direção. Isso é fundamental para a conversão de AC para DC.

## Tipos de Retificadores:

### Retificador de Meia Onda:

Usa apenas metade da forma de onda AC.
Consiste em um diodo conectado em série com a carga.
Durante a metade positiva do ciclo de entrada, o diodo conduzindo permite que a corrente flua para a carga.
Durante a metade negativa, o diodo está reversamente polarizado e não permite que a corrente flua.
A saída é uma série de pulsos de corrente unidirecional.

### Retificador de Onda Completa:

Usa ambos os ciclos positivos e negativos da forma de onda AC.
Pode ser implementado usando uma configuração de ponte de diodos.
A ponte de diodos usa quatro diodos em uma configuração que permite que a corrente flua em direção à carga independentemente da polaridade da entrada AC.
Produz uma saída de corrente contínua mais suave em comparação com o retificador de meia onda.
Mais eficiente do que o retificador de meia onda.

### Retificador Controlado:

Usa dispositivos semicondutores controláveis, como tiristores ou tiristores controlados por tensão, em vez de diodos.
Oferece controle preciso sobre a saída de corrente contínua ajustando o ângulo de disparo dos dispositivos semicondutores.
Pode ser usado em aplicações que exigem regulação de tensão ou controle de potência, como em sistemas de alimentação ininterrupta e conversores de frequência variável.

Exemplo de simulador do carregador com retificador feito no Proteus.
<img width="559" alt="Captura de tela 2024-03-19 211452" src="https://github.com/R-DaRosa-Antonio/Sistemas_Embarcados/assets/142621312/9a5be96a-c374-4261-9772-2e075583c8d7">
<img width="632" alt="Captura de tela 2024-03-19 211512" src="https://github.com/R-DaRosa-Antonio/Sistemas_Embarcados/assets/142621312/f4ca1c7e-3b70-43ed-bd43-77dc66f6d1b6">


Exemplo de um carregador de celular com um led, utlizando um retificador, feito em aula pratica.
![20240312_211421](https://github.com/R-DaRosa-Antonio/Sistemas_Embarcados/assets/142621312/77bd44cf-10fa-4272-a4c3-d0e69bd6c582)
![20240312_211413](https://github.com/R-DaRosa-Antonio/Sistemas_Embarcados/assets/142621312/3d27d5ad-792a-4ec6-8570-1e3ab89a4b5c)
![20240312_211410](https://github.com/R-DaRosa-Antonio/Sistemas_Embarcados/assets/142621312/584c0705-7193-447e-99dc-a077d303fdeb)


