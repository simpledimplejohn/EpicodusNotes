RestSharp is used for making the api call
Newtonsoft is for parsing the json response data 

run in the terminal to add:
dotnet add package RestSharp --version 106.6.10
dotnet add package Newtonsoft.Json --version 12.0.2

Add to the top of your file:
using Newtonsoft.Json;
using Newtonsoft.Json.Linq;

? in an API string beginning of a search string 

Post request 