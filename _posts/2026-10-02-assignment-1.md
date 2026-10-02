---
title: "Assignment 1"
last_modified_at: 2026-10-02T12:00:00-05:00
tags:
  - static sites
  - interactive map
  - F26
---

This is my home country, Sri Lanka, where I was raised and have lived for around 18 years of my life so far. It is an island country located below India and is often called the teardrop of the Indian Ocean because of its shape. Being an island country located between the Tropic of Cancer and close to the equator, Sri Lanka receives rainfall throughout the year, mainly from the southwest monsoon from May to September and the northeast monsoon from October to January. Because of this, as depicted in the satellite map, a large part of the country is covered in lush vegetation and greenery, with the rainfall supporting the already fertile soil and allowing plants to grow throughout the country.

The country's topography and geography have also created different climatic zones. The flat lands around the coastal belt have a warmer equatorial climate, while as you travel towards the inner parts of the country, the elevation increases and temperatures generally decrease. The southwest monsoon brings rainfall from the vast waterbody of the Indian Ocean, resulting in higher rainfall in the southwestern parts of the country. At the same time, the central hills trap much of the cloud cover, limiting how far some of the rain clouds can travel across the country. The northeast monsoon, which comes from the Bay of Bengal, therefore affects different parts of the country in a different way.

Because of these geographical differences, Sri Lanka can be divided according to average annual rainfall into the wet zone, mainly covering the southern and western parts, the dry zone covering the north, east and north central parts of the country, the intermediate zone around the centre of the country, and smaller arid regions near the northwest and southeast. These different zones have allowed farmers and cultivators to grow a variety of crops in different regions based on the conditions required by each plant.

Agriculture in Sri Lanka dates back over 2,500 years, with paddy being its main crop and tea, rubber and cinnamon, along with other condiments, being some of its major agricultural products today. The industry itself contributes around 20% of the country's total export earnings. To study the variation in crops and cultivated land, I have created the interactive map below.

The following feature codes are being studied:

ESTT - An estate which specialises in growing tea bushes

ESTR - An estate which specialises in growing and tapping rubber trees

GRVC - A planting of coconut trees


<div style="width:100%; height:70vh;">
  <iframe
    src="{{ '/assets/Maps/LK_featuremap.html' | relative_url }}"
    style="width:100%; height:100%; border:0;"
    loading="lazy">
  </iframe>
</div>

The data is collected from the Survey Department of Sri Lanka and contains around 57,000 data points. Multiple types of feature codes can be observed, covering road infrastructure, commercial and public buildings, and geographic and topographic features such as lakes, reservoirs, water tanks, mountains and plains. The dataset contains data points gathered as early as 1994 and was last updated on the 14th of September 2026.

During my initial exploration of the data, I noticed that there were not many data points relating to agriculture and cultivation. Sri Lanka is well known for its high-grade tea, but surprisingly, the tea plant is not native to the island. It was introduced during British rule and was later cultivated mainly in the wet zone and central highlands of the country. To support the commercialisation of the crop, the British brought labour from southern India, particularly from the regions of Tamil Nadu and Kerala, where overseas labour was relatively cheaper. This was also influenced by resistance from local workers to working under the colonial system.

Unfortunately, data points relating to the housing of these workers are not available in the dataset. Having this information could have allowed further analysis of the relationship between the plantations shown in blue and the settlements that are still present today in the hill country, including their proximity and concentration.

Along with the introduction and expansion of tea, roads and especially railway infrastructure were developed to transport the produce from the central hills of the country to Colombo, the commercial capital located in the southwestern part of the country where the major harbour was located. These roads and railways were built during the mid-19th century, at times requiring blasting and tunnelling through mountains and rocks. Many of these roads and railway tracks are still being used today.

Ironically, some of these same railway tracks were damaged by landslides caused by heavy and continuous rain last December. They were reconstructed and reopened to the public on the 2nd of October 2026 (Today), allowing travel again from the central hills towards the capital and other parts of the country. Personally, this is one of my favourite things to do when I am back home, and every year I make sure to take this train ride. It goes through the mountains and tea estates, passing dairy farms, waterfalls and lakes along the way. It is one of the most scenic trips that you can take in Sri Lanka.

<video controls style="width:100%; margin-bottom:20px;">
  <source src="{{ '/assets/Videos/download.mp4' | relative_url }}" type="video/mp4">
</video>

As depicted in the map, the blue dots, which represent 240 locations, are heavily concentrated in the southwestern and central parts of the country. The combination of the clouds trapped by the central hills, higher levels of rainfall and colder climate has allowed tea to grow successfully in this region. However, the dataset has failed to capture some major tea estates in the country such as Pedro and Watalawala estates. Because of this, I believe the number of data points shown on the map is significantly lower than the actual number of tea plantations in the country.

Additionally, data on the land area represented by each point is not available. I think this is an important metric for understanding the size of the tea industry, as simply counting the number of estates does not tell us how large each plantation is. The tea industry accounts for around 12–17% of the country's total merchandise and export earnings.

Moving on to rubber, it was another crop that was in high demand during the mid-19th and early 20th centuries, especially with the growth of the automobile industry and later during World War II, when rubber was needed for military vehicles, tyres, aircraft equipment and other supplies. After the 1950s, demand increasingly shifted towards synthetic rubber, reducing the reliance on natural rubber. However, rubber tapping remains an important industry in Sri Lanka today.

For the British, Ceylon was largely a colony of extraction. To make the most out of the land, they planted crops that were in high demand at the time and developed the infrastructure required to support their commercialisation. One of the arguments made in favour of colonialism is that these extractive practices also resulted in infrastructure that continues to be used today, not only in Sri Lanka but across many parts of South Asia.

Rubber estates are represented by purple dots in the interactive map above. The data appears to be more comprehensive in terms of the number of estates, with 676 estates being identified. Similar to the tea estates, the majority are concentrated in the southwestern and central regions of the country, even though the two crops have differences in their structure and cultivation and require somewhat different conditions to grow.

The third crop I wanted to study was coconut. It is one of the plants where almost every part, from its stem to its leaves, can be utilised. The body of the tree is used for construction and carpentry, while the milk extracted from the coconut is used in almost every type of curry made in Sri Lanka. The shell can be used as firewood and, through more advanced processes, is used to produce activated carbon. Activated carbon has applications in gold recovery, edible oil refining, pharmaceuticals, water and wastewater treatment and other industries. The husk is used to make ropes and fibres, while the leaves and branches can be used to make thatched roofs.

I come from a family of cultivators. My grandparents grew paddy, and my dad has taken over from them by cultivating coconuts. During the last two months of my summer break, I was involved in the cultivation with my dad, and we were able to expand our cultivation by planting another 200-odd plants while I maintained my own plant nursery.

<img src="{{ '/assets/images/IMG_1928.JPG' | relative_url }}" style="zoom:50%;" />

Unfortunately, the dataset has only recognised six data points in the entire country as coconut groves, which I believe is significantly understated. If you were to travel along the coast of Sri Lanka, you would see rows of coconut trees, with particularly large concentrations along the southern coastal belt. In Sri Lanka, a large share of the national coconut harvest comes from what is known as the coconut triangle, which is formed by the districts of Kurunegala, Puttalam and Gampaha and accounts for around 70% of the national yield. Interestingly, none of these three districts are represented by coconut grove datapoints in the dataset.

The lack of datapoints might be attributed to the source dataset used by GeoNames from the Survey Department. The latest census conducted by the Department of Census and Statistics has much more detailed information on the number of plantations for each of these three crops across the 25 districts of the country.

This made me think about Kitchin and Lauriault’s argument that data should not simply be viewed as neutral or objective representations of the world. Data are “situated, contingent, relational, and framed,” meaning that how they are collected and classified shapes what they represent. The absence of agricultural datapoints therefore highlights the limitations of the dataset rather than necessarily indicating that the plantations do not exist.

This workflow could also be useful in future research. For example, I could map Sri Lanka’s roads and railways alongside agricultural regions to investigate whether infrastructure availability is related to economic prosperity. Comparing infrastructure with indicators such as agricultural output, employment or income could reveal patterns that could be explored further in an economics research project or capstone.
