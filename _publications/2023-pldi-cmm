---
title: "Compound Memory Models."
collection: publications
permalink: /publication/2023-pldi-cmm
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-06-01
venue: 'PLDI 2023'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Soham Chakraborty, You. (2023). &quot;Compound Memory Models.&quot; <i>PLDI 2023</i>. 1(1).'
---

Today's mobile, desktop, and server processors are heterogeneous, consisting not only of CPUs but also GPUs and other accelerators. Such heterogeneous processors are starting to expose a shared memory interface across these devices.Given that each of these individual devices typically supports a distinct instruction set architecture and a distinct memory consistency model, it is not clear what the memory consistency model of the heterogeneous machine should be. In this paper, we answer this question by formalizing "compound" memory models: we present a compositional operational model describing the resulting model when devices with distinct consistency models are fused together. We instantiate our model with the compound x86TSO/PTX model -- a CPU enforcing x86TSO and a GPU enforcing the PTX model. A key result is that the x86TSO/PTX compound model retains compiler mappings from the language-based (scoped) C memory model. This means that threads mapped to the x86TSO device can continue to use the already proven C-to-x86TSO compiler mapping, and the same for PTX.
