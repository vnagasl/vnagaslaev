# inj-mon

Python tools for injection monitoring and turn-by-turn BPM analysis.

## Layout

- `src/inj_mon/`: analysis scripts and shared project paths
- `data/input/`: source measurement and optics data
- `data/output/`: generated analysis files
- `requirements.txt`: Python dependencies

## Run

Install dependencies in a project-local virtual environment, then run one of the GUI tools from the project root:

```powershell
python src/inj_mon/injOrbits.py
python src/inj_mon/multFrames_X.py
python src/inj_mon/multFrames_Dev2.py
```

The scripts use the files in `data/input/` by default and write generated `.dat` files to `data/output/`.