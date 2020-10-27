TRGN510 Final Project
================
Title:
------------------
Analysis of Differential Expression of Melanoma in white males in 30-40 and white males in 70-80.

Author:
----------------
Mengyuan Zhang

mzhang11@usc.edu

Overview of project:
----------------------
* Due to high resolution, RNA sequencing (RNA-seq) has become a critical method for analyzing differential gene expression. For this project, RNA-seq data would be a great choice. The age of the patients is the variables in this project. Therefore, the RNA-seq data file in the HT-seq format for melanoma in white males in the age of 30-40 and white males in the age of 70-80 be analyzed in the project.
* The objective is to use the Bioconductor in R to analyze the differential gene expression of melanoma in white males in the age of 30-40 and white males in the age of 70-80.
* The following link is a reference of Vignette https://www.bioconductor.org/packages/devel/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html

Data:
------------
All of the data files are obtained from [GDC Data Portal](https://portal.gdc.cancer.gov/)
* Data of white males in the age of 30-40:
1. 15b87438-308c-491e-ac85-6fb75a470182.htseq.counts.gz
2. bbe0252c-d51f-4e74-96b6-e4a0355ccda0.htseq.counts.gz
3. 7b50493c-0691-4612-9721-d8cce38e847b.htseq.counts.gz
4. 42016929-9d4d-4125-b2f2-4b472c3fd772.htseq.counts.gz
5. 5347b69e-eb89-4c1f-829f-3787b6d7db62.htseq.counts.gz
6. f959f0c8-c6be-4601-817a-ee24a17b4432.htseq.counts.gz
7. c15643a8-ed70-40ff-8379-b58cea01ad49.htseq.counts.gz
8. 4ea99594-481e-4d33-9969-da0a90797d23.htseq.counts.gz
9. 677291bf-6149-4c97-b958-dd2b0219bfe5.htseq.counts.gz
10. 19ad10e2-bcfe-4b8a-ba4e-1b59f352050e.htseq.counts.gz
11. 9943770b-b3e2-42c9-a286-85b558de7da3.htseq.counts.gz
12. b46583df-2e98-4507-a730-581cfe113900.htseq.counts.gz
13. 793a4160-f480-4ca2-9afd-42ffec3dc717.htseq.counts.gz
14. 80b5f1bb-3134-438d-8918-b63c73a44e0f.htseq.counts.gz
15. 08b7568c-c002-43ff-8f86-4be189aada9e.htseq.counts.gz
16. ab2983e3-716c-4374-81a2-2837cf76930e.htseq.counts.gz
17. e99fba98-f95e-4fc9-aa7d-5f8164c06f2a.htseq.counts.gz
18. a7ee7e2c-0788-4505-82d0-3db8bb56ea6b.htseq.counts.gz
19. 7a241ae9-e218-4479-8096-d855cf3e8565.htseq.counts.gz
20. 47efad89-24a3-4864-8a60-9315167f304f.htseq.counts.gz

* Data of white males in the age of 70-80:
1. 11797830-6218-43c6-8c41-515583575668.htseq.counts.gz
2. d79aad6b-f80d-4e0c-98f8-f367a4357e0c.htseq.counts.gz
3. d79aad6b-f80d-4e0c-98f8-f367a4357e0c.htseq.counts.gz
4. e4f35921-2d29-421a-91e4-5e06c7f851ec.htseq.counts.gz
5. c0cd55bb-9bec-4e83-a453-cc73637673eb.htseq.counts.gz
6. 95477845-1365-46a6-8c95-8f1ef05ddd0d.htseq.counts.gz
7. d2b31242-6431-4e3c-a663-e6583753e79a.htseq.counts.gz
8. b2e24e75-0895-4fab-8367-af1dc71e4a5e.htseq.counts.gz
9. b10ac900-f925-47e3-bb0a-0fbcf9d5ffc9.htseq.counts.gz
10. 92cc5466-7ae6-458a-80bf-2be5d81f8d37.htseq.counts.gz
11. b0a44ece-6cfe-4d2e-8048-c899516b882e.htseq.counts.gz
12. 0498d3e9-bf60-48ff-bf34-d9725718c576.htseq.counts.gz
13. ac37405d-dfae-4733-bbe6-157d7657023c.htseq.counts.gz
14. 786537c7-34b1-4d87-bbe4-f28b2df869b2.htseq.counts.gz
15. 94e2fc89-29f8-4a60-8d42-d43e01530839.htseq.counts.gz
16. 7b414ea9-1674-41c5-a0b2-5b1925ac9aec.htseq.counts.gz
17. 15c1d1b9-a970-451b-aef6-56bdab123674.htseq.counts.gz
18. 606312ce-9729-4adf-90f9-7fb2febf4dae.htseq.counts.gz
19. 9cc93369-3cc7-4293-9f42-a997c26243c9.htseq.counts.gz
20. 597e0bf5-b228-432f-b469-9498bb812f98.htseq.counts.gz

Milestone 1:
----------------
* Download a total of 40 datasets from the GCD data portal; import these datasets into R; process the datasets and integrate them into a format that meets the analysis standards. The above steps will be completed on November 3.

Milestone 2:
----------------
* Perform differential expression analysis on different data sets created in milestone 1 and get some plots and graphs. The above steps will be completed by November 12th.


Deliverable:
----------------
R MarkDown

