# Nvim Portable for User (non admin)

```sh
[Environment]::SetEnvironmentVariable("PATH", $Env:PATH + ";C:\Program Data\Neovim\ripgrep", [EnvironmentVariableTarget]::User)
[Environment]::SetEnvironmentVariable("PATH", $Env:PATH + ";C:\Program Data\Neovim\node", [EnvironmentVariableTarget]::User)
[Environment]::SetEnvironmentVariable("PATH", $Env:PATH + ";C:\Program Data\Neovim\bin", [EnvironmentVariableTarget]::User)
```

```sh
git clone https://github.com/KinitoSs/nvim-ide.git C:\Users\kinbu\AppData\Local\nvim
```
