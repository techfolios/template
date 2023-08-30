---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "NavyCoreValues"
date: 2023-08-29
published: true
labels:
  - Honor
  - Courage
  - Committment
summary: "What it means to be a United States Navy sailor."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Being a United States Navy sailor embodies the values of honor, courage, and commitment, forming the bedrock of one's service to the nation. Honor serves as the moral compass that guides every direction and decision. Sailors hold themselves to the highest standards of integrity, demonstrating unwavering honesty an accountability in all endeavors. They recognize that their actions not only reflect their personal character but also the reputation of the Navy as a whole. Upholding honor means fostering an environment of trust and respsect among fellow sailors and the global community, regardless of the challenges faced.

Courage stands an dindomitable trait that defines Navy sailors. They face adversity head-on, whether it's the demands of their duties or confronting daunting situations at sea. Courage means acting without hesitation to protect their shipmates, defend their country's interests, and uphold the principles they hold dear. Commitment is the unwavering dedication that Navy sailors bring to their roles, day in and day out. It's a pledge to serve their nation with unwavering loyalty and to contribute their skills and efforts to the greater mission. Hooyah.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
