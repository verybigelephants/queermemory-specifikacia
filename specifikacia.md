strankove templaty:
	homepage 
		posledny prispevok v aktivnej "kategorii" 
		alternativne pinovatelny prispevok aby bol ako prvy
		meta info o nej
		listing n prispevkov z aktivnej kategorie a "load more" 
		kapitolovy listing
	teda momentalne mame strukturu: "projekt" (loading:love) -> "kapitola" -> clanok
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

	detail autora - treba navrhnut este, predpokladam:
		bio textik 
		obrazok
		zoznam autorovych clankov
	
	detail osobnosti
		-rovnako editovatelny blok ako "clanok"
		-metadata navyse (rok, "spovede" - nahravky s nimi, tiez tagy)
		-galeria
	
	search
		vyhladavanie vramci osobnosti/clankov, v poliach z
			-perexy
			-nadpis
			-tagy
			-rok
			- v detailoch clanku nie, pretoze by tam mohlo hrozne vela veci vyskocit co ani nechces vidiet, ale kludne mozme spravit aj tam, daj vediet 
	"kategoria" (vystava/projekt)
		-about stranka
		-"kapitoly" - podkategorie -iba nazov a kratky popis co to je zac, daju sa k nim priradovat clanky

	queer memory
		-o projekte stranka
		-konfigurovatelne temy + obdobia ako tagy
		menu co bude zobrazovat tagy/kategorie podla obsahu ktory je nastranke + veci z aktivnej "kategorie" (projektu, teraz loading:love)

	site mapa a rss feedaktivne 
		- zatial neprogramujeme, mozme dorobit ked bude na stranke obsah
		
		
		
