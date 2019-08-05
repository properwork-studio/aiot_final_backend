## AIOT FINAL PROJECT BACKEND

#### URL Pattern Design:
	<li>"/" : index page (index.jsp)</li>
	"/login" : login page (login.jsp - show login form)
	"toLogin" : to do the login verification (loginFilter - if success then change the dbconnection to the current user database)
	"/setting/account" : create new account page (init_account.jsp - show create account form)
	"/account/new" : to do the account creation (settingFilter - check if the email is not duplicate, if success then change the dbconnection to the current user database and create a new database)
