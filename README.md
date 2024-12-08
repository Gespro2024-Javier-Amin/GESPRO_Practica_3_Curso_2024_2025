![header](https://cloud.githubusercontent.com/assets/6546265/22174630/785cdf04-dfe3-11e6-8cf4-024e8dc1c051.png)

[![ZenHub](https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png)](https://zenhub.com)
[![Build Status](https://travis-ci.org/davidmigloz/go-bees.svg?branch=master)](https://travis-ci.org/davidmigloz/go-bees)
[![codecov](https://codecov.io/gh/davidmigloz/go-bees/branch/master/graph/badge.svg)](https://codecov.io/gh/davidmigloz/go-bees)
[![Code Climate](https://codeclimate.com/github/davidmigloz/go-bees/badges/gpa.svg)](https://codeclimate.com/github/davidmigloz/go-bees)
[![SonarQube](https://sonarqube.com/api/badges/gate?key=go-bees)](https://sonarqube.com/component_measures/?id=go-bees)
[![Dependency Status](https://www.versioneye.com/user/projects/57f7b19e823b88004e06ad33/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/57f7b19e823b88004e06ad33)
[![Documentation Status](https://readthedocs.org/projects/go-bees/badge/?version=develop)](http://go-bees.readthedocs.io/es/develop/?badge=develop)

## License

Copyright (c) 2016 - 2017 David Miguel Lozano

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

# Guía para pasar un commit del repositorio Go Bees a la rama master local

### Autor: Jose Javier Velasco Whu y Mohamed Amin El Amrani El Khottouli
##### URL Repo: https://github.com/Gespro2024-Javier-Amin/GESPRO_Practica_3_Curso_2024_2025

---

## **1. Posicionarse en el commit inicial**

Para comenzar, nos aseguraremos de posicionarnos en el commit correspondiente del repositorio para subir cambios, tener la rama `master` al día y estar posicionados en esta rama.

![image](https://github.com/user-attachments/assets/0b025424-5046-48b4-a3e4-8a928b1d6663)

---

## **2. Crear una nueva rama**

1. Creamos una nueva rama que debe estar vinculada con la tarea correspondiente y cuyo nombre coincida con el del repositorio Go Bees.
2. Esta rama se utilizará para gestionar los cambios de la tarea.

![image](https://github.com/user-attachments/assets/9b851d93-2043-4520-bfd5-d12c4970ccd8)

---

## **3. Posicionarse en la nueva rama localmente**

1. Nos aseguramos de posicionarnos en la rama recién creada en nuestro ordenador local.
2. Para ello, haremos doble clic sobre la rama en el cliente de Git.

![image](https://github.com/user-attachments/assets/796ef86d-2e56-484f-9caa-426764299541)

---

## **4. Copiar los archivos del repositorio**

1. Navegamos a la carpeta donde se encuentra el repositorio Go Bees en nuestro ordenador.
2. Copiamos todos los archivos de esta carpeta, excluyendo el directorio `.git`.
3. Pegamos estos archivos en la carpeta correspondiente de nuestra práctica.

![image](https://github.com/user-attachments/assets/2b40aee9-46ba-49b4-8fbb-22fe0a082f0e)

---

## **5. Registrar los cambios**

1. Abrimos el cliente de Git y seleccionamos **View Changes** para visualizar los cambios realizados.
2. Pulsamos **Stage All Changes** para preparar todos los cambios para el commit.
3. Escribimos un mensaje explicativo y pulsamos **Commit Changes** para registrar el commit.

![image](https://github.com/user-attachments/assets/9b2141f2-e7bd-4224-b2c9-48366e809b03)

4. Hacemos un **Fetch All** para actualizar nuestra copia local con los últimos cambios del repositorio remoto.
5. Realizamos un **Pull** (modo fast-forward si es posible) para asegurarnos de tener la última versión sincronizada.
6. Finalmente, hacemos un **Push** para subir nuestros cambios al repositorio remoto.

![image](https://github.com/user-attachments/assets/bf160e91-335b-4b79-a47a-9dc5eee84be8)

---

## **6. Crear y confirmar el Pull Request**

1. En GitHub, navegamos a la sección **Pull requests** y seleccionamos la opción **Compare & pull request**.
2. Revisamos los cambios y pulsamos en **Create pull request** para iniciar el proceso de revisión.

![image](https://github.com/user-attachments/assets/2afd234c-7e7c-4307-b26e-3df0dbda3ab4)

3. Una vez aprobado, confirmamos el merge pulsando en **Confirm merge**.

![image](https://github.com/user-attachments/assets/87c249fa-8d35-4866-9d54-5511ac9672a1)

4. Verificamos que el estado de la solicitud de extracción indique "Merged".

![image](https://github.com/user-attachments/assets/b6efebde-6493-4839-9270-115bf9304ea8)

---

## **7. Actualizar la rama local**

1. Repetimos el proceso de **Fetch All** para sincronizar nuevamente nuestra copia local.

2. Realizamos un **Pull** para actualizar la rama local con los cambios fusionados en remoto.

3. Finalmente, hacemos otro **Push** para asegurarnos de que todos los cambios estén sincronizados.

![image](https://github.com/user-attachments/assets/c8730d33-b059-4c42-92d0-6f687eea8251)

---

## **8. Verificación del commity visualización de ramas**

1. Verificamos que el commit creado aparece correctamente reflejado en nuestra rama `master` local.

![image](https://github.com/user-attachments/assets/542e1280-cbaa-4bfd-a14f-41e7b7fd6e97)

2. Visualizamos todas las ramas creadas en el proyecto:

![image](https://github.com/user-attachments/assets/af860941-e325-4b18-ada1-370a0efbeef8)

---

## **9. Estadísticas del repositorio**

1. Visualizamos las estadísticas en la sección **Insights** de GitHub:

![image](https://github.com/user-attachments/assets/a97313ee-0d99-4af9-9313-cbfb2bc40617)

2. Revisamos la frecuencia de código en la sección **Code Frequency** de **Insights**:

![image](https://github.com/user-attachments/assets/011e86a4-15f0-46fc-914f-aabdf5fb84e3)

3. Consultamos las pull requests cerradas en el proyecto:

![image](https://github.com/user-attachments/assets/4463aad3-5a5d-49f7-9171-fb76cfcf5f2c)

---

## **10. Foto de todo el proyecto en GitKraken**

Incluimos una captura de todo el grafico del proyecto visualizado en GitKraken para verificar la estructura y el estado de las ramas.

![image](https://github.com/user-attachments/assets/70902a05-3258-4624-9d9e-e6a42fd3957e)

En esta captura se ven claramente todos los commits, pasos, etc... dados en el GitKraken.

1. Especificación del primer commit creado:
   
![image](https://github.com/user-attachments/assets/c2bb64ec-8a83-4f2b-bc8a-56d87803be92)

3. Especificación del ultimo commit creado:

![image](https://github.com/user-attachments/assets/029d4a72-ca5d-4221-8af4-50a3fe73bdc5)

