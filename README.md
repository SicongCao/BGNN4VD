# BGNN4VD:BGNN4VD: Constructing Bilateral Graph Neural-Network for Vulnerability Detection
Vulnerability detection is to automatically identify whethera target program is vulnerable or not and has became ahot research topic. Existing vulnerability detectors focus onusing machine learning to exploit features from source codeto detect vulnerabilities. However, these techniques highlyrely on human experts to construct vulnerability patternsand cause a higher false-positive rate.
In this work, we propose to construct a Bilateral GraphNeural-Network (BGNN) by introducing backward edges foraccommodating more information related to vulnerability.Then, we use the BGNN followed by a CNN to extract fea-tures for classification. We evaluate our approach on fouropen-source C/C++ projects, and the results show that ourapproach is more effective to detect vulnerabilities over thestate-of-the-art approaches. Furthermore, our approach candetect a number of the latest vulnerabilities reported by CVE.
