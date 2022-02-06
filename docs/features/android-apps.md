---
title: Android Apps on toffeeOS
---

## Android Apps on toffeeOS
Since we use APK files on chocolateOS, and we have a mission to unify the "ecosystem," we've built in the ability to run Android apps on toffeeOS natively. 

To activate this feature (experimental), open our console app, and type either of following commands (depending on your version):

## unicorn 1.6.6 and later

```
sudo toffget toffeeos-dev apkrunner -y
```

### unicorn 1.6.5 and earlier

```
sudo toffget install --repo unicorn-dev-latest --package apkrunner -y
```

We also recommend grabbing the latest version of ``toffeeserver`` which is also available on [toffget](/features/package-managers#toffget/).
