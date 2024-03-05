# Bootstrap 5 Theme for Home Assistant

![GitHub Repo stars](https://img.shields.io/github/stars/Eonasdan/home-assistant-bootstrap-5-theme?style=for-the-badge&labelColor=ffc107&color=ffcd39)
![GitHub Repo stars](https://img.shields.io/github/issues/Eonasdan/home-assistant-bootstrap-5-theme?style=for-the-badge&labelColor=dc3545&color=e35d6a)
![GitHub Repo stars](https://img.shields.io/github/issues/Eonasdan/home-assistant-bootstrap-5-theme?style=for-the-badge&labelColor=198754&color=479f76)

This theme matches the Bootstrap 5.3.3 [color palette](https://getbootstrap.com/docs/5.3/customize/color/#colors). It has both a light and dark theme and allows for the "Auto" setting in Home Assistant.

## Dark Mode
![image](https://github.com/Eonasdan/home-assistant-bootstrap-5-theme/assets/1006516/d7043973-9eb5-4347-a59a-4b6652bbb18a)


## Light Mode
![image](https://github.com/Eonasdan/home-assistant-bootstrap-5-theme/assets/1006516/d3d95eb2-11c7-4a89-923f-eb66725b373b)


## Usage
Make sure you have themes enabled in your configuration:
```yaml
frontend:
  # ... your configuration.
  themes: !include_dir_merge_named themes
  # ... your configuration.
```

### With [HACS](https://hacs.xyz/)
1. Go to the Community Store.
2. Search for `Bootstrap 5 theme`.
3. Navigate to `Bootstrap 5 theme` theme.
4. Press `Install`.
5. Go to Developer Tools and trigger "All YAML Configuration"

### Manual
1. Clone the repository
```bash
git clone https://github.com/Eonasdan/home-assistant-bootstrap-5-theme.git
```
2. Copy `themes/bootstrap5.yaml` in your existing (or create it) `themes/` folder.

```bash
mv home-assistant/themes/bootstrap5.yaml ~/config/themes/.
```
