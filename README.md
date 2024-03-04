# Notes
> [!NOTE]
> Aqui temos um sistema bassico de Rega.

>[!IMPORTANT]
>
>Trabalho dado por formador, Paulo Leite, explicando os conseitos que precisamos para trabalho futuro.

# Arduino
![System](ARDUINO.jpg)

# Sistema de Rega

#### Inicio [Link](https://www.tinkercad.com/things/bxOicrJU0QI-copy-of-sistemaderega/editel?returnTo=%2Fdashboard)

- ✅ [Fora das funções](#)
    - ✅ [Adicionara biblioteca <Adafruit_NeonPiel.h>](#)
    - ✅ [Começar por decarar as constantes dos sensores](#)
    - ✅ [Em seguida Declarar um BAUD RATE para ver os sensores](#)
    - ✅ [Declarar um PUMP as regas](#)
    - ✅ [Em seguida declarar um long para Sensores](#)
    - ✅ [Declarar outra constante para a bomba ter um tempo que fica regando](#)
    - ✅ [Declarar outra const para definir o delay entre a rega](#)
    - ✅ [Declarar uma constante valor minimo e o valor maximo](#)
    - ✅ [Declarar outra constante de trigger para desparar](#)
    - ✅ [Declarar 3 constantes, Um para saber onde está ligado os LEDS_Non_Pixel, a quantidade, e a luminosidade](#)
    - ✅ [Usar esse comando para defenir as cores "Adafruit_NeonPixel strip(LED_COUNT, LED_PIN, NEO_GBR + NEO_KHZ800)"](#)
    - ✅ [usar para defenir a cor uint32_t Cor = strip.Color("CODIGO DA COR");](#)
    - ✅ [Criar escalas com const e as entradas](#)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Criar uma nova void de para declar a escala](#)
    - ✅ [Cria um ciclo for que se a o variavel for meno que a quantidade de leds, exibe a cor](#)
    - ✅ [Usar strip.show para mostar ligar as LEDS](#)
    - ✅ [Usara  função map para controlar a quantidade de leds dependo do valor das Leds](#)
    - ✅ [Criar mais um ciclo for para desligar as cores por ordem](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Criar uma função tipo void para ler o sensor](#)
    - ✅ [Dentro do void mudar a variavel do Sensor para ser igual a analogRead(Nome do sensor)](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Criar um nova função de void para ativar as PUMPS](#)
    - ✅ [Dentro dos parametros criar um variavel tipo int para as PUMPS(Para poder mudar o valor para depois não ter que declar toda a vez)](#)
    - ✅ [Criar um digitalWrite para ativar e desligar (HIGH, LOW)](#)
    - ✅ [Colocar o delay entre eles](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Criar uma função void para controlar o pump](#)
    - ✅ [Criar um booliano para controlar se a bomba está ativada](#)
    - ✅ [Criar um condição, se o valor for menor de que o valor do trigger, é falso(ou seja desligado), se não é true(Que fica ligado)](#)
    - ✅ [Criar um "if" para caso seja menos que o trigger, chama a função que ativa a bomba](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Dentro do setup](#)
    - ✅ [Declarar um Serial.begin para ver no painel o sensor](#)
    - ✅ [Declarar o pinMode para dizer que é um INPUT(Dos SENSORES)](#)
    - ✅ [Declarar um pinMode para dar OUTPUT(Das PUMPS)](#)
    - ✅ [Adicionar um strip.begin](#)
    - ✅ [Adicionar o strip para chamar o brilho](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Dentro do loop](#)
    - ✅ [Declarar um Serial.println, para aparecer no painel](#)
    - ✅ [Chamar a função e alterar o parametro para cada sensor](#)
    - ✅ [Colocar um read Sensor](#)
    - ✅ [Chamar a função de controlar os pumps](#)
    - ✅ [Adicionar delay](#)
    - ✅ [Adicionara biblioteca de ligar leds](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------


