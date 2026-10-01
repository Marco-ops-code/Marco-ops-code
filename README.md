<div align="center">

# 👋 Salut, je suis Marcopolo-#Joker

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F7A440&center=true&vCenter=true&width=435&lines=I'll+b+more+better;Python+%7C+Algorithmique;Un+exercice+apr%C3%A8s+l'autre+%F0%9F%9A%80)](https://git.io/typing-svg)

![Profile views](https://komarev.com/ghpvc/?username=Marco-ops-code&color=f7a440&style=flat-square)

</div>

---

## 🧑‍💻 À propos

- 🌱 J'apprends Python en résolvant des exercices d'algorithmique (Задачи)
- 🎯 Objectif : progresser un peu chaque jour
- 🌐 Mon portfolio : [marco-ops-code.github.io](https://marco-ops-code.github.io)
- 📫 Me contacter : via mon portfolio

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

## 📊 Stats GitHub

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Marco-ops-code&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Marco-ops-code&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

## 📚 Mes exercices

> Clique sur un exercice pour afficher le code.

### 🔢 Bases : conditions et calculs

<details>
<summary><b>Задача 4.43 — Un nombre est-il diviseur de l'autre ?</b></summary>

```python
def is_divisor(a, b):
    return a != 0 and b % a == 0


def main():
    try:
        a = int(input("Введите первое число (a): "))
        b = int(input("Введите второе число (b): "))

        if is_divisor(a, b) or is_divisor(b, a):
            print("Да, одно из чисел является делителем другого.")
        else:
            print("Нет, ни одно из чисел не является делителем другого.")
    except ValueError:
        print("Пожалуйста, введите целые числа.")


if __name__ == "__main__":
    main()
```

</details>

<details>
<summary><b>Задача 4.74 — Valeur absolue</b></summary>

```python
number = float(input("Введите вещественное число: "))
absolute_value = (number ** 2) ** 0.5
print("Абсолютная величина числа:", absolute_value)
```

</details>

<details>
<summary><b>Задача 5.43 — Somme des salaires</b></summary>

```python
salaries = [30000, 45000, 25000, 50000, 32000]
total_salary = sum(salaries)
print("Общая сумма выплаченных по ведомости денег:", total_salary)
```

</details>

<details>
<summary><b>Задача 5.74 — Volume total des sphères</b></summary>

```python
import math


def calculate_total_volume():
    total_volume = 0
    initial_radius = 0.05  # Внутренний радиус самого маленького шара в метрах
    thickness = 0.005      # Толщина стенки в метрах

    for i in range(12):
        inner_radius = initial_radius + i * thickness
        outer_radius = inner_radius + thickness

        outer_volume = (4 / 3) * math.pi * (outer_radius ** 3)
        inner_volume = (4 / 3) * math.pi * (inner_radius ** 3)
        shell_volume = outer_volume - inner_volume

        total_volume += shell_volume

    return total_volume * 1000  # m³ -> litres


total_volume_liters = calculate_total_volume()
print("Суммарный объем всех шаров:", total_volume_liters, "литров")
```

</details>

### 📈 Séquences et listes

<details>
<summary><b>Задача 6.43 — Nombres consécutifs égaux et nombres distincts</b></summary>

```python
sequence = [1.0, 2.0, 2.0, 3.0, 3.0, 3.0, 4.0, 5.0, 5.0, 6.0, 6.0, 7.0, 1000.0]


def process_sequence(sequence):
    if sequence[-1] == 1000.0:
        sequence = sequence[:-1]

    if not sequence:
        return 0, 0

    previous_number = sequence[0]
    current_count = 1
    total_equal_count = 0
    unique_numbers = {previous_number}

    for number in sequence[1:]:
        if number == previous_number:
            current_count += 1
        else:
            if current_count > 1:
                total_equal_count += current_count
            current_count = 1
            previous_number = number
            unique_numbers.add(number)

    if current_count > 1:
        total_equal_count += current_count

    return total_equal_count, len(unique_numbers)


total_equal_count, unique_count = process_sequence(sequence)
print("Количество чисел, идущих подряд и равных между собой:", total_equal_count)
print("Количество различных чисел в последовательности:", unique_count)
```

</details>

<details>
<summary><b>Задача 6.74 — Tous les éléments sont-ils égaux ?</b></summary>

```python
sequence = [3, 3, 3, 3, 3, -1]


def check_if_all_elements_equal(sequence):
    if sequence[-1] < 0:
        sequence = sequence[:-1]

    if not sequence:
        return True

    first_element = sequence[0]
    for number in sequence:
        if number != first_element:
            return False
    return True


result = check_if_all_elements_equal(sequence)
if result:
    print("Все элементы последовательности равны между собой.")
else:
    print("Не все элементы последовательности равны между собой.")
```

</details>

### 🔁 Boucles et moyennes

<details>
<summary><b>Задача 8.43 — Somme 1¹ + 2² + … + nⁿ</b></summary>

```python
def compute_sum(n):
    total_sum = 0
    for i in range(1, n + 1):
        total_sum += i ** i
    return total_sum


# Пример использования:
n = 5
result = compute_sum(n)
print(f"Сумма 1^1 + 2^2 + ... + {n}^{n} равна {result}")
```

</details>

<details>
<summary><b>Задача 8.24 — Meilleure groupe par moyenne</b></summary>

```python
def average_score(group_scores):
    return sum(group_scores) / len(group_scores)


group1_scores = [
    [75, 85, 90], [80, 70, 90], [60, 70, 80], [90, 85, 75], [100, 95, 90],
    [85, 80, 70], [75, 70, 85], [80, 85, 90], [70, 65, 75], [60, 75, 80],
    [90, 85, 80], [70, 75, 70], [85, 90, 85], [80, 70, 75], [95, 90, 85],
    [85, 80, 90], [75, 80, 85], [65, 70, 75], [95, 90, 85], [85, 90, 95]
]
group2_scores = [
    [80, 70, 60], [85, 75, 80], [90, 85, 95], [70, 65, 75], [75, 80, 85],
    [85, 90, 95], [60, 70, 75], [80, 85, 90], [70, 75, 80], [65, 70, 75],
    [85, 90, 80], [75, 80, 70], [90, 85, 80], [70, 75, 85], [85, 80, 90],
    [90, 85, 80], [75, 80, 85], [85, 90, 95], [70, 75, 80], [80, 85, 90]
]
group3_scores = [
    [75, 85, 95], [80, 90, 100], [70, 80, 90], [60, 70, 80], [95, 90, 85],
    [85, 80, 75], [75, 70, 65], [80, 85, 90], [70, 75, 80], [60, 65, 70],
    [90, 95, 85], [85, 90, 80], [75, 80, 85], [65, 70, 75], [80, 85, 90],
    [85, 90, 95], [70, 75, 80], [75, 80, 85], [80, 85, 90], [85, 90, 95]
]

group1_average = average_score([sum(s) / len(s) for s in group1_scores])
group2_average = average_score([sum(s) / len(s) for s in group2_scores])
group3_average = average_score([sum(s) / len(s) for s in group3_scores])

print(f"Средний балл группы 1: {group1_average:.2f}")
print(f"Средний балл группы 2: {group2_average:.2f}")
print(f"Средний балл группы 3: {group3_average:.2f}")

if group1_average > group2_average and group1_average > group3_average:
    print("Лучшая группа по среднему баллу: Группа 1")
elif group2_average > group1_average and group2_average > group3_average:
    print("Лучшая группа по среднему баллу: Группа 2")
else:
    print("Лучшая группа по среднему баллу: Группа 3")
```

</details>

### 🔤 Chaînes de caractères

<details>
<summary><b>Задача 9.43 — Caractères aux positions impaires</b></summary>

```python
def get_odd_characters(s1):
    s2 = ""
    for i in range(len(s1)):
        if i % 2 == 0:
            s2 += s1[i]
    return s2


s1 = "программирование"
s2 = get_odd_characters(s1)
print(s2)
```

</details>

<details>
<summary><b>Задача 9.74 — Cinq caractères identiques d'affilée</b></summary>

```python
def has_five_consecutive_same_chars(text):
    for i in range(len(text) - 4):
        if text[i] == text[i + 1] == text[i + 2] == text[i + 3] == text[i + 4]:
            return True
    return False


text = "abcdeeeeeefgh"
result = has_five_consecutive_same_chars(text)
if result:
    print("В тексте есть пять идущих подряд одинаковых символов.")
else:
    print("В тексте нет пяти идущих подряд одинаковых символов.")
```

</details>

### 🧮 Fonctions et récursivité

<details>
<summary><b>Задача 10.24 — PGCD et PPCM</b></summary>

```python
def find_gcd(a, b):
    while b:
        a, b = b, a % b
    return a


def find_lcm(a, b):
    return abs(a * b) // find_gcd(a, b)


a = 24
b = 36

gcd = find_gcd(a, b)
lcm = find_lcm(a, b)

print(f"Наибольший общий делитель чисел {a} и {b} равен {gcd}")
print(f"Наименьшее общее кратное чисел {a} и {b} равно {lcm}")
```

</details>

<details>
<summary><b>Задача 10.43 — Somme des chiffres (récursion)</b></summary>

```python
def sum_of_digits(n):
    if n < 10:
        return n
    return n % 10 + sum_of_digits(n // 10)


number = 12345
result = sum_of_digits(number)
print(f"Сумма цифр числа {number} равна {result}")
```

</details>

---

<div align="center">

⭐ *« I'll b more better »* ⭐

</div>
