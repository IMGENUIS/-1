pattern = "*+*+"  # 定義要重複的組合

for _ in range(10):  # 用字串乘法重複構建花紋，共十行

    print(pattern * 5)  # 在每一行中重複五次 "*+*+" 
    
    print()  # 每行中間插入一行空白
    
