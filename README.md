# List of Medical (Imaging) Datasets
I maintain this list mostly as a personal braindump of interesting medical datasets, with a focus on medical imaging.   
Rather than try to group / cluster datasets, I'm going to try to maintain a set of keywords for each.  
See [commit log](https://github.com/adalca/medical-datasets/commits/master) for a list of additions over time.

Please feel free to contribute!

**Disclaimer**: please remember to solve real clinical problems ☺

## Main Medical Imaging List
  
### [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/)
224,316 chest radiographs of 65,240 patients, with labels from reports  
**Keywords**: very-large, X-ray, labels
  
### [ChestXray-NIHCC](https://nihcc.app.box.com/v/ChestXray-NIHCC)
100000 radiographs  
**Keywords**: very-large, X-ray, labels

### [MIMIC-CXR](https://physionet.org/physiobank/database/mimiccxr/)
371,920 chest x-rays associated with 227,943 imaging studies  
3/16/2019: Not yet linked with MIMIC ICU data. See [news article](http://news.mit.edu/2019/mimic-chest-x-ray-database-0201)  
v2: free-text radiology reports  
Need to request access  
**Keywords**: very-large, X-ray, labels

### [PadChest](http://bimcv.cipf.es/bimcv-projects/padchest/)
160,000 images from 67,000 patients that were interpreted and reported by radiologists   
labeled with 174 different radiographic findings,  19 differential diagnoses and 104 anatomic locations organized as a hierarchical taxonomy mapped to standard Unified Medical Language System (UMLS)   
**Keywords**: very-large, X-ray, labels

### [IBM Xray Eye Gaze](https://physionet.org/content/egd-cxr/1.0.0/)
1000+ dataset of eye gaze, radiological reports, dictation, segmentation on MICMIC-CXR Database  
[code](https://github.com/cxr-eye-gaze/eye-gaze-dataset) to reproduce experiments  
**Keywords**: medium, X-ray, labels

### [Cancer Image Archive](http://www.cancerimagingarchive.net/)
Several collections  
Tons of Images of various kinds, including CT, MR, Pathology, PT, with diagnoses  
**Keywords**: vary-large, CT, MR, labels
  
  
### [National Lung Screening Trial](https://wiki.cancerimagingarchive.net/display/NLST/National+Lung+Screening+Trial)
Part of Cancer Imaging Archive  
50000+ patients with CT data, some pathology, limited availability  
**Keywords**: very-large, CT, labels

### [DeepLesion](https://nihcc.app.box.com/v/DeepLesion)  
32000+ CT scans with annotations, meta-data, semantic labels from radiological reports  
**Keywords**: very-large, CT, labels

### [EchoNet-Dynamic](https://echonet.github.io/dynamic/)  
10,000+ labeled echocardiogram videos and human expert tracing  
**Keywords**: very-large, ultrasound, labels

### [ABCD Neurocognitive Prediction Challenge](https://sibis.sri.com/abcd-np-challenge/)
MRI for 8500 young (9-10yo) subjects (about 4100 for training)  
**Keywords**: large, MRI
  
### [AAPM Sparse-View CT Reconstruction Challenge](https://www.aapm.org/GrandChallenge/DL-sparse-view-CT/)
4,000 simulated sinogram/image pairs of 2D breast CTs
**Keywords**: large, CT, reconstruction

### [Cross-Sectional Multidomain Lexical Processing](https://openneuro.org/datasets/ds002236)
two large scale neuroimaging datasets on reading and language development  
Over 3000 MRI, fMRI  
[article](https://news.vanderbilt.edu/2020/01/10/vanderbilt-researcher-shares-more-than-3000-brain-scans-to-support-the-study-of-reading-and-language-development/amp/?__twitter_impression=true) | [more resources](https://osf.io/f5bde/)  
**Keywords**: large, MRI

### [Neurite-OASIS](https://github.com/adalca/medical-datasets/blob/master/neurite-oasis.md)
414 T1 MRIs from the OASIS dataset, processed using FreeSurfer and SAMSEG  
Includes original images, along with processed volumes and resulting anatomical segmentation maps  
**Keywords**: large, MRI, segmentations, labels, annotations, processed

### [MRNet](https://stanfordmlgroup.github.io/competitions/mrnet/)
1,370 knee MRI exams with diagonsis (healthy/ACL tear/meniscal tear)  
**Keywords**: large, MRI, labels

### [fastMRI](https://fastmri.med.nyu.edu/)
k-space data  
1500 fully sample knee MRIs and 10K clinical MRIs, and 6.5K brain MRIs.  
Part of a [challenge](http://fastmri.org/)  
**Keywords**: large, MRI, k-space

### [OCMR](https://ocmr.info/)
Open-Access Multi-Coil k-Space Dataset for Cardiovascular Magnetic Resonance Imaging  
k-space data, roughly 250 volumes  
**Keywords**: medium, MRI, k-space

### [PREVENT-AD](https://openpreventad.loris.ca/)  
1704 MRI, 556 amyloid and tau CSF samples, blood markers, genetic info and longitudinal cognitive data on ~400 at risk individuals  
**Keywords**: medium, MRI, genetics, labels  

### [Medical Segmentation Decathlon](http://medicaldecathlon.com)
10 Medical image datasets with segmentations  
2000+ CT & MR images of various organs from different sources  
**Keywords**: medium, MRI, segmentations  

### [MASSIVE](http://massive-data.org/download.html)  
Multiple Acquisitions for Standardization of Structural Imaging Validation and Evaluation  
8000 diffusion-weighted volumes  
10 3D FLAIR, T1-, and T2-weighted datasets of a single healthy subject  
**Keywords**: large, MRI

### [AOMIC: the Amsterdam Open MRI Collection](https://nilab-uva.github.io/AOMIC.github.io/)
1000+ fMRI and other modalities subjects with annotated event files; raw and preprocessed  
**Keywords**: medium, fMRI

### [MRIdata](http://mridata.org/)
List of mri k-space datasets  

### [Cancer Imaging Archive: LDCT](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=52758026)
601 series of CT projection data, reconstructed images, and clinical data reports
**Keywords**: medium, CT, reconstruction

### [Brain MRI LGG FLAIR abnormality segmentation](https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation)
Brain MRI images together with manual FLAIR abnormality segmentation masks  
110 subjects from TCIA LGG collection with lower-grade glioma cases  
**Keywords**: medium, brain, MRI, segmentation, LGG, FLAIR

### [Studyforrest](http://studyforrest.org/data.html)
Few subjects, but many modalities (T1,T2,SWI,Angio,DWI, fMRI during Forrest Gump at 3T (audio+visual+eyetracking+physio) and 7T (audio+physio only), some audio tasks, and other important visual tasks)  
**Keywords**: small, multi-modal
  
### [Lung Image Database Consortium](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI)
LIDC-IDRI consists of diagonstic and lung cancer screening CTs.   
1018 cases with some Radiologist Annotations/Segmentations and nodule counts   
Also available through [LUng Nodule Analysis (LUNA) challenge](https://luna16.grand-challenge.org/data/)  
**Keywords**: large, CT, labels

### [Breast Cancer MRI Dataset](https://sites.duke.edu/mazurowski/resources/breast-cancer-mri-dataset/)  
922 breast cancer patients publicly available for machine learning and clinical research.  
Contains breast MRIs, clinical, demographics, pathology, treatment, outcomes, and genomic data as well as image annotations (locations) and features.  
**Keywords**: large, MRI, labels
  
### [UK Biobank](https://biobank.ctsu.ox.ac.uk/crystal/download.cgi)
[All imaging](http://biobank.ctsu.ox.ac.uk/crystal/search.cgi?wot=2&srch=imaging&sta0=on&sta1=on&sta2=on&sta3=on&sta4=on&str0=on&str3=on&fit0=on&fit10=on&fit20=on&fit30=on&fvt11=on&fvt21=on&fvt22=on&fvt31=on&fvt41=on&fvt51=on&fvt61=on&fvt101=on)  
[Fundus imaging](http://biobank.ctsu.ox.ac.uk/crystal/label.cgi?id=100016)  
**Keywords**: very-large
  
### [OpenOrganelle](https://openorganelle.janelia.org/about)  
high resolution tissue-scale volume electron microscopy (vEM) datasets acquired with the enhanced focused ion beam scanning electron microscopy (FIB-SEM) technology developed at Janelia. Accompanying these EM volumes are automated segmentations and analyses of intracellular sub-structures.  
**Keywords**: very large, EM, segmentation

### [BrixIA: COVID19 severity score assessment databse](https://brixia.github.io/)  
4703 CXR of COVID19 patients,  manually annotated Brixia score  
**Keywords**: large, x-ray, covid

### [COVID-CT](https://github.com/UCSD-AI4H/COVID-CT)  
349 CT images collected from several COVID19-related papers  
Image captions  
**Keywords**: medium, CT, covid



### [Penumonia X-Ray](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
~5000 xrays  
**Keywords**: medium, x-ray, pneumonia

### [Medical Imaging Data Resource Center (MIDRC)](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70230281)
998 Chest x-ray examinations from 361 COVID+ patients.
Annotations with appearance classification and Airspace Disease Grading
Clinical variables
**Keywords**: large, x-ray, covid

### [BIMCV-COVID19](http://bimcv.cipf.es/bimcv-projects/bimcv-covid19/)
1350+ Xrays, 150+ CTs, 800 diagnoses  
**Keywords**: medium, CT, covid

### [MosMedData Covid19](https://mosmed.ai/en/)
1000+ CTs of COVID19 patients  
50 are annotated per pixel  
**Keywords**: large, CT, covid, segmentations


### [COVID-19 LUNG CT LESION SEGMENTATION CHALLENGE](https://covid-segmentation.grand-challenge.org/Data/)
~250 chest CTs with positive RT-PCR SARS-CoV-2, annotations of COVID-19 lesions
**Keywords**: medium, CT, covid, annotations, segmentations

### [MedSeg COVID-19 CT](http://medicalsegmentation.com/covid19/)
~100 segmented CT slices  
**Keywords**: medium, CT, segmentations, covid

### [COVID-Chest XRay](https://github.com/ieee8023/covid-chestxray-dataset)
~150 xrays, ongoing, some hospital data  
**Keywords**: medium, x-ray, covid

### [BSTI COVID19](https://bsticovid19.cimar.co.uk/worklist/?embedded=)
ongoing, about 60 patients at last check, CT  
[paper pdf](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7138155/)  
**Keywords**: medium, CT, covid


### [Narratives fMRI](http://datasets.datalad.org/?dir=/labs/hasson/narratives)
345 subjects, 891 functional scans, and 27 diverse stories of varying duration totaling ~4.6 hours of unique stimuli (~43,000 words).  
[Nature paper](https://www.nature.com/articles/s41597-021-01033-3?)  
**Keywords**: medium, fMRI

### [RICORD](https://www.rsna.org/covid-19/COVID-19-RICORD/RICORD-resources)
1000 X-rays and 240 CTs with annotations ([paper](https://pubs.rsna.org/doi/10.1148/radiol.2021203957))  
**Keywords**: large, CT, covid, segmentations


### [FIRE (Fundus Image Registration Dataset)](https://paperswithcode.com/dataset/fire)
129 retinal images.  
**Keywords**: small, fundus


### [DRIVE: Digital Retinal Images for Vessel Extraction](https://drive.grand-challenge.org/)
40 retinal images with segmentations  
**Keywords**: small, retinal, segmentations


### [FLARE: Fast and Low GPU memory Abdominal oRgan sEgmentation](https://flare.grand-challenge.org/)  
500+ CT scans from 11+ countries with Abdominal Organ Segmentation (the liver, kidney, spleen, and pancreas)  
**Keywords**: large, abdominal, CT


### [ADNI](http://adni.loni.usc.edu/)
Various imaging (longitudinal MRI), Genetics, Clinical data  
Several thousand patients  
**Keyworks**: large, MRI, genetics, clinical


### [VISCERAL](http://www.visceral.eu/)  
~120 image volumes (whole body CT and MRI images)  
more than 1900 annotated anatomical structures  
**Keywords**: medium, MRI, CT, whole-body, manual-segmentation


### [Mindboggle](https://mindboggle.info/data.html)
Seems like 101 manually labelled brain MRIs  
**Keywords**: medium, MRI, brain, manual-segmentation


### [Cross-Sectional Multidomain Lexical Processing](https://openneuro.org/datasets/ds002236/versions/1.1.0)
3000 brain scans (T1w, bold, events)   
Standardized tests, scores, demographics  
**Keywords**: large, MRI, fMRI, tests

### [Duke Breast Cancer Screening DBT](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=64685580#64685580bcab02c187174a288dbcbf95d26179e8)
A curated dataset of digital breast tomosynthesis images from 5,060 patients.  
**Keywords**: large, tomosynthesis, DBT, breast, detection

### [CBIS-DDSM (Curated Breast Imaging Subset of DDSM)](https://wiki.cancerimagingarchive.net/display/Public/CBIS-DDSM)
2600+ scanned film mammography studies  
**Keywords**: large, x-ray

### [Neuromorphometrics](http://www.neuromorphometrics.com/?page_id=23#academic)
63 manually labelled brain scans.
Costs ($1500?)
[Discussion](https://www.nitrc.org/forum/message.php?msg_id=8792)  
**Keywords**: medium, MRI, brain, manual-segmentation, costly

### [Automatic Non-rigid Histological Image Registration](https://anhir.grand-challenge.org)
This is a challenge for ISBI2019  

### [7-Tesla rs-fMRI](http://academictorrents.com/details/5fc2f273123336ee34b9ea635ef8440377a42888)
22 particiapnts with cognitive and physiological mreasures, and 7T rs-fMRI  

### [SpineWeb](http://spineweb.digitalimaginggroup.ca/)
200+ subjects across several datasets (CTs, Xrays, MRIs)  

### [Whole-Heart and Great Vessel Segmentation from 3D Cardiovascular MRI in Congenital Heart Disease](http://segchd.csail.mit.edu/data.html)
20 cardiac MR images in Congenital Heart Disease  

### [Longitudinal Neuroimaging in Children](https://openneuro.org/datasets/ds001894/)
[paper](https://www.nature.com/articles/s41597-019-0338-5)  
~50 children (~10yo) with single follow-up with MRI, fMRI and assesments  
**Keywords**: medium, fMRI, longitudinal

### [Longitudinal Neuroimaging on arithmetic processing in children](https://openneuro.org/datasets/ds001486)  
[paper](https://www.nature.com/articles/sdata201940)  
3T fMRI 132 typical dev children, 2 time points, four tasks  
**Keywords**: medium, fMRI, longitudinal

### [Narratives](https://openneuro.org/datasets/ds002245/versions/1.0.2)  
aggregates auditory story-listening fMRI datasets acquired over the course of roughly seven years  
**Keywords**: medium, fMRI  

### [ATLAS: Anatomical Tracings of Lesions After Stroke](http://fcon_1000.projects.nitrc.org/indi/retro/atlas.html)
229 T1-weighted MRI scans (n=220) with lesion segmentation  
MNI152 standard-space T1-weighted average structural template image  
A .csv file containing lesion metadata  
[paper](https://www.nature.com/articles/sdata201811)  
**Keywords**: medium, MRI, segmentations  


### [MITOS_WSI_CMC](https://github.com/DeepPathology/MITOS_WSI_CMC/)
21 Canine mammary carcinoma whole slide images.  
Annotated by 2/3 experts
**Keywords**: small, 2D, whole slide imaging


### [FeTA Dataset](http://neuroimaging.ch/feta)
48 manually annotated in utero fetal MR   
**Keywords**: small, mri, fetal, labels

### [SIMON](http://fcon_1000.projects.nitrc.org/indi/retro/SIMON.html)
Single voluneer, 73 Sessions at multiple sites over ~17 years  
MRI, at least T1 at each session, with other modalities varying by session.  
Phenotype file provided  
**Keywords**: small, MRI, longitudinal

### [BigBrain](https://bigbrain.loris.ca/main.php)  
Single volume, histological  space , 100 micron) with GM/WM surfaces and [cortical layers](https://twitter.com/KonradWagstyl/status/1246467305372037121)  
ftp://bigbrain.loris.ca | [interactive](https://bigbrain.humanbrainproject.org/)  
**Keywords**: small, histology, high-resolution, segmentations


### [100 micron MRI of Human Brain](https://histopath.nmr.mgh.harvard.edu/images/?page=images)  
Single volume, ultra-high resolution MRI dataset (100-micron)  
**Keywords**: small, MRI, brain


### [Natural Scenes Dataset (CMRR initiative)](http://www.naturalscenesdataset.org/)
8-subjects large-scale fMRI (40-sessions, high sampling, high resolution). T1w, T2w, T2*w MRI  
[Video](https://www.youtube.com/watch?v=wD9BCMKb2Qg&feature=youtu.be) description    
**Keywords**: small, MRI, brain, fMRI

### [Brain Catalogue](https://braincatalogue.org/)  
(ex-vivo) brain MRIs or brains of different animals  
**Keywords**: small, MRI, brain, animals

### [Multishell diffusion](https://figshare.com/articles/Multicenter_dataset_of_multishell_diffusion_magnetic_resonance_imaging_in_healthy_traveling_adults_with_identical_setting/8851955)
Three Diffusion of healthy traveling adults  
**Keywords**: small, MRI, diffusion, brain


### [Pre-Natal MRI](https://f1000research.com/articles/6-93/v2)
Prenatal brain MRI samples (looks like single subject?)  
**Keywords**: small, MRI, fetal

### [BCNB: Early Breast Cancer Core-Needle Biopsy WSI Dataset](https://bupt-ai-cz.github.io/BCNB/)
1058 wholes slide images (WSIs) with corresponding clinical characteristics  
Part of tumor regions are annotated in WSIs.  
Clinical characteristics include age, tumor size, tumor type, ER, PR, HER2, HER2 expression, histological grading, surgical, Ki67, molecular subtype, number of lymph node metastases, and ALN status  
[Paper reference](https://arxiv.org/abs/2112.02222)  
**Keywords**: large, breast cancer, multi-modal, WSI, clinical characteristics


## Non-imaging

### [PhysioNet / Pulmonary Edema Severity Grades Based on MIMIC-CXR](https://physionet.org/content/mimic-cxr-pe-severity/)
This dataset is curated based on [MIMIC-CXR](https://mimic-cxr.mit.edu/), containing 3 metadata files that consist of pulmonary edema severity grades extracted from the MIMIC-CXR dataset through different means: 1) by regular expression (regex) from radiology reports, 2) by expert labeling from radiology reports, and 3) by consensus labeling from chest radiographs. <br />
**Keywords**: pulmonary edema, severity grades, chest x-ray, radiology reports, MIMIC-CXR

### [PhysioNet / Computing in Cardiology 2019 Challenge](https://physionet.org/challenge/2019/)
predict sepsis in an ICU population  
5000 ICU patients in three separate hospital systems  

### [eICU-CRD](https://eicu-crd.mit.edu/)
detailed information about critical care stays for over 200,000 admissions at 200+ hospitals across the US.  
With access to MIMIC, can access eICU-CRD immediately after signing an updated DUA.  
[paper](https://www.nature.com/articles/sdata2018178)  


## Non-medical but useful / fun

[Moment in time](http://moments.csail.mit.edu/)


## Other lists or pooling resources ([relevant xkcd](https://xkcd.com/927/))

 - Giorgos Sfikas: medical imaging datasets on [github](https://github.com/sfikas/medical-imaging-datasets)  
 - Andy Beam: medical data on [github](https://github.com/beamandrew/medical-data)  
 - Christopher Madan: [openMorph](https://github.com/cMadan/openMorph) (open-access MRI, well structured list)
 - Stephen Aylward's list of open-Access [Medial Image Repositories](http://www.aylward.org/notes/open-access-medical-image-repositories)
 - [google dataset search](https://toolbox.google.com/datasetsearch)  
 - [grand-challenges](https://www.grand-challenge.org)
 - [academic torrents](http://academictorrents.com/)
 - [multiBrain](https://github.com/Conxz/multiBrain)  
 - [openneuro](https://openneuro.org/) databse  
    Note the nice ["fast preview" feature](https://openneuro.org/datasets/ds001715/versions/1.0.0/file-display/sub-03:anat:sub-03_T1w.nii.gz)  
 - [The Cancer Image Archive](http://www.cancerimagingarchive.net/)
 - [Cornell Public Image Databases](http://www.via.cornell.edu/databases/)  
 
