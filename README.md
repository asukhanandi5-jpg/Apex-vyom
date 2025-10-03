# step2nc — STEP → NC Prototype

This is a prototype repo that reads STEP files, extracts geometry (bbox, holes), selects tools from a JSON DB, 
and generates basic NC G-code (drilling + contour).

## Usage
```
pip install -r requirements.txt
python -m step2nc.cli analyze part.step -o output.nc -t tools.json
```

See `src/step2nc/` for modules.
