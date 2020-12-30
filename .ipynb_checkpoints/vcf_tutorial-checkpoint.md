## Downloading a VCF file


#### 1. Navigate to the DGRP website and download the dgrp2 VCF file

Follow this link to the data page of the DGRP website: http://dgrp2.gnets.ncsu.edu/data.html


At the top of the page you will see the following links:


<img src="vcf_tutorial_images/vcf_download_link.png" alt="drawing" width="600"/>


Click on the first link to download the VCF file. The download will start automatically. The file (called dgrp2.vcf) is 3.7 GB so it may take a few minutes for the download to complete. 

#### 2. Make a project folder

Navigate to your Home folder and make a new folder called "dgrp_vcf". Move dgrp2.vcf from your downloads folder into the dgrp_vcf folder. 


<br/>

---

## Downloading Integrative Genomics Viewer (IGV)

Integrative Genomics Viewer (IGV) is a free desktop application for exploring next-generation sequencing data, including VCF files.

Follow this [link](https://software.broadinstitute.org/software/igv/download) to the IGV downloads page, where you will see the following: 

<img src="vcf_tutorial_images/IGV_download_screenshot.png" alt="drawing" width="300"/>


If you use a MacOS machine, click on: **IGV MacOS App (Java included)**

If you use a Windows machine, click on: **IGV for Windows (Java included)**

<br/>

Once IGV is downloaded, you can move it to wherever you like (e.g. if you use a Mac, you can move it to the Applications folder).


<br/>

---

## Using IGV to view VCFs

1. Open IGV

2. The human genome is set as the default genome upon opening, so we need to set the genome to the _Drosophila melanogaster_ genome. To do this click on the drop-down menu in the top left hand corner, and select "More..."

![image of dgrp2 download page](vcf_tutorial_images/1_IGV_first_open_edited.png)

3. You should see a pop-up that looks like the one below. Scroll down and select "D. melanogaster (dm3)" and press OK. 

<img src="vcf_tutorial_images/2_IGV_genomes_pop_up.png" alt="drawing" width="250"/>

4. Your IGV window should now look like the image below.

![image of dgrp2 download page](vcf_tutorial_images/3_IGV_dm3.png)

5. Now we are ready to load our VCF file. 

- Click on "File", then "Load from File..." (this will open a file browser)

- In the file browser, navigate to the dgrp_vcf folder, select `dgrp2.vcf`, and press open.

- You will see a pop-up that looks like the one below. Press "Go". This will make a file called `dgrp2.vcf.idx` in the dgrp_vcf folder. IGV requires this file to load the VCF, and it might take a few minutes for it to be made.


<img src="vcf_tutorial_images/4_IGV_index_pop_up.png" alt="drawing" width="250"/>

6. Once the index file is load

![image of dgrp2 download page](vcf_tutorial_images/5_IGV_dgrp2_loaded_in.png)

![image of dgrp2 download page](vcf_tutorial_images/6_IGV_viewing_2L.png)