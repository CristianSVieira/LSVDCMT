(FAÇA ISTO ANTE A PROCEDÊNCIA) [[Preparatório a um projecto MAUI]]

Onde se lê "net7.0" nos commandos pode vir a ser também qualquer versão que se tenha instalada.
# No Mac

``dotnet build -t:Run -f net7.0-maccatalyst``

# No iOS (iPhone e iPad nos simuladores do mac)
Obviamente, instala o xcode e os simuladores de ante-mão. 

``dotnet build -t:Run -f net7.0-ios``

# Em simulador especial (GUID imaginária)

``dotnet build -t:Run -f net7.0-ios -p:_DeviceName=:v2:udid=03C3959D-1674-4EB3-B28E-1CD5448CC818``

