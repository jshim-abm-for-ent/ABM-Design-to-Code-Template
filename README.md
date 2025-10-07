# ABM Design-to-Code Template (v0.2-beta)
## Canvas-to-NetLogo Interface Integration

This version introduces automatic generation of NetLogo 7.x interfaces (.nlogox) from ABM Canvas inputs.

### Workflow
1. Complete your Canvas using `templates/ABM_Canvas_Template.md`.
2. Convert Canvas → Code (.nls) with `scripts/build_nls_from_canvas.py`.
3. Convert Canvas → Interface (.nlogox) with `scripts/build_nlogox_from_canvas.py`.
4. Use `templates/widgets_7.0.nlogox` as the default seed for UI generation.

### Configuration
Defined in `config.json`:
```json
{
  "default_widget_template": "templates/widgets_7.0.nlogox",
  "default_include_nls": "templates/Example_Output_Code.nls"
}
```

### License
MIT License © 2025 Jaehu Shim et al.
