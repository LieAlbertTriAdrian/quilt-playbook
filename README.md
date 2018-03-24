# quilt-playbook
My playground of quilt data

## Steps
1. Initiate quilt
```
quilt generate data/[data_folder]
```
2. Build quilt package
```
quilt build albertlie/[data_folder] data/[data_folder]/build.yml
```

3. Push Quilt Package
```
quilt push --public albertlie/[data_folder]
```