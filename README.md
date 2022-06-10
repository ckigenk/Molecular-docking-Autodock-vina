# Molecular-docking-Autodock-vina
Bash script for automating ligand-receptor docking using autodock vina

## Setup
### Download Autodock vina
* Download the file
```
wget https://vina.scripps.edu/wp-content/uploads/sites/55/2020/12/autodock_vina_1_1_2_linux_x86.tgz
```
* Extract the file
```
tar xzvf autodock_vina_1_1_2_linux_x86.tgz
```
* Export to path
```
export PATH=$PATH:$(pwd)/autodock_vina_1_1_2_linux_x86/bin
```
* Test to see whether it runs
```
vina --help
```
