# Hopeful monsters
The term "hopeful monsters" was originally employed in the field of evolutionary biology by Richard Goldschmidt in 1940 as a mechanism to explain how a few mutations in an organism's genome can generate macroevolutionary events and saltational changes in a species, something that the traditional theory of gradual evolution could not do on its own.
A possible example of this type of mechanism could be homeotic mutants, where a part of the organism grows in the wrong region of the body. Examples of this include the replacement of antennae with legs in the case of the fruit fly, or the rearrangement of sepals, petals, stamens, and carpels in the floral structures of plants.
Although from a zoocentric perspective the fitness cost of these mutants should be very high and these types of organisms might not have the possibility of leaving offspring, in other organisms such as plants this is not necessarily true.

Here we wish to extrapolate this evolutionary concept of hopeful monsters to the process of literary writing.
The molecular machinery of an organism's cells replicates genetic material during the organism's growth and the formation of gametes for reproduction. During this process errors are introduced into the DNA chain, and they can have unexpected phenotypic consequences sometimes triggering the generation of a new species.
Similarly, during the literary writing process, it is common to rewrite the work multiple times. This process introduces changes, some deliberately and others involuntarily, that occasionally shift the writing's meaning and improve it.
That is why here we have incorporated an algorithm that mirrors this rewriting process and couples the molecular mechanisms of DNA chain replication to introduce changes that can help the writer identify new ideas to incorporate into their work.

## Requerimientos usar la herramienta

El algoritmo esta escrito en el lenguaje de programacion R y ademas utiliza Ollama.
Instrucciones para la descarga e instalacion de estos programas se pueden encontrar en los siguientes links:

- [Download R](https://www.r-project.org)
- [Download Ollama](https://ollama.com/download)
- [Download RStudio](https://posit.co/download/rstudio-desktop/)

Una vez instalado los programas mencionados, procede a clonar este repositorio usando git, o si no estas familiarizado con git puedes descargar el archivo comprimido de la herramienta en el siguiente [link](https://github.com/Paulonvnv/Hopeful_Monsters/archive/refs/heads/main.zip), y descomprime la carpeta en el directorio de tu preferencia.

## Installacion de la herramienta
De momento la herramienta solo funciona de manera local pero en la siguiente actualizacion se habilitara su uso desde un navegador de internet.

### MacOS o linux

1. Una vez instalados todos los requerimientos previos, abre la terminal de tu ordenador y usando el comando `cd` dirigete hacia la carpeta que descargaste del repositorio en github:
```{bash}
cd /path_to/Hopeful_Monsters-main/
```
2. Luego asegurate de que el archivo `WritingApp.sh` sea ejecutable, esto lo puede vizualizar con el comando `ls`:
```{bash}
ls -l
```

<img src="[image-url](https://github.com/Paulonvnv/Hopeful_Monsters/blob/main/image1.png)" alt="Image 1" width="300" height="200">

3. Si el archivo no es ejecutable, ejecuta el comando `chomd`:

```
chmod +x WritingApp.sh
```
!Este paso lo lo debes ejecutar la primera vez que usas la herramienta.

# Uso de la herramienta

1. Abre la terminal de tu ordenador y usando el comando `cd` dirigete hacia la carpeta que descargaste del repositorio en github:
```{bash}
cd /path_to/Hopeful_Monsters-main/
```
2. Ejecuta la siguiente linea de comando en la terminal:
```
./WritingApp.sh
```
La herramienta deberia abri tu navegador de forma automatica y mostrarte la siguiente ventana:
![image2](https://github.com/Paulonvnv/Hopeful_Monsters/blob/main/image2.png)

3. 
