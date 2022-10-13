# Upwork - Laravel Test Task
[![Build Status](https://shinedezign.com/img/logo.png)](https://shinedezign.com/)

## Test Task Points
__This code has several problems. You can show your experience by fixing them or explaining what would you do differently.__

__Route::get('buy/{cookies}', function ($cookies) {
    $wallet = Auth::user()->wallet;
    Auth::user()->update(['wallet' => $wallet - $cookies * 1]);
    Log:info('User ' . $user->email . ' have bought ' . $cookies . ' cookies'); // we need to log who ordered and how much
    return 'Success, you have bought ' . $cookies . ' cookies!';
});__
- Imagine that this is a code for a small shop where for every $1 you can buy 1 cookie.
- User can order some amount of cookies by entering in the browser: /buy/3 (to buy 3 cookies).
- Add "wallet" column to the "users" table and set the value to 10 ($10).
- Copy provided code to the web.php and fix it.

