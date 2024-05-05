# **NeuronskeMrezeProjekt**

### **Environment**
Before each commit check wheter environment.yaml file needs to be updated.

**Create .yml** simply from 'neumre_projekt' environment with following command:

- **conda env export > environment.yml**

- after creation check if last line in environment.yml file looks like this :
    - prefix: **C:\Users\Mateja\anaconda3\envs\neumre_projekt** and remove it

**Create environment** from environment.yaml file with following command :

- **conda env create -f environment.yml**

**Update environment** with following command:

- **conda env update -f environment.yml --prune**
    - --prune uninstalls removed dependencies

### **Dataset**
Spatial enrichment runs for **90 minutes**, so using premade datasets in dataset folder is prefered.

Joining **deliverytime_with_route_lengths** and **city_basic_stats datasets** results in most spatial information.
