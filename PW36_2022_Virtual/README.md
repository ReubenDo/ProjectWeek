## Welcome to the web page for the 36th Project Week!

[This event](https://projectweek.na-mic.org/PW36_2022_Virtual/) will be held virtually January 17-21, 2022. 

If you have any questions, you can contact the [organizers](../README.md#who-to-contact).

## How to participate
1. Register [here](https://forms.gle/1zE3pDs59sJ4ENP96), it is free!
2. Attend one or more preparation meetings (see next section) to present a project you intend to work on at PW, for which you are seeking collaborators or to join one of the projects proposed by others.
3. Optionally attend a training workshop on the use of MONAILabel with 3D Slicer on AWS cloud resources on January 12 (the week before Project Week) 2-4pm EST.  To attend please [register here](https://forms.gle/sekN29otUGDrVALF6).

## Preparation meetings
We hold weekly preparation meetings at 10am on Tuesdays, starting Nov 9th, 2021 and ending on December 8. Please join at [this link](https://etsmtl.zoom.us/j/86211702920?pwd=TEl0ZTFDam90WVN5bjZhR05kNVRVZz09) if you have a project that you would like to present or work on during project week or to find out about projects you can join.

Tentative schedule (may change each week):
* Nov 9 2021 - Kickoff meeting
* Nov 16 2021 - Cancer Imaging with Machine Intelligence and Data Science
* Nov 23 2021 - Slicer in the cloud
* Nov 30 2021 - Slicer in the cloud (continued) + User interfaces for annotation of corresponding landmarks in a longitudinal time series
* Dec 7 2021 - Low cost IGT systems
* Dec 14 2021 - Low cost IGT systems (continued), other projects
* Dec 21 2022 - All projects, project pages
* Jan 4 2022 - All projects, project pages
* Jan 11 2022 - AR, VR and rendering
* Jan 12 2022 - MONAILabel 3D Slicer AWS workshop (see [item 3 above](#how-to-participate))

##  Agenda

<div id="calendar-container">
</div>

<!--
Adapted from https://stackoverflow.com/questions/31821974/support-user-time-zone-in-embedded-google-calendar
-->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jstimezonedetect/1.0.7/jstz.min.js" integrity="sha512-pZ0i46J1zsMwPd2NQZ4IaL427jXE2RVHMk3uv/wPTNlBVp9AbB1L65/4YdrXRPLEmyZCkY9qYOOsQp44V4orHg==" crossorigin="anonymous"></script>

<!--
<iframe id="calendar-container" src="https://calendar.google.com/calendar/embed?src=kitware.com_sb07i171olac9aavh46ir495c4%40group.calendar.google.com&ctz=Atlantic&mode=WEEK&dates=20210628%2f20210702" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
-->
<script type="text/javascript">
  var timezone = jstz.determine();
  var iframe_src = 'https://calendar.google.com/calendar/embed?src=kitware.com_sb07i171olac9aavh46ir495c4%40group.calendar.google.com&mode=WEEK&dates=20220117%2f20220121&ctz=' + timezone.name()
  var iframe_html = '<iframe src="' + iframe_src + 'style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>'
  document.getElementById('calendar-container').innerHTML = iframe_html;
</script>

[How to add this calendar to your own?](../common/Calendar.md)

## Projects [(How to add a new project?)](Projects/README.md)
    
### VR/AR and Rendering    
1. [Collaborative Slicer session](Projects/SlicerCollaboration/README.md) (Csaba Pinter, Mónica Garcia, Jean-Christophe Fillion-Robin)
2. [AR in Slicer](https://github.com/NA-MIC/ProjectWeek/tree/master/PW36_2022_Virtual/Projects/AR%20in%20Slicer) (Alicia Pose Díez de la Lastra, Javier Pascau, Gabor Fichtinger, Andras Lasso, Adam Rankin, Csaba Pinter, Lucas Gandel, Jean-Christophe Fillion-Robin)
3. [Slicer TMS Module](Projects/SlicerTMS_Module/README.md) (Loraine Franke, Lipeng Ning, Yogesh Rathi, Steve Pieper, Raymond Yang, Daniel Haehn)
4. [PRISM Rendering](Projects/PRISMRendering/Readme.md) (Simon Drouin, Steve Pieper, Andrey Titov, Rafael Palomar)
    
### Image-guided therapy and low cost systems   
1. [GPU Rigid Registration](Projects/GPURigidRegistration/Readme.md) (Gelel Rezig, Houssem Gueziri, Simon Drouin)
2. [Low-Cost Ultrasound Training](Projects/LowCostUltrasoundTraining/README.md) (David Garcia Mato, Csaba Pinter, Rebecca Hisey, Matt McCormick, Steve Pieper, ...)
   
### Cloud
1. [Body Part Regression using IDC](Projects/IDCBodyPartRegression/README.md) (Deepa Krishnaswamy, Andrey Fedorov)
   
### Annotation/segmentation
1. [Spine Segmentation](Projects/SpineSegmentation/README.md) (Ron Alkalay, Steve Pieper, ...)
1. [MR-US landmark placement interface](Projects/AnnotationMR-US/Readme.md) (Fryderyk Kögl, Harneet Cheema, Tina Kapur, Simon Drouin)
1. [Automatic Landmark Identification in 3D Cone-Beam Computed Tomography scans](Projects/ALICBCT/README.md) (Maxime Gillot, Baptiste Baquero, Antonio Ruellas, Marcela Gurgel, Elizabeth Biggs, Marilia Yatabe, Jonas Bianchi, Lucia Cevidanes, Juan Carlos Prieto)
1. [ALIIOS - Automatic Landmarks Identification for Intra OralScans](Projects/ALIDDM/README.md) (Baptiste Baquero, Maxime Gillot, Lucia Cevidanes, Juan Carlos Prieto, Najla Al Turkestani, Marcela Gurgel, Camila Massaro, Aron Aliaga, Maria Antonia Alvarez Castrillon, Marilia Yatabe, Jonas Bianchi, Juan Fernando Aristizabal, Diego Rey, Antonio Ruellas)


### Infrastructure
1. [SlicerPipelines](Projects/SlicerPipelines/README.md) (Connor Bowley, Sam Horvath)
1. [Slicer Internationalization](Projects/SlicerInternationalization/README.md)

## Registrants

Do not add your name to this list below. It is maintained by the organizers based on your registration. [Register here](https://forms.gle/1zE3pDs59sJ4ENP96).

List of registered participants so far (names will be added here after processing registrations):
    
1.	Steve Pieper	,	Isomics, Inc.	,	USA
1.	HINA SHAH	,	UNC Chapel Hill	,	USA
1.	YAHYA TFEIL	,	UNIVERSITY OF NOUAKCHOTT ALASSRIYA	,	Mauritania
1.	Monica García Sevilla	,	Universidad de Las Palmas de Gran Canaria	,	Spain
1.	Rafael Palomar	,	Oslo University Hospital / NTNU	,	Norway
1.	Ismail Irmakci	,	Feinberg School of Medicine - Northwestern University	,	USA
1.	Miguel Xochicale	,	King's College London	,	United Kingdom
1.	Adama Rama WADE	,	École Supérieure Polytechnique (ESP)	,	Senegal
1.	Li Zhenzhu	,	Department of Neursosurgery, Hwa Mei Hospital, University of Chinese Academy of Sciences, Ningbo, China；	,	China
1.	Gang Fu	,	Amazon	,	USA
1.	Maxime Gillot	,	University of Michigan	,	USA
1.	Baptiste Baquero	,	University of Michigan	,	USA
1.	Simon Drouin	,	École de technologie supérieure	,	Canada
1.	Tina Kapur	,	Brigham and Women's Hospital, Harvard Medical School	,	USA
1.	Loraine Franke	,	University of Massachusetts Boston	,	USA
1.	Harneet Cheema 	,	Brigham and Women's Hospital and Harvard Medical School, U Ottawa	,	Canada
1.	Fryderyk Kögl	,	Brigham and Women's Hospital and Harvard Medical School, Technical University of Munich	,	USA
1.	Sonia Pujol	,	Brigham and Women's Hospital,  Harvard Medical School	,	USA
1.	Daniel Haehn	,	University of Massachusetts Boston	,	USA
1.	Juan Ruiz-Alzola	,	Universidad de Las Palmas de Gran Canaria	,	Spain
1.	Felix von Haxthausen	,	University of Lübeck	,	Germany
1.	Deepa Krishnaswamy	,	Brigham and Women's Hospital	,	USA
1.	Antonio Cartón	,	Hospital Universitario La Paz	,	Spain
1.	Yi Shen	,	HIT	,	China
1.	Ahmedou Moulaye IDRISS	,	Faculty of Medicine, University of Nouakchott Al Asriya	,	Mauritania
1.	Csaba Pinter	,	EBATINCA / Pixel Medical	,	Spain
1.	Adam Wittek	,	The University of Western Australia	,	Australia
1.	Reuben Dorent	,	King's College London	,	United Kingdom
1.	David García-Mato	,	Ebatinca S.L.	,	Spain
1.	Rebecca Hisey	,	Queen's University	,	Canada
1.	Leah Groves	,	Queens University 	,	Canada

## History
Please read about our experience in running these events since 2005: [Increasing the Impact of Medical Image Computing Using
Community-Based Open-Access Hackathons: the NA-MIC and 3D Slicer Experience](http://perk.cs.queensu.ca/sites/perkd7.cs.queensu.ca/files/Kapur2016.pdf).
