- Daily Log Template
  template:: DL-Progress
  template-including-parent:: false
  collapsed:: true
	- tags:: #[[DL: Daily Log]]
	  progress:: {{renderer :todomaster}}
	- # [[DL: Daily Log]]: 2,66X.x #week
	  heading:: true
		- {{renderer :interstitial, random, nts}}
	- # [[DL: Habits]]
	  heading:: true
		- random: {{renderer :interstitial, random, self}}
		- #### Morning  Pages (Digital Version)
		- #habit/morning
			-
		- #habit/afternoon
			-
		- #habit/evening
			-
	- # [[DL: Reading]]
	  heading:: true
		- {{renderer :interstitial, random, quote}}
	- # [[DL: Youtube]]
	  heading:: true
		- {{renderer :interstitial, random, self}}
- #.v-eisenhower-matrix
    template:: eisenhower-matrix
	- [[TODO]]
		-
		-
		-
	- [[DECIDE]]
		-
		-
		-
	- [[DELEGATE]]
		-
		-
		-
	- [[ELIMINATE]]
		-
		-
		-
- codal
	- template:: codal
	  template-including-parent:: false
		- alt-title::
		  type:: codal
		  law-subject::
		  tags:: #codal/
		  status:: active
- professor
	- Template:: prof
	  template-including-parent:: false
		- type:: lawyer
		  tags:: professor
		  name::
		  subject::
		  school:: USJ-R School of Law
		  semester::
		  year::
		  email::
- Law Log Template
  template:: Lawlog
  template-including-parent:: false
  collapsed:: true
	- # [[LL: Daily Log]]: X,XXX.x #week
		- {{renderer :interstitial,random,nts}}
	- # [[DL: Habits]]
		- random: {{renderer :interstitial,random,self}}
		- #### Morning  Pages (Digital Version)
			-
		- #habit/morning
			-
		- #habit/afternoon
			-
		- #habit/evening
			-
	- # [[LL: Reading]]
		- {{renderer :interstitial,random,quote}}
	- # [[LL: Youtube]]
		- {{renderer :interstitial,random,self}}
- Lecture Daily Log
  Template:: Lecture
  template-including-parent:: false
	- # [[LL: Lecture Notes]]
		- {{renderer :interstitial, random, canon}}
			- ## Update this Subject ((630b2728-4451-414f-b6e3-7edc46549a3e)) for today
			  icon:: 📖
				-
