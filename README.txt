# 🚗 Car Rental Manager — GitHub Actions Auto Builder

## 📦 Описание
Этот проект автоматически собирает .exe и Windows-инсталлятор с помощью GitHub Actions.

---

## ⚙️ Как использовать

### 1. Загрузите проект в свой GitHub-репозиторий
- Создайте новый репозиторий.
- Загрузите все файлы из этого архива (включая `.github/workflows`).

### 2. Перейдите на вкладку **Actions**
- Вы увидите workflow: **Build Windows Installer**
- Нажмите **Run workflow**

### 3. После завершения
- Перейдите в страницу сборки.
- Внизу появится раздел **Artifacts**.
- Скачайте `CarRentalManager_Build.zip` — внутри будет:
  - `app.exe`
  - `CarRentalManager_Installer.exe`

---

## 💡 Требования
- GitHub Repository с включёнными Actions.
- Workflow создаёт `.exe` и `.exe` инсталлятор автоматически.

✅ После загрузки ничего дополнительно делать не нужно.
