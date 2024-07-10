# **Describing the Delta-Delta Ct Method and Making Calculations Based On Data Prashant Provided**

## **Describing the Delta-Delta Ct Method**

The Delta-Delta Ct (ΔΔCt) method or Livak is commonly used to analyze quantitative real-time PCR (qPCR) data to compare gene expression levels between different samples. When applying the ΔΔCt method, two critical assumptions including; 1. Efficiency of the PCR reaction and 2. Consistent reference gene expression must be met. 
Below is a brief description of the steps involved:

1. **Ct Value Determination**: The cycle threshold (Ct) value is determined for each sample, which is the cycle number at which the fluorescence signal of the PCR product crosses the threshold level, indicating the presence of the target gene.

2. **Normalization (ΔCt Calculation)**: Normalize the Ct values of the target gene to a reference gene (housekeeping gene) to control for variations in the amount of input RNA and efficiency of the reverse transcription process. This is done by subtracting the Ct value of the reference gene from the Ct value of the target gene for each sample:
ΔCt = Ct target − Ct reference

3. **Comparison Between Samples (ΔΔCt Calculation)**: Compare the ΔCt values between the experimental sample and the control sample. Subtract the ΔCt of the control sample from the ΔCt of the experimental sample: ΔΔCt = ΔCt experimental − ΔCt control

Fold Change Calculation: Calculate the relative expression level (fold change) of the target gene in the experimental sample compared to the control sample using the formula: Fold Change = 2<sup> −ΔΔCt</sup> 

### **Note:** 
This method assumes that the PCR efficiencies of the target and reference genes are approximately equal and that the reference gene is stably expressed across all samples.

# **Calculations Based on Data Prashant Provided**

## **Data Provided**

Table

## **Delta Cycle Threshold (ΔCt): ΔCt = Ct target − Ct reference**

Table

## **Delta-Delta Cycle Threshold (ΔΔCt)**: ΔΔCt = ΔCt experimental − ΔCt control

Table

## **Fold Change**: 2<sup> −ΔΔCt</sup> 

Table

 

 



​

​
 


   
   