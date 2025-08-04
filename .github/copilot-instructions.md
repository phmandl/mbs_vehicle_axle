# Copilot Instructions for mbs_vehicle_axle

## Project Overview
- This project models a multi-body system (MBS) of a passenger vehicle axle using Python and Jupyter Notebooks.
- The main analysis and visualization are performed in `mbs_vehicle_axle.ipynb`.
- The codebase is designed for interactive, visual exploration and prototyping, not for production deployment.

## Key Files and Structure
- `mbs_vehicle_axle.ipynb`: Main notebook containing all code, visualizations, and documentation.
- `requirements.txt`: Lists core dependencies (`numpy`, `scipy`, `matplotlib`).
- `.gitignore`: Standard Python ignores, including Jupyter checkpoints and virtual environments.
- `README.md`: Minimal setup instructions.

## Developer Workflow
- Create and activate a virtual environment: `python3 -m venv venv && source venv/bin/activate`
- Install dependencies: `pip install -r requirements.txt`
- Open and run `mbs_vehicle_axle.ipynb` in Jupyter or VS Code.
- Use `%matplotlib widget` for interactive 3D plots in the notebook.

## Coding Patterns and Conventions
- All core logic, visualization, and documentation are in the notebook, not split into modules.
- 3D visualization uses `matplotlib`'s `Axes3D` and custom classes (e.g., `Arrow3D`) for coordinate systems.
- Rotation matrices are constructed using ZYX Euler angles for 3D transformations.
- Code cells are annotated with markdown cells for clarity and reproducibility.
- No automated tests or CI/CD; all validation is manual and visual.

## Integration and Dependencies
- No external data sources or APIs; all data is generated or hardcoded in the notebook.
- No cross-component communication; the project is self-contained.

## Example: Drawing a 3D Coordinate System
- See the code cell in `mbs_vehicle_axle.ipynb` that defines `Arrow3D` and `draw_coordinate_system`.
- Example usage is provided in the notebook for visualizing coordinate systems with custom rotations.

## Project-Specific Notes
- Keep all new logic and documentation in the notebook unless refactoring for scale.
- Use clear markdown explanations for any new code or analysis.
- Follow the existing style for 3D plotting and matrix operations.

---
For questions or unclear conventions, review the notebook's markdown cells or ask the project maintainer.
