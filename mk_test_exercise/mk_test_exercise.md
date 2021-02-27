## BIOL 435 - Molecular Evolution

<br/>

# Testing for positive selection: the McDonald-Kreitman (MK) test


## Introduction

In this exercise, you will be performing an MK test on sequences from _Drosophila melanogaster_ and its close relative, _Drosophila simulans_. The MK test compares levels of synonymous and non-synonymous polymorphism (P<sub>S</sub> and P<sub>N</sub>) to levels of synonymous and non-synonymous divergence (D<sub>S</sub> and D<sub>N</sub>). Therefore, several samples are required from the species of interest in order to calculate levels of polymorphism, and at least one sample is required from a second species to calculate levels of divergence. You have been provided with files containing such data for two genes from _D. melanogaster_ and _D. simulans_.

**Files for the exercise:**

1. `RpL36_dmel_dgrp.txt` - a fasta file containing sequences for the gene `RpL36` from 155 lines of the DGRP
2. `RpL36_dsim.txt` - a fasta file containing `RpL36` sequence from a single _Drosophila simulans_ individual
3. `Pkd2_dmel_dgrp.txt` - a fasta file containing sequences for the gene `Pkd2` from 62 lines of the DGRP
4. `Pkd2_dsim.txt` - a fasta file containing sequences for the gene `Pkd2` from 2 _Drosophila simulans_ individuals



Although there are a number of specialized software packages that perform the MK test, for convenience we will use a web-based MK test created by researchers in the Department of Genetics and Microbiology at the Universitat Autònoma de Barcelona (`http://mkt.uab.es/mkt/MKT.asp`).


<br/>

---

# MK test exercise: Part 1 (online MK tests)

### 1. Navigate to the online MK test homepage (`http://mkt.uab.es/mkt/MKT.asp`)

<br/>

On the homepage you will find four text boxes, as shown below. The two boxes on the left are labeled "Species 1", and the two on the right are labeled "Species 2". The top two boxes are for entering sequences from our two species (the bottom two boxes fill automatically). For our comparison, we will use _Drosophila melanogaster_ as Species 1 and _Drosophila simulans_ as Species 2.

<br/>

<img src="images/1_online_mk_test_homepage.png" alt="drawing" width="600"/>

<br/>

### 2. Enter the _D. melanogaster_ `RpL36` sequences into the "Species 1" box 

- Open the file called `RpL36_dmel_dgrp.txt` in a text editor (the default text editor for Mac is called TextEdit, whereas the default for Windows is called Notepad).

- Once the file is open, select and copy the entire contents of the file.

- Next, return to the MK test hompage and paste the contents of the file into the top box on the left labeled "Species 1".

- The box on the bottom left should then fill automatically, as shown below (you may have to click outside of the text box for the page to refresh).

<br/>

<img src="images/2_annotations_filled.png" alt="drawing" width="600"/>

<br/>

### 3. Enter the  _D. simulans_  `RpL36` sequences into the "Species 2" box

- Open `RpL36_dsim.txt` in a text editor.

- Copy the contents of the file.

- Return to the MK test homepage and paste the contents into the top box on the right labeled "Species 2".

- As with Species 1, the bottom box on the right will fill automatically.


<br/>

### 4. Run the test

- Press the "Run test" button and wait for the results page to appear (this should take no longer than a minute or two).

<br/>

### 5. View the results

- Before examining the results in the table at the bottom of the page, first set the results to be presented without any correction for divergence by clicking the corresponding option:

<img src="images/3_select_without_correction.png" alt="drawing" width="600"/>


<br/>

### 6. Save the results

- To save the results, copy-paste the results table into a word document along with the chi-squared test statistic and the corresponding p-value.


<br/>

### 7. Perform the MK test with `Pkd2`

- Repeat steps 1-6 using the sequences in `Pkd2_dmel_dgrp.txt` for Species 1 and the sequence in `Pkd2_dsim.txt` for Species 2.

- At the end of step 7, you should have two results tables copied into a word document, as well as their corresponding chi-squared test results (_i.e.,_ a chi-squared test statistic and a p-value for each gene).

<br/>


---
---

<br/>

# Exercise questions

See Watnick et al. (2003) [`https://doi.org/10.1016/j.cub.2003.12.002`] to help answer some of the following questions. 

1. What is `Pdk2`'s function in flies? What happens to flies when this gene is mutated? 

2. `Pdk2` is also called "`amo`". What is "`amo`" short for? Why is it called this?

3. What does a significant MK test for `Pdk2/amo` mean? How would you interpret this? 

4. Which of the categories (P<sub>S</sub> , P<sub>N</sub>, D<sub>S</sub>, D<sub>N</sub>) is unusual? 

5. Based on what you know about `Pdk2/amo`'s role, can you speculate why it's got a significant MK test i.e. what's going on?
 

