# Rails with Vagrant and Chef

Pretty simple to set up a Rails project that takes advantage of Vagrant and Chef.

## Usage
1. `git clone https://github.com/dydx/rails-vagrant-chef.git your_new_project`
2. `cd your_new_project`
3. `rails new .`
4. `vagrant up`
5. `vagrant ssh`

## Notes
* The `vagrant up` command is going to probably take a little while. Go ahead and take a smoke break or make a sandwich the first time you run it.

* If you ever edit the `Vagrantfile` or the `Cheffile`, you'll need to run `vagrant provision` to see those changes take place.
