# NuGet Package: Escendit.Tools.CodeAnalysis.StyleCopAnalyzers

This NuGet package leverages the power of StyleCop Analyzers
to enforce code quality standards that are tailored to the organization's specific needs.
By default,
the package uses a set of analyzer rules that have been configured to align with the organization's coding practices,
ensuring that our code is always compliant and maintainable.

Key features:

- Utilize Roslyn .NET Analyzers for powerful and customizable code analysis
- Defaults suited to the organization's coding practices
- Ensures code compliance and maintainability

## Installation
To install this package, use the NuGet Package Manager Console:

```shell
PM> Install-Package Escendit.Tools.CodeAnalysis.StyleCopAnalyzers
```
Or you can search for "Escendit.Tools.CodeAnalysis.StyleCopAnalyzers"
in the NuGet Package Manager UI and install it from there.

## Usage
After installing the package, the MSBuild and .editorconfig properties will be set automatically.
- You can modify the MSBuild properties by updating the values in your .csproj or .vbproj file.
- You can modify the .editorconfig properties by creating .editorconfig file and overriding the default values.

## Configuration

The NuGet package includes the following default rules and severity levels:


| Rule     | Severity | Severity |
|----------|----------|----------|
| SA0001   | error    | ❌        |
| SA0002   | error    | ❌        |
| SA1000   | error    | ❌        |
| SA1001   | error    | ❌        |
| SA1002   | error    | ❌        |
| SA1003   | error    | ❌        |
| SA1004   | error    | ❌        |
| SA1005   | error    | ❌        |
| SA1006   | error    | ❌        |
| SA1007   | error    | ❌        |
| SA1008   | error    | ❌        |
| SA1009   | error    | ❌        |
| SA1010   | error    | ❌        |
| SA1011   | error    | ❌        |
| SA1012   | error    | ❌        |
| SA1013   | error    | ❌        |
| SA1014   | error    | ❌        |
| SA1015   | error    | ❌        |
| SA1016   | error    | ❌        |
| SA1017   | error    | ❌        |
| SA1018   | error    | ❌        |
| SA1019   | error    | ❌        |
| SA1020   | error    | ❌        |
| SA1021   | error    | ❌        |
| SA1022   | error    | ❌        |
| SA1023   | error    | ❌        |
| SA1024   | error    | ❌        |
| SA1025   | error    | ❌        |
| SA1026   | error    | ❌        |
| SA1027   | error    | ❌        |
| SA1028   | error    | ❌        |
| SA1100   | error    | ❌        |
| SA1101   | none     | ⛔        |
| SA1102   | error    | ❌        |
| SA1103   | error    | ❌        |
| SA1104   | error    | ❌        |
| SA1105   | error    | ❌        |
| SA1106   | error    | ❌        |
| SA1107   | error    | ❌        |
| SA1108   | error    | ❌        |
| SA1110   | error    | ❌        |
| SA1111   | error    | ❌        |
| SA1112   | error    | ❌        |
| SA1113   | error    | ❌        |
| SA1114   | error    | ❌        |
| SA1115   | error    | ❌        |
| SA1116   | error    | ❌        |
| SA1117   | error    | ❌        |
| SA1118   | error    | ❌        |
| SA1119   | error    | ❌        |
| SA1120   | error    | ❌        |
| SA1121   | error    | ❌        |
| SA1122   | error    | ❌        |
| SA1123   | error    | ❌        |
| SA1124   | error    | ❌        |
| SA1125   | error    | ❌        |
| SA1127   | error    | ❌        |
| SA1128   | error    | ❌        |
| SA1129   | error    | ❌        |
| SA1130   | error    | ❌        |
| SA1131   | error    | ❌        |
| SA1132   | error    | ❌        |
| SA1133   | error    | ❌        |
| SA1134   | error    | ❌        |
| SA1135   | error    | ❌        |
| SA1136   | error    | ❌        |
| SA1137   | error    | ❌        |
| SA1139   | error    | ❌        |
| SA1141   | error    | ❌        |
| SA1142   | error    | ❌        |
| SA1200   | error    | ❌        |
| SA1201   | error    | ❌        |
| SA1202   | error    | ❌        |
| SA1203   | error    | ❌        |
| SA1204   | error    | ❌        |
| SA1205   | error    | ❌        |
| SA1206   | error    | ❌        |
| SA1207   | error    | ❌        |
| SA1208   | error    | ❌        |
| SA1209   | error    | ❌        |
| SA1210   | error    | ❌        |
| SA1211   | error    | ❌        |
| SA1212   | error    | ❌        |
| SA1213   | error    | ❌        |
| SA1214   | error    | ❌        |
| SA1216   | error    | ❌        |
| SA1217   | error    | ❌        |
| SA1300   | none     | ⛔        |
| SA1302   | error    | ❌        |
| SA1303   | error    | ❌        |
| SA1304   | error    | ❌        |
| SA1305   | error    | ❌        |
| SA1306   | error    | ❌        |
| SA1307   | error    | ❌        |
| SA1308   | error    | ❌        |
| SA1309   | none     | ⛔        |
| SA1310   | error    | ❌        |
| SA1311   | error    | ❌        |
| SA1312   | error    | ❌        |
| SA1313   | error    | ❌        |
| SA1314   | error    | ❌        |
| SA1316   | error    | ❌        |
| SA1400   | error    | ❌        |
| SA1401   | error    | ❌        |
| SA1402   | error    | ❌        |
| SA1403   | error    | ❌        |
| SA1404   | error    | ❌        |
| SA1405   | error    | ❌        |
| SA1406   | error    | ❌        |
| SA1407   | error    | ❌        |
| SA1408   | error    | ❌        |
| SA1410   | error    | ❌        |
| SA1411   | error    | ❌        |
| SA1412   | error    | ❌        |
| SA1413   | error    | ❌        |
| SA1414   | error    | ❌        |
| SA1500   | error    | ❌        |
| SA1501   | error    | ❌        |
| SA1502   | error    | ❌        |
| SA1503   | error    | ❌        |
| SA1504   | error    | ❌        |
| SA1505   | error    | ❌        |
| SA1506   | error    | ❌        |
| SA1507   | error    | ❌        |
| SA1508   | error    | ❌        |
| SA1509   | error    | ❌        |
| SA1510   | error    | ❌        |
| SA1511   | error    | ❌        |
| SA1512   | error    | ❌        |
| SA1513   | error    | ❌        |
| SA1514   | error    | ❌        |
| SA1515   | error    | ❌        |
| SA1516   | error    | ❌        |
| SA1517   | error    | ❌        |
| SA1518   | error    | ❌        |
| SA1519   | error    | ❌        |
| SA1520   | error    | ❌        |
| SA1600   | error    | ❌        |
| SA1601   | error    | ❌        |
| SA1602   | error    | ❌        |
| SA1604   | error    | ❌        |
| SA1605   | error    | ❌        |
| SA1606   | error    | ❌        |
| SA1607   | error    | ❌        |
| SA1608   | error    | ❌        |
| SA1609   | error    | ❌        |
| SA1610   | error    | ❌        |
| SA1611   | error    | ❌        |
| SA1612   | error    | ❌        |
| SA1613   | error    | ❌        |
| SA1614   | error    | ❌        |
| SA1615   | error    | ❌        |
| SA1616   | error    | ❌        |
| SA1617   | error    | ❌        |
| SA1618   | error    | ❌        |
| SA1619   | error    | ❌        |
| SA1620   | error    | ❌        |
| SA1621   | error    | ❌        |
| SA1622   | error    | ❌        |
| SA1623   | error    | ❌        |
| SA1624   | error    | ❌        |
| SA1625   | error    | ❌        |
| SA1626   | error    | ❌        |
| SA1627   | error    | ❌        |
| SA1628   | error    | ❌        |
| SA1629   | error    | ❌        |
| SA1633   | error    | ❌        |
| SA1634   | error    | ❌        |
| SA1635   | error    | ❌        |
| SA1636   | error    | ❌        |
| SA1637   | error    | ❌        |
| SA1638   | error    | ❌        |
| SA1639   | error    | ❌        |
| SA1640   | error    | ❌        |
| SA1641   | error    | ❌        |
| SA1642   | error    | ❌        |
| SA1643   | error    | ❌        |
| SA1648   | error    | ❌        |
| SA1649   | error    | ❌        |
| SA1651   | error    | ❌        |
| SX1101   | error    | ❌        |
| SX1309   | error    | ❌        |
| SX1309S  | error    | ❌        |


To modify the severity level of a rule, you can add the following code to your .editorconfig file:

```editorconfig
# dotnet_diagnostic.<Rule>.severity = <Severity>
```

For example, to change the severity level of `SA9999` to "error", add the following line to your .editorconfig file:

```editorconfig
# dotnet_diagnostic.SA9999.severity = error
```


## Contributing
If you find a bug or have a feature request, please create an issue in the GitHub repository.

To contribute code, fork the repository and submit a pull request.
Please ensure that your code follows the project's coding standards and is thoroughly tested.

## License
This package is released under the MIT License. See the LICENSE.txt file for details.

