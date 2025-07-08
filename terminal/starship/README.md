## Notes
- [Starhsip](https://starship.rs/guide/)
- From `root`, in `.config/starship/` insert the TOML

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