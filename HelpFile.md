# 1. Run Laravel Project
> php artisan serve <br>
> http://127.0.0.1:8000

# 2. Run Web Socket
> php artisan websockets:serve <br>
> http://127.0.0.1:8000/laravel-websockets

# 3. Run Node
> npm run dev

# 4. Create Event 
> php artisan make:event MessageSent

# 5. Call Events using tinker

Write This code : 
  > php artisan tinker <br>
  > event(new App\Events\MessageSent("Hello World"))  

