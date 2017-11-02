# Blocks Theme
clone this repo into your octobercms themes folder.

(assume your in the root of your octobercms installation)

NOTE: the name blocks is important, if you change the themes name you have to alter the groups attribute in the layouts/default.htm
repeater to match the path.

```
cd themes
git clone https://github.com/liip/oc-blocks-theme.git blocks
```

in your backend, check the static pages plugin. You now have a blocks tab where you can add different blocks, enter data 
and even rearrange their order.

To add more block types, edit the meta/groups.yaml file. 
Important: each group definition has a corresponding partial file in 
partials/blocks/{group_name}. The form data is passed as 'data'.
