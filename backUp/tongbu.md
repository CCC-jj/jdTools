自动同步教程:


一:[点击导入仓库](https://github.com/new/import)，URL框填写https://github.com/CCC-jj/jdTools
Repository Name填写仓库名字，点击绿色按钮，等待导入完成(不要把仓库设为私有，会运行失败)。





二:[申请PAT](https://github.com/settings/tokens/new)，Note下面框随意填写，把 repo和workflow 两部分勾上即可。
点击最下方的创建，生成的PAT复制下来。




三:申请完毕后，在新仓库分支中点击Settings-Secrets-New secret，name填PAT，框里面填写你第二步复制的PAT,保存即可。
接着再点击New secret，name填JD_COOKIE，框里面填写你的账号cookie，多账号换行。




四:点击仓库的Code，把上方的Star点亮，完毕
