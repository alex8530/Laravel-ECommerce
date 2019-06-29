

![Laravel Ecommerce Iyzico](https://anilozmen.github.io/laravel-ecommerce-iyzico.gif)

#### Framework Used: Laravel 5.6


### Installation
1. Clone the repo and `cd` into it.
2. Open the terminal and write this command `composer install`
3. Rename or copy `.env.example` file to `.env` and write required database information.
4. Run `php artisan key:generate` command.
5. With `php artisan migrate` command, create the tables.
6. `php artisan db:seed` method to run other seed classes.

### Iyzico Settings
1. Enter your `setApiKey(), setSecretKey(), setBaseUrl()` information in `App/Services/PaymentService` . 

### Features

- Multiple Product Images
- Unlimited Categories
- Unlimited Products
- Virtual POS ( [IYZICO](https://www.iyzico.com/) )
- Shopping Cart
- Dynamic Breadcrumbs
- Add any item to the cart + AJAX
- Ability to checkout the pay
- Membership is required to make a payment
- Being able to see your orders
- Editing profile information etc. (address, telephone)
- Responsivity


## Demo
- **[http://ecommerce.anilozmen.com.tr](http://ecommerce.anilozmen.com.tr/)**
-  Admin: [admin@admin.com] / admin
- User: [user@user.com] / user 

## Packages Used

1. [cviebrock/eloquent-sluggable](https://github.com/cviebrock/eloquent-sluggable)
2. [gloudemans/shoppingcart](https://github.com/Crinsane/LaravelShoppingcart)
3. [intervention/image](https://github.com/Intervention/image)
4. [iyzico/iyzipay-php](https://github.com/iyzico/iyzipay-php)
5. [laravelcollective/html](https://github.com/LaravelCollective/html)

## Template 
[COLOSHOP](https://colorlib.com/etc/coloshop/index.html#)
