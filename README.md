# Windows ugunsmūris jeb firewall prezentacija - DP4-2 Ģirts Gagainis-Kagainis

## Kas ir firewall un ko tas dara?  
Ugunsmūris ir tīkla drošības ierīce, kas atdala uzticamu iekšējo tīklu no ārējā tīkla, kas tiek uzskatīts par neuzticamu.. Tas regulē ienākošo un izejošo tīkla satiksmi, pamatojoties uz iepriekš iestatītiem drošības noteikumiem. 

Ugunsmūri ir ļoti svarīgi, lai aizsargātu tīklus no neatļautas piekļuves, kaitīgām darbībām un iespējamiem draudiem, un tie var pastāvēt kā aparatūra, programmatūra, programmatūra kā pakalpojums (SaaS) vai publiskais vai privātais (virtuālais) mākonis.

Windows ugunsmūris ir Windows operētājsistēmas automātiski uzstādītais ugunsmūris. 

## Kā ieinstalēt vai atinstalēt Windows ugunsmūri?

Kā jau bija minēts, Windows ugunsmūris ir automātiski ieinstalēts (ar jebkuru Windows OS pēc 2004. gada.)
Windows ugunsmūri ir iespējams tikai atslēgt, pašlaik nav iespējams to pavisam atisntalēt. Uz citām sistēmām nav iespējams ieinstalēt Windows ugunsmūri

## Kā izmantot Windows ugunsmūri?

1) Atveriet Windows ugunsmūra iestatījumus un atveriet sadaļu tīkla aizsardzība, lai skatītu un pārvaldītu ugunsmūra iestatījumus.

2) Noklikšķiniet uz "Atļaut lietotni vai līdzekli, izmantojot Windows Defender ugunsmūri", lai pievienotu izņēmumus konkrētām programmām vai līdzekļiem, kuriem nepieciešama piekļuve tīklam.

3) Varat arī pilnībā atspējot Windows ugunsmūri, izslēdzot to tajos pašos iestatījumos, lai gan tas parasti nav ieteicams drošības apsvērumu dēļ. <br/>

Papildus piemēri:  <br/>

**Programmas interneta piekļuves bloķēšana**<br/>
Scenārijs: Jūs nevēlaties, lai kāda konkrēta spēle vai programma piekļūtu internetam, lai neizraisītu nevajadzīgus drošības draudus vai datu pārraidi.<br/>
Darbības: Atveriet Windows ugunsmūra iestatījumus, dodieties uz sadaļu papildus iestatījumi un atlasiet izejošos noteikumus un izveidojiet jaunu noteikumu, izvēloties opciju programma, pēc tam norādiet konkrētās programmas EXE faila atrašanās vietu, izvēlieties darbību "bloķēt savienojumu", un noslēdziet konfigurāciju, saglabājot izmaiņas un piešķirot noteikumam atbilstošu nosaukumu.

**Noteiktas IP adreses piekļuves bloķēšana**<br/>
Scenārijs: Jūsu uzņēmuma serveris ir saņēmis vairākus kiberuzbrukumus no konkrētas IP adreses, un jums nepieciešams bloķēt visus savienojumus no šī avota.<br/>
Darbības: Atveriet Windows ugunsmūra papildu iestatījumus un izvēlieties sadaļu "ienākošie noteikumi". Izveidojiet jaunu noteikumu, izvēloties opciju "pielāgots noteikums". Tālāk konfigurācijas soļos norādiet, ka šis noteikums attieksies uz visu tīkla trafiku. Pievienojiet bloķēšanas nosacījumu, ievadot konkrēto nevēlamo IP adresi laukā "Attiecināmie avoti". Turpiniet konfigurāciju, norādot, ka šim noteikumam ir jābloķē attiecīgā IP trafiks, un noslēdziet ar noteikuma nosaukuma piešķiršanu, piemēram, "Bloķēt IP 192.168.1.100".

**VPN trafika ļaušana, bloķējot visu citu trafiku**<br/>
Scenārijs: Strādājot publiskajā Wi-Fi tīklā, jūs vēlaties bloķēt visas tiešās tīkla piekļuves, izņemot savienojumu caur jūsu VPN klientu.<br/>
Darbības: Dodieties uz Windows ugunsmūra papildu iestatījumiem un atveriet sadaļu "ienākošie noteikumi". Izveidojiet jaunu noteikumu un izvēlieties, ka tas attiecas tikai uz konkrēto vpn programmu vai tās izmantoto portu. Portu skaitu un specifikāciju var noskaidrot vpn klienta iestatījumos. Pievienojiet arī nosacījumu, kas bloķē visu citu trafiku, izņemot atļauto. Lai to izdarītu, var būt nepieciešams izveidot papildus noteikumu, kas norāda, ka visas pārējās savienojumu piekļuves ir liegta. Saglabā un aizver konfigurāciju, saglabājot izveidoto noteikumu un pārliecinoties, ka vpn darbība tiek pareizi atļauta.

**Portu bloķēšana neautorizētām pieejām**<br/>
Scenārijs: Jūs zināt, ka jūsu tīklā netiek izmantots 21. ports (FTP), un vēlaties to bloķēt, lai novērstu iespējamos uzbrukumus.<br/>
Darbības: Izveidojiet jaunu ienākošo noteikumu un norādiet, ka ports 21 tiek bloķēts visiem ienākošajiem savienojumiem.

**Publiskajā tīklā aizsardzība pret nevēlamām pieejām**<br/>
Scenārijs: Izmantojot klēpjdatoru publiskajā Wi-Fi tīklā, vēlaties pārliecināties, ka citi lietotāji nevar piekļūt jūsu koplietotajiem failiem vai resursiem.<br/>
Darbības: Dodieties uz Windows ugunsmūra iestatījumiem un atrodiet tīkla profilu iestatījumu sadaļu. Pārslēdzieties, uz publiskā tīkla profilu, kas automātiski pielāgo drošības politiku stingrākiem noteikumiem. Iespējojiet opciju, kas bloķē visas ienākošās savienojuma piekļuves, ieskaitot koplietoto resursu piekļuvi, un pārliecinieties, ka ugunsmūris pilnībā kontrolē tīkla trafiku. Pārbaudiet iestatījumu darbību, mēģinot piekļūt koplietošanas resursiem no cita tīkla datora vai ierīces. Papildu drošībai deaktivizējiet resursu koplietošanu pašā sistēmā.

## Praktiski piemēri

Ugunsmūri nodrošina aizsardzību pret ārējiem kiberuzbrucējiem, pasargājot jūsu datoru vai tīklu no ļaunprātīgas vai nevajadzīgas tīkla trafika. Ugunsmūri var arī novērst ļaunprātīgas programmatūras piekļuvi datoram vai tīklam, izmantojot internetu.
