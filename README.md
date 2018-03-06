# refs/tags/android-4.4.4_r2.0.1

## Apply all patches

- Copy needed ASB folder to your local Android source
- Apply all changes

```
repo forall -c "git am *.patch"
```

- Now delete all local patchfiles again

```
repo forall -c "rm -rf *.patch"
```

- Add the next ASB folder and start from beginning


## TODO - Add older bulletins

https://review.lineageos.org/#/q/topic:asb-2015.15+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2015.16+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2015.17+(status:open+OR+status:merged)

https://review.lineageos.org/#/q/topic:asb-2016.01+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.02+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.03+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.04+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.05+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.06+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.07+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.08+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.09+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.10+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2016.11+(status:open+OR+status:merged)

https://review.lineageos.org/#/q/topic:cm-11-asb-2017.01+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.02-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.03-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.04-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.05-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.05-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.06-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.07-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.08-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.09.01-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.10.01-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.11-cm-11.0+(status:open+OR+status:merged)
https://review.lineageos.org/#/q/topic:asb-2017.12-cm-11.0+(status:open+OR+status:merged)
