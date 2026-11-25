<!-- brainlife-app:begin (generated from the App manifest; edit the manifest, not this block) -->

> **Prototype test App (compiled MATLAB) that adds 1 to the parameter n1 and saves the sum to a .mat file; the T1w input is not used.**

Course or prototype App for testing brainlife MATLAB packaging. It reads n1 from config.json, computes 1 + n1 and writes out_dir/suma.mat. It does no image processing and should not be used for analysis.

| | |
|---|---|
| 📥 **Inputs** | `neuro/anat/t1w` |
| 📤 **Outputs** | `raw` |
| 🐳 **Container** | `brainlife/mcr:r2019a` |
| ⚙️ **Resources** | 1 GB memory · 0.25 h walltime |
| 🔗 **Run it** | [doi.org/10.25663/brainlife.app.854](https://doi.org/10.25663/brainlife.app.854) |

#### 📥 Inputs

| Input | Datatype | Required | Description |
|---|---|---|---|
| `t1w` | `neuro/anat/t1w` | yes | T1-weighted image (required by the registration but not read by the code). |

#### 📤 Outputs

| Output | Datatype | Description |
|---|---|---|
| `out_dir` | `raw` | suma.mat containing the computed sum. |

<details>
<summary><b>⚙️ Parameters</b> (1)</summary>

| Parameter | Type | Default | Description |
|---|---|---|---|
| `n1` | number | `2` | Number added to 1. |

</details>

<!-- brainlife-app:end -->

RESIZED APP IN BRAINLIFE BASED IN MATLAB 
