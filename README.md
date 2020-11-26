## A simple blog with Laravel & Livewire

<p>
Creating a simple blog in <a href="https://travis-ci.org/laravel/framework">Laravel</a> and <a href="https://laravel-livewire.com/">Livewire</a>. It will be pretty simple and can be used as a starting point for building your blog with these awesome frameworks.
</p>

## Installation

1. Fork this repository to your own account.
2. Clone the Forked repository
   `git clone https://github.com/your_github_username/blog-with-laravel-and-livewire.git`
3. After cloning, now run `cd blog` and get into your newly cloned local
   repository/folder.
4. Run `composer install` to install the dependencies as defined in the
   composer.json file.
5. Now is the time to add the upstream remote address. This will be something
   useful in a team environment. Let’s say three person is working on a
   repository and everyone brings and pushes changes into what we call
   `upstream` or main repository. If you run `git remote -v` you will see that
   you have only `origin` configured and that’s looking to your fork. Now let’s
   add `upstream` as well:
   `git remote add upstream https://github.com/dawlatzai/blog-with-laravel-and-livewire.git`
6. you can create `.env` by `cp .env.example .env` then add your database
   credential in it.
7. Run `php artisan key:generate` to generate a key for your app.
8. Run `php artisan migrate --seed` to run the database migrations.
9. Run `php artisan serve` to Serve the application on the PHP development
   server.

> You can now visit the app in your browser by visiting
> [http://127.0.0.1:8000](http://127.0.0.1:8000).

<p>I have worked this based on <a href="https://api.daily.dev/r/Bw56vaPkL">Create a Blog in Laravel and Livewire</a></p>
