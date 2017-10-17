# New-PnPPersonalSite

## SYNOPSIS
Office365 only: Creates a personal / OneDrive For Business site

>Only available for SharePoint Online

## SYNTAX 

```powershell
New-PnPPersonalSite -Email <String[]>
```

## EXAMPLES

### ------------------EXAMPLE 1------------------
```powershell
PS:> $users = ('katiej@contoso.onmicrosoft.com','garth@contoso.onmicrosoft.com')
                 PS:> New-PnPPersonalSite -Email $users
```

Creates a personal / OneDrive For Business site for the 2 users in the variable $users

## PARAMETERS

### -Email
The UserPrincipalName (UPN) of the users

```yaml
Type: String[]
Parameter Sets: (All)

Required: True
Position: 0
Accept pipeline input: False
```

# RELATED LINKS

[SharePoint Developer Patterns and Practices](http://aka.ms/sppnp)