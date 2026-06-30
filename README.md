# psychopy-hold-release-task-analysis
This project demonstrates a basic PsychoPy-to-Python behavioural data analysis workflow.

The task is a simple hold-release demo. Participants press and hold the SPACE key, continue holding during a "KEEP HOLDING" period, and release the key when a "RELEASE NOW" signal appears.

The main behavioural measure is release latency, recorded in the PsychoPy output as `release_response.rt`.

## Skills demonstrated

- PsychoPy task building
- Keyboard press and release event recording
- Behavioural data handling
- Python/Jupyter Notebook
- pandas DataFrames
- Release-time analysis
- Basic matplotlib plotting

## Project files

- `hold_release_v3_analysis_clean.ipynb` — Python analysis notebook
- `hold_release_demo_v3_test_output.csv` — example PsychoPy output data
- `hold_release_demo_v3_delayed_release_with_ITI_working.psyexp` — PsychoPy task file, if included

## Analysis overview

The notebook demonstrates how to:

1. Load PsychoPy output data
2. Select relevant columns
3. Rename variables for clarity
4. Remove empty rows
5. Calculate mean release latency
6. Plot release latency across trials

## Note

This is a learning/demo project using a small test run. It is not intended for statistical inference. The workflow is being developed as preparation for future behavioural task analysis involving release timing and error awareness.
