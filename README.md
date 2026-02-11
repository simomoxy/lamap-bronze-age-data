# LAMAP Bronze Age Data

30 LAMAP probability maps for archaeological site prediction in Cyprus (Bronze Age).

## Parameters

- **sites**: 10, 15, 20, 25 (k-NN neighbors)
- **weight_params**: 0.1 - 1.0 (distance decay)
- **sample_fraction**: 0.05, 0.10, 0.15, 0.20, 0.25, 0.30
- **PCA**: true/false
- **interpolate**: true/false
- **steps**: std/adaptive

## File Format

Filenames follow the pattern:
```
period=bronze_age_sites={sites}_weight={weight}_sample_fraction={sample}_PCA={PCA}_interpolate={interpolate}_dataset=DEM_seed=42_steps={steps}_norm=None_lamap.png
```

## Usage

Load PNG files directly as probability maps (0-1 range). For georeferencing, use the source DEM:
```
/data/brussel/107/vsc10777/NEEDLES/data/cyprus/multiband/nasadem_bottom_left/bronze_age_multiband.tif
```

## Citation

If you use this data, please cite:
- Carleton, W.C. (2012). A locally-adaptive model of archaeological potential (LAMAP). *Journal of Archaeological Science*, 43, 134-147.
