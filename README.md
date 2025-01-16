# Список оценок
grades = [5, 4, 3, 5, 4, 5, 3, 2]

# Вычисление средней оценки
average_grade = sum(grades) / len(grades)

# Классификация
if average_grade >= 4.5:
    classification = "Отличник"
elif average_grade >= 3.5:
    classification = "Хорошист"
else:
    classification = "Учащийся"

# Вывод результатов
print(f"Средняя оценка: {average_grade:.2f}")
print(f"Классификация: {classification}")
