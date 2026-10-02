# 16_HYER
HYER 2, A, B, Round-1

Shannon entropy:

<img width="561" height="697" alt="image" src="https://github.com/user-attachments/assets/d1a54eac-7c8d-4185-8350-a188a0bd7bc5" />

There was only one sequence of HYER 2 among the 16 HYER's.
Values near or at 0 bits demonstrate that corresponding positions are conserved across aligned sequences of their respective family. This indicates that these positions account for the essential structures and/or functions of the molecule. The appearance of columns in the region between 1.5 to 2.0 bits demonstrate the presence of nonconserved regions, or regions that are not the same across alignments due to their lack of significance to change HYER's structure and/or function.

All classes of HYER have entropies which vary widely across all positions, with the exception of the region approximately between positions 100-200, possibly indicating conserved base pairing essential for structure/function.

Posterior Probability:

<img width="399" height="762" alt="image" src="https://github.com/user-attachments/assets/6fd1a114-46d5-4b69-8838-e57a89e1b039" />

The above kernel density estimations measure the confidence of the alignment of sequences within a given class against its constructed CM. The mean fit line within each plot represents the overall confidence for the alignment. X-axis: Confidence score Y-axis: How many of the sequences share a confidence score

Apart from HYER 2, each kernel density plot is relatively narrow with means above 0.8. This means that the sequences and constructed CMs align relatively well, with high confidence. The narrow distribution and lack of multiple peaks indicate low variance and that sequences fit the corresponding model with equal confidence.

The HYER A is the most narrow, with a high peak at approximately 5.7, indicating high confidence (0.809) of sequence alignment against its CM.

The HYER Round-1 is the most broad, with a peak at 3.5, indicating lower sequence alignment (0.808) confidence against its corresponding CM compared to the other classes.

