# bsit_2d_emerson_mijares_3
def countTarget(arr, target):     if len(arr) == 0:         return 0      if arr[0] == target:         return 1 + countTarget(arr[1:], target)     else:         return countTarget(arr[1:], target)   numbers = [2, 77, 3, 5, 8, 5, 6] target = 10  print(countTarget(numbers, target))
