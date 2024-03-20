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

