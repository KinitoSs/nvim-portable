# Nvim Portable for User (non admin)

```sh
[Environment]::SetEnvironmentVariable("PATH", $Env:PATH + ";C:\Program Data\Neovim\ripgrep", [EnvironmentVariableTarget]::User)
[Environment]::SetEnvironmentVariable("PATH", $Env:PATH + ";C:\Program Data\Neovim\node", [EnvironmentVariableTarget]::User)
[Environment]::SetEnvironmentVariable("PATH", $Env:PATH + ";C:\Program Data\Neovim\bin", [EnvironmentVariableTarget]::User)
```

```sh
pip install pynvim
npm i -g neovim
```

```sh
git clone https://github.com/KinitoSs/nvim-ide.git C:\Users\kinbu\AppData\Local\nvim
```
