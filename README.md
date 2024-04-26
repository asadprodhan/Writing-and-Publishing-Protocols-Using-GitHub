# **Writing and publishing a lab protocol using GitHub** <br />


### **AUTHOR: Dr Asad Prodhan** https://asadprodhan.github.io/


<br />


## **How to write up a GitHub repository**


1.	Open a GitHub account

   
2.	Create a new repository

   
3.	Write it up using the following Markdown format


<br />


# **Title** <br />



```
# **Title** <br />
```


### **AUTHOR: Name** Website


```
### **AUTHOR: Name** Website
```


Space


```
<br />
```



Text formating


## **Heading**


```
## **Heading**
```


### **Sub-headings**


```
### **Sub-headings**
```


- Bullet and sub-bullet


```
- Bullet

	- Sub-bullet
```


> Embedded text



```
> Embedded text
```


*Italic* 


```
*Italic*
```


**Bold** 


```
**Bold**
```


***Italic and Bold*** 


```
***Italic and Bold***
```


Script


``` 
Script
```


**Add a figure**


```
<p align="center">
  <img 
    src="GitHub link"
 align="center" width=100% height=100% >   
</p>
<p align = center>
Figure 1: Figure description".
</p>

```


<br />


**Add a presentation link:**


```
### **An introduction to Nanopore DNA sequencing and data analysis. Nanopore Workshop for Biosecurity, Curtin University, Perth, Australia, 27-29 June 2023.** [VIEW](https://github.com/asadprodhan/Conference_Talks/blob/main/Nanopore_Workshop_AsadProdhan_DPIRD.pdf)
```


<br />


**Add a download button in your repository:**


```
[DOWNLOAD](https://github.com/asadprodhan/blastn/blob/main/main.nf)
```


<br />


**Add a Table of Content**


```
### Content

[01.  Blastn database download and update [NCBI tool]](https://github.com/asadprodhan/blastn#using-ncbi-supplied-script)

```


<br />



### **See some GitHub repository examples here (Prodhan, 2022, 2024)**


Prodhan, M. A. (2022). An Introduction to R Coding. Zenodo. https://doi.org/10.5281/zenodo.5880043


Prodhan, M. A. (2024). About the PATH. Zenodo. https://doi.org/10.5281/zenodo.11068991


<br />


<br />



## **How to add a license to your repository**
	

- Click on Add file
        

- Create a new file


- Type LICENSE in the "Name your file" box


- Choose a license


- Review and submit it


<br />


<br />


## **How to publish your GitHub repository**


1.	Create a Zenodo account

   
2.	Log in in Zenodo using your GitHub account

   
3.	Go to the drop-down menu at the top-right-hand corner displaying your name and select GitHub


4.	Toggle the ON button


5.	Go back to your GitHub repository and create a release
   

   	- On the right-hand side, click Create a new release
        

        - Chhose a tag and create a tag, e.g. v1


        - Click on Publish release



6.	Come back to Zenodo and will now find your GitHub repository in Zenodo along with a DOI


<br />


<br />



## **How to add "Cite this repository" option to your repository**


> you can do this step after publishing it in Zenodo, beacuse you need a DOI for your repository


<br />


### **Step 1: Create a CITATION.cff file**



Open a Notepad file and write the following details



```
cff-version: 1.2.0
message: "If you use this software, please cite it as below."
authors:
- family-names: "Prodhan"
  given-names: "M. Asaduzzaman"
  orcid: "https://orcid.org/0000-0000-0000-0000"
title: "About the PATH"
version: 1
doi: 10.5281/zenodo.11068992
date-released: '2024-04-25'
repository-code: "https://github.com/asadprodhan/About-the-PATH/tree/v1"
preferred-citation:
  type: article
  authors:
  - family-names: "Prodhan"
    given-names: "M. Asaduzzaman"
    orcid: "https://orcid.org/0000-0000-0000-0000"
  doi: "10.5281/zenodo.11068992"
  journal: "Zenodo"
  title: "About the PATH"
  year: 2024

```


### **Step 2: Save as text file**
   

### **Step 3: Rename the text file as CITATION.cff**


### **Step 4: Add the CITATION.cff file to your GitHub repository**


***On the left-hand side, you will see a citation request added***

   
<br />


<br />


    
### **Now you have a publication, you can add it to your institutional research repository, Google Scholar etc**


<br />


<br />



### **Final output**


In text: (Prodhan, 2024)


In bibliography: Prodhan, M. A. (2024). About the PATH. Zenodo. https://doi.org/10.5281/zenodo.11068992


<br />


<br />


## **References**


Prodhan, M. A. (2022). An Introduction to R Coding. Zenodo. https://doi.org/10.5281/zenodo.5880043


Prodhan, M. A. (2024). About the PATH. Zenodo. https://doi.org/10.5281/zenodo.11068991




