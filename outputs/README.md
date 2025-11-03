# Outputs Directory

```
outputs/
├── aeronet_monthly_metrics.csv   # Monthly AERONET fine/coarse mode metrics
├── charts/                       # Static PNG exports of the Datawrapper visuals
├── igra_monthly_metrics.csv      # Monthly IGRA stability statistics
├── igra_seasonal_metrics.csv     # Seasonal IGRA stability statistics
├── near_space_monthly_combo.csv  # Joined stability–aerosol table
└── datawrapper_links.md          # Live chart URLs
```

Regenerate the CSVs with `process_near_space.py`, then republish through the Datawrapper API and refresh the PNG exports in `charts/`.
