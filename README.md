# laravelngphonepassword
Nigerian mobile carriers validation inputs for laravel developers.

# Install
After installing Laravel-ng-phone-password, Open up config/app.php and add this to providers key.

rapulu\laravelngphonepassword\PhoneNumberServiceProvider::class

Now all you have to do is to add phone to the pipe rules.

e.g ['phone' => 'required|phone']
