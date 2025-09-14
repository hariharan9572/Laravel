# Laravel & PHP Essential Quiz for Freshers

*A comprehensive assessment covering core concepts necessary for junior Laravel developers*

**Total Questions: 100 | Time Limit: 3 hours | Passing Score: 70%**

---

## Section 1: PHP Fundamentals (Essential Core Concepts)

### Question 1: Running PHP Programs
How do you run a PHP script from the command line?

A) `php script.php`
B) `run script.php`
C) `execute script.php`
D) `./script.php`

**Answer: A) `php script.php`**

---

### Question 2: PHP Opening Tags
Which is the correct way to start a PHP code block?

A) `<php>`
B) `<?php`
C) `<script type="php">`
D) `<%php`

**Answer: B) `<?php`**

---

### Question 3: Variable Declaration
How do you declare a variable in PHP?

A) `var $name = "John";`
B) `$name = "John";`
C) `string $name = "John";`
D) `declare $name = "John";`

**Answer: B) `$name = "John";`**

---

### Question 4: PHP Data Types
Which of these is NOT a scalar data type in PHP?

A) `string`
B) `integer`
C) `array`
D) `boolean`

**Answer: C) `array` (it's a compound type)**

---

### Question 5: String Concatenation
How do you concatenate strings in PHP?

A) `$str1 + $str2`
B) `$str1 . $str2`
C) `$str1 & $str2`
D) `concat($str1, $str2)`

**Answer: B) `$str1 . $str2`**

---

### Question 6: Arrays
Which creates an indexed array in PHP?

A) `$arr = [1, 2, 3];`
B) `$arr = array(1, 2, 3);`
C) `$arr = ['a' => 1, 'b' => 2];`
D) Both A and B create indexed arrays

**Answer: D) Both A and B create indexed arrays**

---

### Question 7: Conditional Statements
Which is the correct syntax for an if statement in PHP?

A) `if $condition { ... }`
B) `if ($condition) { ... }`
C) `if condition: ... endif`
D) Both B and C are correct

**Answer: D) Both B and C are correct**

---

### Question 8: Function Definition
How do you define a function in PHP?

A) `function myFunction() { ... }`
B) `def myFunction() { ... }`
C) `func myFunction() { ... }`
D) `create function myFunction() { ... }`

**Answer: A) `function myFunction() { ... }`**

---

### Question 9: Class Definition
How do you define a class in PHP?

A) `class MyClass { ... }`
B) `define class MyClass { ... }`
C) `create class MyClass { ... }`
D) `new class MyClass { ... }`

**Answer: A) `class MyClass { ... }`**

---

### Question 10: Class Inheritance
How do you extend a class in PHP?

A) `class Child inherits Parent { ... }`
B) `class Child extends Parent { ... }`
C) `class Child from Parent { ... }`
D) `class Child: Parent { ... }`

**Answer: B) `class Child extends Parent { ... }`**

---

## Section 2: Laravel Fundamentals (Project #1 Essentials)

### Question 11: Laravel Framework
What is Laravel?

A) A PHP library
B) A PHP framework for web application development
C) A database management system
D) A web server

**Answer: B) A PHP framework for web application development**

---

### Question 12: MVC Architecture
What does MVC stand for in Laravel?

A) Model-View-Controller
B) Method-Variable-Class
C) Main-View-Component
D) Module-View-Configuration

**Answer: A) Model-View-Controller**

---

### Question 13: Artisan Commands
Which command creates a new Laravel project?

A) `php artisan new project-name`
B) `composer create-project laravel/laravel project-name`
C) `laravel new project-name`
D) Both B and C are correct

**Answer: D) Both B and C are correct**

---

### Question 14: Routing
How do you define a basic GET route in Laravel?

A) `Route::get('/path', function() { ... });`
B) `Route::path('/get', function() { ... });`
C) `Get::route('/path', function() { ... });`
D) `Laravel::get('/path', function() { ... });`

**Answer: A) `Route::get('/path', function() { ... });`**

---

### Question 15: Controllers
Which command creates a new controller?

A) `php artisan make:controller UserController`
B) `php artisan create:controller UserController`
C) `php artisan new:controller UserController`
D) `php artisan controller:make UserController`

**Answer: A) `php artisan make:controller UserController`**

---

### Question 16: Blade Templates
What is the file extension for Blade templates?

A) `.html`
B) `.php`
C) `.blade.php`
D) `.blade`

**Answer: C) `.blade.php`**

---

### Question 17: Blade Syntax
How do you echo a variable in Blade?

A) `<?php echo $variable; ?>`
B) `{{ $variable }}`
C) `{{{ $variable }}}`
D) `<%= $variable %>`

**Answer: B) `{{ $variable }}`**

---

### Question 18: Models
Which command creates a new Eloquent model?

A) `php artisan make:model User`
B) `php artisan create:model User`
C) `php artisan new:model User`
D) `php artisan model:make User`

**Answer: A) `php artisan make:model User`**

---

### Question 19: Migrations
What is the purpose of migrations in Laravel?

A) To move files between servers
B) Database version control and schema changes
C) To migrate from other frameworks
D) To backup databases

**Answer: B) Database version control and schema changes**

---

### Question 20: Environment Configuration
Where are Laravel environment variables stored?

A) `config/app.php`
B) `.env` file
C) `bootstrap/app.php`
D) `public/index.php`

**Answer: B) `.env` file**

---

## Section 3: Database & Eloquent (Project #2 Essentials)

### Question 21: Eloquent ORM
What is Eloquent in Laravel?

A) A template engine
B) Laravel's built-in Object-Relational Mapping (ORM)
C) A caching system
D) A routing system

**Answer: B) Laravel's built-in Object-Relational Mapping (ORM)**

---

### Question 22: Database Relationships
How do you define a one-to-many relationship in Eloquent?

A) `return $this->belongsTo(Model::class);`
B) `return $this->hasMany(Model::class);`
C) `return $this->hasOne(Model::class);`
D) `return $this->belongsToMany(Model::class);`

**Answer: B) `return $this->hasMany(Model::class);`**

---

### Question 23: Query Builder
How do you retrieve all records from a table using Eloquent?

A) `User::get()`
B) `User::all()`
C) `User::find()`
D) Both A and B work

**Answer: D) Both A and B work**

---

### Question 24: Mass Assignment
What is the purpose of `$fillable` in Eloquent models?

A) To fill the database with data
B) To specify which attributes can be mass assigned
C) To define validation rules
D) To set default values

**Answer: B) To specify which attributes can be mass assigned**

---

### Question 25: Database Seeding
Which command runs database seeders?

A) `php artisan db:seed`
B) `php artisan seed:run`
C) `php artisan run:seeders`
D) `php artisan migrate:seed`

**Answer: A) `php artisan db:seed`**

---

## Section 4: API Development (Project #3 Essentials)

### Question 26: API Routes
Where should API routes be defined in Laravel?

A) `routes/web.php`
B) `routes/api.php`
C) `routes/channels.php`
D) `routes/console.php`

**Answer: B) `routes/api.php`**

---

### Question 27: JSON Response
How do you return a JSON response in Laravel?

A) `return json_encode($data);`
B) `return response()->json($data);`
C) `return $data->toJson();`
D) `return Response::json($data);`

**Answer: B) `return response()->json($data);`**

---

### Question 28: API Resource Classes
What is the purpose of API Resource classes?

A) To define API routes
B) To transform models and collections for JSON responses
C) To validate API requests
D) To authenticate API users

**Answer: B) To transform models and collections for JSON responses**

---

### Question 29: Authentication
Which authentication guard is commonly used for APIs?

A) `web`
B) `api`
C) `sanctum`
D) Both B and C

**Answer: D) Both B and C**

---

### Question 30: HTTP Status Codes
What HTTP status code should be returned for a successful resource creation?

A) 200
B) 201
C) 204
D) 302

**Answer: B) 201**

---

## Section 5: Validation & Forms (Essential Concepts)

### Question 31: Form Validation
How do you validate request data in Laravel?

A) `$request->validate(['field' => 'required']);`
B) `$this->validate($request, ['field' => 'required']);`
C) Using Form Request classes
D) All of the above

**Answer: D) All of the above**

---

### Question 32: CSRF Protection
How do you include CSRF protection in forms?

A) `@csrf`
B) `{{ csrf_token() }}`
C) `<input type="hidden" name="_token" value="{{ csrf_token() }}">`
D) All methods work

**Answer: D) All methods work**

---

### Question 33: Form Methods
How do you specify a PUT method in an HTML form?

A) `<form method="PUT">`
B) `@method('PUT')`
C) `<input type="hidden" name="_method" value="PUT">`
D) Both B and C work

**Answer: D) Both B and C work**

---

## Section 6: File Handling (Project #5 Essentials)

### Question 34: File Uploads
How do you handle file uploads in Laravel?

A) `$request->file('upload')`
B) `$_FILES['upload']`
C) `Input::file('upload')`
D) `File::get('upload')`

**Answer: A) `$request->file('upload')`**

---

### Question 35: File Storage
Which method stores an uploaded file?

A) `$file->save()`
B) `$file->store('path')`
C) `$file->move('path')`
D) `$file->put('path')`

**Answer: B) `$file->store('path')`**

---

## Section 7: Security Basics

### Question 36: Password Hashing
How should passwords be hashed in Laravel?

A) `md5($password)`
B) `Hash::make($password)`
C) `bcrypt($password)`
D) Both B and C are correct

**Answer: D) Both B and C are correct**

---

### Question 37: SQL Injection Prevention
How does Laravel prevent SQL injection?

A) By using Eloquent ORM
B) By using Query Builder with parameter binding
C) By using prepared statements
D) All of the above

**Answer: D) All of the above**

---

## Section 8: Advanced Laravel Basics

### Question 38: Route Model Binding
What is Route Model Binding in Laravel?

A) Binding routes to specific models
B) Automatically injecting model instances based on route parameters
C) Creating relationships between routes
D) Caching route data

**Answer: B) Automatically injecting model instances based on route parameters**

---

### Question 39: Pagination
How do you implement pagination in Laravel?

A) `User::paginate(10)`
B) `User::limit(10)->get()`
C) `User::take(10)->get()`
D) `User::chunk(10)`

**Answer: A) `User::paginate(10)`**

---

### Question 40: Named Routes
What is the benefit of using named routes in Laravel?

A) Better performance
B) URL generation and redirects become easier
C) Automatic caching
D) Better SEO optimization

**Answer: B) URL generation and redirects become easier**

---

### Question 41: Route Parameters
How do you define an optional route parameter in Laravel?

A) `Route::get('/user/{id}', function ($id) {});`
B) `Route::get('/user/{id?}', function ($id = null) {});`
C) `Route::get('/user/[id]', function ($id) {});`
D) `Route::get('/user/{id:optional}', function ($id) {});`

**Answer: B) `Route::get('/user/{id?}', function ($id = null) {});`**

---

### Question 42: Blade Directives
Which Blade directive is used for conditional rendering?

A) `@when`
B) `@if`
C) `@show`
D) `@render`

**Answer: B) `@if`**

---

### Question 43: Blade Loops
How do you loop through an array in Blade?

A) `@for($i=0; $i<count($array); $i++)`
B) `@foreach($array as $item)`
C) `@while($condition)`
D) All of the above work

**Answer: D) All of the above work**

---

### Question 44: Session Management
How do you store data in a session?

A) `session(['key' => 'value'])`
B) `Session::put('key', 'value')`
C) `$request->session()->put('key', 'value')`
D) All methods work

**Answer: D) All methods work**

---

### Question 45: Flash Messages
What method is used to store data in session for only the next request?

A) `session()->flash('key', 'value')`
B) `session()->temporary('key', 'value')`
C) `session()->once('key', 'value')`
D) `session()->next('key', 'value')`

**Answer: A) `session()->flash('key', 'value')`**

---

## Section 9: Database Advanced Concepts

### Question 46: Database Factories
What is the purpose of model factories in Laravel?

A) To create database connections
B) To generate fake data for testing and seeding
C) To create new models
D) To manage database migrations

**Answer: B) To generate fake data for testing and seeding**

---

### Question 47: Eloquent Relationships - Belongs To
How do you define a belongs-to relationship?

A) `return $this->hasOne(Model::class);`
B) `return $this->belongsTo(Model::class);`
C) `return $this->hasMany(Model::class);`
D) `return $this->belongsToMany(Model::class);`

**Answer: B) `return $this->belongsTo(Model::class);`**

---

### Question 48: Eloquent Relationships - Many to Many
How do you define a many-to-many relationship?

A) `return $this->hasMany(Model::class);`
B) `return $this->belongsTo(Model::class);`
C) `return $this->belongsToMany(Model::class);`
D) `return $this->hasOne(Model::class);`

**Answer: C) `return $this->belongsToMany(Model::class);`**

---

### Question 49: Query Scopes
How do you define a local scope in Eloquent?

A) `public function scopeActive($query) { return $query->where('active', 1); }`
B) `public function active($query) { return $query->where('active', 1); }`
C) `public function scope_active($query) { return $query->where('active', 1); }`
D) `protected function scopeActive($query) { return $query->where('active', 1); }`

**Answer: A) `public function scopeActive($query) { return $query->where('active', 1); }`**

---

### Question 50: Soft Deletes
How do you enable soft deletes on a model?

A) Add `use SoftDeletes;` trait to the model
B) Add `'deleted_at'` to `$dates` array
C) Add `deleted_at` timestamp column to migration
D) All of the above

**Answer: D) All of the above**

---

## Section 10: Advanced API Development

### Question 51: API Authentication with Sanctum
How do you protect API routes with Sanctum?

A) `Route::middleware('auth:sanctum')->group(function() {...});`
B) `Route::middleware('sanctum')->group(function() {...});`
C) `Route::auth('sanctum')->group(function() {...});`
D) `Route::protect('sanctum')->group(function() {...});`

**Answer: A) `Route::middleware('auth:sanctum')->group(function() {...});`**

---

### Question 52: API Rate Limiting
How do you apply rate limiting to API routes?

A) `Route::middleware('throttle:60,1')->group(function() {...});`
B) `Route::middleware('ratelimit:60')->group(function() {...});`
C) `Route::limit(60)->group(function() {...});`
D) `Route::throttle(60)->group(function() {...});`

**Answer: A) `Route::middleware('throttle:60,1')->group(function() {...});`**

---

### Question 53: Resource Controllers
Which command creates a resource controller?

A) `php artisan make:controller PostController --resource`
B) `php artisan make:resource PostController`
C) `php artisan create:controller PostController --crud`
D) `php artisan make:controller PostController --api`

**Answer: A) `php artisan make:controller PostController --resource`**

---

### Question 54: API Resource Collections
How do you return a collection of resources?

A) `return UserResource::collection($users);`
B) `return new UserResourceCollection($users);`
C) `return UserResource::make($users);`
D) Both A and B work

**Answer: D) Both A and B work**

---

### Question 55: HTTP Status Codes - Client Errors
What HTTP status code represents "Unauthorized"?

A) 400
B) 401
C) 403
D) 404

**Answer: B) 401**

---

### Question 56: HTTP Status Codes - Validation Error
What HTTP status code should be returned for validation errors?

A) 400
B) 422
C) 500
D) 401

**Answer: B) 422**

---

## Section 11: Form Handling & Validation

### Question 57: Form Request Validation
Which command creates a Form Request class?

A) `php artisan make:request UserRequest`
B) `php artisan make:form UserRequest`
C) `php artisan create:request UserRequest`
D) `php artisan make:validation UserRequest`

**Answer: A) `php artisan make:request UserRequest`**

---

### Question 58: Validation Rules
How do you make a field required and limit its length?

A) `'field' => 'required|max:255'`
B) `'field' => 'required,max:255'`
C) `'field' => ['required', 'max:255']`
D) Both A and C work

**Answer: D) Both A and C work**

---

### Question 59: Custom Validation Messages
How do you define custom validation messages?

A) Override `messages()` method in Form Request
B) Pass messages as third parameter to `validate()`
C) Use `Lang::get()` method
D) Both A and B work

**Answer: D) Both A and B work**

---

### Question 60: Error Display in Blade
How do you display validation errors in Blade templates?

A) `@error('field') {{ $message }} @enderror`
B) `{{ $errors->first('field') }}`
C) `@if($errors->has('field')) {{ $errors->first('field') }} @endif`
D) All methods work

**Answer: D) All methods work**

---

## Section 12: File Management & Storage

### Question 61: File Storage Configuration
Where are file storage configurations defined?

A) `config/app.php`
B) `config/filesystems.php`
C) `config/storage.php`
D) `.env` file

**Answer: B) `config/filesystems.php`**

---

### Question 62: File Upload Validation
How do you validate an uploaded image file?

A) `'image' => 'required|image|max:2048'`
B) `'image' => 'required|file|mimes:jpg,png|max:2048'`
C) `'image' => 'required|image|mimes:jpeg,png,jpg|max:2048'`
D) All are valid approaches

**Answer: D) All are valid approaches**

---

### Question 63: File Storage Methods
Which method stores a file with a custom name?

A) `$file->store('uploads')`
B) `$file->storeAs('uploads', 'filename.jpg')`
C) `$file->save('uploads/filename.jpg')`
D) `$file->move('uploads', 'filename.jpg')`

**Answer: B) `$file->storeAs('uploads', 'filename.jpg')`**

---

### Question 64: File Retrieval
How do you get the URL of a stored file?

A) `Storage::url($path)`
B) `asset('storage/' . $path)`
C) `url('storage/' . $path)`
D) All methods work depending on configuration

**Answer: D) All methods work depending on configuration**

---

## Section 13: Authentication & Authorization

### Question 65: Laravel Breeze
What does Laravel Breeze provide?

A) Basic authentication scaffolding
B) Admin panel
C) API authentication only
D) Social media login

**Answer: A) Basic authentication scaffolding**

---

### Question 66: Authentication Check
How do you check if a user is authenticated in a controller?

A) `Auth::check()`
B) `auth()->check()`
C) `$request->user()`
D) All methods work

**Answer: D) All methods work**

---

### Question 67: Authorization Gates
How do you define an authorization gate?

A) `Gate::define('update-post', function ($user, $post) {...});`
B) `Gate::create('update-post', function ($user, $post) {...});`
C) `Gate::make('update-post', function ($user, $post) {...});`
D) `Gate::register('update-post', function ($user, $post) {...});`

**Answer: A) `Gate::define('update-post', function ($user, $post) {...});`**

---

### Question 68: Policy Classes
Which command creates a policy class?

A) `php artisan make:policy PostPolicy`
B) `php artisan make:auth PostPolicy`
C) `php artisan create:policy PostPolicy`
D) `php artisan make:authorization PostPolicy`

**Answer: A) `php artisan make:policy PostPolicy`**

---

### Question 69: Middleware Authentication
How do you protect routes with authentication middleware?

A) `Route::middleware('auth')->group(function() {...});`
B) `Route::auth()->group(function() {...});`
C) `Route::protected()->group(function() {...});`
D) `Route::login()->group(function() {...});`

**Answer: A) `Route::middleware('auth')->group(function() {...});`**

---

### Question 70: User Roles
How do you check if an authenticated user has a specific role?

A) `auth()->user()->hasRole('admin')`
B) `Auth::user()->role === 'admin'`
C) `$request->user()->can('admin')`
D) Implementation depends on your role system

**Answer: D) Implementation depends on your role system**

---

## Section 14: Caching & Performance

### Question 71: Cache Configuration
Where is cache configuration stored?

A) `config/cache.php`
B) `config/app.php`
C) `.env` file
D) Both A and C

**Answer: D) Both A and C**

---

### Question 72: Cache Operations
How do you store and retrieve cached data?

A) `Cache::put('key', $value, $seconds); Cache::get('key');`
B) `cache(['key' => $value], $seconds); cache('key');`
C) `Cache::remember('key', $seconds, function() {...});`
D) All methods work

**Answer: D) All methods work**

---

### Question 73: Query Caching
How do you cache database query results?

A) `User::cache()->get()`
B) `Cache::remember('users', 3600, function() { return User::all(); });`
C) `User::remember(3600)->get()`
D) `User::all()->cache(3600)`

**Answer: B) `Cache::remember('users', 3600, function() { return User::all(); });`**

---

### Question 74: Cache Clearing
How do you clear all cached data?

A) `php artisan cache:clear`
B) `Cache::flush()`
C) `php artisan cache:forget --all`
D) Both A and B work

**Answer: D) Both A and B work**

---

## Section 15: Background Jobs & Queues

### Question 75: Job Creation
Which command creates a new job class?

A) `php artisan make:job ProcessEmail`
B) `php artisan make:queue ProcessEmail`
C) `php artisan create:job ProcessEmail`
D) `php artisan make:task ProcessEmail`

**Answer: A) `php artisan make:job ProcessEmail`**

---

### Question 76: Job Dispatching
How do you dispatch a job to the queue?

A) `ProcessEmail::dispatch($user)`
B) `dispatch(new ProcessEmail($user))`
C) `Queue::push(new ProcessEmail($user))`
D) All methods work

**Answer: D) All methods work**

---

### Question 77: Queue Workers
How do you start a queue worker?

A) `php artisan queue:work`
B) `php artisan queue:start`
C) `php artisan queue:run`
D) `php artisan job:work`

**Answer: A) `php artisan queue:work`**

---

### Question 78: Job Failures
How do you handle failed jobs?

A) Implement `failed()` method in job class
B) Use `php artisan queue:failed` to view failed jobs
C) Use `php artisan queue:retry` to retry failed jobs
D) All of the above

**Answer: D) All of the above**

---

## Section 16: Testing Fundamentals

### Question 79: Test Creation
Which command creates a feature test?

A) `php artisan make:test UserTest`
B) `php artisan make:test UserTest --feature`
C) `php artisan create:test UserTest`
D) Both A and B work

**Answer: D) Both A and B work**

---

### Question 80: Database Testing
How do you use a separate database for testing?

A) Set `DB_DATABASE=testing` in `.env.testing`
B) Use `RefreshDatabase` trait in test classes
C) Configure `phpunit.xml` with test database
D) All approaches work

**Answer: D) All approaches work**

---

### Question 81: HTTP Testing
How do you test a GET request to `/users`?

A) `$response = $this->get('/users');`
B) `$response = $this->call('GET', '/users');`
C) `$response = $this->request('GET', '/users');`
D) Both A and B work

**Answer: D) Both A and B work**

---

### Question 82: Test Assertions
How do you assert a successful HTTP response?

A) `$response->assertStatus(200);`
B) `$response->assertOk();`
C) `$response->assertSuccessful();`
D) All methods work

**Answer: D) All methods work**

---

## Section 17: Laravel Artisan Commands

### Question 83: Custom Commands
Which command creates a custom Artisan command?

A) `php artisan make:command SendEmails`
B) `php artisan make:console SendEmails`
C) `php artisan create:command SendEmails`
D) `php artisan make:artisan SendEmails`

**Answer: A) `php artisan make:command SendEmails`**

---

### Question 84: Command Scheduling
Where do you define scheduled commands?

A) `app/Console/Kernel.php`
B) `routes/console.php`
C) `config/schedule.php`
D) `app/Console/Commands/`

**Answer: A) `app/Console/Kernel.php`**

---

### Question 85: Database Commands
Which command runs pending migrations?

A) `php artisan migrate`
B) `php artisan migrate:run`
C) `php artisan db:migrate`
D) `php artisan migration:run`

**Answer: A) `php artisan migrate`**

---

### Question 86: Cache Commands
Which command clears the application cache?

A) `php artisan cache:clear`
B) `php artisan clear:cache`
C) `php artisan cache:flush`
D) `php artisan app:clear`

**Answer: A) `php artisan cache:clear`**

---

## Section 18: Laravel Mix/Vite & Frontend

### Question 87: Asset Compilation
What is Laravel Mix used for?

A) Database migrations
B) Compiling CSS and JavaScript assets
C) API development
D) User authentication

**Answer: B) Compiling CSS and JavaScript assets**

---

### Question 88: Vite Configuration
In Laravel 9+, which file configures Vite?

A) `webpack.mix.js`
B) `vite.config.js`
C) `mix.config.js`
D) `assets.config.js`

**Answer: B) `vite.config.js`**

---

### Question 89: Asset Loading in Blade
How do you include compiled assets in Blade templates?

A) `@vite(['resources/css/app.css', 'resources/js/app.js'])`
B) `<link href="{{ mix('css/app.css') }}" rel="stylesheet">`
C) `<script src="{{ asset('js/app.js') }}"></script>`
D) Depends on whether using Vite or Mix

**Answer: D) Depends on whether using Vite or Mix**

---

### Question 90: NPM Commands
Which command installs JavaScript dependencies?

A) `npm install`
B) `npm run dev`
C) `npm run build`
D) `composer install`

**Answer: A) `npm install`**

---

## Section 19: Error Handling & Debugging

### Question 91: Debug Mode
How do you enable debug mode in Laravel?

A) Set `APP_DEBUG=true` in `.env`
B) Set `DEBUG=true` in `config/app.php`
C) Use `--debug` flag with artisan commands
D) Install debug toolbar

**Answer: A) Set `APP_DEBUG=true` in `.env`**

---

### Question 92: Exception Handling
Where is global exception handling configured?

A) `app/Exceptions/Handler.php`
B) `config/exceptions.php`
C) `bootstrap/app.php`
D) `app/Http/Kernel.php`

**Answer: A) `app/Exceptions/Handler.php`**

---

### Question 93: Logging
How do you log information in Laravel?

A) `Log::info('message')`
B) `logger('message')`
C) `info('message')`
D) All methods work

**Answer: D) All methods work**

---

### Question 94: Debugging Tools
Which tool helps debug database queries?

A) Laravel Debugbar
B) Laravel Telescope
C) Clockwork
D) All of the above

**Answer: D) All of the above**

---

## Section 20: Configuration & Environment

### Question 95: Environment Files
What is the purpose of the `.env` file?

A) Store environment-specific configuration
B) Define routes
C) Store user data
D) Configure middleware

**Answer: A) Store environment-specific configuration**

---

### Question 96: Configuration Caching
Which command caches configuration files?

A) `php artisan config:cache`
B) `php artisan cache:config`
C) `php artisan config:clear`
D) `php artisan optimize`

**Answer: A) `php artisan config:cache`**

---

### Question 97: Environment Variables
How do you access environment variables in Laravel?

A) `env('APP_NAME')`
B) `config('app.name')`
C) `$_ENV['APP_NAME']`
D) All methods work

**Answer: D) All methods work**

---

### Question 98: Application Key
What is the purpose of the application key?

A) Database encryption
B) Session and cookie encryption
C) API authentication
D) File storage encryption

**Answer: B) Session and cookie encryption**

---

### Question 99: Service Providers
What is the purpose of service providers?

A) Bind services into the service container
B) Bootstrap application services
C) Register routes and middleware
D) All of the above

**Answer: D) All of the above**

---

### Question 100: Laravel Lifecycle
What happens first in the Laravel request lifecycle?

A) Route matching
B) Middleware execution
C) Service provider registration
D) Bootstrap the framework

**Answer: D) Bootstrap the framework**

---

## Answer Summary

**Section 1 - PHP Fundamentals (1-10):**
1. A  2. B  3. B  4. C  5. B  6. D  7. D  8. A  9. A  10. B

**Section 2 - Laravel Fundamentals (11-20):**
11. B  12. A  13. D  14. A  15. A  16. C  17. B  18. A  19. B  20. B

**Section 3 - Database & Eloquent (21-25):**
21. B  22. B  23. D  24. B  25. A

**Section 4 - API Development (26-30):**
26. B  27. B  28. B  29. D  30. B

**Section 5 - Validation & Forms (31-33):**
31. D  32. D  33. D

**Section 6 - File Handling (34-35):**
34. A  35. B

**Section 7 - Security Basics (36-37):**
36. D  37. D

**Section 8 - Advanced Laravel Basics (38-45):**
38. B  39. A  40. B  41. B  42. B  43. D  44. D  45. A

**Section 9 - Database Advanced Concepts (46-50):**
46. B  47. B  48. C  49. A  50. D

**Section 10 - Advanced API Development (51-56):**
51. A  52. A  53. A  54. D  55. B  56. B

**Section 11 - Form Handling & Validation (57-60):**
57. A  58. D  59. D  60. D

**Section 12 - File Management & Storage (61-64):**
61. B  62. D  63. B  64. D

**Section 13 - Authentication & Authorization (65-70):**
65. A  66. D  67. A  68. A  69. A  70. D

**Section 14 - Caching & Performance (71-74):**
71. D  72. D  73. B  74. D

**Section 15 - Background Jobs & Queues (75-78):**
75. A  76. D  77. A  78. D

**Section 16 - Testing Fundamentals (79-82):**
79. D  80. D  81. D  82. D

**Section 17 - Laravel Artisan Commands (83-86):**
83. A  84. A  85. A  86. A

**Section 18 - Laravel Mix/Vite & Frontend (87-90):**
87. B  88. B  89. D  90. A

**Section 19 - Error Handling & Debugging (91-94):**
91. A  92. A  93. D  94. D

**Section 20 - Configuration & Environment (95-100):**
95. A  96. A  97. D  98. B  99. D  100. D

---

## Assessment Guidelines for Freshers

**Scoring (Out of 100 Total Questions):**
- 90-100 correct: Excellent (Senior Junior/Ready for mid-level) - 90%+
- 80-89 correct: Very Good (Strong junior developer) - 80-89%
- 70-79 correct: Good (Solid junior developer) - 70-79%
- 60-69 correct: Average (Entry-level with mentoring) - 60-69%
- Below 60: Needs Significant Improvement - Below 60%

**Time Limit Suggestion:** 3 hours (180 minutes)

**Minimum Passing Score:** 70/100 (70%)

**Essential Knowledge Areas Covered:**

✅ **PHP Core Concepts** - Variables, functions, classes, arrays
✅ **Laravel Basics** - MVC, routing, controllers, models  
✅ **Blade Templates** - Syntax and usage
✅ **Database Operations** - Eloquent, relationships, migrations
✅ **API Development** - Routes, responses, authentication
✅ **Form Handling** - Validation, CSRF, file uploads
✅ **Security Fundamentals** - Password hashing, SQL injection prevention
✅ **Common Features** - Caching, queues, middleware

**What This Quiz Assesses:**
- Essential PHP knowledge for Laravel development
- Core Laravel framework concepts and patterns
- Database operations and Eloquent ORM basics
- API development fundamentals
- Form handling and validation
- Basic security practices
- Common Laravel features used in daily development

**Perfect For:**
- Junior developer interviews
- Bootcamp assessments  
- Self-evaluation for beginners
- Screening candidates for entry-level positions
- Measuring readiness for Laravel projects

**Note:** This focused quiz covers the absolute essentials. Candidates scoring 70%+ demonstrate readiness for junior Laravel development roles with proper mentoring and continued learning.
