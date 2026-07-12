# Master-Thesis Docuemntation
- Collection of my Masters work done during 2012-2015
- [**Abstract**](https://github.com/LifnaJos/Master-Thesis/blob/main/ME-Report-Abstract-2015.pdf)
- [**Final Presentation**](https://github.com/LifnaJos/Master-Thesis/blob/main/Final_Project_Presentation.pdf)
- [**Handout for the External Examiner**](https://github.com/LifnaJos/Master-Thesis/blob/main/Handout.pdf)
- [**Phase-1 Implementation of detecting Concept Drift in Twitter Data Streams**](https://drive.google.com/file/d/0B9gX2dSK40SCaVhreTZyYzJQcmc/view?usp=sharing&resourcekey=0-xdQXKlbGhOMtHpcDdzwOyw)
- [**Phase-2 Implementation of Concept Drift Mining Engine**](https://drive.google.com/file/d/0B9gX2dSK40SCSk9pRHlESnBuRDg/view?usp=sharing&resourcekey=0-4uU8aKErroHRwHgqR9NApg)

Concept Drift Mining Engine
===========================
Phase 1: Data Gathering
   a. Downloading Tweets from @shaktivahini
   b. Expanding tinyURLs
   c. Crawling webpages associated with expanded tinyURLs

Phase 2: Data Cleansing
   a. Cleansing raw tweets
   b. Cleansing expanded tinyURLs
   c. Cleansing crawled webpages of expanded tinyURLs
   d. Merging the three  tweet components
      (i) merge all the url files into a single file
      (ii)merge tweets with urls
   e. Cleaning fully expanded tweets

Phase 3: Grouping concepts into 13 subdomains
   a. identify unique concepts
   b. group unique concepts into 13 subdomains manually
   c. replace the concepts with corresponding subdomain.
   
Phase 4: Mining Association Rules from refined sample dataset
   a. Support-Confidence Framework (SC)
   b. Augmented Support-Confidence Framework with
      all_confidence correlation measure (ASC)
   c. Temporal Weighted Utility Association Rule Mining  
      (TWUARM)

Phase 5. Data Visualization
   a. Combine all the charts
   b. Plot the graphs for varying support values
      (support = 35,45,55,65,75,85,95)
      confidence = .85
      all_confidence = .90
      wt_threshold = 20.0
