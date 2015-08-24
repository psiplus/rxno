# Introduction #

The Name Reaction Ontology (RXNO) connects chemical reactions, usually ones named after famous chemists, because organic chemistry is a bit like chess in that respect, to (a) their roles in a synthesis and (b) the Molecular Process Ontology.


# Planned reaction step #

A good place to start exploring is from 'planned reaction step', RXNO:0000001. This has the following high-level children:

  * cleaving reaction (RXNO:0000073): "A reaction where atoms are lost from the molecular skeleton"
  * functional modification (RXNO:0000010): "A reaction where the number of atoms in the skeleton, and their connectivity, remain the same"
    * addition, deprotection, functional group addition, functional group modification, molecular skeleton elimination, protection and substitution are all children.
  * molecular skeleton joining reaction (RXNO:0000000): "A reaction where the number of atoms in the molecular skeleton increases."
    * chain lengthening, joining with rearrangement, molecular skeleton insertion reaction, multiple-bond metathesis and polymerisation reaction are all children.
  * rearrangement step (RXNO:0000025): "A reaction which preserves the number of rings and number of skeletal atoms and in which the molecule rearranges so that one or more atoms or groups of atoms move from one atom to another."
  * ring breaking (RXNO:0000205): "A planned reaction step in which the product has fewer rings than the reactants."
  * ring formation (RXNO:0000005): "A planned reaction step where the product contains a ring that was not in any of the reactants."
    * fused-ring-system formation, heterocycle synthesis, ring contraction, ring expansion and ring arrangement are all children of this.