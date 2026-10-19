# 課題0304 提出用ファイル

## ソースコード

```c
#include <stdio.h>
int main(void)
{
    /* 課題0304: 入力されたintのデータを16進数として表示するプログラムを書け． */
    int i;
    scanf("%d", &i);
    printf("%x\n", i);
    return 0;
}
```

## 実行確認

入力: `11`
出力: `b`

```bash
gcc main.c -o main && printf '11\n' | ./main
```

結果:

```text
b
```
