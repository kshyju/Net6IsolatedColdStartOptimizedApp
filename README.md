# Net6IsolatedColdStartOptimizedApp

 - One http trigger (/api/Function1) with anonymous auth.
 - R2R publishing enabled.
 - Cold start optimization settings enabled.

#### Publishing

##### Linux
```bash
dotnet publish -c release -r linux-x64 --no-self-contained
```
##### Windows
```bash
dotnet publish -c release -r win-x64 --no-self-contained
```
> Also change the platform bitness from 32 bit(default) to 64 bit via azure portal.
