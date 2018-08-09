# Vuugaa

Vuugaa is a RideSharing application that allows you and other Andelans to collaborate and carpool to work.

## Usage
This application is built using the lastest version of [ruby](https://www.ruby-lang.org/en/downloads/) and rails which can be downloaded from [here](https://rubyonrails.org/)

Clone the repo using this command bellow
```
git clone https://github.com/chadwalt/ride-sharing-app.git
```

After cloning download and install the application dependencies using the command below
```
bundle install
```

The application uses `postgresql` as the default database. Execute the following commands to fully setup the database.
```
rails db:migrate
rails db:setup
```

To run the application you can use the built in server of rails which webrick and to do this, the command below needs to be executed.
```
rails s
```