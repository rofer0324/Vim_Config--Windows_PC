# NeoVim_Config--Windows_PC

Install Chocolatey in POWERSHELL like Admn {

https://chocolatey.org/install

 $ Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
 
 }
 
 THEN
 
 Install NeoVim from prowershell {
 
 choco install neovim
 
 }
 
 in the route: AppData\Local
 if exist the directory "nvim-data" you go for the good way.
 
 CREATE this directory in the route AppData\Local: "nvim" and paste the content of this repository in this route.
 
 then excute nvim init.vim from your cmd and execute:
 :PlugInstall
 :PlugUpdate
 
 now this is ready to program
 
 this Config. is inspired from this channel https://www.youtube.com/watch?v=buYfMTbT-DA&t=321s. !!



