
    list =[]
    input_lines = int(input())
    for i in range(input_lines):
        judge = input()
        list.append(judge)
        list.count("strike")
        if list.count("strike") == 3:
            print("out!")
            break
        elif list.count("ball") == 4:
            print("fourball!")
            break
        else:
            print(judge + "!")
## 参考

https://hibiki-press.tech/learn_prog/python/count/103
