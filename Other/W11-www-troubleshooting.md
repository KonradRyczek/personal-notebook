# W11 www troubleshooting

`Get-NetIPAddress`
`Get-NetIPConfiguration`
`Get-NetAdapter`
`Enable-NetAdapter`/ `Disable-NetAdapter`
`Get-NetRoute`
`Test-Connection` (it has many more options that pinf ex. -TraceRoute)
`Get-NetTCPConnection` (similar to netstat)
`Resolve-DnsName`
`Get-DnsClient`
`Get-DnsClientCache`
`Clear-DnsClientCache`
`Get-DnsClientServerAddress`
`Get-Service -Name DhcpServer`
`Restart-Service -Name DHCPServer`

`Test-NetConnection -InformationLevel "Detailed"`
`Test-NetConnection -ComputerName "www.contoso.com" -InformationLevel "Detailed"`
`Test-NetConnection -ComputerName www.contoso.com -DiagnoseRouting -InformationLevel Detailed ComputerName : www.contoso.com`