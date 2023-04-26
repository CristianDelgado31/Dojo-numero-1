# Documentación Dojo Número Uno
---
## Integrantes
* Delgado Cristian
* Deniz Lucas
* Avalos Milagros
* Ibarrola Camila


## Proyecto: Semáforo Inclusivo
![semaforo](https://i.gyazo.com/fd306af2908c0f05be424a1e138b642c.png "semáforo")

## Descripción
Ayuda a que la gente con ciega pueda identificar que color 

## Función principal

Su función es hacer sonar el buzzer cada ciertos segundos dependiendo el color del led que este prendido del semáforo.  

Muestra de como se conforma el codigo:
```c++
//LED ROJO
  for(int i=0;i<44;i++)
  {
    digitalWrite(LED_ROJA, HIGH);
    digitalWrite(LED_ROJAD, HIGH);
    if(i % 2 == 0)
    {
      tone(buzzer, 1000,100);
      delay(1000);
    }
  }
  digitalWrite(LED_ROJA, LOW);
  digitalWrite(LED_ROJAD, LOW);
  delay(500);
```

## Link del proyecto 🚦
* [proyecto](https://www.tinkercad.com/things/dgq2oux0nnQ?sharecode=_1RQx2QgV9fmdtxc5UsD5-yn9UekD7Xsmg8jOOh2Lts)


## Fuentes
* [tutorial markdown](https://www.youtube.com/watch?v=oxaH9CFpeEE)



