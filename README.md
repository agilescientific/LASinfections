# LASinfections
Examples of LAS files that have been infected, diseased, broken, and in need of treatment.

Upload the culprit file to the `examples` folder, and link to it in the description.

## Will not load

1. Data and Description fields in header are flipped. [ex1_1044859098.las](examples/ex1_1044859098.las)

2. Start depth is greater than Stop depth. [ex2_1044839000.las](examples/ex2_1044839000.las)

3. Degree symbol in Latitude and Longitude – may cause problems with some encodings. [ex3_1044839000.las](examples/ex2_1044839000.las)

4. Missing `~Parameter` header section. [ex4_1044782786.las](examples/ex4_1044782786.las)

5. Cannot read file using welly 0.3.3. Reason unknown [ex5_1045399772.las](examples/ex5_1045399772.las).

6. Cannot read file using welly 0.3.3. Absurd line breaks after the Depth column in the ~A section. [ex6_1045400092.las](examples/ex6_1045400092.las)

7. Cannot read file using welly 0.3.3. Missing `~Parameter` information section. Also Suspiciously long `~Other` section. [ex7_1045627887.las](examples/ex7_1045627887.las)

8. Data section (`~A`) named incorrectly. Named as `~Log_Data[1] | Log_Definition[1]` [ex8_1046089355.las](examples/ex8_1046089355.las)

9. Depth column not listed in `~C` Curve information block [ex9_1046102218.las](examples/ex9_1046102218.las)

10. Blank lines in header section [ex10_1046102494.las](examples/ex10_1046102494.las)

11. Fragment of numbers at end of file [ex11_1046102494.las](examples/ex11_1046102494.las)

12. Uses commas and semi-colons as delimeters in places. Also many possible other reasons this might not be loading [ex12_1046114346.las](examples/ex12_1046114346.las)

13. Reasons unknown. [ex13_1046410674.las](examples/ex13_1046410674.las) 

14. Reasons unknown. [00-10-26-083-05W4-0.LAS](examples/00-10-26-083-05W4-0.LAS) originally from McMurray < a href="http://ags.aer.ca/publications/SPE_006.html">dataset</a>.

15. Reasons unknown. [00-10-04-081-05W4-0.LAS](examples/00-10-04-081-05W4-0.LAS) originally from McMurray < a href="http://ags.aer.ca/publications/SPE_006.html">dataset</a>.

