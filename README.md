# Blue Archive theme login theme for SDDM

Modify some problems in "Sugar Candy login", and make the theme adapted to Blue Archive (my favorite game)

![Preview](/Previews/PartialBlur.png "Preview")

# Usage

Fitstly, download the zip file from release page. Then unzip it to the sddm theme directory like this:
```bash
sudo cp /Arona /usr/share/sddm/themes/
```

After that you will have to point SDDM to the new theme by editing its config file, preferrably at /etc/sddm.conf (create if necessary). You can take the default config file of SDDM as a reference which might be found at: /usr/lib/sddm/sddm.conf.d/sddm.conf.

In the [Theme] section simply add the themes name to this line: Current=Arona. If you don't care for SDDM options and you had to create the file from blank just add these two lines and save it!

# Thanks to

This repo is built up on the [Sugar Candy login](https://github.com/Kangie/sddm-sugar-candy)