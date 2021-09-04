# Dotnet instalação

## Dependências

```
wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
```
```
sudo dpkg -i packages-microsoft-prod.deb
```
```
sudo apt-get update; \
sudo apt-get install -y apt-transport-https && \
sudo apt-get update && \
sudo apt-get install -y dotnet-sdk-3.1
```
```
dotnet --version
```
## Estrutura MVC
```
sudo dotnet new mvc -o mvcProject
sudo chmod -R 777 mvcProject
export TMPDIR=/tmp/NuGetScratch/
mkdir -p ${TMPDIR}
```
## VSCode 
[Plugin C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)

## Start Serve
```
dotnet run
> Open serve https://localhost:5001

