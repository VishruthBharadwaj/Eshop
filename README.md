# Ecommerce_Django_Vishruth_Eshop

I have named my application as Store and Project name is Eshop.

I have created model for 

 1)Category- Name of the category we can add in DB by admin which will be displayed in home page.
 
 2)Customer- Customer details who will signup to buy products will be stored in DB .
 
 3)Order - Order Details of Particular Product with customer name,quantity,price,date ordered online with his address and phone no.
 If Nurcery owner accept the order then need to tick mark completed and save it.Then Status of order will be as completed in Customer profile.
 
 4)Product-Product Details.


 In Home of Admin panel where we have Authentication and Authorization where we have Users(It is Nurcery owner details).
 
 Need to migrate first before using code.
 
 python manage.py makemigrations
 
 python manage.py migrate
 
 For admin create superuser:
 
 python manage.py createsuperuser
 
 When user orders for data it should be accepted by admin then once admin accepts the order then status will change from pending to completed for user.
