## **Techniques**

The Frontend is based on GitDataV framwork using Vue-cli and Vue 2 to build and also use the following 3-th party library:

 ● ECharts

● Element-Ui

● Vue-Worldcloud

● Animate.css

● Axios

Besides, the animation are with the help of setInterval function and the watch function whitch can fetch the updating data in real-time.

### Visualization

#### **General** View

The whole data is shown in this view clearly.

![img](https://docimg2.docs.qq.com/image/AgAACLEozRlPN5ESoN9FD6ri8p1vl1x9.png?w=1920&h=942)

#### **Charts**

We uses many kinds of charts and each of them has different functions.

1. Wordcloud chart (made with Vue-Worldcloud)

This wordcloud chart shows the hot issue topics and the topic which mentioned more will be bigger in the view.

![img](https://docimg10.docs.qq.com/image/AgAACLEozRmKBgpvFuBAX7X1cUzXhy11.png?w=459&h=263)

2. Pie chart (made with ECharts)

This pie chart shows the detail proportion of the top ten hot topics.

![img](https://docimg5.docs.qq.com/image/AgAACLEozRnnrKR7W-FNNohcyKSBW3dh.png?w=447&h=336)

3. Line chart (made with ECharts)

There are three line sharts. The top-left chart shows the commit times by time, like morning, forenoon and so on. The top-right chart shows the commit times by each day in a week. The bottom chart shows the commit times between two releases.![img](https://docimg3.docs.qq.com/image/AgAACLEozRlGmOfLVwpJV5r3h5aJu5ua.png?w=1069&h=736)

4. Form chart (made with ECharts)

This form chart shows the typical issue resolution time including average time, range time and variance time. 

![img](https://docimg4.docs.qq.com/image/AgAACLEozRmNOhWjAj1HcrkCso7DcyyO.png?w=454&h=119)

5. Ranking (made with ECharts)

This ranking form shows the commit authors' s name and their commit times which also sorted by the commit times.

![img](https://docimg1.docs.qq.com/image/AgAACLEozRmQ2zjhjw5FWrXS_aOAov--.png?imageMogr2/thumbnail/1600x%3E/ignore-error/1)

#### **User Interact**

1. Search

When user view hom many commit times between twe releases, he can choose how many releases he want to see.

![img](https://docimg1.docs.qq.com/image/AgAACLEozRnxkGj08vNI5pkWAHAphsN3.png?w=989&h=358)

2. Check

**range check**

Since the releases number is limited, when searching, if the search release number is larger then the true release number, it will give a warning.

![img](https://docimg8.docs.qq.com/image/AgAACLEozRlfQ51bCfBG_JYdJSw-qaSr.png?w=1425&h=942)

**number check**

Besides, if the user put some invalid number like alphabet, it will also give a warning.

![img](https://docimg6.docs.qq.com/image/AgAACLEozRkZW4T6oMBDAZD6fNqpiDXX.png?w=1421&h=942)

3. Highlight

The echarts can auto focus on one series of data and highlight them, just like this.

![img](https://docimg9.docs.qq.com/image/AgAACLEozRmCxkCuojpHCKbfy6LenAtw.png?w=449&h=332)

![img](https://docimg9.docs.qq.com/image/AgAACLEozRmSI_V-_v5GxbykAEFp6Duz.png?w=512&h=300)

4. Change repository

There are four repositories, and if the user want to change the repository, he can change it commodiously, just like the following shows.

![img](https://docimg4.docs.qq.com/image/AgAACLEozRnLtBwBsUBMwrTJ-U66g7vA.png?w=1920&h=942)

![img](https://docimg8.docs.qq.com/image/AgAACLEozRnTK-qFZBNJ6o9KODiT8jMX.png?w=1920&h=942)

