## Diversity Indices  

Mathematical measure of **species diversity** in a community.  

Two aspects:  

* **Species richness** (the number of species present)  
* **Equitability** (evenness, the number of individuals per species)  

Both aspects are considered in the following two commonly-used indices:  

* **Shannon's Diversity Index (H)**  
* **Simpson's Diversity Index (D)**  

Shannon's diversity index is more dependant on **species richness**, while Simpson's diversity index has more emphasis on **dominant species and evenness**.  

#### Shannon's Diversity Index (H)  
$$H=-\sum_{n=1}^{S}{p_i \ln{p_i}}$$  

#### Simpson's Diversity Index (D)  
$$D=\frac{1}{\sum\limits_{n=1}^{S}{p_i}^2}$$    
$S$: total number of species in the community (richness)  
$p_i$: proportion of S made up of the i-th species  

$H_{max}=\ln{S}$ and $D_{max}=S$ refering to the case of all even species.  


Each index has its own corresponding equitability (evenness) measure,  

#### Shannon's Equitability ($E_H$)  

$$E_H=\frac{H}{H_{max}}=\frac{H}{\ln{S}}$$

#### Simpson's Equitability ($E_D$)  

$$E_H=\frac{D}{D_{max}}=\frac{1}{\sum\limits_{n=1}^{S}{p_i}^2}\times \frac{1}{S}$$  



#### References  

http://www.tiem.utk.edu/~gross/bioed/bealsmodules/simpsonDI.html  

http://www.tiem.utk.edu/~gross/bioed/bealsmodules/shannonDI.html  

http://entnemdept.ifas.ufl.edu/hodges/ProtectUs/lp_webfolder/9_12_grade/Student_Handout_1A.pdf  

