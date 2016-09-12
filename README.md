# amitkhare/host-to-sub-directory
Base project to redirect all calls to sub-directory for Apache web server.

# Install

Run this command from the directory in which you want to install your new Slim 3 Framework with modular HMVC.

Via Composer:

    php composer.phar create-project amitkhare/host-to-sub-directory [my-app-name]

Via Git:

    git clone https://github.com/amitkhare/host-to-sub-directory.git [my-app-name]

    composer update

Replace `[my-app-name]` with the desired directory name for your new application. You'll want to:

* Point your virtual host document root to your new application's root `/` directory.

That's it!