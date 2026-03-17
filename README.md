# 📝 Laboratory Activity 2: Laravel Routings, Controllers

## 🎯 Project Objectives
* Implement Laravel **Routes** to navigate between pages.
* Create **Controllers** to handle application logic and data passing.
* Build dynamic User Interfaces using **Blade Templates**.
* Collect, validate, and display user input using **Laravel Forms**.

---

## 🗺️ System File Location Map
This map highlights the essential files created for this registration system:

```text
student-registration/
├── app/
│   └── Http/
│       └── Controllers/
│           └── RegistrationController.php  <-- [Logic] Handles form display & validation
├── resources/
│   └── views/                              <-- [Views] All Blade templates
│       ├── home.blade.php                  <-- The Landing Page
│       ├── register.blade.php              <-- The Input Form (with validation)
│       └── success.blade.php               <-- The Output/Data Display Page
└── routes/
    └── web.php                             <-- [Routes] Defines GET and POST paths