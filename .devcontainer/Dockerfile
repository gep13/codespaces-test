FROM mcr.microsoft.com/oryx/build:vso-20200706.2

RUN dotnet --info \
	&& dotnet tool install Cake.Tool --global
    && dotnet-cake --info
