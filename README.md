# scenario_and_camera_image_based_navigation

このリポジトリは〜で用いたリポジトリたちをまとめたものです．
git submoduleによって管理されています．

## 使い方
```
git clone https://github.com/haruyama8940/scenario_and_camera_image_based_navigation.git
cd scenario_and_camera_image_based_navigation
```

```
git submodule init
git submodule update
```
最新のコミットを参照する場合
```
git submodule foreach git fetch
git submodule update --remote
```
最新のコミットを参照先に変更する場合
```
git add .
git commit -m "hogehoge"
git push
```
