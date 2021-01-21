# Mobile-wallet-adoption
### Analysis Steps
All the steps are listed below ,sequentially we will apply them
* 1.Check for sample adequacy.
* 2.0 Find component by principle component analysis.
* 2.1 Check the total varience explained matrix.
* 3.Decide number of component visually.
* 4.Segregate variables into underlined factors.
### Cheking Sample Adequacy
![](https://github.com/pankajknitj/Mobile-wallet-adoption/blob/master/utils/kmo.png)
* The **KMO value** should greater than .5, it will be better if near 0.8 or 0.9
* Here we can observe the KMO value is greater than 0.8, Means our sample is adequate in amount to performe Factor analysis.
### Finding components(Factors)
* In software we have to choose the one method, we will choose PCA
* Set the Eigenvalues limit to 1, Means we will select that component or factor having Eigen value greater than 1.
![](https://github.com/pankajknitj/Mobile-wallet-adoption/blob/master/utils/total%20veience%20explained.png)
* We can clearilly see that 4 component has been made from the 16 variables.
* The first component have the highest varience explained, around 38%.
# Scree plot
* We generally take the knee value number of component, lets see the below plot
![](https://github.com/pankajknitj/Mobile-wallet-adoption/blob/master/utils/scree%20plot.png)
### Segregating variables into factors.
* Variables having the highest value of correlation, put that varible into that factor only. By this we will comeup with the segregated variables.
![](https://github.com/pankajknitj/Mobile-wallet-adoption/blob/master/utils/rotated%20component%20matrix.png)
### Factor 1 consist of
* Save time
* Convinient transaction
* Easy to track history
* More convinient than debitcard.
* Secured Mode transaction
* Reliable transaction
### Factor 2 comprises of
* when alone try new things.
* Explore new technology
* experiment with way of life
### Factor 3 coprises of
* Prefer to used which used by friend.
* Recomended by family or friend.
* Use when see people using it.
### Factor 4 comprises of
* Easy in payment to local vendor.

## Factor labeling
means we assign a label to each of the factor based the charactristics of the contained variable.
* F1->Feature of payment app.
* F2->Excitment towards new technology.
* F3->Promotion by peoples.
* F4->mostlly related to F1
