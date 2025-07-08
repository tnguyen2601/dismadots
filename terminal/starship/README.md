## Notes
- [Starship](https://starship.rs/guide/)
- From `root`, create a `starship` directory in `.config` and insert the TOML.
  - `.config/starship/starship.toml`

**Addtionally:**
### Bash
```bash
eval "$(starship init bash)"
```
### Powershell
```powershell
$ENV:STARSHIP_CONFIG = "$HOME\.config\starship\starship.toml"
Invoke-Expression (&starship init powershell)
```