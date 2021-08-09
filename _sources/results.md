## 1 Hypotheses

### Hypothesis 1
   Delta and theta oscillations are increased in schizophrenic patients during rest.
### Hypothesis 2
   Alpha oscillations are reduced in schizophrenic patients during rest.
### Hypothesis 3
   Beta oscillations are reduced in schizophrenic patients during rest.
### Hypothesis 4
   Gamma oscillations are increased in schizophrenic patients during rest.

## 2 Results & Outcomes

Here we present you our results of Preprocessing, ICA and frequency-band analysis.

### 2.1 Preprocessing and ICA

For Preprocessing we used a bandpass filter with 0,5 and 45 Hz.
For the ICA we used seven components to identify and exclude eye movement artifacts.
Here, you can see one example of an ICA result of schizophrenic patient #1.
In this example, we concluded that component #000 and #002 might be such artifacts of interest but because of the more central distribution of the activity in #000 which makes it more unclear we excluded only #002. For components #004 and #006 we observe a relatively strong temporal and parietal shift of the activity but didn't exclude those because we couldn't identify them as artifacts.

![grafik](https://user-images.githubusercontent.com/83219542/128736569-e46067eb-2710-4e97-b840-f2ff2681f567.png)

### 2.2 Average delta activity and critical electrodes

For delta activity (1-4 Hz; vmin: 0.03, vmax: 0.07) in schizophrenic patients we observe a reduced frontotemporal activity compared to healthy controls. Here, the three electrodes of interest are F8, F7 and Cz whereby F8 shows the highest difference. Yet, the differences for Cz as well as for F7 and F8 are not significant after independent t-test. However, for F8 the test value tends to significance (p = 0.054).

![grafik](https://user-images.githubusercontent.com/83219542/128730869-f80b7611-752b-4359-aeab-5d8ecc4d5a7e.png)

![grafik](https://user-images.githubusercontent.com/83219542/128731576-b18a074d-7abd-47fd-ac2e-e306a52af4ba.png)
   - F8: test_indResult(statistic=2.015, pvalue=0.054)
   - F7 and Cz were not approximately significant

### 2.3 Average theta activity and critical electrodes

For theta activity (4-9 Hz; vmin: 0.02, vmax: 0.03) in schizophrenic patients we observe a reduced central activity compared to healthy controls. Here, the two electrodes of interest are Fz and Cz whereby Cz shows a slightly greater difference. After independent t-test, the Cz difference doesn't show any signficance (p = 0.342).

![grafik](https://user-images.githubusercontent.com/83219542/128731826-4901ba0f-aa02-430b-9552-131e51ec6ce7.png)

![grafik](https://user-images.githubusercontent.com/83219542/128731876-3009968f-7d1a-445b-9a42-6ed28317705b.png)
   - Fz was not approximately significant
   - Cz: Ttest_indResult(statistic=0.968, pvalue=0.342)

### 2.4 Average alpha activity

For alpha activity (9-12 Hz; vmin: 0.03, vmax: 0.07) in schizophrenic patients we observe a slightly stronger and more distributed activity overall compared to healthy controls. Yet here, the differences for all electrodes are too small for any significance. Generally spoken, alpha activity is more present in the occipital lobe.

![grafik](https://user-images.githubusercontent.com/83219542/128732054-8d7a5181-eadf-4505-b485-37c377930fd4.png)
   - none of the electrode differences was approximately significant

### 2.5 Average beta activity and critical electrode

For beta activity (12-30 Hz; vmin: 0.006, vmax: 0.009) in schizophrenic patients we observe a reduced tempoparietal activity compared to healthy controls. Here, the only electrode of interest is T5. However, the difference for T5 is not significant after independent t-test (p = 0.554).

![grafik](https://user-images.githubusercontent.com/83219542/128732252-61fd9537-a678-4f46-8144-53805e8f983b.png)

![grafik](https://user-images.githubusercontent.com/83219542/128732305-8f24b93b-e6ea-4183-91a4-2e0613e911ad.png)
   - T5: Ttest_indResult(statistic=0.601, pvalue=0.554)

### 2.6 Average gamma activity and critical electrodes

For gamma activity (30-45 Hz; vmin: 0.001, vmax: 0.005) in schizophrenic patients we observe an increased temporal activity compared to healthy controls. Here, the two electrodes of interest are T4 and T3. After independent t-test, both of the electrodes show no significance (T4: p = 0.075; T3: p = 0.085) but have a trend to.

![grafik](https://user-images.githubusercontent.com/83219542/128732639-3e6aaada-a5bf-401e-aa78-5e8ae1f7971c.png)

![grafik](https://user-images.githubusercontent.com/83219542/128732707-e913c178-3fd3-4fbc-b48c-d55c2820fe73.png)
   - T4: Ttest_indResult(statistic=-1.859, pvalue=0.075)
   - T3: Ttest_indResult(statistic=-1.812, pvalue=0.085)
