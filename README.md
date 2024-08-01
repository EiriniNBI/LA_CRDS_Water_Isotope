# LA - CRDS Water Isotope Measurements on Ice - Analysis

## Setting Up the Environment in Google Colab
1. **Mount Google Drive:**
   - Use `drive.mount('/content/drive')` to access your Google Drive within Colab.
2. **Navigate to your project directory:**
   - Change directory with `%cd /content/drive/MyDrive`.
3. **Install Necessary Packages:**
   - Install packages using `pip install allantools` and LaTeX with the following commands:
     ```
     !apt-get update
     !apt-get install texlive-fonts-recommended texlive-fonts-extra cm-super
     ```

## Data Processing and Visualization
- **Data Handling:**
  - Scripts are provided to handle data downloading from Zenodo, data pre-processing, calibration, and statistical analysis directly within the notebook environment.
- **LaTeX Integration:**  
  - Generates LaTeX tables directly from processed data.
- **Visualization:**
  - Produces figures, automatically formatted for publications with LaTeX.



## Usage Instructions
- Run cells sequentially to ensure all data manipulations and visualizations are performed correctly.



