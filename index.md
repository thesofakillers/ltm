**Memory** is arguably an essential ingredient of general intelligence. The
Atkinson–Shiffrin memory model [1], categorizes memory into “working” and
“long-term” memory frameworks, besides an initial sensory register. **Working
memory** (WM) acts as a temporary and limited store of information to be used in
cognitive tasks that can be addressed with a small amount of steps. **Long-term
memory** (LTM) instead acts as a more permanent storage of information
previously “rehearsed”. We hypothesize that integrating some LTM mechanism
should address the issue of **catastrophic forgetting** commonly faced by
computational models capable of working memory. This is the phenomenon in which
the **performance on previously learned tasks is compromised upon learning a new
task**. We extend the biologically plausible working memory model AuGMEnT [2] by
integrating a LTM repetition-based thresholding mechanism. We analyse the
performance of our model with and without the LTM mechanism on two tasks learned
model performance differ from the non-LTM-enabled model in that their
performance in the original task does not drop upon learning a new task\*\*.
This underlines the clear necessity of LT memory-like mechanisms for continual
learning, which is undeniably present in biological agents.

## Tasks Considered

We analyse the performance of our model with and without the LTM mechanism on
two tasks learned sequentially. We also compare to the performance of monkeys as
a measure of biological plausibility.

1. The first task is a saccade/anti-saccade task. In this task, agents first see
   a blank screen, then a fixation mark appear, indicating whether it’s a anti
   or pro saccade. Then another cue appear on left or right, determine whether
   it’s a right or left saccade. Agents need to respond with correct saccade
   direction.
2. The second task is a delayed match-to-category task. Agents first see a
   fixation mark, followed by the cue 1, then another fixation mark. After, cue
   2 appears, and agents need to decide whether cue 2 matches cue 1 by
   indicating with a left or right saccade.

## References

[1] R. C. Atkinson and R. M. Shiffrin, ‘Human Memory: A Proposed System and its
Control Processes’, vol. 2, K. W. Spence and J. T. Spence, Eds. Academic Press,
1968, pp. 89–195. doi: https://doi.org/10.1016/S0079-7421(08)60422-3.

[2] J. O. Rombouts, S. M. Bohte, and P. R. Roelfsema, ‘How Attention Can Create
Synaptic Tags for the Learning of Working Memories in Sequential Tasks’, PLOS
Computational Biology, vol. 11, no. 3, p. e1004060, Mar. 2015, doi:
10.1371/journal.pcbi.1004060.

[3] J. Gottlieb and M. E. Goldberg, ‘Activity of neurons in the lateral
intraparietal area of the monkey during an antisaccade task’, Nat Neurosci, vol.
2, no. 10, pp. 906–912, Oct. 1999, doi: 10.1038/13209.

[4] D. J. Freedman and J. A. Assad, ‘Experience-dependent representation of
visual categories in parietal cortex’, Nature, vol. 443, no. 7107, Art. no.
7107, Sep. 2006, doi: 10.1038/nature05078.

[5] N. Cowan, ‘What are the differences between long-term, short-term, and
working memory?’, Prog Brain Res, vol. 169, pp. 323–338, 2008, doi:
10.1016/S0079-6123(07)00020-9.

[6] L. Himmer, M. Schönauer, D. P. J. Heib, M. Schabus, and S. Gais, ‘Rehearsal
initiates systems memory consolidation, sleep makes it last’, Science Advances,
vol. 5, no. 4, p. eaav1695, Apr. 2019, doi: 10.1126/sciadv.aav1695.

## Contact

- Steven Bommer: steven DOT bommer AT student DOT uva DOT nl
- Eline Troquay: eline DOT troquay AT projectmarch DOT nl
- Xinyao Zhang: xinyao DOT Zhang AT student DOT uva DOT nl
- Giulio Starace: giulio DOT starace AT student DOT uva DOT nl
