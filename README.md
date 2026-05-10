<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Speisekarte - Basti Pizzaservice Rheine</title>
    <style>
        :root { --primary: #c0392b; --secondary: #2c3e50; --bg: #fdfdfd; }
        body { font-family: 'Helvetica Neue', Arial, sans-serif; line-height: 1.4; margin: 0; background: var(--bg); color: #222; }
        header { background: var(--primary); color: white; padding: 25px; text-align: center; border-bottom: 5px solid #a93226; }
        .container { max-width: 1100px; margin: auto; padding: 20px; background: white; }
        .info-header { text-align: center; margin-bottom: 30px; font-weight: bold; background: #f9f9f9; padding: 15px; border: 1px solid #ddd; font-size: 0.9em; }
        h2 { color: var(--primary); border-bottom: 2px solid var(--primary); margin-top: 40px; text-transform: uppercase; letter-spacing: 1px; font-size: 1.4em; }
        .menu-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(400px, 1fr)); gap: 15px; }
        @media (max-width: 600px) { .menu-grid { grid-template-columns: 1fr; } }
        .item { padding: 10px; border-bottom: 1px solid #eee; }
        .item-head { display: flex; justify-content: space-between; font-weight: bold; font-size: 1.05em; align-items: baseline; }
        
        /* Preise in Schriftgröße 1em und dezentem Grau */
        .price { color: #888; font-size: 1em; font-weight: normal; margin-left: 10px; white-space: nowrap; }
        
        .desc { font-size: 0.88em; color: #555; margin-top: 4px; font-style: italic; }
        sup { color: #c0392b; font-weight: bold; font-size: 0.75em; }
        .legend { background: #f9f9f9; padding: 20px; font-size: 0.75em; margin-top: 50px; border: 1px solid #ddd; border-radius: 5px; line-height: 1.6; }
        footer { background: var(--secondary); color: white; text-align: center; padding: 20px; margin-top: 40px; }
    </style>
</head>
<body>

<header>
    <h1 style="margin:0">BASTI PIZZASERVICE</h1>
    <p style="margin:5px 0;">Catenhorner Straße 2 • 48431 Rheine</p>
    <p style="font-size: 1.5em; margin:10px 0; font-weight:bold;">☎ 05971 - 9914855</p>
</header>

<div class="container">
    <div class="info-header">
        Öffnungszeiten: Mo, Di, Mi, Do 16:00-21:30 | Mi & Do 11:00-14:00 | Fr 16:00-22:00 | Sa & So 15:00-22:00 | Feiertage 16:00-21:00 <br>
    </div>

    <h2>Pizza Menüs</h2>
    <div class="menu-grid">
        <div class="item">
            <div class="item-head"><span>195 Menü 1</span><span class="price">12,00 €</span></div>
            <div class="desc">1 Große Pizza mit 4 Zutaten nach Wahl, 1 kleiner gemischter Salat nach Wahl, 1 Softgetränk 0,33l nach Wahl</div>
        </div>
        <div class="item">
            <div class="item-head"><span>196 Menü 2</span><span class="price">22,50 €</span></div>
            <div class="desc">1 Familien Pizza mit 4 Zutaten nach Wahl, 1 großer Salat nach Wahl, 1 Softgetränk 1,0l nach Wahl</div>
        </div>
    </div>

    <h2>Pizza (Ø 24cm / Ø 28cm)</h2>
	<h5>Alle Pizzen:<br>
		-mit Tomatensauce<br>
		-enthalten die Allergene A,G,I,J<br>
		-auch in 40cm / 50cm Familiengröße erhältlich</h5><br>
	<div class="menu-grid">
        <div class="item"><div class="item-head"><span>1 Margherita</span><span class="price">5,10 / 6,20</span></div><div class="desc">Tomatensauce, Käse<sup>1</sup></div></div>
        <div class="item"><div class="item-head"><span>6 Casa<sup>A,G</sup></span><span class="price">7,10 / 8,20</span></div><div class="desc">Putenschinken<sup>2,3,4,5</sup>,frische Champignons</div></div>
        <div class="item"><div class="item-head"><span>7 Rustica</span><span class="price">7,40 / 8,50</span></div><div class="desc">Salami<sup>1,2,3</sup>, frische frische Paprika, frische Champignons</div></div>
        <div class="item"><div class="item-head"><span>8 Veggie</span><span class="price">8,70 / 9,80</span></div><div class="desc">Spinat, Brokkoli, frische Champignons, frische Paprika, Zwiebeln, Tomatenscheiben, Mozzarella, Knoblauch</div></div>
        <div class="item"><div class="item-head"><span>11 Tonno Cipolla<sup>D</sup></span><span class="price">7,20 / 8,40</span></div><div class="desc">Thunfisch, Zwiebeln</div></div>
        <div class="item"><div class="item-head"><span>12 Stockholm</span><span class="price">7,80 / 8,90</span></div><div class="desc">Thunfisch, Zwiebeln, Kräutercreme</div></div>
        <div class="item"><div class="item-head"><span>13 Muezza<sup>D,C</sup></span><span class="price">8,00 / 9,10</span></div><div class="desc">Thunfisch, Brokkoli, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>15 Bari<sup>C</sup></span><span class="price">7,10 / 8,20</span></div><div class="desc">Brokkoli, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>16 Royal<sup>C</sup></span><span class="price">7,40 / 8,50</span></div><div class="desc">Brokkoli, Putenschinken<sup>2,3,4,5</sup>, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>17 Hawaii</span><span class="price">6,50 / 7,80</span></div><div class="desc">Putenschinken<sup>2,3,4,5</sup>, Ananas</div></div>
        <div class="item"><div class="item-head"><span>20 Palma<sup>D</sup></span><span class="price">8,20 / 9,20</span></div><div class="desc">Salami<sup>1,2,3</sup>, Putenschinken<sup>2,3,4,5</sup>, frische Paprika, frische Champignons, Thunfisch, Zwiebeln</div></div>
        <div class="item"><div class="item-head"><span>22 Padua<sup>D</sup></span><span class="price">9,50 / 10,50</span></div><div class="desc">Salami<sup>1,2,3</sup>, Putenschinken<sup>2,3,4,5</sup>, Thunfisch, frische Champignons, frische Paprika, Zwiebeln, milde Peperoni, Oliven, frische Tomaten, Mozzarella</div></div>
        <div class="item"><div class="item-head"><span>25 Austin</span><span class="price">8,00 / 9,00</span></div><div class="desc">würziges Hackfleisch, Hähnchenbrustfilet, BBQ Sauce, frische Paprika, milde Peperoni</div></div>
        <div class="item"><div class="item-head"><span>26 Antep<sup>D</sup></span><span class="price">9,10 / 10,10</span></div><div class="desc">würzige Sucuk-Salami<sup>1,3,4</sup>, frische Champignons, gekochtem Ei, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>27 Sole Mio</span><span class="price">9,00 / 10,00</span></div><div class="desc">würzige Sucuk-Salami<sup>1,3,4</sup>, Zwiebeln, Weichkäse, frische Paprika, milde Peperoni, Oliven</div></div>
        <div class="item"><div class="item-head"><span>28 Italia</span><span class="price">6,90 / 8,00</span></div><div class="desc">Tomaten, Mozzarella, Basilikum</div></div>
        <div class="item"><div class="item-head"><span>30 Rucola</span><span class="price">7,80 / 8,80</span></div><div class="desc">Rucola mit Tomaten gebacken, anschließend mit Rinderschinken, Rucola, frischem Parmesan</div></div>
        <div class="item"><div class="item-head"><span>31 Tokio</span><span class="price">7,00 / 8,00</span></div><div class="desc">Bolognese, frische Paprika, Mais, scharfe Peperoni</div></div>
        <div class="item"><div class="item-head"><span>32 Popeye</span><span class="price">6,60 / 7,60</span></div><div class="desc">Spinat, Mozzarella, Knoblauch</div></div>
        <div class="item"><div class="item-head"><span>33 Pirat<sup>D,C</sup></span><span class="price">8,60 / 9,60</span></div><div class="desc">Spinat, Lachs, Sauce Hollandaise, Knoblauch</div></div>
        <div class="item"><div class="item-head"><span>35 Lachs<sup>D</sup></span><span class="price">8,30 / 9,30</span></div><div class="desc">Lachs gebacken und anschließend mit frischen Tomaten, Weichkäse, Zwiebeln, Rucola, Balsamico</div></div>
        <div class="item"><div class="item-head"><span>36 Scampi<sup>D</sup></span><span class="price">7,80 / 8,90</span></div><div class="desc">Krabben, Knoblauch, frische Tomaten</div></div>
        <div class="item"><div class="item-head"><span>37 Quattro for Maggi</span><span class="price">7,00 / 8,00</span></div><div class="desc">Gouda<sup>1</sup>, Mozzarella, Weichkäse, Gorgonzola</div></div>
        <div class="item"><div class="item-head"><span>38 Provolone</span><span class="price">6,50 / 8,00</span></div><div class="desc">Gouda<sup>1</sup>, Mozzarella, Weichkäse, Olivenöl ohne Tomatensauce</div></div>
        <div class="item"><div class="item-head"><span>39 Basti<sup>C</sup></span><span class="price">8,00 / 9,00</span></div><div class="desc">Hähnchenbrustfilet, Zwiebeln, frische Paprika, frische Champignons, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>40 Palermo</span><span class="price">8,00 / 9,00</span></div><div class="desc">Hähnchenbrustfilet, BBQ Sauce, Mozzarella, rote Zwiebeln</div></div>
        <div class="item"><div class="item-head"><span>42 Cappadocia<sup>C</sup></span><span class="price">8,00 / 9,00</span></div><div class="desc">Dönerfleisch, Zwiebeln, Tzatziki<sup>2,4</sup></div></div>
        <div class="item"><div class="item-head"><span>43 Döner Hollo<sup>C</sup></span><span class="price">7,70 / 8,70</span></div><div class="desc">Dönerfleisch, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>44 Konya<sup>C</sup></span><span class="price">8,00 / 9,10</span></div><div class="desc">Dönerfleisch, Brokkoli, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>45 Antalya<sup>C</sup></span><span class="price">8,20 / 9,20</span></div><div class="desc">Dönerfleisch, Zwiebeln, Weichkäse, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>46 Mare<sup>D</sup></span><span class="price">8,00 / 9,00</span></div><div class="desc">Meeresfrüchte, Knoblauch</div></div>
        <div class="item"><div class="item-head"><span>47 Döner BBQ<sup>C</sup></span><span class="price">8,20 / 9,20</span></div><div class="desc">Dönerfleisch, frische Paprika, Zwiebeln, BBQ-Sauce, Knoblauch</div></div>
        <div class="item"><div class="item-head"><span>48 Döner Chilli<sup>C</sup></span><span class="price">8,40 / 9,90</span></div><div class="desc">Dönerfleisch, Zwiebeln, frische Champignons, Chilli Sauce, Jalapenos, Rucola</div></div>
        <div class="item"><div class="item-head"><span>49 Hähnchen Pizza<sup>A,C</sup></span><span class="price">8,00 / 9,00</span></div><div class="desc">Hähnchen Drehspieß, Zwiebeln, Tzatziki<sup>2,4</sup></div></div>
        <div class="item"><div class="item-head"><span>50 Hähnchen Spezial<sup>A,C</sup></span><span class="price">8,40 / 9,40</span></div><div class="desc">Hähnchen Drehspieß, Tzatziki<sup>2,4</sup>, Weichkäse, scharfe Peperoni</div></div>
        <div class="item"><div class="item-head"><span>51 Hähnchen Capri<sup>A,C</sup></span><span class="price">8,40 / 9,40</span></div><div class="desc">Hähnchen Drehspieß, Brokkoli, frische Champignons, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>52 Bud Spencer<sup>A,D</sup></span><span class="price">7,90 / 8,90</span></div><div class="desc">Putenschinken<sup>2,3,4,5</sup>, Thunfisch, frische Champignons, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>53 Diavolo<sup>A,G</sup></span><span class="price">7,60 / 8,40</span></div><div class="desc">Salami<sup>1,2,3</sup>, Zwiebeln, frische Paprika, Oliven, scharfe Peperoni</div></div>
        <div class="item"><div class="item-head"><span>54 Spaghetti<sup>A</sup></span><span class="price">7,60 / 8,40</span></div><div class="desc">Spaghetti, Bolognese</div></div>
        <div class="item"><div class="item-head"><span>55 Cheeselover<sup>A</sup></span><span class="price">9,30 €</span></div><div class="desc">Pizza mit Käserand und 2 Zutaten nach Wahl</div></div>
        <div class="item"><div class="item-head"><span>56 Burrata<sup>A,G</sup></span><span class="price">10,30 €</span></div><div class="desc">Cherry Tomaten, Rucola, Burrata-Käse, rote Zwiebeln, Knoblauch, Balsamico</div></div>
        <div class="item"><div class="item-head"><span>57 Chilli Cheese<sup>A</sup></span><span class="price">9,80 €</span></div><div class="desc">Rinderhack, Cheddar, Jalapenos</div></div>
        <div class="item"><div class="item-head"><span>58 Rocco<sup>A</sup></span><span class="price">8,90 €</span></div><div class="desc">Cherry Tomaten, Rucola, Parmesan, Mozzarella, Knoblauch</div></div>
        <div class="item"><div class="item-head"><span>59 Hähnchen BBQ<sup>A,C</sup></span><span class="price">9,10 €</span></div><div class="desc">Hähnchen Drehspieß, frische Paprika, rote Zwiebeln, Sauce Hollandaise, BBQ-Sauce</div></div>
        <div class="item"><div class="item-head"><span>60 Kefalonia<sup>A</sup></span><span class="price">9,10 €</span></div><div class="desc">Dönerfleisch, Metaxasauce</div></div>
    </div>

    <h2>Calzone & Doppeldecker</h2>
    <div class="menu-grid">
        <div class="item"><div class="item-head"><span>80 Calzone Napoli<sup>A,D</sup></span><span class="price">8,80</span></div><div class="desc">frische Champignons, Thunfisch, Salami, Ei</div></div>
        <div class="item"><div class="item-head"><span>81 Calzone Bella<sup>A,C</sup></span><span class="price">8,80</span></div><div class="desc">Salami<sup>2,3</sup>, Putenschinken<sup>2,3,4,5</sup>, frische Champignons, Brokkoli, Bolognese, Sauce Hollandaise</div></div>
        <div class="item"><div class="item-head"><span>82 Calzone Cappadocia<sup>A</sup></span><span class="price">8,80</span></div><div class="desc">Dönerfleisch, Zwiebeln, Tzatziki<sup>2,4</sup></div></div>
        <div class="item"><div class="item-head"><span>83 Calzone Korfu<sup>A</sup></span><span class="price">8,80</span></div><div class="desc">Hähnchen- oder Dönerfleisch, Zwiebeln, Krautsalat, Tzatziki<sup>2,4</sup></div></div>
        <div class="item"><div class="item-head"><span>84 Calzone Hähnchenspezial<sup>A</sup></span><span class="price">9,00</span></div><div class="desc">Hähnchen Drehspieß, Brokkoli, Spargel, Sauce Hollandaise, Mais</div></div>
        <div class="item"><div class="item-head"><span>85 Calzone Verdure<sup>A,C,D</sup></span><span class="price">8,70</span></div><div class="desc">Brokkoli, Mais, frische Champignons, frische Paprika, Sauce Hollandaise, Weichkäse</div></div>
        <div class="item"><div class="item-head"><span>86 Calzone Adria<sup>A,G,C</sup></span><span class="price">8,70</span></div><div class="desc">Hähnchen Drehspieß, Sauce Hollandaise, Weichkäse, Krautsalat</div></div>
        <div class="item"><div class="item-head"><span>90 Doppeldecker Cappadocia<sup>A,C</sup></span><span class="price">9,80</span></div><div class="desc">gefüllte Pizza mit Dönerfleisch, Zwiebeln, Tzatziki<sup>2,4</sup></div></div>
        <div class="item"><div class="item-head"><span>91 Doppeldecker Padua<sup>A,D</sup></span><span class="price">11,00</span></div><div class="desc">gefüllte Pizza mit Salami<sup>1,2,3</sup>, Putenschinken<sup>2,3,4,5</sup>, Thunfisch, frische Champignons, frische Paprika, Zwiebeln, milde Peperoni, Oliven, frische Tomaten, Mozzarella</div></div>
        <div class="item"><div class="item-head"><span>92 Doppeldecker Basti<sup>A,C</sup></span><span class="price">9,80</span></div><div class="desc">gefüllte Pizza mit Hähnchenbrustfilet, Zwiebeln, frische Paprika, frische Champignons, Sauce Hollandaise</div></div>
    </div>
    
	<h2>Extra Zutaten</h2>
		<div class="desc">Dönerfleisch, Thunfisch, Hähnchen Drehspieß, Hähnchenbrustfilet, Weichkäse, Gouda, Cheddar, Sucuk-Salami, Rinderschinken, Parmesan, Krabben, Lachs, würziges Hackfleisch, Meeresfrüchte <span class="price">1,20 / 1,60</span><br>
		<div class="desc">Salami<sup>2,3</sup>, Putenschinken<sup>2,3,4,5</sup>, frische Champignons, Brokkoli, Sauce Hollandaise, Tzatziki<sup>2,3</sup>, Zwiebeln, frische Paprika, Ei, Oliven, Mozzarella, frische Tomaten, milde/scharfe Peperoni, Mais, Ananas, Rucola, Sardellen, Bolognese, Jalapenos <span class="price">0,90 / 1,10</span>
		</div></div>
		
	
    <h2>Pasta & Aufläufe</h2>
	<h5>Zu allen Pasta Gerichten gibt es 3 Pizzabrötchen dazu<br>
		 Alle Nudelgerichte enthalten die Allergene A,C,G,I,J</h5><br>
	<div class="menu-grid">
        <div class="item"><div class="item-head"><span>100B Spaghetti Carbonara</span><span class="price">9,50</span></div><div class="desc">Putenschinken<sup>2,3,4,5</sup>, Ei, Sahnesauce</div></div>
        <div class="item"><div class="item-head"><span>101 Spaghetti Bollo</span><span class="price">10,50</span></div><div class="desc">Bolognese, Käse<sup>1</sup> überbacken</div></div>
        <div class="item"><div class="item-head"><span>103 Penne Aida</span><span class="price">10,10</span></div><div class="desc">Hähnchenbrustfilet, frische Champignons, Mais, Sahnesauce, Käse<sup>1</sup> überbacken</div></div>
        <div class="item"><div class="item-head"><span>104 Penne Del Chef</span><span class="price">10,20</span></div><div class="desc">Hähnchenbrustfilet, Zwiebeln, frische Paprika, frische Champignons, Tomaten-Sahnesauce</div></div>
        <div class="item"><div class="item-head"><span>105 Tortellini alla Panna</span><span class="price">9,30</span></div><div class="desc">Putenschinken<sup>2,3,4,5</sup>, Sahnesauce</div></div>
        <div class="item"><div class="item-head"><span>107 Tortellini Aurela</span><span class="price">10,00</span></div><div class="desc">Hähnchenbrustfilet, frische Champignons, Sahnesauce, Käse<sup>1</sup> überbacken</div></div>
		<div class="item"><div class="item-head"><span>108 Tagliatelle Bari</span><span class="price">9,60</span></div><div class="desc">Bandnudeln, Spinat, Gorgonzola, Sahnesauce, C überbacken</div></div>
		<div class="item"><div class="item-head"><span>111 Pasta Mista</span><span class="price">9,50</span></div><div class="desc">4 Nudelsorten, Bolognese-Sahne, Käse<sup>1</sup> überbacken</div></div>
        <div class="item"><div class="item-head"><span>112 Lasagne Bolognese</span><span class="price">10,00</span></div><div class="desc">Putenschinken<sup>2,3,4,5</sup> Bolognese-Sahnesauce,Käse<sup>1</sup>überbacken</div></div>
	    <div class="item"><div class="item-head"><span>113 Lasagne Vegetarisch</span><span class="price">10,00</span></div><div class="desc">Spinat, frische Champignons, Zwiebeln, Weichkäse, Tomatensauce, Käse<sup>1</sup>überbacken</div></div>
        <div class="item"><div class="item-head"><span>114 Hähnchenauflauf<sup>A,C</sup></span><span class="price">10,20</span></div><div class="desc">Dönerfleisch, Penne, frische Paprika, Zwiebeln, frische Champignons, Tomaten-Sahne</div></div>
        <div class="item"><div class="item-head"><span>115 Griechischer Auflauf<sup>A,C</sup><span class="price">10,00</span></div><div class="desc">Kartoffelscheiben, Putenschinken<sup>2,3,4,5</sup>, Ei, Artischocken, Weichkäse, Käse-Sahnesauce</div></div>
	    <div class="item"><div class="item-head"><span>116 Toskanischer Auflauf<sup>A,C</sup></span><span class="price">10,00</span></div><div class="desc">Kartoffelscheiben, Brokkoli, frische Champignons, Putenschinken<sup>2,3,4,5</sup>, Hähnchenbrustfilet, Sauce Hollandaise, Sahnesauce</div></div>
		<div class="item"><div class="item-head"><span>117 Basti Auflauf<sup>A,C</sup></span><span class="price">10,00</span></div><div class="desc">Kartoffelscheiben, Hähnchenbrustfilet, Brokkoli, frische Champignons, Sahnesauce</div></div>
        <div class="item"><div class="item-head"><span>118 Kebab Pfanne<sup>A,C</sup></span><span class="price">13,00</span></div><div class="desc">Dönerfleisch, frische Tomaten, rote Zwiebeln, Knoblauchöl, Kräuter, Tomaten-Sahnesauce dazu Pommes und eine Salatbeilage</div></div>
		<div class="item"><div class="item-head"><span>119 Penne Maris</span><span class="price">13,00</span></div><div class="desc">Dönerfleisch, Penne, Sahne, Käse<sup>1</sup> überbacken</div></div>
	</div>
	
	
	<h2>Pizzaschnecken</h2>
	<h5>Dip Auswahl Pizzaschnecken Aioli, Kräutercreme oder Kräuterbutter</h5>
	<div class="menu-grid">
		<div class="item"><div class="item-head"><span>130 Pizzabrötchen</span><span class="price">4,00</span></div><div class="desc">6 Stück</div></div>
		<div class="item"><div class="item-head"><span>131 Käse Schnecken</span><span class="price">6,00</span></div><div class="desc">6 Pizzaschnecken gefüllt mit Käse<sup>1</sup></div></div>
		<div class="item"><div class="item-head"><span>132 Prosciutto Schnecken</span><span class="price">7,00</span></div><div class="desc">6 Pizzaschnecken gefüllt mit Putenschinken<sup>2,3,4,5</sup> Käse<sup>1</sup></div></div>
		<div class="item"><div class="item-head"><span>133 Salami Schnecken</span><span class="price">7,00</span></div><div class="desc">6 Pizzaschnecken gefüllt mit Salami<sup>1,2,3</sup> Käse<sup>1</sup></div></div>
		<div class="item"><div class="item-head"><span>134 Thunfisch Schnecken<sup>D</sup></span><span class="price">7,00</span></div><div class="desc">6 Pizzaschnecken gefüllt mit Thunfisch und Käse<sup>1</sup></div></div>
		<div class="item"><div class="item-head"><span>135 Toscana Schnecken</span><span class="price">7,50</span></div><div class="desc">6 Pizzaschnecken gefüllt mit frische Paprika, Bolognese und Käse<sup>1</sup></div></div>
		<div class="item"><div class="item-head"><span>136 Cipolla Schnecken</span><span class="price">7,50</span></div><div class="desc">6 Pizzaschnecken gefüllt mit Zwiebeln, milde Peperoni, Knoblauch und Käse<sup>1</sup></div></div>
		<div class="item"><div class="item-head"><span>137 Döner Schnecken</span><span class="price">7,00</span></div><div class="desc">6 Pizzaschnecken gefüllt mit Dönerfleisch, Käse<sup>1</sup></div></div>
		<div class="item"><div class="item-head"><span>138 Hähnchen Schnecken<sup>A,C</sup></span><span class="price">7,00</span></div><div class="desc">6 Pizzaschnecken gefüllt mit Hähnchen Drehspieß und Käse<sup>1</sup></div></div>
		<div class="item"><div class="item-head"><span>139 Brokkoli Schnecken</span><span class="price">7,00</span></div><div class="desc">6 Pizzaschnecken gefüllt mit Brokkoli, Sauce Hollandaise und Käse<sup>1</sup></div></div>
	</div>

    <h2>Salate</h2>
	<h5>Dressing Auswahl Joghurt, French, Essig Öl oder Joghurt-French Mix Dressing</h5>
    <div class="menu-grid">
        <div class="item"><div class="item-head"><span>150 Gemischter Salat</span><span class="price">5,80 / 6,80</span></div><div class="desc">Eisbergsalat, Tomate, Gurke, rote Zwiebeln, Mais</div></div>
        <div class="item"><div class="item-head"><span>151 Thunfisch Salat<sup>D</sup></span><span class="price">6,30 / 7,80</span></div><div class="desc">Eisbergsalat, Thunfisch, rote Zwiebeln, Gurke, frische Tomate, gekochtem Ei, Käse<sup>1</sup></div></div>
		<div class="item"><div class="item-head"><span>152 Bauern Salat</span><span class="price">6,80 / 8,30</span></div><div class="desc">Eisbergsalat, Tomate, Gurke, Weichkäse, Oliven, Peperoni</div></div>
        <div class="item"><div class="item-head"><span>153 Dello Chef Salat</span><span class="price">6,80 / 8,80</span></div><div class="desc">Eisbergsalat, frische Tomate, Gurke, rote Zwiebeln, frische Paprika, Hähnchenbrustfilet, Thunfisch, Ananas, Weichkäse</div></div>
		<div class="item"><div class="item-head"><span>154 Basti Salat</span><span class="price">6,80 / 8,60</span></div><div class="desc">Eisbergsalat, frische Tomate, Gurke, frische Paprika mit gebratenem Hähnchenbrustfilet, frische Champignons, rote Zwiebeln, Ananas und Essig Öl Dressing</div></div>
        <div class="item"><div class="item-head"><span>156 Casa Salat<sup>D</sup></span><span class="price">6,80 / 8,30</span></div><div class="desc">Eisbergsalat, frische Tomate, Gurke, Käse<sup>1</sup> Hähnchen, Ei, frische Paprika</div></div>
		<div class="item"><div class="item-head"><span>157 Salat des Hauses</span><span class="price">6,80 / 8,30</span></div><div class="desc">Eisbergsalat, frische Tomate, Gurke, Weichkäse, rote Zwiebeln, Döner oder Hänchen Drehspieß</div></div>
        <div class="item"><div class="item-head"><span>158 Hawaii Salat</span><span class="price">6,80 / 8,30</span></div><div class="desc">Eisbergsalat, frische Tomate, Gurke, Putenschinken<sup>2,3,4,5</sup>,Karotten, Ei, Ananas</div></div>
        <div class="item"><div class="item-head"><span>159 Italia Salat<sup>D</sup></span><span class="price">6,80 / 8,60</span></div><div class="desc">Eisbergsalat, frische Tomate, Gurke, Putenschinken<sup>2,3,4,5</sup>, Mozzarella, Thunfisch, Zwiebeln, Karotten, Ei</div></div>
		<div class="item"><div class="item-head"><span>160 Samos Salat</span><span class="price">7,80 / 8,60</span></div><div class="desc">Eisbergsalat, Cherry Tomaten, Gurke, Rucola, Hähnchenbrustfilet, rote Zwiebeln, Mozzarella, Parmesan mit Essig Öl</div></div>
		<div class="item"><div class="item-head"><span>161 Nizza Salat<sup>D</sup></span><span class="price">7,80 / 8,60</span></div><div class="desc">Eisbergsalat, Cherry Tomaten, Gurke, Mozzarella, Ei, Thunfisch, Oliven, Weichkäse</div></div>
	</div>
	
	
	<h2>Rollos</h2>
	<h5>Alle Rollos auch als Menü mit Pommes - nur 10,00</h5>
	<div class="menu-grid">
		<div class="item"><div class="item-head"><span>170 Chicken Rollo</span><span class="price">7,20</span></div><div class="desc">gebratenes Hähnchenbrustfilet, Blattsalat, Tomate, Zwiebeln, Gurke, BBQ-Sauce</div></div>
		<div class="item"><div class="item-head"><span>171 Mexico Rollo (Scharf)</span><span class="price">7,70</span></div><div class="desc">gebratenes Hähnchenbrustfilet, Zwiebeln, Käse<sup>1</sup>, Blattsalat, Gurken, Tomate und Sauce Hollandaise</div></div>
		<div class="item"><div class="item-head"><span>173 Veggi Rollo</span><span class="price">7,20</span></div><div class="desc">Blattsalat, frische Paprika, Zwiebeln, Tomate, Gurke, Weichkäse, Oliven, Tzatziki<sup>2,4</sup></div></div>
		<div class="item"><div class="item-head"><span>174 Döner Rollo</span><span class="price">7,70</span></div><div class="desc">Dönerfleisch, Tomate, Gurke, Zwiebeln, Blattsalat, Tzatziki<sup>2,4</sup> oder Cocktailsauce</div></div>
		<div class="item"><div class="item-head"><span>175 Hähnchen Rollo<sup>A,C</sup></span><span class="price">7,70</span></div><div class="desc">Hähnchen Drehspieß,Tomate, Gurke, Zwiebeln, Blattsalat, Tzatziki<sup>2,4</sup> oder Cocktailsauce</div></div>
		<div class="item"><div class="item-head"><span>176 Döner Rollo Spezial</span><span class="price">8,10</span></div><div class="desc">Dönerfleisch, Rucola, Weichkäse, Tomaten, rote Zwiebeln, Balsamico und Cocktailsauce</div></div>
		<div class="item"><div class="item-head"><span>177 Hähnchen Rollo Spezial<sup>A,C</sup></span><span class="price">8,10</span></div><div class="desc">Hähnchen Drehspieß, Pommes, Cocktailsauce, rote Zwiebeln und Käse<sup>1</sup></div></div>
	</div>
	
	
	<h2>Fleischspezialitäten & Co</h2>
    <div class="menu-grid">
        <div class="item"><div class="item-head"><span>180 Döner überbacken</span><span class="price">9,00</span></div><div class="desc">Dönerfleisch, frische Paprika, Zwiebeln, milde Peperoni, Sauce Hollandaise, Tomatensauce, Weichkäse, Käse<sup>1</sup> überbacken und 6 Pizzabrötchen</div></div>
		<div class="item"><div class="item-head"><span>181 Hähnchen überbacken<sup>A,C</sup></span><span class="price">9,00</span></div><div class="desc">Hähnchen Drehspieß, frische Champignons, Brokkoli, Sauce Hollandaise, Tomatensauce, Käse<sup>1</sup> überbacken und 6 Pizzabrötchen</div></div>
		<div class="item"><div class="item-head"><span>182 Chicken Wings (6/9/12)</span><span class="price">3,50 / 5,30 / 7,50</span></div><div class="desc">BBQ oder Süß-Sauer Sauce</div></div>
        <div class="item"><div class="item-head"><span>183 Chicken Nuggets (6/9/12)</span><span class="price">3,50 / 5,30 / 7,50</span></div><div class="desc">BBQ oder Süß-Sauer Sauce</div></div>
		<div class="item"><div class="item-head"><span>184 Döner Teller<sup>A,C</sup></span><span class="price">11,00</span></div><div class="desc">Döner oder Hähnchen Drehspieß, Zwiebeln, gemischter Salat, Tzatziki<sup>2,4</sup> und Pommes</div></div>
        <div class="item"><div class="item-head"><span>185 Hähnchen Teller<sup>A,C</sup></span><span class="price">12,00</span></div><div class="desc">gebratenes Hähnchenbrustfilet Zwiebeln, Tzatziki<sup>2,4</sup>, gemischter Salat und Pommes</div></div>
		<div class="item"><div class="item-head"><span>186 Döner/Hähnchen Spezial</span><span class="price">12,00</span></div><div class="desc">Döner oder Hähnchen Drehspieß, Metaxasauce, Käse<sup>1</sup> überbacken dazu Pommes oder Pizzabrötchen</div></div>
		<div class="item"><div class="item-head"><span>210 Pommes</span><span class="price">4,00</span></div></div>
        <div class="item"><div class="item-head"><span>187 Dolcisimo<sup>Z</sup></span><span class="price">6,00</span></div><div class="desc">Pizza mit Nutella, Pistazien<sup>Z</sup>, Puderzucker</div></div>
        <div class="item"><div class="item-head"><span>190 Kiddie Box (Junge/Mädchen)</span><span class="price">6,00</span></div><div class="desc">6er Nuggets mit Pommes oder kleine Pizza (20cmm), 1 Dip, 1 Getränk, Spielzeug</div></div>
        <div class="item"><div class="item-head"><span>220 Fontina Sandwich</span><span class="price">10,00</span></div><div class="desc">Salami oder Putenschinken<sup>2,3,4,5</sup>, Cherry Tomaten, Cheddar, Burrata, Rucola, Rucola und Cocktail Sauce</div></div>
    </div>

    <h2>Getränke</h2>
    <div class="menu-grid">
        <div class="item"><div class="item-head"><span>Fritz Cola / Fritz Zero / Mexxo / Fanta / 7UP / Uludag Gazoz</span><span class="price">2,60 (0,33l)</span></div></div>
        <div class="item"><div class="item-head"><span>Coca-Cola / Mezzo</span><span class="price">3,20 (1,0l)</span></div></div>
        <div class="item"><div class="item-head"><span>Ayran</span><span class="price">1,80</span></div></div>
		<div class="item"><div class="item-head"><span>Wasser</span><span class="price">2,00</span></div></div>
    </div>

    <div class="legend">
        <strong>Zusatzstoffe:</strong> 1: Farbstoff; 2: konserviert; 3: Antioxidationsmittel; 4: Geschmacksverstärker; 5: Phosphat; 7: koffeinhaltig; 8: geschwärzt <br><br>
        <strong>Allergene:</strong> A: Gluten; B: Krebstiere; C: Ei; D: Fisch; G: Milch/Laktose; H: Schalenfrüchte; N: Weichtiere; Z: Erdnüsse <br><br>
		* Dönerfleisch = Drehspieß aus fein zerkleinertem Kalb- und Rinderfleisch, Soja
</div>

<footer>
    <p>&copy; 2026 Basti Pizzaservice Rheine • Catenhorner Straße 2 • 48431 Rheine</p>
</footer>

</body>
</html>
