# **NeuronskeMrezeProjekt**

### **Environment**
Before each commit check wheter environment.yaml file needs to be updated.

**Create .yml** simply from 'neumre_projekt' environment with following command:

- **conda env export > environment.yml**

- after creation check if last line in environment.yml file looks like this :
    - prefix: **C:\Users\Matej\anaconda3\envs\neumre_projekt** and remove it

**Create environment** from environment.yaml file with following command :

- **conda env create -f environment.yml**

**Update environment** with following command:

- **conda env update -f environment.yml --prune**
    - --prune uninstalls removed dependencies

### **Dataset**
Spatial enrichment runs for **90 minutes**, so using premade datasets in dataset folder is prefered.

Joining **deliverytime_with_route_lengths** and **city_basic_stats datasets** results in most spatial information.

### **Full dataset**
Due to the limitation of the size of the project's submission, the final dataset that has been processed and enriched with spatial data can be found at the following link: https://ferhr-my.sharepoint.com/:u:/g/personal/mz53039_fer_hr/EU7rvABVRX9Lp-1qUUh6QwUBi8PbvMID08ZBaAjtWUty0A?e=G7mmRZ

### **Github project link**
https://github.com/DavIvek/NeuronskeMrezeProjekt