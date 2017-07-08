# CH3

## 陣列處理
* pop, push
* shift, unshift
* splice

## Perl 最愛的預設變數: $_
> 省略foreach 控制變數時，Perl 會內定使用$_作為預設變數。
```perl
foreach (1..10)    # same as foreach $tmp (1..10)
{
    say $_;        # say $tmp;
}
```

## 實用運算符
* reverse
* sort
* each

```perl
# reverse
@arr = 6..10;
reverse @arr;
@arr = reverse @arr;  # assign value back

# sort 使用方法同上 
```
