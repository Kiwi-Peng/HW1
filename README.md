# HW1
def fibonacci_recursive(n):
    """
    使用遞迴計算費氏數列的第 n 項。
    """
    if n <= 1:
        return n
    else:
        return fibonacci_recursive(n-1) + fibonacci_recursive(n-2)

# 範例：計算費氏數列的第 10 項
num = 10
print(f"費氏數列的第 {num} 項是: {fibonacci_recursive(num)}")
# 輸出: 費氏數列的第 10 項是: 55
