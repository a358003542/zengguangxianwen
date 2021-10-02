# 增广贤文
增广贤文



## 制作epub

```
pandoc -o main.epub main.tex --metadata-file=epub.yaml
```

## 制作html

```
pandoc --toc -s -o main.html main.tex --metadata-file=epub.yaml
```

