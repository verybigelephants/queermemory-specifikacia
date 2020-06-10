	homepage 
		posledny prispevok v aktivnej "kategorii" 
		alternativne pinovatelny prispevok aby bol ako prvy
		meta info o nej
		listing n prispevkov z aktivnej kategorie a "load more" 
		kapitolovy listing
	teda momentalne mame strukturu: "projekt" (loading:love) -> "kapitola" -> clanok
	----
		12h frontend
		4h backend 
	
	detail clanku
		header image +optional video
		perex a meta o autorovi
		clanok - tento je zlozenyz roznych dynamicky vkladatelnych kokotin ze
			-1 stlpcovy/2 stlpcovy text
			-citatik
			-oranomvany ciernym borderom box, asi nejaky dolezity text
			-duhovy blok
			-obrazok (2/3 konfigurovatelne velkosti, content first, nie je to designovy prvok
			-obrazok fullscreen
			-audio upload na styl https://wepresent.wetransfer.com/story/grimes-youll-miss-me-when-im-not-around-fan-videos/
			-inline galeria na styl slidera
			-medajlonik osobnosti
			-dalsie citanie: nasledujuce clanky chrnologicky po aktualnom vramci rovnakeho "projektu"
		clanok bude mat navyse: tagy, spomenute osobnosti, do akej kategorie (projektu) patri - mozu byt nezaradene?, nepovinna podkategoria (kapitola)
		duhovy progressbar ktory sa naplna podla toho v kolko% z clanku sa clovek nachadza
	----
		27h frontend
		6h backend
		
	subscribe s napojenim na mailchimp
	----
		2h backend
		2h frontend

	detail autora - treba navrhnut este, predpokladam:
		bio textik 
		obrazok
		zoznam autorovych clankov
	----
		[?] frontend
		2h backend 
	
	detail osobnosti
		-rovnako editovatelny blok ako "clanok"
		-metadata navyse (rok, "spovede" - nahravky s nimi, tiez tagy)
		-galeria
	----
		5h frontend
		2h backend 
	
	search
		vyhladavanie vramci osobnosti/clankov, v poliach z
			-perexy
			-nadpis
			-tagy
			-rok
			- v detailoch clanku nie, pretoze by tam mohlo hrozne vela veci vyskocit co ani nechces vidiet, ale kludne mozme spravit aj tam, daj vediet
	----
		6h frontend
		5h backend
	  
	"kategoria" (vystava/projekt)
		-about stranka
		-"kapitoly" - podkategorie -iba nazov a kratky popis co to je zac, daju sa k nim priradovat clanky
	----
		3h backend
		ziadny frontend, tento bod je administracii a prepojenia struktury na frontend do templatov 

	queer memory
		-o projekte stranka
		-konfigurovatelne temy + obdobia ako tagy
		menu co bude zobrazovat tagy/kategorie podla obsahu ktory je nastranke + veci z aktivnej "kategorie" (projektu, teraz loading:love)
	----
		1h backend 
		6h frontend
		extra frontend [?] - neviem co bude v stranke "o projekte"

	site mapa a rss feedaktivne 
		- zatial neprogramujeme, mozme dorobit ked bude na stranke obsah
		
	extra veci
		pripomienky - odhadujem to podla pripomienok k blanke a landing page  
			4h-18h frontend
			1h-2h backend 
		"devops" (hosting, certifikaty, serverove veci) -malo by byt vpohode, sme na websupporte
			2h backend
		accounting, calliky, dohadovacky
			2-4h? accounting 
		tato specifikacia a odhad
			3h accounting
		
	========================= 
		28h - 29h backend, 35€/h, 980€ - 1015€
		62h - 76h frontend, 25€h, 1550€- 1900€ + naklady co su este [?] a nemaju design  
		5h - 7h accounting, 25€/h, 125€ - 175€
	---
		2655€ - 3090€ + naklady co su este [?] a nemaju design
