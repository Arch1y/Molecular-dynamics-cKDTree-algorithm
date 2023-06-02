# Molecular dynamics cKDTree algorithm 
## project description

The source code is in the directory ```src/lib/``` is a Python notebook.

This project is a learning project. In the course of the work, the basics of molecular dynamics were studied and a way was found to significantly speed up the speed of the program. The speed up method is a [cKDTree algorithm](https://en.wikipedia.org/wiki/K-d_tree) method with [boundary conditions](https://docs.scipy.org/doc/scipy/reference/generated/scipy.spatial.cKDTree.html). Thanks to this algorithm, you can not go through all the particles, but quickly find the nearest ones and count interactions only with them. <br>
The paper presents the parameters of the program to achieve three states of matter: gas, liquid and solid. It also compares the speed of two methods: cKDTree and [BruteForce](https://en.wikipedia.org/wiki/Brute-force_search)

## launch
In folder ```src/lib/``` there is a ```molecular dynamics.ipynb``` file, which is the main and only necessary file. <br>
The program was written in google colab and worked on their servers.