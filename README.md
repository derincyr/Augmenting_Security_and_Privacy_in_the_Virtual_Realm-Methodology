# SoK_Methodology
This repository outlines the methodology used in our Systematization of Knowledge (SoK) paper, titled "Augmenting Security and Privacy in the Virtual Realm: An Analysis of Extended Reality Devices".

## Venues Considered. 
For venue selection, we used [CSRankings](https://scholar.google.com/citations?view_op=top_venues) where we selected *Engineering and Computer Science* as the category, a similar approach was followed in other survey papers[1]. This presented different subcategories of venues, and we selected the ones related to security and privacy and AR/VR/MR devices. 

Hence, we chose:
* Computer Security & Cryptography: security and privacy attacks are directly related to computer security
* Computer Graphics: AR/VR/MR devices utilize computer graphics in their design
*  Human-Computer Interaction: AR/VR/MR devices are about humans interacting with computer-generated environments and objects
  
As each category contained the top 20 venues, this resulted in 60 total venues for which we analyzed submissions.

## Phrases Considered.
We define phrases as the words that we looked for when we were finding published papers, and set of phrases as the combinations of keywords that resulted in our search. With the set of phrases, we aim to find all relevant papers that are proposing security and privacy attacks or their defenses on AR/VR/MR devices. We selected the phrases by first understanding how Google Scholar's Advanced Search option operates. For the **exact phase** bar we wrote the phrases that we wanted to be present in the paper that must be included in the exact order we wrote the phrases. Furthermore, we used **with all of the words** search bar, to yield papers that included all of the phrases that we chose in the paper. To span all possible words, we used OR operations which are identifiable by Google Scholar Advanced Search. 

Table 1 shows the set of phrases that are used for literature paper searches. The table is based on Boolean logic operations AND and OR, where each phrase in Phrase-1 can be combined with phrases in the Phrase-2 column. Additionally, the phrases in each column are combined with OR operations. With this idea, Google Scholar returns articles that contain at least one phrase from each column.

| Phrase-1                   |                      | Phrase-2          |
|----------------------------|----------------------|-------------------|
| augmented reality          | AND                  | security          |
| virtual reality            |                      | privacy           |
| mixed reality              |                      | security attack   |
| head-mounted display       |                      | privacy attack    |
| extended reality           |                      | security defense  |
| augmented reality devices  |                      | privacy defense   |
| virtual reality devices    |                      | defense           |
| mixed reality devices      |                      | attack            |
| holographic display        |                      |                   |
Table 1: Identified Set of Phrases for Literature Review Search

## Eligibility Criteria.
The search strategy that is explained in further detail in Appendix A yielded 101 potential papers which we double-checked if they met our elimination criteria. This step was done manually and no automation tool was utilized. To check if it met the criteria, one author read the abstracts of the papers in detail and skimmed through the papers if the abstracts weren't enough to get an understanding of the paper. The elimination criteria are given below:


*Eligibility Criteria-1: Is the article related to the security and/or privacy of XR devices? If not, exclude the paper from the list.
*Eligibility Criteria-2: Is the article only proposing an authentication model, without going into the details of possible attacks that can be done on the devices? If yes, exclude the paper from the list.


This criteria alone eliminated 59 papers. This number being high is due to several factors. For instance, we realized during the elimination of the papers that, the initial set of 101 potential papers also contained articles that had a scope of AR apps in smart phones [2], which is not related to XR devices. Additionally, the first set of papers contained many articles that weren't directly related to the devices' or the users' security and privacy, or not going into depth on the attacks and defenses [3]. We also removed 9 additional papers from the first potential papers list that were either a magazine version of the conference paper that was also included in the list or papers that were only expanding the work done on a paper that was already included in the list [4].


## References
- [1] Stephenson, Sophie, et al. "Sok: Authentication in augmented and virtual reality." 2022 IEEE Symposium on Security and Privacy (SP). IEEE, 2022.

- [2] Harborth, David, and Alisa Frik. "Evaluating and redefining smartphone permissions with contextualized justifications for mobile augmented reality apps." Seventeenth Symposium on Usable Privacy and Security (SOUPS 2021). 2021.

- [3] Freeman, Guo, et al. "Disturbing the peace: Experiencing and mitigating emerging harassment in social virtual reality." Proceedings of the ACM on Human-Computer Interaction 6.CSCW1 (2022): 1-30.

- [4] Moore, Alec G., et al. "Personal identifiability of user tracking data during VR training." 2021 IEEE Conference on Virtual Reality and 3D User Interfaces Abstracts and Workshops (VRW). IEEE, 2021.

