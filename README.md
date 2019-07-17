# List of Medical Datasets
I maintain this list mostly as a personal braindump of interesting medical datasets, with a focus on medical imaging.   
Rather than try to group / cluster datasets, I'm going to try to maintain a set of keywords for each.  
See [commit log](https://github.com/adalca/medical-datasets/commits/master) for a list of additions over time.

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
Need to request access  
**Keywords**: very-large, X-ray, labels

### [PadChest](http://bimcv.cipf.es/bimcv-projects/padchest/)
160,000 images from 67,000 patients that were interpreted and reported by radiologists   
labeled with 174 different radiographic findings,  19 differential diagnoses and 104 anatomic locations organized as a hierarchical taxonomy mapped to standard Unified Medical Language System (UMLS)  
**Keywords**: very-large, X-ray, labels

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

### [ABCD Neurocognitive Prediction Challenge](https://sibis.sri.com/abcd-np-challenge/)
MRI for 8500 yound (9-10yo) subjects (about 4100 for training)  
**Keywords**: large, MRI
  
### [MRNet](https://stanfordmlgroup.github.io/competitions/mrnet/)
1,370 knee MRI exams with diagonsis (healthy/ACL tear/meniscal tear)  
**Keywords**: large, MRI, labels

### [fastMRI](https://fastmri.med.nyu.edu/)
k-space data  
1500 fully sample knee MRIs and 10K clinical MRIs  
Part of a [challenge](http://fastmri.org/)  
**Keywords**: large, MRI, k-space

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

### [MRIdata](http://mridata.org/)
List of mri k-space datasets  

### [Studyforrest](http://studyforrest.org/data.html)
Few subjects, but many modalities (T1,T2,SWI,Angio,DWI, fMRI during Forrest Gump at 3T (audio+visual+eyetracking+physio) and 7T (audio+physio only), some audio tasks, and other important visual tasks)  
**Keywords**: small, multi-modal
  
### [Lung Image Database Consortium](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI)
LIDC-IDRI consists of diagonstic and lung cancer screening CTs.   
1018 cases with some Radiologist Annotations/Segmentations and nodule counts   
Also available through [LUng Nodule Analysis (LUNA) challenge](https://luna16.grand-challenge.org/data/)  
**Keywords**: large, CT, labels

  
### [UK Biobank](https://biobank.ctsu.ox.ac.uk/crystal/download.cgi)
[All imaging](http://biobank.ctsu.ox.ac.uk/crystal/search.cgi?wot=2&srch=imaging&sta0=on&sta1=on&sta2=on&sta3=on&sta4=on&str0=on&str3=on&fit0=on&fit10=on&fit20=on&fit30=on&fvt11=on&fvt21=on&fvt22=on&fvt31=on&fvt41=on&fvt51=on&fvt61=on&fvt101=on)  
[Fundus imaging](http://biobank.ctsu.ox.ac.uk/crystal/label.cgi?id=100016)  
**Keywords**: very-large
  
### [ADNI](http://adni.loni.usc.edu/)
Various imaging (longitudinal MRI), Genetics, Clinical data  
Several thousand patients  
**Keyworks**: large, MRI, genetics, clinical

### [Mindboggle](https://mindboggle.info/data.html)
Seems like 101 manually labelled brain MRIs  
**Keywords**: medium, MRI, brain, manual-segmentation


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

### [Longitudinal Neuroimaging on arithmetic processing in children](https://openneuro.org/datasets/ds001486/versions/1.2.1)  
[paper](https://www.nature.com/articles/sdata201940)  
3T fMRI 132 typical dev children, 2 time points, four tasks  
**Keywords**: medium, fMRI, longitudinal

### [ATLAS: Anatomical Tracings of Lesions After Stroke](http://fcon_1000.projects.nitrc.org/indi/retro/atlas.html)
229 T1-weighted MRI scans (n=220) with lesion segmentation  
MNI152 standard-space T1-weighted average structural template image  
A .csv file containing lesion metadata  
[paper](https://www.nature.com/articles/sdata201811)  
**Keywords**: medium, MRI, segmentations  

### [SIMON](http://fcon_1000.projects.nitrc.org/indi/retro/SIMON.html)
Single voluneer, 73 Sessions at multiple sites over ~17 years  
MRI, at least T1 at each session, with other modalities varying by session.  
Phenotype file provided  
**Keywords**: small, MRI, longitudinal

### [100 micron MRI of Human Brain](https://histopath.nmr.mgh.harvard.edu/images/?page=images)  
Single volume, ultra-high resolution MRI dataset (100-micron)  
**Keywords**: small, MRI


## Non-imaging

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
 