---
OMICS: "[[L6 Proteomics - Data]]"
---
To match the peptide sequence using the common approach of database matching, the underlying protein has to be present in the database. The main difference between different search engines (that match the sample data with a theoretical spectrum) is their scoring mechanism. UniPort is the most commonly used database and like many others the data is stored in the form of FASTA files. 
## Limitations of FASTA databases
Besides the need for the protein sequence being contained in the database, FASTA isn't able to take sequence variation or different splicing into account. The data might also include signal peptides, that are not present within the cell.

## Search engines
As described before search engines are used to compare sample and database to [[Identify peptides with tandem MS|identify]] the peptide. This requires the following steps:
1. Data reduction - the peak heights are [processed](content/Attachments/KIMN20_data_identification_quantification_2067540178%204.png) to have similar height across the whole spectrum
2. Build [theoretical spectra](content/Attachments/KIMN20_data_identification_quantification_2067540178%205.png) - from sequences in database
3. Count matched peaks - between sample and theoretical spectra
4. Compute cross correlation - which is the best fit
This produces a candidate peptide for each spectrum with a corresponding score. By defining a score threshold that is unique to each sample *"correct"* and *"incorrect"* samples are discriminated.
To discern whether the cutoff range is usable a package called **PeptidePropher** can be used. It assumes standard [distributions](content/Attachments/KIMN20_data_identification_quantification_2067540178%206.png) of the correct and incorrect samples and then calculates the probabilities for a correct alignment.
With this model, we can adjust the preferred accuracy/error rate of the match as a trade of with sensitivity (amount of sequences identified).

## Example: X!Tandem
X!Tandem is an open source database, that includes its own scoring and allows calculating an expectation value. This E-value assigns a statistical confidence to all individual spectra, by calculating the chance of the match to be my chance. It takes the size of the database into account and so the highest E-value represents the number of entries in the database (low values give high confidence in the match).

---
Created: 2024-12-11 15:53