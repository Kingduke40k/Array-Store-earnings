total = 0
i = 0
weekDays = [""] * (7)
dailySalesValue = [0] * (7)

while i < 7:
    print("Please enter a weekday: ")
    weekDays[i] = input()
    print("Please enter a total sales value for the weekday posted above: ")
    dailySalesValue[i] = float(input())
    i = i + 1
while i <= 7:
    print(weekDays[i])
    print(dailySalesValue)
    i = i - 1
