install probe
uncomment probe
set probe z endstop
adjust beacon offset
QUERY_PROBE - check if triggered
PROBE_ACCURACY
adjust z offset - G28 - QUAD_GANTRY_LEVEL - G28 - Z_ENDSTOP_CALIBRATE - Z_OFFSET_APPLY_ENDSTOP - SAVE_CONFIG
QGL - QUAD_GANTRY_LEVEL
G28 - home
input shaper
- ACCELEROMETER_QUERY
- SHAPER_CALIBRATE AXIS=Y
- SAVE_CONFIG
- SHAPER_CALIBRATE AXIS=X
- SAVE_CONFIG
