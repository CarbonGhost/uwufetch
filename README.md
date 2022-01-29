<p align="center">
  <img src="https://user-images.githubusercontent.com/39361743/151651600-a1dcfcac-9068-4eca-b21a-942ba8906a9a.png" />
</p>
  
<p align="center">uwufetch - a very serious winfetch fork.</p>

<h3 align="center">Usage</h3>

Download the `winfetch.ps1` file in this repository to your PowerShell scripts folder.

If you wish to trigger it with an alias, add a line to your `$PROFILE` like this:

```ps1
Set-Alias winfetch winfetch.ps1
```

<h3 align="center">Configuration</h3>

In your terminal run:

```bash
winfetch -genconf
```

which will generate a configuration file. This fork currently adds one ASCII art variatoion, which can be set by changing the value:

```ps1
# Set the version of Windows to derive the logo from.
$logo = "UWU"

```

<p align="center">
  <img src="https://user-images.githubusercontent.com/39361743/151663911-5461cb0e-4ff3-467a-883d-1a581ccdbe7a.png" />
</p>
  
---

[Original project](https://github.com/kiedtl/winfetch)    •    ASCII art by _@mineland#1324_ on Discord
