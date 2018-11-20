# Replication Package for the paper entitled "Exploiting Natural Language Structures in Software Informal Documentation"

Description of the content of folder "NEON_replication_package":
1) the folder "RQ1" contains:
   
   a) "RQ1_results.xlsx" which contains the tasks descriptions and the answers collected from our study's participants.

2) the folder "RQ2" contains:
  
   a) "classification_results.xlsx" which contains the detailed classification results achieved by each study subject
   
   b) "subject1_patterns.xml" containing the NLP heuristics identified by Subject 1 with the support of NEON
   
   c) "subject2_patterns.xml" containing the NLP heuristics identified by Subject 2 with the support of NEON
   
   d) "subject3_patterns.xml" containing the NLP heuristics identified by Subject 3 manually
   
   e) "subject4_patterns.xml" containing the NLP heuristics identified by Subject 4 manually

2) the folder "RQ3" contains:
   
   a) "ASE2015_FR.xml" containing the xml versions of NLP heuristics related to the FEATURE REQUEST category identified 
      in our previous work "Development Emails Content Analyzer: Intention Mining in Developer Discussions". 
   
   b) "ASE2015_PD.xml" containing the xml versions of NLP heuristics related to the PROBLEM DISCOVERY category identified 
      in our previous work "Development Emails Content Analyzer: Intention Mining in Developer Discussions".       
   
   c) "heuristicsSelection.xlsx" containing the results of the heuristics selection process.
   
   d) "NEON_FR.xml" containing the heuristics related to the FEATURE REQUEST category, which have been automatically extracted 
      with the NEON approach and manually selected by researchers.      
   
   e) "NEON_PD.xml" containing the heuristics related to the PROBLEM DISCOVERY category, which have been automatically extracted 
      with the NEON approach and manually selected by researchers.      
   
   f) "RQ3a_results.xlsx" containing the results obtained by the NEON-extracted heuristics in classifying development email messages
   
   g) "RQ3b_results.xlsx" containing the results of the comparisons between the NEON-extracted and manually identified heuristics.
   
   h) "trainingSetWeka.arff" and "testSetWeka.arff" to replicate the results obtained with machine learning classifiers.
   
3) the folder "RQ4" contains:
   
   a) "issues.csv" containing the collected issue titles.   
   
   b) "RQ4_results.xlsx" containing the results obtained for answering RQ4.
   
   c) the folder "BUG_heuristics", containing the xml files with the NLP heuristics extracted from the issue titles with 
      labels belonging to the "bug" issue type related to each of the selected projects for this issue type.
      
   d) the folder "ENHANCEMENT_heuristics", containing the xml files with the NLP heuristics extracted from the issue titles with 
      labels belonging to the "enhancement" issue type related to each of the selected projects for this issue type.
