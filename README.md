# lm-test-app

``` bash
    source <(multiwerf use 1.0 alpha)
    werf stages build --stages-storage :local


    werf build-and-publish --stages-storage :local --images-repo nexus.lm-edu.flant.ru/hv6 --tag-custom=1.0.0
    werf deploy --env dev --stages-storage :local --images-repo nexus.lm-edu.flant.ru/hv6 --tag-custom=1.0.0 --env prod
```
