![Yu Wang — Machine Learning & Bioacoustics](assets/birdsong-cover.png)

# Yu Wang

**Machine Learning · Computing Science PhD candidate at the University of Alberta**

[Try the Demo](https://huggingface.co/spaces/fionawyu/birdsong-note-order) · [Personal Website](https://fionawyu.github.io/) · [Research Notes](#research-notes-and-reading)

I build machine learning methods that turn bird recordings into interpretable note sequences for comparing vocalizations across species, dialects, and individuals.

## Selected work

**[BirdTokenSequences](https://github.com/fionawyu/birdtokensequences)** — Research code for comparing and classifying bird vocalizations with symbolic note sequences. The pipeline fits formulas to frequency contours, maps them to shape tokens, and compares sequences with edit distance.

**Research question.** When does note order add information beyond pitch, duration, and note counts? Comparing an ordered sequence with a shuffle of the same notes gives us one way to test it.

## Recent update

- **November 2026** · [BirdTokenSequences research code](https://github.com/fionawyu/birdtokensequences) is available on GitHub.

## Research notes and reading

- **Does the representation retain note order?** [Perch 2.0](https://research.google/pubs/perch-20-the-bittern-lesson-for-bioacoustics/) provides a transfer-learning baseline. An order test can hold the note embeddings fixed and change only their sequence.
- **Does the same note change with its neighbours?** [Sharma et al. on sperm whale vocalisations](https://www.nature.com/articles/s41467-024-47221-8) suggests a question for birdsong. Do the pitch and duration of a note type depend on where it appears in a phrase?
- **What should a learned token preserve?** [SoundStream](https://arxiv.org/abs/2107.03312) uses discrete codes for audio reconstruction. For birdsong, I would also check whether the codes retain pitch contours and note boundaries.

[Audio research on arXiv](https://arxiv.org/list/cs.SD/recent) · [Machine learning preprints on arXiv](https://arxiv.org/list/cs.LG/recent) · [GitHub Changelog](https://github.blog/changelog/)

## Collaborate

I bring experience in audio representation, sequence comparison, and experimental design to collaborations in bioacoustics, audio machine learning, and ecological monitoring. I'm open to 2027 postdoctoral and applied research opportunities.

[Contact via my personal website](https://fionawyu.github.io/)

Outside research, I enjoy reading, coding, and keeping a journal.
