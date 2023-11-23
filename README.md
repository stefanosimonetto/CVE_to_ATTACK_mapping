# CVE_to_ATTACK_mapping
This repository provide the bigger dataset of CVEs mapped to the MITRE ATT&amp;CK framework

## Description

[Provide a more detailed explanation of your project. Explain the functionality, features, and what problems it solves.]

## Getting Started

### Dependencies

- Python 3.9 or higher

### Executing the Program

#### Windows Users

1. **Open Command Prompt**:
   - Navigate to the folder containing the scripts and the batch file.

2. **Run the Batch File**:
   - Type and execute:
     ```
     run_scripts.bat
     ```
   - This will sequentially run `pars.py`, `add_CWE_descr.py`, and `final_step.py`.

#### Linux/macOS Users

1. **Open Terminal**:
   - Navigate to the folder containing the scripts and the bash script.

2. **Make the Bash Script Executable** (only needs to be done once):
```
chmod +x run_scripts.sh
```

3. **Run the Bash Script**:
- Type and execute:
  ```
  ./run_scripts.sh
  ```
- This script checks for Python installation and then runs the scripts `pars.py`, `add_CWE_descr.py`, and `final_step.py` in sequence.


## Authors

Anonized for review

## Version History

- 0.1
 - Initial Release

