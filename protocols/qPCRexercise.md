# qPCR exercise: 18S standard curve

## Learning objectives
-	Gain experience assembling a qPCR reaction
-	Learn to manage your workspace for molecular work
-	Continue to develop accurate and repeatable pipetting skills
-	Prepare a serial dilution of nucleic acids with precision and accuracy

## Rationale 
Spectrophotometry can provide a useful quantification tool for nucleic acids, and give you some insight as to whether your sample has contamination from the RNA extraction process.  However, spectrophotometry can assess nothing about RNA quality.  We will introduce you to a quality-control step we use for our samples that is based on real-time PCR quantitation of high abundance RNAs present in all samples.

## RT-PCR
PCR is ultimately based on DNA (not RNA) amplification, as the enzymes involved are much more efficient in replicating a DNA template than an RNA template. This is because RNA molecules are typically single-stranded and much more fragile at high temperatures than DNA molecules. PCR relies on the separation of DNA strands at high temperatures and subsequent annealing and extension at lower temperatures, thus RNA is not a suitable molecule for PCR amplification. Therefore, all expression samples (RNA) must be converted to DNA to be used in PCR.  This process is called reverse transcription and this is the “RT” in “RT-PCR.”  Note: RT does not stand for “real-time” in this course.  You will learn much more about the process and biology of reverse transcription in a later exercise.  

## rRNA
The most abundant RNA molecules in biological samples are ribosomal RNAs (rRNAs).  Many techniques that assess the quality of RNA do so via looking at the integrity of ribosomal RNAs in the sample. There are many ways to do this, the most common being gel electrophoresis to visualize rRNA bands. For example: compare the "Degraded" lane in the gel to the "Intact" lane in the image linked below.
https://www.thermofisher.com/content/dam/LifeTech/global/life-sciences/DNARNAPurification/Images/1114/f00286.gif

A more up-to-date way of doing this is through a BioAnalyzer type machine that uses capillary electrophoresis to separate RNA and then absorbance measures to quantify ribosomal content.  Because our endpoint is qPCR, we have developed a simple and straightforward way of validating RNA quality using a qPCR based approach.  

## One-Step vs Two-Step Reactions
What are “one-step RT-qPCR” and "two-step RT then qPCR" reactions?  Normally, the enzymatic reactions involved in reverse transcription and PCR are carried out separately in sequence (aka "two-step").  In a one-step reaction, these different enzyme mixtures are combined to serially conduct RT and PCR all in one tube ("aka "one-step"). 

## EXERCISE TWO – WORKFLOW qPCR:

Before beginning – read through and think about your workflow.  Gloves, ice, racks and tubes.  What will you need and why?

1. You will find a protocol in your shared folder called “[TaqManqPCRProtocol.pdf](TaqManqPCRProtocol.pdf)”.  Open this protocol and read it through before starting the exercise.  Even if you don’t understand everything in the protocol, a once-through will prime you for what is to come. 
2. Obtain an aliquot of cDNA for use in the exercise.  This cDNA was prepared from total RNA from the mouse brain and then reverse transcribed using oligo(dT) and random primers. 
3. Design a dilution series that will consist of 6 samples where each step in the dilution series represents an 8-fold dilution.  Check with one of the instructors before beginning your dilution series to make sure it is well designed.  These diluted samples will be run in triplicate qPCR reactions to quantify 18S rRNA levels in the sample.  
4. Obtain a pair of 18S rRNA PCR primers from an instructor.  Note the concentration of the primers you are given. 
5. Consult the Promega protocol file and construct a blueprint of a qPCR reaction with the following parameters:
a. Each concentration will be measured in triplicate in 10 μl reactions.
b. Forward and reverse primers will be at a final concentration of 300 nM each.
c. Each reaction of a triplicate will get 2 μl of input cRNA.
6. When your experimental design and reaction mix plan is complete, run it by one of the instructors and make sure all is well before proceeding with the reaction construction. When given the green light, make sure to record all pertinent information in your lab notebook. 
7. Set up your reactions.  
9. Each reaction is loaded into its own well in a 96-well plate.  All of you will share one plate, so when you are ready to load the plate let us know and we will set up a queue for loading the plate.
10. When everyone has loaded the plate, we will take you up and load the plate on the realtime machine and provide further instruction at that point.
11. While the plate is running, think about what your expectations are for the outcome.  Also, revisit the process of setting up the reaction.  What went wrong that slowed you down?  What could you have done better?  
12. We will look at and analyze the data together.  
