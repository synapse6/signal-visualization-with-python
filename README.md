# Signals and Linear System: Signal Plotting

Coursework for Signals and Linear Systems: a Jupyter Notebook that derives and visualizes continuous-time signals and discrete-time sequences with NumPy, Matplotlib, and SciPy.

The notebook combines mathematical definitions, Python implementations, and plotted results so that each signal can be compared with its equation.

## Signals Covered

- Sinusoidal signals: $x(t)=A\sin(\omega t)$ and $x(t)=A\cos(\omega t)$
- Normalized sinc function: $\operatorname{sinc}(t)=\frac{\sin(\pi t)}{\pi t}$
- Rectangular pulse
- Unit step: $u(t)$
- Shifted step combination: $u(t-2)-u(t-4)$
- Ramp: $r(t)=t\,u(t)$
- Unit impulse sequence: $\delta[n]$
- Impulse shifting, scaling, and reversal
- Triangular pulse and its ramp-based representation
- Real exponential: $e^t$
- Parabolic sequence: $x[n]=n^2$
- Sawtooth and square waves
- Damped complex exponential: $x(t)=e^{(\sigma+j\omega)t}$

## Included Files

- `signals_plots.ipynb` - derivations, implementations, and plots
- `notebook.pdf` - PDF export of the assignment notebook
- `requirements.txt` - Python and Jupyter dependencies

## Requirements

- Python 3.9 or newer
- Jupyter Notebook or JupyterLab

Install the dependencies with:

```bash
python -m pip install -r requirements.txt
```

## Running the Notebook

1. Open `signals_plots.ipynb` in Jupyter Notebook, JupyterLab, or VS Code with the Jupyter extension.
2. Select a Python kernel with the dependencies installed.
3. Run the cells from top to bottom to reproduce the derivations and plots.

The notebook is organized with Markdown headings so each signal definition and visualization can be reviewed independently.

To export a fresh PDF after making changes:

```bash
jupyter nbconvert --to pdf signals_plot.ipynb
```

## Project Structure

```text
.
├── signals_plot.ipynb
├── notebook.pdf
├── requirements.txt
└── README.md
```

## Academic Note

This repository contains coursework for Signals and Linear System. The equations and plots are intended for study and demonstration.
