# MoonWX's Scoop Bucket

## Description
This is MoonWX's private scoop bucket though is a public repository.

And this bucket is here to provide some of my favorite tools and applications that I use on a daily basis.
This bucket is not intended to be a complete list of all the applications I use, but rather a curated selection of tools that I find particularly useful.

ONLY FOR MY PERSONAL USE!

NO WARRANTY FOR ANYTHING!

## Installation

Don't forget to change scoop directory to your preferred location. You can do this by running the following command:

```powershell
[Environment]::SetEnvironmentVariable('SCOOP', 'D:\Apps\Scoop', 'User');
[Environment]::SetEnvironmentVariable('SCOOP_GLOBAL', 'D:\Apps\Scoop\Global', 'Machine');
```

In case you don't have Scoop installed, you can install it by running the following command in PowerShell:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

Then, you can add this bucket to your Scoop installation by running the following command:

```powershell
scoop bucket add moonwx https://github.com/MoonWX/scoop_bucket
```

After that, you can install any of the applications in this bucket by running the following command:

```powershell
scoop install <app-name>
```
