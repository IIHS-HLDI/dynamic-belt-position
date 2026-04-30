```bash
xsensor-belt-position/
├── src/
│   └── belt_position/
│       ├── algorithm/
│       │   ├── belt_position/
│       │   │   ├── calculate_raw_metrics.py
│       │   │   ├── clean_edge_points.py
│       │   │   ├── detect_edges.py
│       │   │   ├── ensure_consistent_direction.py
│       │   │   ├── estimate_belt_position.py
│       │   │   └── fit_edge_line.py
│       │   ├── data_cleaning/
│       │   │   ├── clean_frame_data.py
│       │   │   ├── process_speckles.py
│       │   │   └── remove_outlier_frames.py
│       │   ├── signal_processing/
│       │   │   ├── interpolate_belt_position.py
│       │   │   ├── merge_belt_and_chest_data.py
│       │   │   └── trim_channels.py
│       │   ├── units/
│       │   │   └── resolve_pressure.py
│       │   ├── visualization/
│       │   │   └── animate_estimated_belt_position.py
│       │   ├── workflow/
│       │   │   └── driver.py
│       ├── config/
│       │   ├── settings.py
│       ├── services
│       │   ├── data_loading/
│       │   │   ├── discover_data.py
│       │   │   ├── load_data.py
│       │   │   └── merge_baseline_frame_data.py
│       │   ├── cleanup.py
│       │   ├── exceptions.py
│       │   ├── logging_service.py
│       │   └── sanitize_data.py
│       └── main.py
├── templates/
│   ├── baseline_file
│   ├── chest deflection file
│   └── frame_file
├── .gitignore
├── pyproject.toml
├── README.md
└── requirements.txt
```
