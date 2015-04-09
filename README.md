# Salt

In order to automatically lint Salt files before pushing to GitHub, we now require a git pre-push hook for all committers. Just run the following command from the `Salt/` folder to automatically install the hook.

```
cd Salt/
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Expenisfy/Salt/master/pre-push-hook.rb)"
```

<br>