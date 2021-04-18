FROM mcr.microsoft.com/windows/servercore/iis

RUN dism.exe /online /enable-feature /all /featurename:iis-webserver /NoRestart

WORKDIR c:\inetpub\wwwroot