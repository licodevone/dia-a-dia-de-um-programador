
# VSCode instalações e configurações

![alt text](image-6.png)

![alt text](image-8.png)

![alt text](image-9.png)

![alt text](image-10.png)

![alt text](image-12.png)

## Configuração do terminal powerlevel 10K

![alt text](image-7.png)

https://github.com/romkatv/powerlevel10k/issues/671

Baixe estes quatro arquivos ttf:

MesloLGS NF Regular.ttf
MesloLGS NF Bold.ttf
MesloLGS NF Italic.ttf
MesloLGS NF Bold Italic.ttf
Clique duas vezes em cada arquivo e clique em “Instalar”. Isso disponibilizará MesloLGS NFa fonte para todos os aplicativos do seu sistema.

Abra Configurações no Visual Studio Code .

No PC: pressione Ctrl+,ou clique em Arquivo → Preferências → Configurações .
No Mac: pressione ⌘ ,ou clique em Código → Preferências → Configurações .
Digite terminal.integrated.fontFamilyna caixa de pesquisa na parte superior da guia Configurações e defina o valor abaixo como MesloLGS NF.

![alt text](image-23.png)

Você pode encontrar instruções semelhantes para todos os terminais populares neste documento: https://github.com/romkatv/powerlevel10k/blob/master/font.md

```
terminal.integrated.fontFamily
```

![alt text](image-24.png)

Inserir as duas linhas no settigins.json
```
{
    "terminal.integrated.shell.osx": "/bin/zsh",
    "terminal.integrated.fontFamily": "MesloLGS NF",
}
```
![alt text](image-25.png)

settings.json

```json
{
    "terminal.integrated.shell.osx": "/bin/zsh",
    "terminal.integrated.fontFamily": "MesloLGS NF",
    "workbench.iconTheme": "vscode-icons",
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "editor.fontVariations": false
}
```

## ESLint

![alt text](image-36.png)