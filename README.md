#  Мій перший проєкт на Git
## Структуру мого проєкту:

**main**
- README.md
- collab.txt
- readme.txt


**fix-issue-1**
- **my-first-repo-Vivtyk**
  - ...
    
  - **feature-add-zhyrnov**
  - readme.txt
  - students.txt
- .Rhistory
- collab.txt
- readme.txt

[Мій профіль GitHub](https://github.com/Kostya921)

## Приклад коду:
```
python
  with open("numbers.txt", "r", encoding="utf-8") as file:
    s = 0
    file_length = 0

    for line in file:

        file_length += 1

    #print(file_length)

    file.seek(0)   # - перемістити курсор на початок файлу

    for i in range(file_length):
        input_numbers = [file.readline()]
        input_numbers[0] = input_numbers[0].replace("\n", "")
        s += int(input_numbers[0])
        #print(input_numbers, s)

print(f"Сума чисел: {s}")
```
