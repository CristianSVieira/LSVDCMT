# Instala o Brew 
(Um commando só, corra-o no terminal do Mac)
[brew.sh](http://brew.sh)

# Instala o Visual Studio Code com o Brew

``brew install --cask visual-studio-code``

# Instala a .NET SDK

.NET 6++
- Qualquer um do sítio da Microsoft

# Instala as cargas do MAUI (Somente funcionará com a SDK instalada, fixe?)

(Instalação da Carga)
``dotnet workload install maui``
(Instalação dos modelos de projectos MAUI)
``dotnet new install Microsoft.Maui.Templates``

(Cria um novo projecto MAUI)
``dotnet new maui -n projecto``