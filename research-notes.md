# Research Notes

I study how to turn audio into representations that support biological comparisons. These notes trace ideas from bioacoustics, animal communication, and machine learning to specific experiments.

## The question behind BirdTokenSequences

**When does the order of notes help distinguish recordings?** Compare an ordered sequence with a shuffled version that contains the same notes. The [interactive demo](https://huggingface.co/spaces/fionawyu/birdsong-note-order) shows what the edit distance can detect in a synthetic phrase. A held-out comparison of classification with and without note order tests whether that difference matters for a biological task. A separate acoustic baseline using note counts, pitch, and duration helps assess any value added by order.

## Reading notes

### Test what embeddings preserve

[Perch 2.0](https://research.google/pubs/perch-20-the-bittern-lesson-for-bioacoustics/) studies transfer learning across bioacoustics tasks. For a sequence experiment, use the same note boundaries and embeddings in both conditions, shuffle the order in one condition, and compare held-out performance using the same sequence model and splits.

### Measure how notes depend on context

[Sharma et al. on sperm whale vocalisations](https://www.nature.com/articles/s41467-024-47221-8) describes variation in click patterns associated with conversational context. A birdsong analogue would test whether pitch or duration varies with a note's neighbours or phrase position after accounting for individual and recording conditions.

### Decide which details a token should preserve

[SoundStream](https://arxiv.org/abs/2107.03312) learns discrete codes for audio reconstruction. A vocabulary for birdsong analysis can be evaluated on separate targets, such as note boundaries, pitch contour, and the distinctions needed to compare recordings. Holding the vocabulary size fixed would make it easier to compare which details different tokenizers retain.

## Follow new work

[Audio and sound preprints](https://arxiv.org/list/cs.SD/recent) · [Machine learning preprints](https://arxiv.org/list/cs.LG/recent) · [Conference papers on OpenReview](https://openreview.net/group?id=NeurIPS.cc%2F2026%2FConference) · [GitHub Changelog](https://github.blog/changelog/)

[Personal website](https://fionawyu.github.io/) · [BirdTokenSequences software](https://github.com/fionawyu/birdtokensequences)
