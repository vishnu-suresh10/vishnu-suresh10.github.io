---
layout: project
type: project
image: images/micromouse.jpg
title: Positweet
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2019-04-06
labels:
  - NLP
  - Sentiment Analysis
  - Python
summary: My team developed an application that notified users if they had negative tweets on their twitter account.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/gallery.jpg">
  <img class="ui image" src="../images/gallery-2.jpg">
  <img class="ui image" src="../images/gallery-3.jpg">
</div>

My team developed an application that notified users if they had negative tweets on their twitter account.

Here is some code that illustrates how we read values from the line sensors:

```js
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

You can learn more on [Devpost](https://devpost.com/software/positweet-ijdez1).



