# LASinfections
Examples of LAS files that have been infected, diseased, broken, and in need of treatment.

Upload the culprit file to the `examples` folder, and link to it in the description.

## Examples

1. Data and Description fields in header are flipped. [ex1_1044859098.las](examples/ex1_1044859098.las)

2. Start depth is greater than Stop depth. [ex2_1044839000.las](examples/ex2_1044839000.las)

3. Degree symbol in Latitude and Longitude – may cause problems with some encodings. [ex3_1044839000.las](examples/ex2_1044839000.las)

4. Missing `~Parameter` header section. [ex4_1044782786.las](examples/ex4_1044782786.las)

5. Cannot read file using welly 0.3.3. Reason unknown [ex5_1045399772.las](examples/ex5_1045399772.las).

6. Cannot read file using welly 0.3.3. Absurd line breaks after the Depth column in the ~A section. [ex6_1045400092.las](examples/ex6_1045400092.las).

7. Cannot read file using welly 0.3.3. Missing `~Parameter` information section. Also Suspiciously long `~Other` section. (ex7_1045627887.las)[examples/ex7_1045627887.las]