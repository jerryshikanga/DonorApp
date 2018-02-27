This is a site to connect donors to those who need funds.
A working example can be found at http://35.196.70.43/Projects/Donor
It utilises the following
	CodeIgniter Php Framework
	Twitter Bootstrap
	JQuery
	Tawk.to Live Chat
	IonAuth Codeigniter Library
	Pesapal Payments gateway API


CONFIGURATION
In the application/config/database.php file change your credentials to your servers
In the application/config/config file look for the line base_url and change it your server
Run application/sql/donor.sql file Ive provided in your database client
In the application/controller/Pesapal.php change your CONSUMER_KEY AND CONSUMER_SECRET to what would have been provided by Pesapal when yousign up for a merchant account.
In the application/views/tawk.php replace the TAWK_KEY with the one you willb egiven by tawk.to
Change the urls in the application/controllers/pesapal.php from demo.pesapal..... to pesapal to migrate from sandbox to live environment

ENJOY!

