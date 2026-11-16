# County Rainfall and Planting Advisory

This project cleans monthly rainfall data for five Kenyan counties (Nairobi, Nakuru, Kisumu, Mombasa, Machakos), analyses patterns with NumPy, and produces a short planting advisory for a farmer-support NGO.

## How to Run

1. Install the required library:
   ```
   pip install -r requirements.txt
   ```
2. Open `rainfall_analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Restart the kernel and run all cells from top to bottom.

The notebook will print intermediate results, write `rainfall_summary.csv`, and display the planting advisory.

## Planting Advisory (Summary)

- Prioritise the April–May window for Nairobi, Nakuru, Kisumu and Mombasa; target November–December for Machakos.
- Prepare land early in the long-rains season (March) for most counties to take advantage of peak consecutive rainfall.
- Treat the two imputed Machakos values as approximate until original station records can be verified.
