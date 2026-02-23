# CKA Practice (Simple Edition)

Straightforward CKA practice labs derived from the CKA-PREP playlist. Every question lives in its own folder with three bash files:

- `LabSetUp.bash` � copy/paste into Killercoda (or any Kubernetes cluster) to prep the environment.
- `Questions.bash` � the scenario text plus the YouTube link for the walkthrough.
- `SolutionNotes.bash` � a step-by-step solution when you need a hint.

## How to Use

### on killercoda CKA playground, clone the repo
git clone https://github.com/hirushinidem/CKA-PREP-2025-v2.git

### run the setup script
cd ~/CKA-PREP-2025-v2
bash scripts/run-question.sh "Question-15 Etcd-Fix"

### or manually
cd "CKA-PREP-2025-v2/Question-15 Etcd-Fix"
bash LabSetUp.bash
cat Questions.bash

## Available Questions
| Question | Topic | Video |
|----------|-------|-------|
| Question-01 | Install Argo CD using Helm without CRDs | https://youtu.be/8GzJ-x9ffE0 |

More questions can be added by copying the template folder and dropping in the three bash files from the original collection.
