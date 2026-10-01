<div align="center">

# Marc-Onel Volcimus

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&pause=1200&color=3B82F6&center=true&vCenter=true&width=520&lines=D%C3%A9veloppeur+full+stack+freelance;Software+%26+Cybersecurity;Graduate+%C2%B7+Computer+Science;Un+support+qui+parle+tout+seul.)](https://marco-ops-code.github.io/)

**Sites vitrines · Landing pages · Applications mobiles · Présentations PowerPoint**

[![Portfolio](https://img.shields.io/badge/Portfolio-3B82F6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://marco-ops-code.github.io/)
[![Landing page](https://img.shields.io/badge/Landing_page-080D1A?style=for-the-badge&logo=githubpages&logoColor=3B82F6)](https://marco-ops-code.github.io/landingPageMarc/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/marc.mus.ing)
[![Réserver 30 min](https://img.shields.io/badge/R%C3%A9server_30_min-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://marco-ops-code.github.io/#contact)

</div>

---

## 👨‍💻 À propos

Diplômé en informatique, je construis des produits numériques propres et rapides, et je me forme en cybersécurité.
J'aide les indépendants et les TPE à paraître plus crédibles dès la première visite.

- 🌍 Je travaille à distance, en **français** et en **anglais**
- ⚡ Réponse sous 24 h · devis sous 48 h
- 🎁 Consultation de 30 minutes offerte
- 🔐 En ce moment : cybersécurité, Security Operations, réseaux, génie logiciel

## 🧰 Ce que je propose

| Format | Pour quoi faire |
|---|---|
| 🌐 **Site vitrine** | Présenter ton activité avec des pages claires, rapides et bien référencées |
| 🎯 **Landing page** | Une page unique, centrée sur la conversion |
| 📱 **Application mobile** | Un outil sur téléphone en C# / .NET, pensé pour un usage réel |
| 📊 **Présentation PowerPoint** | Pitch, cours ou rapport : clair, visuel, prêt à présenter |

👉 [Demander un devis](https://marco-ops-code.github.io/#contact)

## 🚀 Projets

| Projet | Description | Liens |
|---|---|---|
| **LK Studio** | Site vitrine de salon : services, galerie, avis, réservation en quelques secondes | [Site](https://marco-ops-code.github.io/studio-lk/) · [Code](https://github.com/Marco-ops-code/studio-lk) |
| **Matrix Generator** | Application C# / .NET qui génère des devoirs individuels (matrices, systèmes d'équations linéaires) | [Code](https://github.com/Marco-ops-code/TaskGenerator) |
| **TaskEngine** | Écosystème pour générer, organiser et gérer des tâches académiques | [Code](https://github.com/Marco-ops-code/GeneratorMultiTask) |
| **Portfolio** | Sites, applications, présentations et études de cas | [Ouvrir](https://marco-ops-code.github.io/) |

## 🛠️ Stack

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white)

## 📊 Stats GitHub

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Marco-ops-code&show_icons=true&hide_border=true&bg_color=080D1A&title_color=3B82F6&text_color=cbd5e1&icon_color=3B82F6" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Marco-ops-code&layout=compact&hide_border=true&bg_color=080D1A&title_color=3B82F6&text_color=cbd5e1" />
</p>

---

## 📚 Exercices Python (Задачи)

<details>
<summary><b>Ouvrir mes exercices (4.43 → 10.43)</b></summary>

<br>

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
<summary><b>Задача 8.24 — Meilleur groupe par moyenne</b></summary>

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

</details>

---

<div align="center">

**Software · Cybersecurity · Lifestyle**

*Always learning. Never finished.*

</div>
