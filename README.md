Projekta apraksts:

      Šajā repozitorijā ir Python skripts, kas izstrādāts, lai veiktu detalizētu eBay meklēšanas rezultātu analīzi attiecībā uz noteiktu preci. Izmantojot Selenium tīmekļa skrāpēšanas iespējas, skripts iegūst vidējās cenas, piemēro statistiskās metodes, lai identificētu izlecošās vērtības, un pieraksta rezultātus Excel failā. Šis projekts kalpo kā praktisks piemērs tīmekļa skrāpēšanas paņēmienu piemērošanai e-komercijas datiem.

Izmantotās Python bibliotēkas:

    Projekts balstās uz šādām Python bibliotēkām:
        Selenium: Izmanto tīmekļa skrāpēšanai un pārlūkprogrammas automatizācijai.
        NumPy: Izmanto skaitliskajām operācijām un procentiļu aprēķiniem.
        openpyxl: izmanto Excel failu apstrādei un analīzes rezultātu glabāšanai.
        datetime: Izmanto pašreizējā datuma iegūšanai.
        time: Izmanto, lai skripta izpildē ieviestu aizkavēšanos.
    Lietošanas iemesli:
        Selenium ir jaudīgs rīks tīmekļa mijiedarbības automatizēšanai, tāpēc tas ir piemērots tīmekļa skrāpēšanas uzdevumiem.
        NumPy vienkāršo statistiskos aprēķinus, kas ir ļoti svarīgi, lai identificētu un apstrādātu izlecošās vērtības.
        openpyxl atvieglo darbības ar Excel failiem, ļaujot uzglabāt un analizēt datus.
        datetime tiek izmantots, lai katram datu ierakstam atzīmētu pašreizējo datumu, tādējādi nodrošinot ierakstu par to, kad analīze tika veikta.
        time tiek izmantots, lai pēc meklēšanas vaicājuma iesniegšanas eBay ieviestu kavēšanos, nodrošinot, ka meklēšanas rezultāti ir ielādēti, pirms tos mēģina nolasīt.

Programmatūras lietošanas metodes:

    Lai izmantotu programmatūru, izpildiet šādas darbības:
        Palaidiet skriptu.
        Pēc pieprasījuma ievadiet vajadzīgā vienuma nosaukumu.
        Novērojiet, kā skripts iegūst eBay meklēšanas rezultātus, aprēķina vidējās cenas un filtrē izlecošās vērtības.
        Rezultāti, ieskaitot pašreizējo datumu un vidējo cenu, tiek ierakstīti Excel failā ar nosaukumu price.xlsx.
