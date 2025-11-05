# Neural-Network-Based-Prediction-of-Nivolumab-PD-1-Binding-and-Epitope-Mapping
Predicts Nivolumab–PD-1 binding using a neural network trained on experimental data. Includes epitope mapping, amino acid substitution analysis, and 2D/3D visualizations of predicted binding regions using PyTorch, Matplotlib, and Py3Dmol.
Description:
This notebook implements a full deep learning pipeline to model Nivolumab antibody binding to PD-1 peptide fragments. It trains a neural network using experimental binding data, predicts epitope regions on the PD-1 sequence, and visualizes results through binding heatmaps, 3D molecular models, and fine-mapping analyses of amino acid substitutions. The workflow integrates PyTorch, Matplotlib, and Py3Dmol for model training, performance evaluation, and structural visualization.

Key Features:

Neural network architecture for quantitative binding prediction.

PD-1 epitope scanning using overlapping 10-mer peptides.

Visualization of predicted binding intensities (2D and 3D).

Fine-mapping analysis for identifying critical amino acids.

Integration with AlphaFold structure for 3D binding interpretation.
