---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}"  target="_blank">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}






[//]: # (* **Dianshi Yang**, Abhinav Kumar, Stuart Ray, Wei Wang, Reza Tourani. IoT Sentinel: Correlation-based Attack Detection, Localization, and Authentication in IoT Networks. ICCCN 2023. [https://doi.org/10.1109/ICCCN58024.2023.10230209]&#40;https://doi.org/10.1109/ICCCN58024.2023.10230209&#41;{:target="_blank"})

[//]: # ()
[//]: # (* Zheng Yang, Tien Tuan Anh Dinh, Yingying Yao, **Dianshi Yang**, Xiaolin Chang, Jianying Zhou. LARP: A Lightweight Auto-Refreshing Pseudonym Protocol for V2X. SACMAT 2022. [https://doi.org/10.1145/3532105.3535027]&#40;https://doi.org/10.1145/3532105.3535027&#41;{:target="_blank"})

[//]: # (  )
[//]: # (* Daniël Reijsbergen, Aung Maw, Sarad Venugopalan, **Dianshi Yang**, Tien Tuan Anh Dinh, Jianying Zhou. Protecting the Integrity of IoT Sensor Data and Firmware With A Feather-Light Blockchain Infrastructure. ICBC 2022. [https://doi.org/10.1109/ICBC54727.2022.9805485]&#40;https://doi.org/10.1109/ICBC54727.2022.9805485&#41;{:target="_blank"})

[//]: # ()
[//]: # (* **Dianshi Yang**, Daisuke Mashima, Wei Lin, Jianying Zhou. DecIED: Scalable k-Anonymous Deception for IEC61850-Compliant Smart Grid Systems. CPSS 2020. [https://doi.org/10.1145/3384941.3409592]&#40;https://doi.org/10.1145/3384941.3409592&#41;{:target="_blank"})

[//]: # ()



