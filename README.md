# az-functions-development-vs-code
Dotnet add package <package-reference-name> 

 

Manually adding reference 

 

<PackageReference Include="Microsoft.Azure.WebJobs.Extensions.Storage" Version="3.0.0" /> 
<PackageReference Include="Microsoft.NET.Sdk.Functions" Version="1.0.24" /> 

 

Access key vault from functions 

1. Enable system assigned Identity for the functions so that the function is registered in AD 

Now from key vault, Access Policies; add the function as service principal 

 

x 
Discard 
Refresh 
Please click the Save' button to commit your changes. 
Enable Access to: 
Azure Virtual Machines for deployment O 
v Azure Resource Manager for template deployment O 
Azure Disk Encryption for volume encryption O 
 
