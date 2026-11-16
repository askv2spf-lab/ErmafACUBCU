# GP 70 / GP 95 ACU BCU PWA

## GitHub Pages
1. Створіть новий репозиторій GitHub.
2. Завантажте **вміст** цієї папки в корінь репозиторію.
3. Відкрийте **Settings → Pages**.
4. У **Build and deployment** виберіть **Deploy from a branch**, гілку `main`, папку `/(root)`.
5. Відкрийте опубліковану HTTPS-адресу та у браузері виберіть **Встановити застосунок**.

## Офлайн
Після першого відкриття через GitHub Pages service worker кешує `index.html`, маніфест та іконку. Для оновлення кешу змініть значення `CACHE` у `service-worker.js`.

> Відкриття `index.html` напряму через `file://` працює як HTML, але встановлення PWA та service worker потребують HTTPS або localhost.
