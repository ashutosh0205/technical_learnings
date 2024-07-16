# technical_learnings


## Spring


## VS Code

### Disabling Security in Launch.json configuration

```
"runtimeArgs": [
                "--disable-web-security",
                "--no-default-browser-check",
                 "--disable-first-run",
                 "--ignore-certificate-errors 'http://127.0.0.1:8081'",
               //  "--user-data-dir=/c/temp",
                 "--disable-features=SameSiteByDefaultCookies,CookiesWithoutSameSiteMustBeSecure"
            ],
```
