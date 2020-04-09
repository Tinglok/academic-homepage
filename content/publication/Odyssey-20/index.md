---
title: "Optimal Mapping Loss: A Faster Loss for End-to-End Speaker Diarization"
date: 2020-02-01
publishDate: 2020-02-01T13:59:10.998650Z
authors: ["Qingjian Lin", "**Tingle Li**", "Lin Yang", "Junjie Wang", "Ming Li"]
publication_types: ["3"]
abstract: "Recently, deep neural network based approaches have become more and more popular among modules of speaker diarization such as voice activity detection, speaker embedding extraction and clustering. However, end-to-end speaker diarization training still remains as a challenging task, partly due to difficult loss design for the speaker-label ambiguity problem. The permutation-invariant training (PIT) loss could be a possible solution, but its time complexity is O(T*N*N!), where T and N denote the duration and the number of speakers in audios. In this paper, we investigate improvement on the PIT loss and further propose a novel optimal mapping loss, which directly computes the best matches between the output speakers and the target speakers through the Hungarian algorithm. Our proposed loss successfully reduces the time complexity to O(T*N^2) + O(N^3), meanwhile keeping the same performance as PIT loss."
featured: false
publication: "*Odyssey 2020*"
links:
  - icon_pack: ai
    icon: arxiv
    name: Preprint
---

