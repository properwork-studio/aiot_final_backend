## AIOT FINAL PROJECT BACKEND

#### URL Pattern Design:
	"/" : index page (index.jsp)

	"/login" : login page (login.jsp - show login form)

	"/toLogin" : to do the login verification (loginFilter - if success then change the dbconnection to the current user database)

	"/setting/account" : create new account page (init_account.jsp - show create account form)

	"/account/new" : to do the account creation (settingFilter - check if the email is not duplicate, if success then change the dbconnection to the current user database, create a new database and tables inside it - members, contact, medicines, medicineRecords, doorRecords, fallRecords)

	"/setting/member" : add new member page (init_member.jsp - show member initialization form)

	"/member/new" : to do the member creation

	"/setting/contact" : add new contact page (init_contact.jsp - show contact initialization form)

	"/contact/new" : to do the contact creation

	"/contact/edit" : to do the contact update

	"/setting/medicines" : add new medicine rule page (init_medicine.jsp - show medicine initialization form)

	"/medicine/new" : to do the medicine rule creation

	"/medicine/edit" : to do the medicine rule update

	"medicine/delete" : to do the medicine rule delete

	"/dashboard" : dashboard page - to show all the information
