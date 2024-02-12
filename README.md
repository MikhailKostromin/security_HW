Базовое задание:
Внимание ДЗ выполнять в версии SpringBoot:2.7.14(модули security и web)
Вам необходимо создать Spring Boot приложение, которое управляет доступом к ресурсам в зависимости от роли пользователя. У вас должно быть два типа пользователей: USER и ADMIN.
1. Создайте ресурс /private-data, доступный только для аутентифицированных пользователей с ролью ADMIN.
2. Создайте ресурс /public-data, доступный для всех аутентифицированных пользователей независимо от их роли.
3. Реализуйте форму входа для аутентификации пользователей с использованием стандартных средств Spring Security.
4. Если неаутентифицированный пользователь пытается получить доступ к /private-data, он должен быть перенаправлен на форму входа.
_
ФОТО проекта
<img width="1280" alt="Снимок экрана 2024-02-12 в 23 55 46" src="https://github.com/MikhailKostromin/security_HW/assets/110930748/75a12b52-b440-43f1-adaf-1f6875ca5d3b">

<img width="1280" alt="Снимок экрана 2024-02-12 в 23 55 51" src="https://github.com/MikhailKostromin/security_HW/assets/110930748/0d9648b8-badf-4452-9f24-de18a6123f32">

<img width="1280" alt="Снимок экрана 2024-02-12 в 23 56 12" src="https://github.com/MikhailKostromin/security_HW/assets/110930748/ddcbd083-d64b-44ee-8699-726dad54245f">

<img width="1280" alt="Снимок экрана 2024-02-12 в 23 56 18" src="https://github.com/MikhailKostromin/security_HW/assets/110930748/4b6c0780-20cd-4ffe-bf36-a8b108e0ae81">

<img width="1280" alt="Снимок экрана 2024-02-12 в 23 59 04" src="https://github.com/MikhailKostromin/security_HW/assets/110930748/ff2afa3f-363d-43ea-860a-dabf4018b288">

<img width="1280" alt="Снимок экрана 2024-02-13 в 00 03 08" src="https://github.com/MikhailKostromin/security_HW/assets/110930748/520ae64d-ec12-40c8-99c1-205e21630240">

