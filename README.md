# Neurology Notes

Personal study notes on the human mind, written up as a single LaTeX document: **_From Potentials and Chemicals to the Mind_**.

These notes are a study of the human mind, and the place where I study the mind, awareness and consciousness. They draw on four areas: neurology, psychiatry, psychedelics, and the philosophy of mind.

The study is rooted in science and physics, so it begins with neurology, starting from the physical substrate (ions, membranes, neurons, glia) and working upward toward perception, emotion, memory, and behaviour. The neurological sections pursue the _easy_ problems of consciousness, in Chalmers' sense: how emotions, behaviours, self-awareness and experience arise from biological processes. Later parts go further, taking up the hard problem of consciousness and deeper spiritual questions, because these are part of the lived experience of having a mind. The document's introduction sets out this framing, and the closing section of the neurology takes stock of how far a purely physical account currently reaches.

## Source Material

The neurological sections follow the structure of **Ninja Nerd's Neurology lecture series** on YouTube:

- Playlist: [Ninja Nerd, Neurology](https://www.youtube.com/watch?v=ADAOsuaOSCk&list=PLTF9h-T1TcJgx3OFachdjHPMX6VE4VDS1)

Ninja Nerd provides the scaffolding and the ordering of topics; the written notes are my own reworking of that material, written in a lecture-note style and supplemented where useful with additional explanation, clinical context, and connections to psychology.

## Contents

The sections follow the order of the Ninja Nerd playlist: the cellular basics first, then the central nervous system from the top down, then the main systems that run across it. Sections marked _to be written_ are placeholders for lectures not yet reached.

1. **Nervous System Structure**, CNS and PNS anatomy, cerebrum, cerebellum, diencephalon, brainstem, the twelve cranial nerves, ventricles, spinal cord, and the autonomic nervous system.
2. **Neuron Structure**, soma, dendrites, axon, internal machinery, axonal transport, synaptic vesicles, SNARE proteins, and neurotransmitters.
3. **Neuron Firing**, resting potential, the Nernst equation, graded potentials, the action potential, synaptic release, reuptake, refractory periods, retrograde signalling by endocannabinoids, autoreceptors, and the drugs that mimic or block neurotransmitters at their receptors.
4. **Glial Cells**, astrocytes, oligodendrocytes, Schwann cells, myelin, ependymal cells, microglia, and their roles in health and disease.
5. **The Meninges**, _to be written._
6. **The Frontal Lobe**, primary motor cortex, premotor and supplementary motor areas, frontal eye field, Broca's area, and the prefrontal cortex.
7. **The Parietal Lobe**, primary somatosensory cortex, somatosensory association cortex, and the posterior association area.
8. **The Temporal Lobe**, primary auditory cortex, auditory association cortex, primary olfactory cortex, olfactory association cortex, and Wernicke's area.
9. **The Occipital Lobe**, primary visual cortex and the visual association cortex.
10. **The Insula**, primary gustatory cortex, interoception and visceral sensation, and the anterior insula's role in emotion, disgust, and awareness.
11. **The Cerebral Cortex: An Overview**, _to be written._
12. **The Thalamus**, structure and the nuclear groups, the reticular nucleus as the gate, limbic involvement through the anterior and mediodorsal nuclei, the modality-specific sensory relays and how they are gated by attention and arousal, and the motor loops returning from the basal ganglia and cerebellum.
13. **The Hypothalamus**, structure and nuclei, its role as the output stage of the limbic system, control of the pituitary and the endocrine axes, command of the autonomic nervous system, and the pathways linking it to the hippocampus, amygdala, and prefrontal cortex.
14. **The Midbrain**, _to be written._
15. **The Pons**, _to be written._
16. **The Medulla**, _to be written._
17. **The Cerebellum**, _to be written._
18. **The Cranial Nerves**, _to be written._
19. **The Spinal Cord: Gross Anatomy and Spinal Nerves**, _to be written._
20. **The Spinal Cord: Grey Matter**, _to be written._
21. **The Spinal Cord: White Matter**, _to be written._
22. **The Basal Ganglia**, components and the cortex-striatum-thalamus loop, the direct and indirect pathways, dopamine and the D1 and D2 receptors, and the nigrostriatal modulation of movement.
23. **The Limbic System**, the limbic lobe and the cingulate and parahippocampal gyri, the hippocampus and its trisynaptic circuit, the amygdala, the limbic roles of the hypothalamus and thalamus, the septal area and the habenula, and the system's functions in olfaction, memory, emotional responses, and motivation and behaviour.
24. **The Autonomic Nervous System**, _to be written._
25. **The Sympathetic Nervous System**, _to be written._
26. **The Parasympathetic Nervous System**, _to be written._
27. **The Enteric Nervous System**, _to be written._
28. **Gustation: The Taste Pathway**, _to be written._

Further neurology sections will be added as the lecture series progresses, followed by parts on psychiatry, psychedelics, and the philosophy of mind.

## Files

- `neurology.tex`, the source document.
- `neurology.pdf`, the compiled PDF (rebuilt from the source).
- `neurology.aux`, `neurology.log`, `neurology.out`, `neurology.toc`, `neurology.synctex.gz`, LaTeX build artifacts.

## Building

The document is a standard `article`-class LaTeX file and can be built with any modern TeX distribution:

```
pdflatex neurology.tex
pdflatex neurology.tex
```

Two passes are needed to resolve the table of contents and cross-references.

## Status

Work in progress. Expect the document to grow and be revised as the lectures are worked through.
