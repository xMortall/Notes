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
    - ✅ [Começar por decarar as constantes dos sensores](#)
    - ✅ [Em seguida Declarar um BAUD RATE para ver os sensores](#)
    - ✅ [Criar um PUMP as regas](#)
    - ✅ [Em seguida declarar um long para Sensores](#)
    - ✅ [Criar outra constante para a bomba ter um tempo que fica regando](#)
    - ✅ [Criar outra const para definir o delay entre a rega](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Criar uma função tipo void para ler o sensor](#)
    - ✅ [Dentro do void mudar a variavel do Sensor para ser igual a analogRead(Nome do sensor)](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Criar um nova função para ativar as PUMPS](#)
    - ✅ [Dentro dos parametros criar um variavel tipo int para as PUMPS(Para poder mudar o valor para depois não ter que declar toda a vez)](#)
    - ✅ [Criar um digitalWrite para ativar e desligar (HIGH, LOW)](#)
    - ✅ [Colocar o delay entre eles](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Dentro do setup](#)
    - ✅ [Criar um Serial.begin para ver no painel o sensor](#)
    - ✅ [Declar o pinMode para dizer que é um INPUT(Dos SENSORES)](#)
    - ✅ [Criar um pinMode para dar OUTPUT(Das PUMPS)](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- ✅ [Dentro do loop](#)
    - ✅ [Criar um Serial.println, para aparecer no painel](#)
    - ✅ [Chamar a função e alterar o parametro para cada sensor](#)
    - ✅ [Colocar um read Sensor](#)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------


- ✅ [](#)

