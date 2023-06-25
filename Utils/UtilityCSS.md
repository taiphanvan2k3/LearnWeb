# 1. Cách tạo dấu 3 chấm khi nội dung dài
```
p:last-of-type {
    background-color: orange;
    display: -webkit-box;
    -webkit-line-clamp: 3;
    -webkit-box-orient: vertical;
    overflow: hidden;
}
```

# 2. Tối ưu hiển thị font chữ:
- Tối ưu việc không hiển thị răng cưa:
```
body {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
```