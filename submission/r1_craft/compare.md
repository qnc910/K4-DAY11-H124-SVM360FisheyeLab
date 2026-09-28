# So sánh L với R

Chỉ số L/R là thứ tự box cao ≥ H=40 trong từng frame, theo thứ tự XML; bắt đầu từ 1.
Box L trong ignore_region được báo IGNORE_SCOPE, không tính SPURIOUS.

## adasind_152940.jpg
- R6 mid MISSING
## adasind_167700.jpg
- L5 mid IGNORE_SCOPE
- L7+R4 center WRONG_CLASS
## adasind_212280.jpg
- L2 mid IGNORE_SCOPE

## Theo zone
| zone | n_ref | matched | missing | spurious |
|---|---|---|---|---|
| center | 10 | 9 | 1 | 1 |
| mid | 6 | 5 | 1 | 0 |
| edge | 2 | 2 | 0 | 0 |
