# Day to Day Hacks

## VS Code / Angular

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





# Online References

## Java Spring etc

### Spring K8s docker deployment
Buildpack - Maven plugin to create docker images
https://bell-sw.com/blog/how-to-use-buildpacks-with-spring-boot/

Tilt - https://docs.tilt.dev/
Kubernetes for Prod, Tilt for Dev. They (Tilt team) saying it can spin up all services on a new environment with one command like tilt up.
kind of like teraform but for local development like lightweight.
Jkube - https://eclipse.dev/jkube/ Just do mvn k8s:push and it will deploy your service to k8s...

