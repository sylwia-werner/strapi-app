# 🚀 Strapi Shop - Sylwia 54162

Projekt opiera się na Strapi, posiada REST API do zarządzania sklepem z akcesoriami.

## Content Types

Projekt zawiera w sobie **Collection Types** takie jak:
### Product

- title (text)
- description (text)
- price (number)
- in_stock (boolean)
- gender (enumeration - men, women, unisex)
- discounts (relacja n-n z promocjami)
- reviews (relacja 1-n z opiniami)
- slug (uuid)
- product_images (media)
- category (relacja n-1 z kategoriami)

![image](https://github.com/sylwia-werner/strapi-app/assets/97024171/4bfccaae-4ca3-4037-a3d3-d0593b5d66bb)

---

### Carousel

- title (text)
- description (text) 
- products (relacja 1-n z produktami)

![image](https://github.com/sylwia-werner/strapi-app/assets/97024171/8687cad9-a1bc-43ea-9069-b55ea085694b)

---

### Category

- name (text)
- products (relacja 1-n z produktami)

![image](https://github.com/sylwia-werner/strapi-app/assets/97024171/f3fbbc47-b312-4178-92ea-5a648efaacd8)

---

### Discount

- code (text)
- amount_percentage (number)
- products (relacja n-n z produktami)
- expiration_date (datetime)
- description (text)

![image](https://github.com/sylwia-werner/strapi-app/assets/97024171/efd952a0-fbad-4e57-a531-c8c02ac91119)

---

### Review

- rating (number)
- comment (text)
- product (relacja n-1 z produktami)
- user (relacja n-1 z użytkownikami)

![image](https://github.com/sylwia-werner/strapi-app/assets/97024171/b9b5caae-b84f-463c-a951-1670c87d6b4c)

---

### User

- domyślne pola Strapi
- reviews (relacja 1-n z opiniami)

---

Projekt zawiera także **Single Types**:

### Hero Banner

- title (text)
- text (text)
- pinned_products (relacja 1-n z produktami)

![image](https://github.com/sylwia-werner/strapi-app/assets/97024171/ca3aba8a-ebc1-4c33-84b4-44a029f57763)



