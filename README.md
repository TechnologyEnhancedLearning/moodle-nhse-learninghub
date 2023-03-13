## NHSE Moodle theme (Boost extension)
### Latest version v1.0

Requirements
1. Node 19.4
2. Moodle 4.1 with Boost theme

Installation 
1. Clone that repository into your Moodle `theme/nhse` directory.
```
git clone git@github.com:NHSLeadership/moodle-nhse.git nhse
``` 

2. Before activating theme in Moodle theme selector the dependencies need loading.
```
npm install
```
Tested with NPM v9.2.0 and Node v19.4.0, you can check both versions with:
```
npm -v
node -v
```

3. Proceed with Moodle installer instructions when new theme is detected 

4. If you need to change any dependencies of the SCSS files please remember to clear Moodle caches in Moodle admin panel `/admin/purgecaches.php`. Moodle SCSS compiler will do the rest for you.
