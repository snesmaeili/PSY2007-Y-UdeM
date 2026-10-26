# PSY2007-Y-UdeM

Course notebooks for PSY2007 at the Université de Montréal: mobile EEG recorded during a lexical decision task, seated and walking
(Brain Walk project).

## Learning modules

The Python and MNE learning modules were written by Hamza Abdelhedi. They are in the course repository
[thecocolab/PSY2007D-UdeM](https://github.com/thecocolab/PSY2007D-UdeM/tree/2025), branch `2025`. Start with module 0.

| Module | Topic |
|---|---|
| [0](https://github.com/thecocolab/PSY2007D-UdeM/tree/2025/module%200%20-%20essential-tools) | Essential tools |
| [1](https://github.com/thecocolab/PSY2007D-UdeM/tree/2025/module%201%20-%20version-control) | Version control (optional) |
| [2](https://github.com/thecocolab/PSY2007D-UdeM/tree/2025/module%202%20-%20python%20basics) | Python basics |
| [3](https://github.com/thecocolab/PSY2007D-UdeM/tree/2025/module%203%20-%20python%20for%20m_eeg) | Python for M/EEG |
| [4](https://github.com/thecocolab/PSY2007D-UdeM/tree/2025/module%204%20-%20mne%20data%20manipulation) | MNE data manipulation |
| [5](https://github.com/thecocolab/PSY2007D-UdeM/tree/2025/module%205%20-%20meeg%20preprocessing) | M/EEG preprocessing |
| [6](https://github.com/thecocolab/PSY2007D-UdeM/tree/2025/module%206%20-%20meeg%20time-frequency) | M/EEG time-frequency |
| [7](https://github.com/thecocolab/PSY2007D-UdeM/tree/2025/module%207%20-%20meeg%20machine%20learning) | M/EEG machine learning |

His autumn 2026 PSY2007D notebooks (séances 4 and 5) and the installation guide are on the
[`main` branch](https://github.com/thecocolab/PSY2007D-UdeM) of the same repository.

## Autumn 2026

| Séance | Notebook | Content |
|---|---|---|
| 1 | [`00_preprocessing_teaching_seated.ipynb`](autumn-2026/seance1/00_preprocessing_teaching_seated.ipynb) [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/snesmaeili/PSY2007-Y-UdeM/blob/main/autumn-2026/seance1/00_preprocessing_teaching_seated.ipynb) | Preprocessing of one seated participant: bad channels, filtering and Auto-CCA, average reference, ICA, quality control, epochs and ERPs before and after cleaning |
| 1 | [`00_preprocessing_teaching_walking.ipynb`](autumn-2026/seance1/00_preprocessing_teaching_walking.ipynb) [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/snesmaeili/PSY2007-Y-UdeM/blob/main/autumn-2026/seance1/00_preprocessing_teaching_walking.ipynb) | The same participant while walking, with the pipeline tuned for walking: bad channels judged over time, regression on the head accelerometer, AMICA, a stride template after ICA (Gwin et al., 2010), epochs and ERPs before and after cleaning |

The notebooks download the course data (1.2 GB, 17 participants) once, into `tasks/brainwalk/` next to them, and install the missing
packages the first time they run.
