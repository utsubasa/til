# 数列中で偶数番目だけ足し上げる
    number = input()
    a= len(number) 
    print(a)　//数列の桁を確認
    even = 0
    for b in range(a):
        if b % 2 != 0:
        　　even += int(number[b])
        　　print(even)
# リストは通常文字列型になっている         
