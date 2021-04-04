# Routing

```php
  Route::get('/user', [UserController::class, 'index']);
  Route::post('/user', [UserController::class, 'index']);
  Route::put('/user', [UserController::class, 'index']);
  Route::patch('/user', [UserController::class, 'index']);
  Route::delete('/user', [UserController::class, 'index']);

  Route::resource('user', UserController::class);
```

# DI

# Database

# Testing
