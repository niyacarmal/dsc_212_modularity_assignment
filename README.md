# Modularity on the Karate Club Graph

**Course:** DSC212, Research Assignment on Graph Theory Module  
**Author:** Niya Carmal Jaison / IMS25285

This repository contains my submission for the DSC212 research assignment on community detection using modularity. The work is built around Zachary's Karate Club network. Because the graph is small, easy to visualise and historically meaningful, it is widely used as the standard test case for community-detection methods, and it lets us ask whether purely structural information about who interacts with whom can reveal the fault lines of a group.

The notebook implements a spectral modularity method from scratch, following Newman (2006), to find communities in the graph. Modularity measures how much more a division of a network contains within-group connections than a degree-preserving random baseline would produce. Beyond finding the communities, the notebook visualises the network after every split and tracks how four node-level measures change as the communities are refined. Using only NumPy, NetworkX and Matplotlib keeps every step of the method visible, so the notebook serves as a worked example of how the linear algebra behind modularity connects to a real social network.

## A Note on Responsible AI Usage

I used two AI tools, Claude and ChatGPT, as support tools while preparing this assignment. They helped me mainly with the visualisations, the implementation of the algorithms, reviewing my notebook for problems, and improving the wording of the explanatory text. The AI did not replace my own understanding of the material. I ran the notebook myself, checked that the results are consistent, and I take full responsibility for the code and the claims in this submission.

Since AI-generated suggestions can be wrong, I treated them as drafts to verify rather than as authoritative answers. The only data used is the public Karate Club network bundled with NetworkX, and no personal or private data was involved.

## References

1. Newman, M. E. J. (2006). Modularity and community structure in networks. *Proceedings of the National Academy of Sciences*, 103(23), 8577–8582. https://doi.org/10.1073/pnas.0601602103
2. Zachary, W. W. (1977). An information flow model for conflict and fission in small groups. *Journal of Anthropological Research*, 33(4), 452–473.
