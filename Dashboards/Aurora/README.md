<span>Aurora Guide</span></h3>
							
							<div class="messageBody">
																<div id="postText456804">
									Hier wie versprochen der kleine Anleitungsthread zu Aurora, welches letzte Woche von ehemaligen TeamFSD Mitglieder veröffentlicht wurde.<br>
<br>
<div style="text-align: center"><img src="http://xboxunity.net/Resources/Images/RMS.Front.Page.Aurora.By.Phoenix.png" class="resizeImage" alt=""></div><br>
<br>
<div style="text-align: center">Bei Aurora handelt es sich wie beim FSD und XexMenu um ein weiteres, alternatives Dashboard für JTAG/Glitch Xbox 360 Konsolen. Es ist gut strukturiert aufgebaut, leicht zu bedienen und bietet ein paar neue grafische Aspekte zum FreeStyleDash.<br>
<br>
Aurora ist ein „etwas anderes FSD“, welches teils unnütze Einstellungen weg lässt, sich aber durch die neue, etwas andere Bedienung und neuen grafischen Elemente „reifer“ anfühlt. Ein generelles Hauptmenü gibt es in dem Sinne nicht mehr, man befindet sich sofort im Coverflow und kann komplette Einträge wie Homebrew Anwendungen ein-, oder ausblenden. Dazu aber später mehr. Da dieses Dashboard von Grund auf neu geschrieben wurde, konnte es bereits in den früheren Versionen so optimiert werden, dass es schnell und stabil läuft.</div><br>
<br>
<strong><span style="text-decoration: line-through"><span class="yellowBox"><span style="text-decoration: underline">Funktionen im Kurzüberblick:</span></span></span></strong><br>
<br>
*direkter Start in die Coverflow Ansicht<br>
*verschiedene, vor allem neue Coverflow Ansichten<br>
*es gibt eine Schnellsuche Funktion<br>
*neue Gamedetails können angezeigt werden<br>
*lokaler Support für Übersetzungsdateien<br>
*Sortierungs- und Filteroptionen<br>
*Kompatibel zum Freestyle Plugin (LiNK), sowie zur neuen Unity Webseite<br>
<br>
<div style="text-align: center"><object width="640" height="400"><param name="movie" value="http://www.youtube.com/v/BLa9QOtJ9_o?controls=1?version=3&amp;hl=de"><param name="allowFullScreen" value="true"><param name="allowscriptaccess" value="always"><embed src="http://www.youtube.com/v/BLa9QOtJ9_o?controls=1?version=3&amp;hl=de" "="" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" width="640" height="400"></object><br><a href="http://www.youtube.com/watch?v=BLa9QOtJ9_o">http://www.youtube.com/watch?v=BLa9QOtJ9_o</a></div><br>
<br>
<div style="text-align: center"><strong><span style="text-decoration: underline"><span class="yellowBox">Installation Aurora</span></span></strong><br>
<br>
Nachdem man sich das Paket (am Besten immer die aktuellste Version) <a href="http://www.xboxhacks.de/aurora_0_1a_by_phoenix.t58774.html" class="externalURL">hier</a> heruntergeladen hat, entpackt man dieses und bekommt einen Ordner mit dem Namen Aurora (Versionsnummer). Sicherlich hat jeder Benutzer einer JTAG/Glitch Box das XexMenu, oder FreeStyleDash installiert und sich einen Ordner für Applications, beziehungsweise Homebrew erstellt. Genau in diesen Ordner kopiert man nun den oben genannten Ordner Aurora. Gestartet wird die Anwendung dann über die aurora.xex. Das war es eigentlich schon mit der normanen Installation auf einem Speichermedium.<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Wie funktioniert der Autoboot ins Aurora?</span></span></strong><br>
<br>
Genau wie beim FSD wird dies über Dash Launch bewerkstelligt. Ich verweise nun aber im Grunde auf den <a href="http://www.xboxhacks.de/freestyledash_2_0_rc_2_2_fsd3_0_guide_inklusive_link_tutorial_update_20_08_2013.t38838.html" class="externalURL">FSD Guide</a>, da dies hier nichts anderes ist. Einfach in DL den Pfad zur aurora.xex angeben, per RB in den Speichern/Laden Tab wechseln, ein Speichermedium auswählen und mit X die launch.ini im angegebenen Verzeichnis speichern. Da sich der Autoboot auf eine Anwendung beschränkt, sollte man sich daher die anderen alternativen Dashboards auf verschiedene Tasten legen, oder später aus der gestarteten Oberfläche anwählen.<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Wie komme ich nach Einstellung des Autoboots in Aurora mithilfe Dash Launch ins NXE und wie kann man es aus dem NXE heraus starten?</span></span></strong><br>
<br>
Dazu betätigt man den Xbox Guide Button, drückt Y--&gt;JA--&gt;und hält RB gedrückt. Oder man geht den kleinen Umweg, auch über das Miniblade--&gt;Systemeinstellungen, dann befindet man sich auch im NXE, um zum Beispiel Speicher, oder Netzwerkeinstellungen vorzunehmen. Der Dash Launch Parameter "nosysexit" muss dann aber deaktiviert sein. Zudem kann man sich mithilfe der Programme <a href="http://www.xboxhacks.de/shortcut360_v1_1_7.t36517.html?highlight=shortcut" class="externalURL">Shortcut360</a> und <a href="http://www.xboxhacks.de/quickboot_v2_0_v2_1.t2596.html" class="externalURL">QuickBoot</a> eine Verknüpfung zu Aurora anlegen und diese im NXE unter "Meine Spiele" oder in der "Spiele Bibliothek" heraus starten.<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Einstieg und Konfiguration von Aurora</span></span></strong><br>
<br>
Bitte lest Euch den kompletten Absatz durch, um nicht durcheinander zukommen. <br>
<br>
Beim ersten Start von Aurora sieht man außer der Navigationsleiste unten erst mal nichts, man muss wie beim FSD die Pfade angeben, um Spiele, XBLA, Homebrew Anwendungen und so weiter aufgelistet zu bekommen. Bevor wir aber zu dem Hinzufügen der Pfade kommen, machen wir einen kleinen Abstecher in den Einstellungsmenüpunkt Xbox Marktplatz, welchen man über die Start Taste auf den Controller für Einstellungen findet. Hier solltet ihr nun idealerweise die Marktplatz Region auf Germany stellen, um die Spielbeschreibungen auf Deutsch zu erhalten. Diese Einstellung solltet Ihr UNBEDINGT vor den Pfad Einstellungen machen! Screenshots, oder Hintergründe können auch später nachgeladen werden, indem man das kleine Kästchen links neben den Eintrag anwählt und unten Herunterladen fehlender "Assets“ drückt. Wie bekannt sollte der<em> Dash Launch Parameter livestrong deaktiviert</em> sein, damit Cover, ect heruntergeladen werden.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild7assetsodj44.png"><img src="http://abload.de/img/bild7assetsodj44.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Nun kommen wir zu den Pfaden, dazu drückt man die Start Taste für Einstellungen und navigiert zu dem Unterpunkt Pfade verwalten.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild1pfade1bqjko.png"><img src="http://abload.de/img/bild1pfade1bqjko.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Drückt die Schaltfläche „Hinzufügen“, danach „Ändern“ und wählt mithilfe der A Taste das Speichermedium aus und mit der Y Taste dann den Ordner, in denen sich zum Beispiel Eure Xbox360 Games befinden.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild2pfade2zaqty.png"><img src="http://abload.de/img/bild2pfade2zaqty.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<a class="externalURL" href="http://abload.de/img/bild3pfade3imrhe.png"><img src="http://abload.de/img/bild3pfade3imrhe.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<a class="externalURL" href="http://abload.de/img/bild4pfade4frqew.png"><img src="http://abload.de/img/bild4pfade4frqew.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Der Pfad wird dann angezeigt und Ihr könnt diesen über „Speichern“ unten rechts sichern. Zuvor müsst Ihr aber je nach Eurer Ordner Struktur noch die Scantiefe anpassen, der Standardwert beträgt 2. Es wird mit der Indexierung nach relevanten Dateien ab den Ordner angefangen, welcher vorher eingestellt wurde.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild5pfade55vso2.png"><img src="http://abload.de/img/bild5pfade55vso2.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Wenn die automatische Scan Einstellung aktiviert ist, wird nun der angegebene Ordner durchsucht und die Spielen werden aufgelistet. Sollte die Automatische Scan Option deaktiviert sein, kann über „Jetzt scannen“ manuell gesucht werden.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild6pfadescans0r3g.png"><img src="http://abload.de/img/bild6pfadescans0r3g.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Geht man aus den Einstellungen raus, werden nun die Einträge aus den angegebenen Ordner(n) aufgelistet. In meinen Fall sind es jetzt mal die Applications. Bei jedem weiteren Pfad werden dann die Einträge hinzugefügt.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild8ersteansichtq9kjs.png"><img src="http://abload.de/img/bild8ersteansichtq9kjs.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Nun werden welche sagen: „Mann, jetzt wird alles durcheinander angezeigt, Xbox360 Spiele, Emulatoren, XBLA, Homebrew, usw“ HALT! Wie ich bereits am Anfang des Threads erwähnt habe, gibt es eine umfangreiche Filterfunktion, sowie Sortiereinstellungen, welche ich im nächsten Punkt erläutere.<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Filter- und Sortiereinstellungen in Aurora</span></span></strong><br>
<br>
In diesem Kapitel geht es ausschließlich um die Filter und Sortiereinstellungen, welche mit Aurora neu hinzugekommen sind. Um die Option aufzurufen müsst Ihr die B Taste für „Ansicht“ drücken, nun befindet Ihr Euch in diesem Menü. Nachfolgend werden dann die anderen Ansichtsoptionen chronologisch in weiteren Kapiteln durchleuchtet.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild9filterundsortierwvplj.png"><img src="http://abload.de/img/bild9filterundsortierwvplj.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Schauen wir uns erst mal auf der linken Seite die Filtereinstellungen an, danach geht es auf der rechten Seite mit den Sortiereinstellungen weiter.<br>
<br>
Mit einstellen von Filter(n) kann man sich bestimmte und ausgewählte Einträge anzeigen lassen, sei es Xbox360 Games, Homebrew Anwendungen, oder dergleichen. Möchte man wie ich jetzt nun nur Xbox360 Games angezeigt bekommen, muss man unter „Filter“ jene Funktionen anklicken Xbox360 (Bild oben). Die Filtereinstellungen reichen soweit, dass man sogar einzelne Genre nur auswählen kann, oder über den Ordner „Misc“ nur Spiele, welche Link kompatibel sind. Alle Filter lassen sich mit einen Klick wieder zurücksetzen. Nachfolgend 3 Bilder zu den hier zuletzt Geschriebenen.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild11filtermkjgi.png"><img src="http://abload.de/img/bild11filtermkjgi.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<a class="externalURL" href="http://abload.de/img/bild12filtermisclinkpfrnu.png"><img src="http://abload.de/img/bild12filtermisclinkpfrnu.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<a class="externalURL" href="http://abload.de/img/bild13filtermisclinksbykxn.png"><img src="http://abload.de/img/bild13filtermisclinksbykxn.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Nun kurz noch zu den Sortiereinstellungen. Wenn wir nun auf die Schaltfläche unter "Sortierung" gehen, können wir die anzeigende Spiele, Anwendungen, usw. nach Entwickler, Hersteller, zuletzt hinzugefügt (Bild unten) und Namen ordnen. Zudem kann eingestellt werden, ob die Einträge aufsteigend, oder absteigend der eingestellten Option angezeigt werden soll.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild10filterundsortie1ws49.png"><img src="http://abload.de/img/bild10filterundsortie1ws49.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Unter Option--&gt;Nur Favoriten können Einträge angezeigt werden lassen, welche man zu den Favoriten hinzugefügt hat. Zudem können versteckte Einträge über „Zeige versteckte Titel“ wieder sichtbar gemacht werden. Wie man Favoriten einstellen und Spiele verstecken kann, erkläre ich weiter unten im Kapitel „Die Spiele Detail Taste Y“.<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Schnellansichtfunktion in Aurora</span></span></strong><br>
<br>
Eine gute und unscheinbare Funktion bietet die Schnellansicht in Aurora, welches ein schnelles Wechseln zwischen den einzelnen Kategorien, sei es Emulatoren, Xbox 360 Spiele und so weiter ermöglicht. Diese Funktion hatte mir in Aurora gefehlt, sodass dieser Vorschlag zwischen verschiedenen Kategorien per Knopfdruck über die Schultertasten RB und LB am Controller wechseln zu können über ein Mitglied hier im Forum an das an Aurora arbeitende Team weitergeben und zum Glück eingebaut wurde! Zusätzlich können neben den schon verfügbaren Kategorien weitere erstellt werden, zum Beispiel eine nur LiNK kompatible Spiele Kategorie, zudem ich ein Stückchen weiter unter ein Beispiel habe.<br>
<br>
Wieder gelangt man per B Taste in die "Ansicht" Einstellungen, sodass man sich nachdem man auf Schnellansicht geht im folgenden Hauptfenster sich befindet.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild14schnellansichtb7dpwl.png"><img src="http://abload.de/img/bild14schnellansichtb7dpwl.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Wir kümmern uns erst mal um den Punkt "Liste bearbeiten" <br>
<br>
<a class="externalURL" href="http://abload.de/img/bild15schnellansichtl2sjvy.png"><img src="http://abload.de/img/bild15schnellansichtl2sjvy.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Hier sieht man nun alle Kategorien im späteren Auswahlmenü der Schnellansicht. Eine Kategorie lässt sich als Standard einstellen, diese wird dann beim Start von Aurora angezeigt. Per X können wiederum Kategorien deaktivieren, sodass diese später auch nicht ausgewählt werden können, bei gedrückter Y Taste lassen sie sich in der Reihenfolge verschieben. Das war es eigentlich schon im Punkt "Liste bearbeiten", nun zum Hinzufügen einer neuen Kategorie/Schnellansicht. Wir befinden und nun im folgenden Fenster:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild16schnellansichte9aj1h.png"><img src="http://abload.de/img/bild16schnellansichte9aj1h.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Wie oben erwähnt erstellte ich mir eine neue Kategorie, welche nur Spiele anzeigen soll, welche LiNK kompatibel sind. Man geht auf Schnellansicht, welches standardmäßig bei einer Erstellung da steht und vergibt den Namen. Nun kann man sich per Icon ändern ein passendes Bild, welches hier im Beispiel glücklicherweise schon vorhanden ist auswählen. Über ein Optionsmenü können anders farbige Icons ausgewählt, oder neue hinzugefügt werden. Unter Filter hinzufügen befinden man sich nun hier, wo man Befehle und Filter unterscheidet:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild165schnellansichtdmx7q.png"><img src="http://abload.de/img/bild165schnellansichtdmx7q.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Unter Befehle können verschiedene Kriterien angegeben werden, sodass zum Beispiel Xbox 360 Spiele und/oder auch XBLA, welche LiNK unterstützen zusammengefasst und ausgegeben werden (Die Befehle beschreibe ich in naher Zukunft mal noch etwas genauer, denn hier kann man viele Spielereien einstellen). Lassen wir dies mal außen vor und widmen uns weiter dem Filter in der erstellenden Kategorie.<br>
<br>
Wir geben nun an, dass der Filter "LiNK supported" Spiele in der Kategorie zusammenfassen soll. Über Filter--&gt;Ordner Misc--&gt;LiNK Supported wird dies erreicht. Nachdem dies geschehen ist, sollte es auch bei Euch wie auf den folgendem Bild ausschauen:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild17schnellansichte6iqlv.png"><img src="http://abload.de/img/bild17schnellansichte6iqlv.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Ein Klick auf Speichern und die Kategorie wurde erstellt. Wie sieht diese Schnellansicht eigentlich aus? Bisher nur darüber geschrieben, gibt es sie nun auf dem folgenden Bild auch zu sehen:<br>
<br>
<a class="externalURL" href="http://abload.de/img/schnellansichtmeny2r2x.png"><img src="http://abload.de/img/schnellansichtmeny2r2x.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Über RB und LB kann man zwischen den einzelnen Kategorien wie bereits geschrieben wechseln. Dabei gibt es auch die Option, per X alle Kategorien anzeigen zu lassen. <br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Kann man weitere Skins verwenden, oder das Haupthintergrundbild in Aurora ändern? Und wie sieht es eigentlich mit dem Coverflow aus?</span></span></strong><br>
<br>
Beschäftigen wir uns erst mal mit dem "Ansichtsreiter Theme", welches den Coverflow und den Hintergrund betrifft.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild18reitertheme9sltl.png"><img src="http://abload.de/img/bild18reitertheme9sltl.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Unter Cover Layout lässt sich unter einer Vielzahl von bereits vorhandenen Anzeigelayouts auswählen, was die Cover der anzuzeigenden Dateien betrifft. Man kann aber auch selber Cover Layouts erstellen, oder bereits von anderen Usern Erstellte Aurora hinzufügen. Die Cover Layout Endung heißt Name<span style="color: #ff0000">.cfljson</span>. Neue Layouts werden über das Verzeichnis Aurora/Media/Layouts hinzugefügt. Ich hab dies bereits getan, sodass ich aus über 30 verschiedene Anzeigelayouts auswählen kann. In der Folge zwei Bilder dazu:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild33coverlayoutiponj.png"><img src="http://abload.de/img/bild33coverlayoutiponj.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<a class="externalURL" href="http://abload.de/img/bild34coverlayoutansi6co13.png"><img src="http://abload.de/img/bild34coverlayoutansi6co13.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<strong><em>Diese und weitere Coverlayouts gibt es <a href="http://www.realmodscene.com/index.php?/topic/5376-cfl-focuscircle-more-18-layouts-fixfinal-version240515/" class="externalURL">hier</a></em></strong><br>
<br>
Das Hintergrundbild kann geändert werden, indem man ausgewählte Bilder in den Ordner "Background" im Hauptverzeichnis von Aurora einfügt (diesen Ordner gibt es bei den ersten Versionen von Aurora noch nicht und wird auch nicht automatisch nach einem Update angelegt, man kann diesen aber bei Vorhandensein einer aktuellen Version erstellen). Dabei werden folgende Dateitypen unterstützt: <span style="color: #ff0000">.png;.jpg;.bmp;.dds</span>.<br>
<br>
<a class="externalURL" href="http://abload.de/img/backgrounddeqlb.png"><img src="http://abload.de/img/backgrounddeqlb.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
In diesem Kapitel geht es auch um Skins. Um zwischen mehreren Solcher auswählen zu können, müssen weitere Skins in das Skin Verzeichnis von Aurora hinterlegt werden. Dieses Verzeichnis findet man im Hauptverzeichnis. Die Aurora Skins haben die Endung .xzp. Im Reiter Skin geht es nun auf Ändern, sodass man dann aus verschiedenen Skins auswählen kann:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild19reiterskinydux5.png"><img src="http://abload.de/img/bild19reiterskinydux5.png" class="resizeImage" alt="" width="650" height="366"></a><br>
  <br>
<a class="externalURL" href="http://abload.de/img/bild20skinauswahl9auqq.png"><img src="http://abload.de/img/bild20skinauswahl9auqq.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Nach einem erforderlichen Neustart wird nun der neue Skin angezeigt. Im nachfolgenden Spoiler gibt es eine kleine Auswahl an aktuellen Skins:<br>
<br>
<br>

<div class="quoteBox spoiler jsSpoiler">
	<div class="quoteHeader container-4">
		<h3>
							<img src="wcf/icon/warningS.png" alt="Spoiler">
				Spoiler
					</h3>
	</div>
	<div class="quoteBody container-4" style="">
		<a class="externalURL" href="http://i61.tinypic.com/344bksx.jpg"><img src="http://i61.tinypic.com/344bksx.jpg" class="resizeImage" alt="" width="650" height="170"></a><br>
<br>
<a class="externalURL" href="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-35264000-1418902465.jpg"><img src="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-35264000-1418902465.jpg" class="resizeImage" alt="" width="650" height="366"></a><br>
<a class="externalURL" href="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-00475100-1418902474.jpg"><img src="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-00475100-1418902474.jpg" class="resizeImage" alt="" width="650" height="366"></a><br>
<a class="externalURL" href="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-09569100-1418902481.jpg"><img src="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-09569100-1418902481.jpg" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<blockquote class="quoteBox container-4">
	<div class="quoteHeader">
		<h3><img src="wcf/icon/quoteS.png" alt="">
					Zitat				</h3>
	</div>
	<div class="quoteBody">
		<span style="text-decoration: underline">Features</span><br>
<br>
-You can use RB\LB to navigate to right\left,most quickly;<br>
- Dark ambient based on carbon wallpaper and orange details;<br>
- Menu animation: when you open menu,carbon's background divided it into two parts,<br>
first go down and second go up and vice versa if you close it;<br>
- New menu's icon;<br>
- Skin updated for Aurora 0.5b!	</div>
</blockquote><br>
<br>
<strong><span style="color: #ff0000">Download:</span></strong> <a href="https://www.xboxhacks.de/index.php?page=Attachment&amp;attachmentID=59808">DarkSide0.5b.xzp.rar</a><br>
<br>
<br>
<a class="externalURL" href="http://i61.tinypic.com/xt55y.jpg"><img src="http://i61.tinypic.com/xt55y.jpg" class="resizeImage" alt="" width="650" height="170"></a><br>
<br>
<a class="externalURL" href="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-08674200-1418902864.jpg"><img src="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-08674200-1418902864.jpg" class="resizeImage" alt="" width="650" height="366"></a><br>
<a class="externalURL" href="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-63671600-1418902869.jpg"><img src="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-63671600-1418902869.jpg" class="resizeImage" alt="" width="650" height="366"></a><br>
<a class="externalURL" href="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-25938400-1418902889.jpg"><img src="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-25938400-1418902889.jpg" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<blockquote class="quoteBox container-4">
	<div class="quoteHeader">
		<h3><img src="wcf/icon/quoteS.png" alt="">
					Zitat				</h3>
	</div>
	<div class="quoteBody">
		<span style="text-decoration: underline">Features</span><br>
<br>
-You can use RB\LB to navigate to right\left,most quickly;<br>
- Wrap list into details menu and settings\view;<br>
- Slim main menu and dark buttons;<br>
- Orange buttons and white vertors's menu;<br>
-New menu's icons:<br>
-Move up "save\delete" buttons into paths menu,to make selection faster;<br>
- Correct "Altro"(more) in details menu (gameoptions);<br>
- Fix some bugs into settings menu;<br>
<br>
- Some option's icons are changed;<br>
<br>
- Fixed path list in settings.	</div>
</blockquote><br>
<br>
<strong><span style="color: #ff0000">Download:</span></strong> <a href="https://www.xboxhacks.de/index.php?page=Attachment&amp;attachmentID=59809">Paradise0.5b.xzp.rar</a><br>
<br>
<br>
<a class="externalURL" href="http://i57.tinypic.com/2houz41.jpg"><img src="http://i57.tinypic.com/2houz41.jpg" class="resizeImage" alt="" width="650" height="170"></a><br>
<br>
<a class="externalURL" href="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-69918200-1418904075.jpg"><img src="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-69918200-1418904075.jpg" class="resizeImage" alt="" width="650" height="366"></a><br>
<a class="externalURL" href="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-27063800-1418904081.jpg"><img src="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-27063800-1418904081.jpg" class="resizeImage" alt="" width="650" height="366"></a><br>
<a class="externalURL" href="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-25278000-1418904087.jpg"><img src="http://www.realmodscene.com/uploads/monthly_12_2014/post-281-0-25278000-1418904087.jpg" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<blockquote class="quoteBox container-4">
	<div class="quoteHeader">
		<h3><img src="wcf/icon/quoteS.png" alt="">
					Zitat				</h3>
	</div>
	<div class="quoteBody">
		<span style="text-decoration: underline">Features</span><br>
<br>
<br>
- Fixs bugs "more"(altro) in details;<br>
- New setting's icons and buttons;<br>
- New select path in settings;<br>
- New hexagon fond when open menu and add an animation:hexagon come to life<br>
(thanks to MaX7o);<br>
- Add mask to background so you can change background without loosing crysis atmosphere and you can apply animation with a great effect(look at image below:view's menu).<br>
<br>
 <br>
***NEW***<br>
<br>
- Fix 2 in path menu when select new\modify path;<br>
- Fix white text in simple buttons;<br>
- Improved animations when open menu;<br>
- Fix bug into settings menu;<br>
- Added Crysis style to notification popup ( ex. when select language );<br>
- Added hex animation,like into menu, as alternative background;<br>
- Fix minor bugs.<br>
<br>
	</div>
</blockquote><br>
<br>
<strong><span style="color: #ff0000">Download:</span></strong> <a href="https://www.xboxhacks.de/index.php?page=Attachment&amp;attachmentID=59810">Crysis0.5b.xzp.rar</a><br>
<br>
<strong>Quelle:</strong> <a href="http://www.realmodscene.com/index.php?/topic/4596-skin-darkside05b-paradise05b-crisis05b-rev2-190515/" class="externalURL">realmodscene.com</a><br>
<br>
	</div>
</div><br>
<br>
<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">„Die Spiele Detail Taste Y“</span></span></strong><br>
<br>
Mithilfe der Y Taste kommt nun in ein Menü, indem Ihr zu jeden Spiel Details erfahrt und Einstellungen vornehmen könnt. <br>
<br>
<a class="externalURL" href="http://abload.de/img/bild13favaqzlu.png"><img src="http://abload.de/img/bild13favaqzlu.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Ich erörtere an dieser Stelle nicht alle Punkte, weil alle eigentlich mehr, oder weniger selbsterklärend sind. Aber Ich wollte ja erklären, wie man Spiele zu den Favoriten hinzugefügt. Dazu drückt auf den Stern und dieser verfärbt sich von grün in orange, zudem ziert die Spiele Hülle eine orangene Umrandung (es gibt noch eine weitere Möglichkeit, dies einzustellen, dazu den Punkt "Was ist diese Schnellsuche Option?" lesen! anschauen). Wie oben erwähnt können nur die Favoriten angezeigt werden, wenn man dies möchte. Und wie verstecke ich Spiele? Dazu auf das letzte Icon gehen, einmal nach links klicken und bekommt bei der A Taste die Option „Verstecken“ angezeigt.<br>
<br>
Die anderen Symbole stehen für Archievements, Title Updates, oder zum Starten des Spiels.<br>
Unten wird Euch ja eine kleine Legende angezeigt, welches Symbol was bewirkt. Vergesst daher auch nicht, dass man via Steuerkreuz, oder Analog Stick mit einem Klick nach links weitere Symbole erscheinen. Die Title Update Funktion stelle ich im nächsten Punkt kurz noch vor.<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Title Updates unter Aurora managen</span></span></strong><br>
<br>
Title Updates bezieht Aurora von der neu angelegten Webseite XboxUnity.net, welche Title Updates, Custom Cover und Link vereint. Sie ersetzt jqe360.com. Um Title Updates nutzen zu können, müssen FSD Nutzer auf Aurora umsteigen.<br>
<br>
Wir befinden uns auf dieses Symbol:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild14tu1u3k48.png"><img src="http://abload.de/img/bild14tu1u3k48.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Unter Installiert werden die derzeit sich auf der Konsole befinden Title Updates angezeigt. Mit A kann man es de- und aktivieren, per X löscht man es.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild15tu23lko9.png"><img src="http://abload.de/img/bild15tu23lko9.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Im Punkt Unity Marktplatz werden alle verfügbaren Updates angezeigt, per A kann das jeweilige Update heruntergeladen werden (höchste, zuletzt erschienene Version reicht aus), per X kann wird die Liste aktualisiert und per Y kann man das Speichermedium auswählen.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild16tu39iu3c.png"><img src="http://abload.de/img/bild16tu39iu3c.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Wie sieht es mit LiNK unter Aurora aus?</span></span></strong><br>
<br>
Anmerkung: Dieser Absatz wird später nochmal leicht verändert, da es in der Oberfläche einen kleinen Anzeigefehler gibt. Zudem verweise ich auf den FSD Guide, da es viele Parallelen gibt im Bezug auf LiNK!<br>
<br>
Um LiNK unter Aurora nutzen zu können, müsst Ihr erst mal schauen, ob der Account noch gültig ist, welchen Ihr früher für jqe360 angelegt habt. Ich musste mir ein neues Passwort zukommen lassen, damit ich mich einloggen konnte, beziehungsweise mein Account erst mal erkannt wurde. Die zweite Möglichkeit wäre natürlich, sich einfach einen frischen Accout anzulegen. Dies geht über <a href="http://xboxunity.net/" class="externalURL">xboxunity.net</a>.<br>
<br>
Zu erst müssen wir wie beim FSD das Unity Konto in den Einstellungen angeben.<br>
Dazu geht in die Einstellungen unter Unity--&gt;Verbindung und gebt euren Benutzername in das dafür vorgesehene Fenster an. In dieser Übersicht gibt es nun einen Anzeigefehler! Das Passwort müsst Ihr erst mal unter API in der Schaltfläche Anfordern eingeben. Somit wird das Konto in Aurora verifiziert (Bild unten).<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild27unitylinkklsnx.png"><img src="http://abload.de/img/bild27unitylinkklsnx.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Nun geht man in den Einstellungen zu Plugin:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild28pluginlinkd5ku4.png"><img src="http://abload.de/img/bild28pluginlinkd5ku4.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Hier muss erst mal kontrolliert werden ob LiNK aktiviert ist. Sollte dies der Fall sein, vergibt man den Daten Port und den Broadcast Port. In meinen Fall hab ich die vorgegebenen Ports verwendet. Wenn der Router UPNP unterstützt, kann diese Option gleich aktiviert werden. So müssen im Normalfall keine weiteren Einstellungen am Router vorgenommen werden. Trotz der UPNP Funktion kann es vorkommen, dass die Ports manuell bearbeiten werden müssen. Deaktiviert nun am Besten die "UPNP" Funktion in der Plugin Übersicht, da es sonst zu Problemen beim Beitreten bereits erstellter Spielen kommen kann, wenn diese noch aktiviert ist (man sieht die erstellen Spiele, kann diese aber nicht beitreten). <br>
<br>
Ansonsten müssen die vergebenen Ports dementsprechend ohne UPNP Funktion manuell weitergeleitet/ gegebenenfalls geöffnet werden. Man trägt unter TCP und UDP dieselben Ports ein in der jeweiligen Regel! Man hat also zwei Netzwerkregeln zu erstellen, eine je Port! Wie man diese Einstellungen im Konfigurationsmenü des Router vornimmt, kann entsprechenden Internetseiten und Bedienungsanleitungen entnommen werden. Nun kontrollieren wir, ob der Dash Launch Netzwerk Parameter <span style="color: #ff0000">devlink</span> deaktiviert und der <span style="color: #ff0000">Ping Patch</span> Parameter aktiviert ist. Nachdem dies geschehen ist, klickt man auf "Testen".<br>
<br>
Jetzt öffnet sich ein neues Fenster, in welchem die Einstellungen auf Richtigkeit überprüft werden. Sollte bis auf UPNP (je nach Benutzung) überall ein grünes Häkchen und Pass erscheinen, funktioniert LiNK.<br>
<br>
Nun, wie geht es jetzt weiter? Wie wir wissen, kann ein Filter eingestellt werden, welcher nur LiNK kompatible Spiele anzeigt. Jetzt starten wir ein solches Spiel und gehen über das Mini Blade (Xbox Guide Button drücken) in das System Link Menü. Hier kann man einem bereits offenen Raum beitreten, oder einen Solchen selber erstellen. Denkt daran, entweder das gleiche, oder immer aktuellste TU zu benutzen!<br>
<br>
Nun verweise ich wieder auf den <a href="http://www.xboxhacks.de/freestyledash_2_0_rc_2_2_fsd3_0_guide_inklusive_link_tutorial_update_20_08_2013.t38838.html" class="externalURL"><strong><span style="color: #ff0000"><span style="font-size: 12pt">FSD Guide</span></span></strong></a>, da dort die weiteren System Link Einstellungen ausführlich erklärt worden. <br>
<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Wie funktioniert ein Update über die Aurora Oberfläche?</span></span></strong><br>
<br>
Entweder wird beim Start eine Information angezeigt, oder Ihr geht in die Einstellungen zu den Punkt "Über/About"<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild22updatebersichtbbj8q.png"><img src="http://abload.de/img/bild22updatebersichtbbj8q.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Hier müsste bei einem Update unter Updater aber "Neue Version verfügbar" stehen. Nun klickt Ihr die Download Schaltfläche an und der Download des Updates beginnt. Man sieht eine Anzeige, welche den Fortschritt des Downloads anzeigt:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild21update2ohk2g.png"><img src="http://abload.de/img/bild21update2ohk2g.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Danach wird das Update extrahiert. Dann öffnet sich ein Fenster, wo angezeigt wird, dass das Update erfolgreich heruntergeladen wurde. Nun kann man das Update installieren, indem man auf „Update“ drückt.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild22update3dgyhj.png"><img src="http://abload.de/img/bild22update3dgyhj.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Jetzt erschient diese Ansicht (Bild unten), wo man A fürs Update drücken kann, oder mit B den Installer verlässt.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild23update40yx7w.png"><img src="http://abload.de/img/bild23update40yx7w.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Auch hier gibt es wieder eine Fortschritt Anzeige:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild24update5o5r5u.png"><img src="http://abload.de/img/bild24update5o5r5u.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Wenn der Vorgang beendet wird, startet Aurora neu.<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Was ist diese Schnellsuche Option?</span></span></strong><br>
<br>
Wenn ihr die X Taste drückt sollte dieses Fenster erscheinen:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild23schnellsucheydsit.png"><img src="http://abload.de/img/bild23schnellsucheydsit.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Es handelt sich hierbei um eine Art „Schnellauswahlmenü“, wobei man mithilfe der A Taste sofort zum Eintrag im Coverflow gelangt, per X man nach Titeln suchen und mit Y das mit einem grünen Streifen unterlegte Spiel als Favorit an-, oder abwählen kann. <br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Kann ich mit Aurora die erweiterte WebUI Oberfläche aufrufen?</span></span></strong><br>
<br>
Natürlich! Denn wie erwähnt unterstützt es das Freestyle Plugin (LiNK). Dieses muss aber aktiviert sein, was es im Normalfall auch standardmäßig ist! Man gibt dazu die IP Adresse (Select für Information, hier kann die IP Adresse abgelesen werden) im Internetbrowser auf dem Rechner ein und führt die Adresse mit :9999 fort. Dabei kann diese Oberfläche unabhängig davon, wo man sich gerade befindet, aufgerufen werden (zum Beispiel auch im NXE). Die Anmeldedaten für Benutzername und Passwort lauten „xboxhttp“, welche man unter den Einstellungen--&gt; Server einsehen und ändern kann. Das gilt auch für das FTP.<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild24serverftpbask9.png"><img src="http://abload.de/img/bild24serverftpbask9.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Nun befindet man sich direkt im Reiter Game. Ist gerade kein Spiel gestartet, werden auch keine Infos angezeigt, sondern nur über das aktuelle laufende Dashboard. Ich verweise ab hier auf den <a href="http://www.xboxhacks.de/freestyledash_2_0_rc_2_2_fsd3_0_guide_inklusive_link_tutorial_update_20_08_2013.t38838.html" class="externalURL">FSD Guide</a>, weil ich dort weitere Informationen bereits angegeben habe.<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Kann man Screenshots erstellen?</span></span></strong><br>
<br>
Aber sicher! Dies geschieht durch die erweiterte Screenshot Funktion Kombi unter Einstellungen--&gt;Plugin, welche aktiviert und deaktiviert werden kann. Start für den „Activator“ und Select für den "Auslöser". Die Tastenkombination kann auch anderweitig lauten. Die erstellten Screenshots können in der erweiterten Weboberfläche eingesehen werden, wenn man unter Notes--&gt;Screen Captures rechts den Aktualisierungsbutton drückt. Dann wird die Liste aktualisiert und das zuletzt erscheinende Bild wird angezeigt.<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Wie bekommt man Aurora auf Deutsch?</span></span></strong><br>
<br>
Benutzt einfach immer die neueste Version von Aurora. Unter Einstellungen--&gt;Sprache befindet man sich im folgenden Fenster:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild25sprache2rjxn.png"><img src="http://abload.de/img/bild25sprache2rjxn.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Mit einen Klick auf Ändern kann man nun aus verschiedenen Sprachen auswählen:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild26sprache2xpjnz.png"><img src="http://abload.de/img/bild26sprache2xpjnz.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Nachdem eine Sprache ausgewählt wurde, bedarf es einen Neustart des Dashboards. Je nach Spracheinstellung der Konsole ändert sich auch die Sprache in der Aurora Oberfläche. <br>
<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Dateimanager</span></span></strong><br>
<br>
Mit einer zuletzt erschienenen Aurora Version wurde der für viele User hilfreiche Dateimanager eingebaut. Diesen findet man unter System/Werkzeuge:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild29systembersicht4rxtf.png"><img src="http://abload.de/img/bild29systembersicht4rxtf.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
Nachdem dieser gestartet wurde befindet man sich in der Hauptansicht des Dateimanager, wobei sich dieser im Stammverzeichnis in zwei eigenen Fenster aufteilt (wie auch beim FSD), ein Linkes "L" und ein Rechtes "R", was bei Dateioperationen sicherlich bequem sein kann. Man kann aber genauso gut nur mit einem Fenster arbeiten. Die Funktionen eines Dateimanagers sollte eigentlich jedem klar sein, sodass ich hier nun nicht weiter drauf eingehe. Am linken Rand befinden sich die Optionen, um zum Beispiel ein neues Verzeichnis zu erstellen, Dateien umzubenennen, zu löschen, aber natürlich auch jene Dateien kopieren, ausschneiden, einfügen zu können. Die Controller Tasten sind hierbei natürlich auch belegt, eine Legende unten am Fenster zeigt die aktuelle Funktion an. Wenn man über die Symbole am linken Rand geht, wird auf der A Taste die aktuelle Funktion zum ausgewählten Symbol angegeben. <br>
<br>
Der Dateimanager lässt es zudem zu, mehrere Dateien markieren und in einen anderes Verzeichnis einfügen zu können (Taste X).<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild30dateimanager1ziomr.png"><img src="http://abload.de/img/bild30dateimanager1ziomr.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<a class="externalURL" href="http://abload.de/img/bild31dateimanager2au68pvw.png"><img src="http://abload.de/img/bild31dateimanager2au68pvw.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">HUD Änderung</span></span></strong><br>
<br>
Hierbei hat Dr.Gonzo in <a href="http://www.xboxhacks.de/aurora_nderung_des_hud_freestyle_home_aurora_home.t61983.html" class="externalURL">diesem Thread</a> bereits ein Paket hoch geladen, damit im Miniblade nicht mehr FreeStyle Home, sondern Aurora Home steht. Nebenbei kann auch das Icon ausgetauscht werden. Und genau dies habe ich gemacht, dass das Aurora Icon mit der typischen Farbe türkis/grün hinterlegt ist und bei LiNK dieses in rot erscheint. <br>
<br>
Im Paket befinden sich zwei XUR Dateien, welche ins Verzeichnis Aurora--&gt; Plugins--&gt; HudScene eingefügt werden müssen <span style="color: #ff0000"><strong>(die gleichnamigen Dateien werden beim Einfügen der neuen Dateien überschrieben, sodass es nie verkehrt sein kann, dass man vorher ein Backup der Dateien, oder des ganzen Verzeichnisses erstellt)</strong></span>. Im Paket weiterhin befindet sich ein "images" Ordner, welcher die beiden Icons beinhaltet. Diese Dateien fügt man nun in den "images" Ordner im Verzeichnis Aurora--&gt; Plugins--&gt; HudScene ein. Nun kann man einen Neustart durchführen, oder entlädt/lädt das Plugin. Ist alles erfolgreich von Statten gegangen, sollte es wie auf diesen Bild ausschauen:<br>
<br>
<a class="externalURL" href="http://abload.de/img/bild35nderunghud21rs76.png"><img src="http://abload.de/img/bild35nderunghud21rs76.png" class="resizeImage" alt="" width="650" height="366"></a><br>
<br>
<strong>Download des Paketes:</strong> <a href="https://www.xboxhacks.de/index.php?page=Attachment&amp;attachmentID=59811">Aurora HudScene.rar</a><br>
<br>
<a href="http://www.realmodscene.com/index.php?/topic/5384-enjoy-aurora-get-this-custom-hud-theme-and-post-to-help-support-the-phoenix-dev-team-2-new-versions-july-4/" class="externalURL">Weitere Möglichkeiten und Quelle</a><br>
<br>
<br>
<strong><span style="text-decoration: underline"><span class="yellowBox">Weitere Einstellungsmöglichkeiten im Bereich Settings</span></span></strong><br>
<br>
Uns fehlt unter Einstellungen der Punkt Unity, welcher noch keine Bedeutung von mir bekam. Hier kann der API Key eingetragen werden und der Benutzername, mit dem man sein Benutzerkonto in Aurora verifizieren kann. Das muss man auch tun, um LiNK nutzen können! Zudem muss die Unity Verbindung aktiviert sein! Des Weiteren können dadurch zum Beispiel Custom Cover auf die Box übertragen werden.<br>
<br>
Unter „Plugin“ kann das Freestyle Plugin „entladen“, also deaktiviert werden. Man sieht hier auch die erweiterte Screenshot Kombo Funktion, welche auch deaktiviert werden kann. Rechts geht es um die LiNK Einstellungen, welchen oben erklärt worden.<br>
<br>
<br>
Eine Fehlerliste mit Lösungen zu etwaigen Problemen wird es unter Umständen demnächst noch geben, sofern ich komplexe Fehler ausmache.<br>
<br>
<br>
11.07.2014: Guide online gestellt<br>
23.07.2014: Bilder ausgetauscht, Wörter ergänzt<br>
24.07.2014: LiNK mit eingebracht, Update über Aurora Oberfläche erklärt<br>
04.08.2014: Skin und Hintergrund Wechsel unter Aurora 0.1a.1 eingebracht<br>
16.08.2015: umfangreiches Update des Guide, austauschen von Bildern, Änderungen von Textpassagen,<br>
                     Schnellansicht/Kategorie Funktion eingefügt, Skin, Coverlayout, Sprache, Dateimanager, HUD Änderung<br>
geplant:        Strukturierung verbessern, wenige Sachverhalte ergänzen<br>
<br>
Dieses Tutorial wurde von <a href="http://www.xboxhacks.de/supermario.u12724.html" class="externalURL">SuperMario</a> @ xboxhacks.de verfasst und darf nicht ohne meine weitere Einverständnis verbreitet werden!</div>
