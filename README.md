### Structure of data file
* Data located in `data/participant_data.csv`

* Every row corresponds to a single trial. Each participant completed 9 trials although some trials for some 
participants were excluded.

* `pid`: unique participant identifier

* `expertise`: expertise rating for trial (0-100)

* `confidence`: confidence rating for trial (0-100)

* `click_outside`: whether the participant clicked outside the browser window during the trial ("NA" or "clicked")

* `correct`: whether the participant response was correct (1: Correct, 0: Incorrect)

* `rt`: reaction time for abstract option selection and pressing "continue" (milliseconds)

* `abstract_id`: unique abstract identifier. (machine abstracts are a subset of human ones: duplicate IDs)

* `journal_section`: whether a human or machine created item and which journal section it is from

* `click_slider`: whether participant clicked either of the rating sliders for the trial (1: Yes, 0: No)

* `recognised`: whether participant recognised abstract (1: Yes, 0: No)

* `age`: participant age

* `country`: "Which country are you based in?"

* `current position`: current academic position (dropdown selection)

* `experience`: years of experience in the field of neuroscience

* `sex`: "To which gender identity do you most conform?" (dropdown selection)

### Map abstract id to doi
* Use `abstract_id_doi.csv`

### BrainBench Test cases
* Human created: https://huggingface.co/datasets/BrainGPT/BrainBench_Human_v0.1.csv

* GPT-4 created: https://huggingface.co/datasets/BrainGPT/BrainBench_GPT-4_v0.1.csv

### Attribution
```
@misc{luo2024large,
      title={Large language models surpass human experts in predicting neuroscience results}, 
      author={Xiaoliang Luo and Akilles Rechardt and Guangzhi Sun and Kevin K. Nejad and Felipe Yáñez and Bati Yilmaz and Kangjoo Lee and Alexandra O. Cohen and Valentina Borghesani and Anton Pashkov and Daniele Marinazzo and Jonathan Nicholas and Alessandro Salatiello and Ilia Sucholutsky and Pasquale Minervini and Sepehr Razavi and Roberta Rocca and Elkhan Yusifov and Tereza Okalova and Nianlong Gu and Martin Ferianc and Mikail Khona and Kaustubh R. Patil and Pui-Shee Lee and Rui Mata and Nicholas E. Myers and Jennifer K Bizley and Sebastian Musslick and Isil Poyraz Bilgin and Guiomar Niso and Justin M. Ales and Michael Gaebler and N Apurva Ratan Murty and Chloe M. Hall and Jessica Dafflon and Sherry Dongqi Bao and Bradley C. Love},
      year={2024},
      eprint={2403.03230},
      archivePrefix={arXiv},
      primaryClass={q-bio.NC}
}
```
