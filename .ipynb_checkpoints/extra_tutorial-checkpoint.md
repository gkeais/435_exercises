
## Exploring the VCF file from the command line

Open a Terminal window (Applications > Utilities > Terminal)

To move into your project folder using the Terminal, type the following command and press enter:

```
cd ~/dgrp_vcf
```

We can now view the first line of the VCF file with the following command:

```
sed -n 1p dgrp2.vcf
```

You should see the following output, which is the first header line of the VCF:
`##fileformat=VCFv4.1`

or the first six lines:
```
sed -n 1,6p dgrp2.vcf
```



## The VCF file format

The Variant Call Format (VCF) is a standardized format for storing information on genetic variation from many individuals. VCF files are simply text files that follow the VCF format. They have the file extension `.vcf`.

VCF files have several header lines that specify information about how the file was made. These are shown in red and green text in the image below. For our purposes, these can be ignored!

![image of dgrp2 dowload page](https://bioinf.comav.upv.es/courses/sequence_analysis/_images/vcf_format.png)

Each line of the body of the VCF file contains information from a single variant.


<br/>

---
