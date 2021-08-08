# Results & outcomes

* What results did the applied analyses yield?

### Hypothesis 1
* The first hypothesis was that functional connectivity differs between depressed patients and healthy controls.

### Hypothesis 2
* The second hypothesis was that replicating the methods that were used in the original study but using different analysis and preprocessing tools (mriqc, Nilearn, Nipype) would lead to different results regarding the differences in functional connectivity between depressed patients and healthy controls.

* Were there other outcomes of the project (e.g. software, etc.)?

## Results of the original study


* At first the main results of Bezmaternykh et al. (2021) regarding the differences in functional connectivity between the two groups were evaluated.
Bezmaternykh et al. (2021) performed an ICA (Table 2) and afterwards looked for connectivity differences (Table 3 & Figure 1) between the depressed and control group. They found decreased functional connectivity within the default mode network (DMN) which is not inline with the majority of other studies in this field. Moreover, a global increase of functional connectivity was found in the depressive group between the DMN and the executive control network (ECN). This is also not a typical finding for patients with depression. Another notable result was the overconnectivity of the medial visual cortex (mVis) with the audial cortex (AN) in the depressive group.

![Table 1 (Bezmaternykh et al., 2021, p. 5)]( https://github.com/Jakob236/notreadyyet/blob/master/project/Table%202%20Paper.PNG?raw=true)

![Table 2 (Bezmaternykh et al., 2021, p. 6)]( https://github.com/Jakob236/notreadyyet/blob/master/project/Table%203%20Paper.PNG?raw=true)

![Figure 1 (Bezmaternykh et al., 2021, p. 6)](  https://github.com/Jakob236/notreadyyet/blob/master/project/Figure%201%20Paper.PNG?raw=true)



## Results of our analysis



* In the table below the areas are listed that showed the biggest correlation coefficient differences when comparing both groups.


![Table 4 (Most important brain areas of the analysis)]( https://github.com/Jakob236/notreadyyet/blob/master/project/Our%20Results%20as%20Table%20-%20biggest%20differences.PNG?raw=true)
* To compare our results with the results of (Bezmaternykh et al., 2021) we needed to categorize the brain areas into the networks they belong to. 
  * Motor was categorized as sensorimotor network.
  * L Ant IPS was categorized as dorsal attention network.
  * Cing was categorized as default mode network.
  * V ACC was categorized as salience network.
  * R Par was categorized as default mode network.
  * Broca was categorized as language network.

* The table below displays the correlation coefficient differences within the default mode network (DMN).

![Table 5 (Results DMN)]( https://github.com/Jakob236/notreadyyet/blob/master/project/Our%20Results%20as%20Table%20-%20DMN.PNG?raw=true)
  
## Conclusion
* First, it was hypothesized that functional connectivity differs between depressed patients and healthy controls. This hypothesis is seen as confirmed because big differences in correlation were found for multiple brain areas.
Differences between the two groups are in line with Bezmaternykh et al. (2021) as well as with further studies.
The second hypothesis was that the use of different preprocessing and analysis tools would lead to different results. This hypothesis was confirmed too.
Bezmaternykh et al. (2021) found decreased connectivity for the depressed group within the default mode network (DMN). This was not the case in this analysis. DMN connectivity (R Par – Cing) was increased in the depressed group. When looking at broader areas rather than specific regions in the DMN, a higher correlation coefficient in the healthy group could only be found for L DMN - Front DMN, L DMN - R DMN and Med DMN - Front DMN.
Furthermore, big correlation coefficient differences were found between the groups for areas from the language network with the sensorimotor network (Broca - Motor), between the language network and the dorsal attention network (Broca - L Ant IPS) and the salience network and the sensorimotor network (V ACC - Motor). These results were not found in the original study.
In conclusion, functional brain connectivity differs between healthy and depressed subjects. This can be found in this study as well as in the study by Bezmaternykh et al. (2021) . However, the try replicate the concrete differences with different tools, was unsuccessful.
