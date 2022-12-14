# Nvim Portable for User (non admin)

```sh
[Environment]::SetEnvironmentVariable("PATH", $Env:PATH + ";C:\Users\kinbu\Neovim\ripgrep", [EnvironmentVariableTarget]::User)
[Environment]::SetEnvironmentVariable("PATH", $Env:PATH + ";C:\Users\kinbu\Neovim\node", [EnvironmentVariableTarget]::User)
[Environment]::SetEnvironmentVariable("PATH", $Env:PATH + ";C:\Users\kinbu\Neovim\bin", [EnvironmentVariableTarget]::User)
```

```sh
pip install pynvim
npm i -g neovim
```
