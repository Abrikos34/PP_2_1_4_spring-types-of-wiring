# 🧙‍♂️ **Koschei The Deathless - Spring Dependency Injection Demo**

**Описание проекта:**  
Этот проект демонстрирует принципы внедрения зависимостей (**Dependency Injection**) в **Spring Framework** на примере сказочной истории о Кощее Бессмертном. В проекте используются различные способы связывания бинов, такие как:
- **Внедрение через сеттеры (@Autowired)**
- **Внедрение через конструктор (@Autowired)**
- **Внедрение через методы @Bean в конфигурационном классе**

---

## 📖 **Легенда:**
*"На свете есть океан, на океане остров, на острове дерево, на дереве заяц, в зайце утка, в утке яйцо, в яйце иголка, смерть Кощея на игле."*

Эта история реализована в виде цепочки бинов, связанных между собой с использованием Spring.

---

## 🚀 **Стек технологий:**
- **Java 17+**
- **Spring Framework (Core, Context)**
- **JUnit 5** (для тестирования)
- **Maven** (для сборки проекта)

---

## 🛠️ **Как запустить проект:**

1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/your-repo/koschei-deathless.git
   cd koschei-deathless

2. **Запустите приложение.**


3. **Запустите тесты.**


## 🔄 **Как это работает?**

1. KoscheiTheDeathless связан с Ocean1 через сеттер с @Autowired.
2. Ocean1 получает Island2 из метода @Bean в AppConfig.
3. Island2 получает зависимость Wood3 через конструктор.
4. Остальные зависимости передаются через @Autowired в полях или методах сеттера.
5. Итоговая строка собирается методом toString() в каждом из бинов.


## ✅ **Ожидаемый результат:**

После успешного запуска приложения или тестов, вы увидите в консоли:

На свете есть океан, на океане остров, на острове дерево, на дереве заяц, в зайце утка, в утке яйцо, в яйце иголка, смерть Кощея на игле :(
