
Inicialmente criamos um diretório, nos movemos para ele e podemos então criar uma solution:
´mkdir projeto-final
cd projeto-final
dotnet new sln´
<br>
com o novo arquivo .sln criado criamos um novo projeto do tipo console, colocando na pasta criada anteriormente ´dotnet new console --output projeto-final´

por fim temos que adcionar a solucion no projeto ´dotnet sln add .´
depois de tudo configurado para buildar usamos apenas o comando ´dotnet build
´