# ukaea-sysuq-box
System Uncertainty Quantification (SysUQ) for a box.

`SysUQ.ipynb` walks through a full surrogate modelling workflow:
- setup and authentication with the Uncertainty Engine,
- data preparation and latent-space construction,
- cloud training with TorchScript export,
- local rollout, uncertainty propagation, and visualisation.

## Quick start
1. Create a `.env` file with your Uncertainty Engine credentials.
2. Install dependencies from `requirements.txt`.
3. Run the `SysUQ.ipynb` notebook top to bottom.
