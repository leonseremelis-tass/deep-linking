**parent.lounge.home.page**
----
  Redirects to the Parent Lounge home page after a successful user login.

* **Version History:**

    	`TASS v59.07 - Method Added`

* **Version:**

  	`1`

* **Permission Required:**

  	`Parent Lounge`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

*  **Optional Params:***

    `prod_menu [char]` - Y/N falg to show/hide the menu.
    
* **Sample Parameters:**

	```HTML
	"target":"parent.lounge.home.page"
	"prod_menu":"Y"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"parent.lounge.home.page","prod_menu":"Y"}
	```
