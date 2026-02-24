# 🎓 Python Engineering Course (MIT-level)

**Курс "Python для системных инженеров"** — 6 месяцев углублённого изучения Python для студентов 2-го курса, знающих C++.

---

## 📚 Структура курса

### 🔬 Блок 1: Системный Python (месяцы 1-2)
**Цель:** Понять CPython изнутри — интерпретатор, память, GIL, C-расширения

- **Лекция 01:** CPython internals (байт-код, AST)
- **Лекция 02:** Модель памяти (refcounting vs GC vs C++ RAII)
- **Лекция 03:** GIL и параллелизм
- **Лекция 04:** Pythonic структуры данных vs STL
- **Лекция 05:** ООП (metaclasses, descriptors)
- **Лекция 06:** Функции (декораторы, closures)
- **Лекция 07:** Исключения и контекстные менеджеры
- **Лекция 08:** C-расширения (Cython, pybind11)

### 🧮 Блок 2: Численные методы (месяцы 3-4)
**Цель:** Научиться решать математические задачи на Python

- **Лекция 09:** NumPy internals (C-backend)
- **Лекция 10:** Линейная алгебра (SVD, LU, QR)
- **Лекция 11:** Решение СЛАУ
- **Лекция 12:** Интерполяция и аппроксимация
- **Лекция 13:** Численное интегрирование и ОДУ
- **Лекция 14:** Градиентный спуск from scratch
- **Лекция 15:** SciPy экосистема
- **Лекция 16:** Профилирование и оптимизация

### 🤖 Блок 3: ML фреймворки (месяцы 5-6)
**Цель:** Production ML с PyTorch/TensorFlow + C++ inference

- **Лекция 17:** PyTorch (autograd, тензоры)
- **Лекция 18:** TensorFlow/Keras + XLA
- **Лекция 19:** Нейросети from scratch
- **Лекция 20:** CNN/RNN архитектуры
- **Лекция 21:** ONNX + C++ inference
- **Лекция 22:** MLflow production pipelines
- **Лекция 23:** Docker deployment
- **Лекция 24:** Capstone project

---

## 📁 Навигация по репозиторию

```
pythonlearn/
├── 01_python_core/          # Блок 1: Системный Python
│   ├── lectures/            # 8 лекций (Jupyter notebooks)
│   ├── seminars/            # 8 семинаров (практика)
│   └── homework/            # 8 домашних заданий
├── 02_numerical_methods/    # Блок 2: Численные методы
│   ├── lectures/
│   ├── seminars/
│   └── homework/
├── 03_ml_frameworks/        # Блок 3: ML фреймворки
│   ├── lectures/
│   ├── seminars/
│   └── homework/
├── students/                # Решения студентов
│   └── {student_name}/
├── resources/               # Датасеты, бенчмарки
├── COURSE_OUTLINE.md        # Полная программа 24 недель
├── SYSTEM_PROMPT.md         # Промт для LLM-преподавателя
└── README.md
```

---

## 🚀 Как использовать этот курс

1. **Клонируй репозиторий:**
   ```bash
   git clone https://github.com/sashaai2006/pythonlearn.git
   cd pythonlearn
   ```

2. **Создай виртуальное окружение:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/Mac
   ```

3. **Установи зависимости:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Запусти Jupyter:**
   ```bash
   jupyter notebook
   ```

5. **Начни с первой лекции:**
   - Открой `01_python_core/lectures/01_cpython_internals.ipynb`

---

## 🎯 Для кого этот курс

- ✅ Студенты 2-го курса, знающие C++
- ✅ Инженеры, переходящие с C++/Java на Python
- ✅ Те, кто хочет понять Python **под капотом**
- ❌ Не для новичков без опыта программирования

---

## 📖 Рекомендуемая литература

1. **"Fluent Python"** — Luciano Ramalho
2. **"CPython Internals"** — Anthony Shaw
3. **"High Performance Python"** — Micha Gorelick
4. **"Numerical Python"** — Robert Johansson
5. **"Deep Learning with PyTorch"** — Eli Stevens

---

## 🤝 Контрибьюция

Нашли ошибку? Есть идея для улучшения? Открывайте Issue или Pull Request!

---

## 📧 Контакты

**Репозиторий:** [github.com/sashaai2006/pythonlearn](https://github.com/sashaai2006/pythonlearn)

---

**Лицензия:** MIT © 2026