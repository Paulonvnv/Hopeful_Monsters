# Hopeful monsters
The term "hopeful monsters" was originally employed in the field of evolutionary biology by Richard Goldschmidt in 1940 as a mechanism to explain how a few mutations in an organism's genome can generate macroevolutionary events and saltational changes in a species, something that the traditional theory of gradual evolution could not do on its own.
A possible example of this type of mechanism could be homeotic mutants, where a part of the organism grows in the wrong region of the body. Examples of this include the replacement of antennae with legs in the case of the fruit fly, or the rearrangement of sepals, petals, stamens, and carpels in the floral structures of plants.
Although from a zoocentric perspective the fitness cost of these mutants should be very high and these types of organisms might not have the possibility of leaving offspring, in other organisms such as plants this is not necessarily true.

Here we wish to extrapolate this evolutionary concept of hopeful monsters to the process of literary writing.
The molecular machinery of an organism's cells replicates genetic material during the organism's growth and the formation of gametes for reproduction. During this process errors are introduced into the DNA chain, and they can have unexpected phenotypic consequences sometimes triggering the generation of a new species.
Similarly, during the literary writing process, it is common to rewrite the work multiple times. This process introduces changes, some deliberately and others involuntarily, that occasionally shift the writing's meaning and improve it.
That is why here we have incorporated an algorithm that mirrors this rewriting process and couples the molecular mechanisms of DNA chain replication to introduce changes that can help the writer identify new ideas to incorporate into their work.

## Requirements for using the tool

The algorithm is written in the R programming language and also uses Ollama.
Instructions for downloading and installing these programs can be found at the following links:

- [Download R](https://www.r-project.org)
- [Download Ollama](https://ollama.com/download)
- [Download RStudio](https://posit.co/download/rstudio-desktop/)

Once you've installed the mentioned programs, proceed to clone this repository using git, or if you're not familiar with git, you can download the compressed file of the tool at the following [link](https://github.com/Paulonvnv/Hopeful_Monsters/archive/refs/heads/main.zip), and extract the folder to your preferred directory.

## Tool installation

At the moment, the tool only works locally, but in the next update its use will be enabled through a web browser.

**Note!**: Next steps are for MacOS or Linux user, if you work with Windows system, you have to run the tool directly from RStudio.

1. Once all the prerequisites are installed, open your computer's terminal and using the `cd` command navigate to the folder you downloaded from the github repository:
```
cd /path_to/Hopeful_Monsters-main/
```
2. Then make sure the `WritingApp.sh` file is executable, you can check this with the `ls` command:
```
ls -l
```

<img src="https://github.com/Paulonvnv/Hopeful_Monsters/blob/main/image1.png" alt="" width="550" height="350">

3. If the file is not executable, run the `chmod` command:

```
chmod +x WritingApp.sh
```
**Note!:** You only need to execute this step the first time you use the tool.

## Using the Tool

1. Open your computer's terminal and using the cd command navigate to the folder you downloaded from the github repository:
```
cd /path_to/Hopeful_Monsters-main/
```
2. Execute the following command line in the terminal:
```
./WritingApp.sh
```
The tool should automatically open your browser and show you the following window:

<img src="https://github.com/Paulonvnv/Hopeful_Monsters/blob/main/image2.png" alt="" width="350" height="550">

3. In it you will find a text box where you can enter the sentence or paragraph you want to use as a query:
   
<img src="https://github.com/Paulonvnv/Hopeful_Monsters/blob/main/image3.png" alt="" width="350" height="550">

5. Then you can modify the following parameters:
    - Sample size (n): Desired number of outputs.
    - Variants (v): Number of times the query is going to be paraphrased before simulation starts.
    - Population size (N): Number of individuals (Sentences or paragraphs) in the simulated population.
    - Generations (t): Number of generations the simulation will run.
    - Mutation rate (𝜇): per site (character or letter), per individual rate at which mutation might occur.
    - Recombination rate (𝜌): Rate at which haplotypes (sentences within the diploid stage of the individual) might recombine (switching of words between haplotypes).

More information regarding how these parameters are used by the tool can be found at [Writing tool scheme](https://github.com/Paulonvnv/Hopeful_Monsters/blob/main/Writing_tool_scheme.pptx)

5. Once the parameters are defined, simply press the `Go` button and wait a few seconds or minutes. When the process finishes, a table will be generated with the initial variants that were used in the simulation. Note: this is not the final result, just a paraphrase of your original query.

<img src="https://github.com/Paulonvnv/Hopeful_Monsters/blob/main/image4.png" alt="" width="350" height="550">

7. To obtain a sample of the final result, press the `sample` button and scroll down the window, and a table with the final result of the simulation will be displayed. You can press the sample button as many times as you wish, and each time it will provide you with a slightly different result.

<img src="https://github.com/Paulonvnv/Hopeful_Monsters/blob/main/image5.png" alt="" width="350" height="550">

8. to stop the tool just close the window at your browser and your terminal or press `Ctrl + c` on your temrinal.
