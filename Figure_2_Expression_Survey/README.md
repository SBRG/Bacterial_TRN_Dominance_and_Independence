# Expression Survey
Categories of genes:
1) **(HIGH - Top iM exp var) - 1190**
   - Gene is explained well by an iModulon
2) **(LOW - Top iM exp var - LOW VARIANCE - LOW TPM median - LOW Range) - 402**
   - Gene is not explained well but is poorly expressed on all conditions 
3) **(LOW - Top iM exp var - LOW VARIANCE - LOW TPM median - High Range) - 272**
   - Gene is not explained well but is poorly expressed on most conditions - and few active conditions don't seem to be captured 
4) **(LOW - Top iM exp var - LOW VARIANCE - MEDIUM/HIGH TPM median) - 816**
   - Gene is not explained well but is low variance
5) **(LOW - Top iM exp var - MEDIUM/HIGH VARIANCE - LOW TPM median) - 871**
   - Gene is not explained well and is not well expressed with good variation
6) **(LOW - Top iM exp var - MEDIUM/HIGH VARIANCE - MEDIUM/HIGH TPM median - Complex Regulation) - 177**
    - Gene is not explained well and is well expressed with good variation, and its regulation may not be explained well by MA at the promoter level (i.e. this particular gene seems to fail and it appears to be due to complex regulation at the promoter)
7) **(LOW - Top iM exp var - MEDIUM/HIGH VARIANCE - MEDIUM/HIGH TPM median - Single Regulator Failure) - 261**
    - Gene is not explained well and is well expressed with good variation, and its regulation may not be explained well by MA at the regulator level
    (i.e. many genes for the same regulator seem to fail)
8) **(LOW - Top iM exp var - MEDIUM/HIGH VARIANCE - MEDIUM/HIGH TPM median - Activation Condition) - 268**
    - Gene is not explained well and is well expressed with good variation, but regulator may not be activated in P1k (presumably they are 
    active enough to alter the expression of this gene, but maybe not in an isolated way where ICA can find the regulon) 
