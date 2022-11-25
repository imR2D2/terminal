# PERSONALIZAR TERMINAL

- Descargar OHMYPOSH
https://ohmyposh.dev/docs/installation/windows

- Iconos
https://github.com/devblackops/Terminal-Icons

- Autocompletado
) Install-Module PSReadLine -Force -Scope CurrentUser
-- Estos dos los debes de meter en el archivo de guardado
) Set-PSReadLineOption -PredictionSource History
) Set-PSReadLineOption -PredictionViewStyle Listview

- Configurar perfil
)notepad $PROFILE

Import-Module oh-my-posh
Import-Module -Name Terminal-Icons
Set-PoshPrompt -Theme atomic
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle Listview
