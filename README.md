# Large-screen-visualization
预览请点击：
https://zzzoucy.github.io/Large-screen-visualization/index.html#/

#打包过程：

yarn build --base ./

cd dist

git init

git add .

git commit -m deploy

git remote add origin git@github.com:ZZZoucy/Large-screen-visualization.git

branch -M main

push -u origin main
