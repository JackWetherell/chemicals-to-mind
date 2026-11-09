**_From Potentials and Chemicals to the Mind_**.

Personal study notes on the human mind.

These notes are a study of the human mind, and the place where I study the mind, awareness and consciousness. They draw on four areas: neurology, psychiatry, psychedelics, and the philosophy of mind.

The study is rooted in science and physics, so it begins with neurology, starting from the physical substrate (ions, membranes, neurons, glia) and working upward toward perception, emotion, memory, and behaviour. The neurological sections pursue the _easy_ problems of consciousness, in Chalmers' sense: how emotions, behaviours, self-awareness and experience arise from biological processes. Later parts go further, taking up the hard problem of consciousness and deeper spiritual questions, because these are part of the lived experience of having a mind. The document's introduction sets out this framing.

## Source Material

The neurological sections follow the structure of **Ninja Nerd's Neurology lecture series** on YouTube:

- Playlist: [Ninja Nerd, Neurology](https://www.youtube.com/watch?v=ADAOsuaOSCk&list=PLTF9h-T1TcJgx3OFachdjHPMX6VE4VDS1)

Ninja Nerd provides the scaffolding and the ordering of topics; the written notes are my own reworking of that material, written in a lecture-note style and supplemented where useful with additional explanation, clinical context, and connections to psychology.

## Contents

The sections follow the order of the Ninja Nerd playlist: the cellular basics first, then the central nervous system from the top down, then the main systems that run across it.

1. **Nervous System Structure**, CNS and PNS anatomy, the five lobes of the cerebrum, cerebellum, diencephalon, brainstem, the twelve cranial nerves, ventricles, spinal cord, and the autonomic and enteric nervous systems.
2. **Neuron Structure**, soma, dendrites, axon, internal machinery, axonal transport, synaptic vesicles, SNARE proteins, and neurotransmitters.
3. **Neuron Firing**, resting potential, the Nernst equation, graded potentials, the action potential, synaptic release, reuptake, refractory periods, retrograde signalling by endocannabinoids, autoreceptors, the drugs that mimic or block neurotransmitters at their receptors, and the drugs that regulate neurotransmission: SSRIs, SNRIs, NDRIs, stimulants, antipsychotics, and anaesthetics.
4. **Glial Cells**, astrocytes, oligodendrocytes, Schwann cells, myelin, ependymal cells, microglia, and their roles in health and disease.
5. **The Frontal Lobe**, primary motor cortex, premotor and supplementary motor areas, frontal eye field, Broca's area, and the prefrontal cortex.
6. **The Parietal Lobe**, primary somatosensory cortex, somatosensory association cortex, and the posterior association area.
7. **The Temporal Lobe**, primary auditory cortex, auditory association cortex, primary olfactory cortex, olfactory association cortex, and Wernicke's area and aphasia.
8. **The Occipital Lobe**, primary visual cortex and the visual association cortex.
9. **The Insula**, primary gustatory cortex, interoception and visceral sensation, and the anterior insula's role in emotion, disgust, and awareness.
10. **The Thalamus**, structure and the nuclear groups, the reticular nucleus as the gate, limbic involvement through the anterior and mediodorsal nuclei, the modality-specific sensory relays and how they are gated by attention and arousal, and the motor loops returning from the basal ganglia and cerebellum.
11. **The Hypothalamus**, structure and nuclei, its role as the output stage of the limbic system, control of the pituitary and the endocrine axes, command of the autonomic nervous system, and the pathways linking it to the hippocampus, amygdala, and prefrontal cortex.
12. **The Midbrain**, the plan common to the three levels of the brainstem, the tectum and its colliculi, blindsight, the oculomotor nuclei, the red nucleus, the substantia nigra and ventral tegmental area, the periaqueductal grey and the descending control of pain, and the reticular formation and the ascending arousal system.
13. **The Pons**, the base and the tegmentum, the locked-in syndrome, the corticopontine relay to the cerebellum, the nuclei of the trigeminal, abducens, facial, and vestibulocochlear nerves, the locus coeruleus, REM sleep and dreaming, and the parabrachial nuclei and the shaping of breathing.
14. **The Medulla**, the pyramids and their decussation, the dorsal column nuclei and the medial lemniscus, the inferior olive, the nuclei of the glossopharyngeal, vagus, and hypoglossal nerves, the solitary nucleus and area postrema, the lateral and medial medullary syndromes, the baroreflex, the generation of breathing, and brainstem death.
15. **The Cerebellum**, the lobes, deep nuclei, and three functional divisions, the uniform cortical circuit of mossy fibres, granule cells, Purkinje cells, and climbing fibres, error-driven learning and long-term depression, forward models and the attenuation of self-produced sensation, the loop through the pons and thalamus, the signs of cerebellar damage, and the cerebellar contribution to cognition.
16. **The Cranial Nerves**, the levels at which the nerves attach, the arrangement of their nuclei in functional columns, the nerves taken by function (smell and sight, eye movement, the face, hearing and balance, the throat and viscera, the neck and tongue), and the brainstem reflexes used to examine a patient in coma.
17. **The Spinal Cord**, gross anatomy, the spinal nerves and their roots, and dermatomes; the grey matter, with the dorsal horn as a gate on pain, the motor neurons, the stretch and withdrawal reflexes, and the spinal generators of walking; and the white matter, with the ascending and descending tracts, where each crosses, and the lesions that show it.
18. **The Basal Ganglia**, components and the cortex-striatum-thalamus loop, the direct and indirect pathways, dopamine and the D1 and D2 receptors, the nigrostriatal modulation of movement, and Parkinson's and Huntington's disease.
19. **The Limbic System**, the limbic lobe and the cingulate and parahippocampal gyri, the hippocampus and its trisynaptic circuit, the amygdala, the limbic roles of the hypothalamus and thalamus, the septal area and the habenula, and the system's functions in olfaction, memory, emotional responses, and motivation and behaviour.
20. **The Autonomic Nervous System**, the two-neuron plan, the sympathetic division with its chain, adrenal medulla, and adrenergic receptors, the parasympathetic division with the vagus, muscarinic receptors, and vagal tone, how the two oppose and cooperate, central control from the hypothalamus and limbic system, and the visceral afferents that return the state of the body to the brain.
21. **The Enteric Nervous System**, the myenteric and submucosal plexuses and their neurons, glia, and pacemaker cells, the peristaltic reflex and the other programmes the gut runs without the brain, serotonin in the gut, and the gut-brain axis, with the vagus, gut hormones, the microbiome, and the gut-first hypothesis of Parkinson's disease.

These sections complete the neurological foundation. Parts on psychiatry, psychedelics, and the philosophy of mind are to follow.

## Files

- `mind.tex`, the source document.
- `mind.pdf`, the compiled PDF (rebuilt from the source).
- `mind.aux`, `mind.log`, `mind.out`, `mind.toc`, LaTeX build artifacts.

## Building

The document is a standard `article`-class LaTeX file and can be built with any modern TeX distribution:

```
pdflatex mind.tex
pdflatex mind.tex
```

Two passes are needed to resolve the table of contents and cross-references.

## Status

Work in progress. The neurology is complete in outline and will be revised as the lectures are worked through; the parts on psychiatry, psychedelics, and the philosophy of mind are still to be written.
