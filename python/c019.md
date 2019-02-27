
    def yakusuu():　＃約数を判定して和をつくる
        for i in range(1,line): ＃１からline（入力）まで繰り返す
            if line % i == 0:
                yakusuu_list.append(i)　＃割り切れる数をリストに加える
        yakusuu_str = list(map(int,yakusuu_list))　＃リストの中身をint化
        ans = sum(yakusuu_str)　＃約数の和をとる
        if ans == line:
            print("perfect")
        elif ans == abs(line -1):
            print("nearly")
        else:
            print("neither")
                       
    N =int(input())
    for i in range(N):
        yakusuu_list = []
        line= int(input())
        yakusuu() ＃入力された数値の約数の和の計算をN回繰り返す 
