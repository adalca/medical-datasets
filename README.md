# List of Medical Datasets
I maintain this list mostly as a personal braindump of interesting medical datasets, with a focus on medical imaging.   
Rather than try to group / cluster datasets, I'm going to try to maintain a set of keywords for each.

**Disclaimer**: please remember to solve real clinical problems ☺

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

## Main Medical Imaging List
  
### [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/)
224,316 chest radiographs of 65,240 patients, with labels from reports  
**Keywords**: very-large, X-ray, labels
  
### [ChestXray-NIHCC](https://nihcc.app.box.com/v/ChestXray-NIHCC)
100000 radiographs  
**Keywords**: very-large, X-ray, labels

### [Cancer Image Archive](http://www.cancerimagingarchive.net/)
Several collections  
Tons of Images of various kinds, including CT, MR, Pathology, PT, with diagnoses  
**Keywords**: vary-large, CT, MR, labels
  
  
### [National Lung Screening Trial](https://wiki.cancerimagingarchive.net/display/NLST/National+Lung+Screening+Trial)
Part of Cancer Imaging Archive  
50000+ patients with CT data, some pathology, limited availability  
**Keywords**: very-large, CT, labels

### [ABCD Neurocognitive Prediction Challenge](https://sibis.sri.com/abcd-np-challenge/)
MRI for 8500 yound (9-10yo) subjects (about 4100 for training)  
**Keywords**: large, MRI
  

### [fastMRI](https://fastmri.med.nyu.edu/)
k-space data  
1500 fully sample knee MRIs and 10K clinical MRIs  
Part of a [challenge](http://fastmri.org/)  
**Keywords**: large, MRI, k-space

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
more than 200 subjects across several datasets (CTs, Xrays, MRIs)  

### [Whole-Heart and Great Vessel Segmentation from 3D Cardiovascular MRI in Congenital Heart Disease](http://segchd.csail.mit.edu/data.html)
20 cardiac MR images in Congenital Heart Disease  

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
