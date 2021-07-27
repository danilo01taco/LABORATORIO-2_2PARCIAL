![image](https://user-images.githubusercontent.com/85728185/127173356-9a38e813-46cb-48a0-9206-c37781ebebb5.png)

# TEOREMA DE THÉVENIN
#

### Fundamentos de Circuitos Eléctricos
### Ingeniero Darwin Alulema  Flores
#
### Integrantes: Erick Maisincho, Danilo Taco, David Vasquez

#
 
## 1.Objetivos
***Objetivos general de la práctica***

***Objetivos específicos***

## 2.Marco Teorico

![image](https://user-images.githubusercontent.com/85728185/127186399-423d5541-0154-4d94-9713-823552292c78.png)

## 3.Explicación

***3.1 Material y equipo requerido***

![image](https://user-images.githubusercontent.com/85728185/127175300-c92107ef-07e6-44de-93f8-1872ec39f245.png)

*** 3.2 Procedimiento ***

_5.5.1. Arme el circuito que se muestra en la figura 5.1._

![image](https://user-images.githubusercontent.com/85259801/127082027-53f91d0b-3cfa-4332-83fc-3e1694f2852d.png)

_5.5.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2._

![image](https://user-images.githubusercontent.com/85259801/127081839-f7a22818-088d-45b7-ab4b-d9d841dbf790.png)

_5.5.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor
medido en la tabla 5.1._

![image](https://user-images.githubusercontent.com/85259801/127081863-877d9597-4c43-4e91-ad8e-9544c8f211e7.png)

_5.5.4. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito
abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1._

![image](https://user-images.githubusercontent.com/85259801/127081906-167950b5-81d1-4649-9c49-6dd7aed57266.png)

_5.5.5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la
corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2._

![image](https://user-images.githubusercontent.com/85259801/127081936-074f4996-bdfd-4e99-9886-118980bae485.png)



## PLANTEAMIENTO DE ECUACIONES

_Abriendo el circuito para obtener RTH_

![image](https://user-images.githubusercontent.com/84418933/127096456-d63f1a3d-8334-44ef-b05f-bf0880a8de28.png)

![image](https://user-images.githubusercontent.com/84418933/127096485-c68eb283-9a1c-44ca-b286-9450d8ac36bf.png)

_Realizando análisis de mallas al circuito._

![image](https://user-images.githubusercontent.com/84418933/127096531-7e395e44-e0ec-4db8-aa15-9a5ff939a957.png)

_En la Malla 3 tenemos que I3=0, por lo tanto, no hay corriente en R4_

![image](https://user-images.githubusercontent.com/84418933/127096559-f775fc5d-5948-4063-820e-4a1c5c465040.png)

_*Para la Malla 1 se tiene:_

![image](https://user-images.githubusercontent.com/84418933/127096587-1c9ed4a8-89e0-454f-a2ba-e5aadf86cda7.png)

_*Para la Malla 2 tenemos:_

![image](https://user-images.githubusercontent.com/84418933/127096619-3301ad37-b809-4b40-b863-e981581e923a.png)

_*Obteniendo el siguiente sistema de ecuaciones_

![image](https://user-images.githubusercontent.com/84418933/127096650-0f91f601-fff1-46f0-9951-18f222c38c94.png)

_*Resolviendo el sistema de ecuaciones_

![image](https://user-images.githubusercontent.com/84418933/127096688-9008855b-e843-449a-8d8b-661a84da7f08.png)

_*Remplazando I2 en Ec2_

![image](https://user-images.githubusercontent.com/84418933/127096720-648218b1-e691-49fa-bd32-d9ad42bb2f21.png)

_*Para calcular VTH_

![image](https://user-images.githubusercontent.com/84418933/127096768-35fd4590-6618-4fc5-90e5-7db4090f4d93.png)

_*Una vez calculado RTH y VTH tenemos el siguiente circuito equivalente_

![image](https://user-images.githubusercontent.com/84418933/127096799-8b5d8034-a515-4326-8436-55de10c74197.png)

![image](https://user-images.githubusercontent.com/84418933/127096824-9333f235-6aea-4f12-809c-a83ee07b2710.png)

_Tabla 5.1. Valores del Circuito Equivalente de Thévenin_

![image](https://user-images.githubusercontent.com/85259801/127175977-1bc51a5f-57d2-491f-84f3-12e12174e1d3.png)

_Tabla 5.2. Comprobación del Teorema de Thévenin._

![image](https://user-images.githubusercontent.com/85259801/127178056-686cc22a-836d-4b09-9e1b-ca86dc15de5f.png)


### 4. Resultados

***Calculo de error***

![image](https://user-images.githubusercontent.com/84418933/127186751-49c5f754-2b67-4ee6-b186-81e012c9dfd7.png)

_Tabla 5.1. Valores del Circuito Equivalente de Thévenin._

_*VTH_

![image](https://user-images.githubusercontent.com/84418933/127186865-e69eea65-361f-4624-9fe0-485ea2e6f77f.png)

_*RTH_

![image](https://user-images.githubusercontent.com/84418933/127186930-c68af2bb-e047-46da-9fe5-31a6ec533240.png)


_Tabla 5.2. Comprobación del Teorema de Thévenin._

_*Circuito Original_

![image](https://user-images.githubusercontent.com/84418933/127187049-b480b5cd-e4e9-41f1-8c19-e8a80ad86e95.png)

_*Circuito de Thévenin_

![image](https://user-images.githubusercontent.com/84418933/127187089-6384b5d1-4b9a-46a4-9b36-dd0159662d11.png)

## Video

## Conclusiones

## Bibliografia
