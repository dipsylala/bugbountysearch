# Bug Bounty Searches

Courtesy of https://twitter.com/Alra3ees and a set of tweets starting here: https://twitter.com/Alra3ees/status/1738483582618743245

## Bug Bounty Google Dorks

```
intext:"As a token of our gratitude for your assistance, we offer a reward for every report of a security problem that was not yet known to us"
```

```
intext:"The minimum reward will be"
```

```
intext:"The amount of the reward will be determined based on the severity"
```

## Find bug bounty programs that running on @intigriti and @yeswehack  via waybackurls

```shell
waybackurls app.intigriti.com/researcher/pro… | grep /programs/
```

```shell
waybackurls app.intigriti.com/researcher/pro… | grep /project/
```

```shell
waybackurls yeswehack.com/programs/  | grep /programs/
```

## Google Dork Bounty programs

```
inurl:(responsible-disclosure-policy | Coordinated-Vulnerability-Disclosure| bug bounty policy)
```

```
intext:(responsible disclosure policy | Coordinated Vulnerability Disclosure| bug bounty policy)
```

```
inurl:disclaimer intext:(responsible disclosure statement bug bounty)
```

```
inurl:disclaimer intext:"Responsible disclosure statement"
```

```
inurl:(responsible disclosure $200)
```

## Find bug bounty via Google Dork security txt

```
inurl:"/.well-known/security.txt"
```

```
inurl:/.well-known/security.txt
```


```
inurl:/security/bugbounty
```

```
inurl:/security/bugreport
```

```
intext:"submit a security vulnerability report"
```

```
intext:"submit a bug bounty report"
```

## Find bug bounty programs via firebounty

```
site:"firebounty.com" intext:"bugcrowd.com"
```

```
site:"firebounty.com" intext:"hackerone.com"
```

```
site:"firebounty.com" intext:"yeswehack.com"
```

## Find bug bounty programs running on @zerocopter via waybackurls and google dorks

```shell
waybackurls app.zerocopter.com |grep /cvd/ |sort
```

```shell
waybackurls app.zerocopter.com |grep /rd/ |sort
```


```
intext:"app.zerocopter.com"
```

```
intext:"app.zerocopter.com/en/rd/"
```



