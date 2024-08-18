---
title: "Formal Analytics for Stealthy Attacks Against Contingency Analysis in Power Grids"
collection: publications
permalink: /publication/2024-02-01-Paper_SCOPF
excerpt: 'This paper formally model complex attacks on power grid contingency analysis and solve them using Satisfiability Modulo Theories (SMT)'
date: 2024-02-01
venue: 'Sustainable Energy, Grids and Networks'
# slidesurl: 'http://shahriar0651.github.io/files/slides2.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S2352467724000390'
citation: 'Shahriar, M. H., Rahman, M. A., Jafari, M., & Paudyal, S. (2024). Formal analytics for stealthy attacks against Contingency Analysis in power grids. Sustainable Energy, Grids and Networks, 38, 101310.'
---

Contingency Analysis (CA) is a critical part of the Energy Management System of a power grid, ensuring the optimal operating set-points without violating constraints, even in the face of contingency events. CA relies on State Estimation (SE) to perform its analysis, paving the way for Security Constrained Optimal Power Flow (SCOPF) that ensures optimal economic generator dispatches, even in scenarios like contingencies, such as a single line failure. This integrated approach enhances the grid’s resilience and efficiency under diverse conditions. However, it is shown that an adversary can alter specific power measurements to corrupt the SE without being detected. Such a corrupted estimation will provide CA with a fake model to deal with, which can further lead the grid to an even more vulnerable state. This research formally models and analyzes these attacks on CA, particularly on SCOPF, which are routed from SE. We formally model these complex attacks as a set of constraints and solve them using Satisfiability Modulo Theories (SMT) to synthesize potential attack vectors. Each of these vectors specifies a set of measurements that an adversary can alter to cause one or more transmission lines to be overloaded when some specific contingencies happen. We apply various sensitivity factors to make the solution to this complex synthesis problem tractable. We demonstrate our formal analytics on IEEE bus systems and verify the results using OPAL-RT, a standard virtual power grid testbed. We finally evaluate the tool with respect to various attack and grid characteristics.