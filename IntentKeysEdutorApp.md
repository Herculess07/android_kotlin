# Intent Key-Value Documentation for Screen Navigation

This document outlines the required intent keys and values for navigating to different screens in
the app from Notifications Click. Some screens require a single key-value pair, while others need
multiple key-value pairs to be passed for proper navigation.

---

## 1. Special Exam

- **Description**: Opens the special exam subjects page.
- **Direct URL** : https://web.edutorapp.com/special_exam/{:id}

| **Key** |   **Value**    | **Description**                            |
|:-------:|:--------------:|:-------------------------------------------|
|  `key`  | `special_exam` | Fixed value to pass                        |
|  `id`   |      `1`       | 1 : NMMS <br/>2 : Gyan Sadhana<br/>3 : CET |

---

## 2. Gulab Selection

- **Description**: Opens the gulab selection page only for Teacher login.

| **Key** | **Value**      | **Description**     |
|---------|----------------|---------------------|
| `key`   | `create_gulab` | Fixed value to pass |

---

## 3. Payment History Page

- **Description**: Opens the Payment History only for Teacher login.

| **Key** | **Value**                                              | **Description**     |
|---------|--------------------------------------------------------|---------------------|
| `key`   | `pending_create_gulab` or <br/>`success_premium_gulab` | Fixed value to pass |

---

## 4. Open Particular Vishesh

- **Description**: Opens Any Vishesh.only from URL.
- **Direct URL** : https://web.edutorapp.com/vishesh/{:id}

| **Key** | **Value** |   **Description**   |
|:-------:|:---------:|:-------------------:|
|  `key`  | `vishesh` | Fixed value to pass |
|  `id`   |  `3433`   |   Pass Vishesh Id   |

---

## 5. Open View Vishesh Page

- **Description**: Opens the View Vishesh Page.
- **Direct URL** : https://web.edutorapp.com/view_vishesh

| **Key** |   **Value**    |   **Description**   |
|:-------:|:--------------:|:-------------------:|
|  `key`  | `view_vishesh` | Fixed value to pass |

---
