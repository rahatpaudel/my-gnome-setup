# My GNOME Setup

## THEMING

The GTK theme colors are inspired (copied) from the "Dark Blue Style" in [Planify](https://github.com/alainm23/planify).

- Install [Rewaita](https://github.com/SwordPuffin/Rewaita)
- Add Planify 🕶️.css from above to your Rewaita themes folder (usually `$HOME/.var/app/io.github.swordpuffin.rewaita/data/dark`)
- Open Rewaita and select "Planify" from the list of themes
- Enable "Transparency" toggle

### TRANSLUCENT EFFECT

[Blur My Shell](https://extensions.gnome.org/extension/3193/blur-my-shell/) extension is used to achieve the blur effect. Under blur my shell settings, activate "Applications blur" and whitelist the apps where you want a blurred background.

I currently disble certain apps (such as e-book readers and video players) from the transparency effect by launching them with a different `XDG_CONFIG_HOME` variable (for example, `env XDG_CONFIG_HOME=/home/rahat/.config/no-transparency foliate`). Though, I am looking for a better way of doing this.
