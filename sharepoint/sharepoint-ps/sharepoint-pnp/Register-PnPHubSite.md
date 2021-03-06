---
external help file:
online version: https://docs.microsoft.com/powershell/module/sharepoint-pnp/register-pnphubsite
applicable: SharePoint Online
schema: 2.0.0
---

# Register-PnPHubSite

## SYNOPSIS
Registers a site as a hubsite

## SYNTAX 

```powershell
Register-PnPHubSite -Site <SitePipeBind>
                    [-Connection <SPOnlineConnection>]
```

## DESCRIPTION
Registers a site as a hubsite

## EXAMPLES

### ------------------EXAMPLE 1------------------
```powershell
Register-PnPHubSite -Site https://tenant.sharepoint.com/sites/myhubsite
```

This example registers the specified site as a hubsite

## PARAMETERS

### -Site
The site to register as a hubsite

```yaml
Type: SitePipeBind
Parameter Sets: (All)

Required: True
Position: Named
Accept pipeline input: False
```

### -Connection
Optional connection to be used by the cmdlet. Retrieve the value for this parameter by either specifying -ReturnConnection on Connect-PnPOnline or by executing Get-PnPConnection.

```yaml
Type: SPOnlineConnection
Parameter Sets: (All)

Required: False
Position: Named
Accept pipeline input: False
```

## RELATED LINKS

[SharePoint Developer Patterns and Practices](https://aka.ms/sppnp)