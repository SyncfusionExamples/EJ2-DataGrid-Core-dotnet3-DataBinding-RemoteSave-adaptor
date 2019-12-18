# EJ2-DataGrid-Core-dotnet3-DataBinding-RemoteSave-adaptor

I257114 – This sample demonstrates on how to bind data to the grid from a url adaptor. In dotnet3 since the Json.Net api is not included by default, the following JSON api code must be included in the startup.cs file for displaying the data in grid,

| Code |
| --- |
| services.AddMvc().AddJsonOptions(o => {      o.JsonSerializerOptions.PropertyNamingPolicy = null; o.JsonSerializerOptions.DictionaryKeyPolicy = null; }); |
