# Haker Warehouse

## A web Application that you can control your invintory on it, you can add product or remove product and add categories or remove it you can see your history or your dashboard.

<img width="1556" height="748" alt="image" src="https://github.com/user-attachments/assets/7fe43bec-5ee4-4874-8929-ad685885ce3c" />
<img width="1600" height="896" alt="image" src="https://github.com/user-attachments/assets/21ed86cb-2a06-4f3a-8c87-8309a8cc5bfa" />
<img width="1551" height="744" alt="image" src="https://github.com/user-attachments/assets/bb818a36-f14b-492f-806e-8f8f16b679e6" />




### Tech Stack

- **Backend:** Python, Django, Django REST Framework
- **Database:** PostgreSQL
- **Frontend:** Vanilla JavaScript, Tailwind CSS, HTML5
- **Auth:** Django Sessions & JWT

## How to Use

1. **Log in or Register:** Create an account or sign in with your credentials.
2. **Browse Inventory:** Click through categories and subcategories.
3. **Add Items:** create a new Category, Product, or receive Stock.
4. **Withdraw Stock:** Open any product, use the **+ / -** counters on its variants.
5. **View History:** Click **History** in the navigation bar to review stock movements, undo mistakes, or export records to CSV.

#### There is no real Login system yet :D -anyone can create an account that can access the main DB- 

## The team

- Timo : Did the DataBase structure and the BackEnd, Also did the new UI/UX.
- Mohammed : Asisted ALOT in both the Front&Back ends, Also configured the API endpoints.
- Baraa : Did the old Frontend structure.

## our server 🙂

### You can test the latest version on our UNIQUE domain <a href="https://hackerwarehouse.shop">hackerwarehouse.shop</a> (which we bougth with our pocket money at 2AM,LOL!!) !!!

### To test the back end please visit hackerwarehouse.shop/admin/ with the same login crednitials to test the back end

### to run the server run "python manage.py runserver"

### to run the tailwind css while devlopment run

````npx @tailwindcss/cli \
  -i ./static/css/input.css \
  -o ./static/css/output.css \
  --watch ```
````
