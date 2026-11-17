# County Rainfall and Planting Advisory

- **Project summary:** This project cleans and analyses monthly rainfall observations for Nairobi, Nakuru, Kisumu, Mombasa and Machakos using Python and NumPy. It calculates annual totals, monthly averages, wettest months, dry-month counts and the highest-rainfall consecutive two-month window, then exports the results to `rainfall_summary.csv`.
- **How to run:** Install Python 3 and the dependencies using `pip install -r requirements.txt`, open `rainfall_analysis.ipynb` in Jupyter Notebook or Google Colab, select a Python 3 kernel, and run all cells from top to bottom; the CSV will be created in the notebook's working directory.
- **Planting advisory:** Use each county's highest-rainfall consecutive two-month period as an initial planning window, but advise farmers to confirm actual planting time using rainfall onset, soil moisture, crop requirements and local agricultural guidance; results are indicative because two Machakos values were imputed and only one year of monthly data is available.

## Files
- `rainfall_analysis.ipynb` — explained analysis with code and saved outputs.
- `rainfall_summary.csv` — one summary record for each county.
- `requirements.txt` — Python dependencies.
