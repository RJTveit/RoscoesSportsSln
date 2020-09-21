# RoscoesSportsSln
Student project demo based on Adam Freeman's PRO ASP.NET Core 3 book. (https://www.apress.com/gp/book/9781484254394)

## Create Solution and Projects


    dotnet new globaljson --sdk-version 3.1.101 --output RoscoesSportsSln/OutdoorProducts
    dotnet new web --no-https --output RoscoesSportsSln/OutdoorProducts --framework netcoreapp3.1
    dotnet new sln -o RoscoesSportsSln
    dotnet sln RoscoesSportsSln add RoscoesSportsSln/OutdoorProducts 
    dotnet new xunit -o RoscoesSportsSln/OutdoorProducts.Tests --framework netcoreapp3.1
    dotnet sln RoscoesSportsSln add RoscoesSportsSln/OutdoorProducts.Tests 
    dotnet add RoscoesSportsSln/OutdoorProducts.Tests reference RoscoesSportsSln/OutdoorProducts 

## Chapter 8 Additions

![Image1](https://github.com/RJTveit/RoscoesSportsSln/blob/master/Screenshots/Sports%20Store%201.png)

![Image2](https://github.com/RJTveit/RoscoesSportsSln/blob/master/Screenshots/Sports%20Store%202.png)

![Image3](https://github.com/RJTveit/RoscoesSportsSln/blob/master/Screenshots/Sports%20Store%203.png)

Currently troubleshooting the final test class.

![Image4](https://github.com/RJTveit/RoscoesSportsSln/blob/master/Screenshots/Sports%20Store%204.png)
