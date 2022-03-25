# Michelangelo-Rezeption
# Ein Netzwerkprojekt am Beispiel der Cascinaschlacht

## Die Netzwerke
Ein Netzwerk der Figuren der Cascinaschlacht und der Bilder, in denen sie vorkommen:
[Netzwerk Figuren](https://tonimassenberg.github.io/Rezeption-Michelangelo/Figuren/)

Ein Stammbaum der Michelangelorezeption:
[Netzwerk Stammbaum](https://tonimassenberg.github.io/Rezeption-Michelangelo/Stammbaum/)

## 1 Einleitung

Michelangelo Buonarotti (1475-1564) hat die Kunst der Frühen Neuzeit maßgeblich geprägt. Eines seiner meistrezipierten Werke war dabei der Karton zur „Schlacht bei Cascina“ von 1504, der, obwohl er nie als Fresko ausgeführt und 1515 zerstört wurde, dank der zahlreichen Kopien und frühen Vervielfältigung durch Druckgraphiken eine große Bekanntheit und Reichweite erlangte. Daher eignet er sich besonders als Beispiel für ein Netzwerkprojekt, das die Zusammenhänge zwischen Werken untersucht, die dieselben Vorbilder rezipieren. Darüber hinaus zeigt die „Cascinaschlacht“ 20 Figuren, die unterschiedlich oft aufgegriffen wurden. Sie bietet sich also an, um zu untersuchen, welche Kriterien eine Figur zu einer beliebten Vorlage machen könnten.
In diesem Projekt wurden Bilder, die im Zusammenhang mit dem zerstörten Karton der „Schlacht bei Cascina“ stehen, in zwei Netzwerkgraphen geordnet. Dazu gehören Werke, die Figuren der „Cascinaschlacht“ rezipieren, aber auch Michelangelos vorbereitende Skizzen. Der [erste Graph (im Folgenden „Figurengraph“)](https://tonimassenberg.github.io/Rezeption-Michelangelo/Figuren/) zeigt alle Bilder in Verbindung mit den Figuren, die darin zu sehen sind. Der [zweite Graph (im Folgenden „Stammbaumgraph“)](https://tonimassenberg.github.io/Rezeption-Michelangelo/Stammbaum/) zeigt 13 der Werke und visualisiert die Reihenfolge der Rezeptionen.
![Die berühmteste Kopie](https://firebasestorage.googleapis.com/v0/b/aries-a0120.appspot.com/o/-MtYnHWt73vQzDabD1K6%2Fimages%2F-MtYnMqbV476dJdzsiIy?alt=media&token=309f5510-bdd2-43b2-a9b0-db5e2762b5ef)

_Abb.1: Sangallo, Bastiano (Aristotile): Die Schlacht bei Cascina nach Michelangelo. Ca. 1541; Öl auf Holz; 77x130cm; Holkham Hall, Leicester Collection. Abb. nach: http://prometheus.uni-koeln.de/pandora/image/show/artemis-808de58240adac762d9613493271eab850f3b5e3 (06.02.22)._

Der vorliegende Text wird zunächst die „Cascinaschlacht“ und ihre Entstehung vorstellen, bevor er eine Einführung in die Phänomene der Aemulatio und Bildrezeption in der Renaissance im Allgemeinen und im Bezug auf die Cascinaschlacht im Besonderen bietet. Schließlich werden die hier entstandenen Netzwerkgraphen erklärt und einige mögliche Schlüsse daraus gezogen.

## 2 Die "Cascinaschlacht"

Die toskanische Stadt Cascina gehörte im Mittelalter und in der Frühen Neuzeit zur Republik Pisa und liegt am Fluss Arno, der in Michelangelos Historie im Vordergrund dargestellt ist. Von der Schlacht bei Cascina von 1364 ist legendenhaft überliefert, die florentinischen Soldaten hätten statt wachsam einen Angriff zu erwarten im Arno gebadet, seien aber von einem Angriff der Armee Pisas überrascht worden. In aller Eile mussten die Badenden zu den Waffen stürzen und sich verteidigen. Die Schlacht endete mit einem florentinischen Sieg. Dieser Moment der Überraschung ist auf dem Karton dargestellt, den Michelangelo Buonarotti 1504-1505 in Florenz anfertigte. Das Fresko war für den Sala dei Cinquecento im Palazzo Vecchio vorgesehen, wurde aber nie ausgeführt. Der Karton wurde vermutlich 1515 zerstört und liegt daher nur in Kopien vor.[^1] Die Grundlage der folgenden Beschreibung bietet eine Kopie (angefertigt ca. 1541) von Bastiano (Aristotile) da Sangallo (1481-1551), die heute in Holkham Hall in Norfolk aufbewahrt wird. Es ist ein Ölbild von 77 x 130 cm Größe und basiert auf Zeichnungen, die Sangallo nach dem Original angefertigt hatte. Die Maße des Originals sind nicht überliefert.

Sangallos Kopie von Michelangelos Karton der Cascinaschlacht zeigt eine Gruppe von 20 Männern verschiedenen Alters. Die Komposition ist asymmetrisch und keine der Figuren steht im Mittelpunkt oder ist besonders betont. Die Männer sind grob in drei Reihen aufgeteilt: liegende, sitzende und aus dem Wasser steigende Männer vorne, sich Bückende oder Gehende in der Mitte und stehenden Figuren hinten, doch wird diese Ordnung durch ihre Bewegungen an mehreren Stellen aufgelöst. Sie sind in bewegten Posen festgehalten, die Körper sind angespannt, drehen und wenden sich, einzelne Kleidungsstücke und Haare flattern im Wind. Nach links wird die Gruppe von einem aus dem Wasser kletternden Mann, der sich nach links wendet, begrenzt; am rechten Rand wenden sich die Figuren nach rechts, auf imaginäre weitere Szenen verweisend. Es ist kein Hintergrund ausgeführt.
Um alle Figuren der Cascinaschlacht eindeutig benennen zu können, wurden ihnen im vorliegenden Projekt IDs in Form von Buchstaben zugeordnet. Im Folgenden werden sie anhand dieser IDs benannt.

![Die Figuren der Cascinaschlacht mit IDs.](https://firebasestorage.googleapis.com/v0/b/aries-a0120.appspot.com/o/-MtYnHWt73vQzDabD1K6%2Fimages%2F-MuSHplZSWmC4pXiaSqQ?alt=media&token=1a9ad597-4cad-481c-9f2b-459c9569576a)
_Abb.5: Die verwendeten IDs für die Figuren. Auf Basis von Sangallo, Bastiano: Die Schlacht bei Cascina nach Michelangelo. Ca. 1541._

Den Auftrag für das Fresko der Schlacht von Cascina erhielt Michelangelo Ende 1504. Florenz hatte gerade die Familie der Medici als Herrscher abgesetzt und die Signoria, eine demokratische Regierung, gegründet. Diese tagte im Palazzo Vecchio, der zu diesem Zweck neu mit Wandgemälden ausgestattet werden sollte. Der Gonfaloniere Piero Soderini beauftragte Michelangelo und Leonardo da Vinci mit jeweils einem Fresko, die einander im Saal gegenüberliegen sollten.[^2] Als Thema vorgegeben wurden Illustrationen von historischen Siegen des Stadtstaaten Florenz, die „wichtige Ereignisse der Florentiner Geschichte vergegenwärtigen und zugleich die Bühne für einen programmatischen Künstlerwettstreit bereiten“[^3] sollten, bei dem Leonardo gegen den 20 Jahre jüngeren Michelangelo antrat, der mit der Pietá in St. Peter in Rom und dem David in Florenz gerade zu hoher Bekanntheit und Popularität gekommen war.[^4]
Beide Künstler beendeten die Kartons für das geplante Fresko, aber ausgeführt wurde keines von beiden. Leonardo begann sein Fresko der „Anghiarischlacht“, gab es aber auf, da seine experimentelle Freskiertechnik nicht die gewünschten Ergebnisse brachte, und Michelangelo beließ es bei der Fertigstellung des Kartons. Er war von Papst Julius II. nach Rom berufen worden, wo er das Grabmal des Papstes planen und ausführen sollte, dann aber 1508 die Ausmalung der Sixtinischen Kapelle begann.[^5] 

## 3 Aemulatio und Rezeption

### 3.1 Aemulatio als Prinzip der Frühen Neuzeit

Die Rezeption vorausgegangener Werke war nicht nur lange ein grundlegender Pfeiler der Ausbildung von Künstlern,[^6] sondern auch ein wesentlicher Bestandteil der geschaffenen Kunst und eine Antriebskraft für künstlerischen Fortschritt.[^7] Dieser Wettbewerbscharakter der Rezeption äußert sich im Begriff der aemulatio (lat. Wetteifer). Zunächst steht die imitatio,[^8] also die Nachahmung einer anerkannten Autorität, an deren Werk ein Künstler sich messen will.[^9] Erst die Aemulatio führt dazu etwas Besseres schaffen zu wollen – das Bessere ist dabei dasjenige, das „Schöner und Vollkommener“[^10] ist als sein Vorbild. Ursprünglich mag das ein Wettstreit mit der Natur gewesen sein, doch entwickelte sich im 15. und 16. Jahrhundert eine Spannung zwischen möglichst genauer Naturnachahmung und ihrer Idealisierung und Übertreffung heraus.[^11] So tritt „jedes neue Kunstwerk nicht nur in die Nachfolge älterer Vorbilder, sondern auch in Wettstreit mit ihnen“.[^12]
Michelangelo war spätestens durch Vasaris Vite 1550 zum Höhepunkt der nachzuahmenden Vorbilder geworden, was eine der Grundlagen der Herausbildung des Manierismus des 16. Jahrhunderts war.[^13] Dabei waren seine Werke in der Wahrnehmung seiner Zeitgenossen nicht nur so schön wie die Natur, sondern – wie in den idealisierten Körpern der „Cascinaschlacht“ – übertrafen diese bereits. [^14] Im Fall der „Cascinaschlacht“ und der „Anghiarischlacht“ bestand die Künstlerkonkurrenz dabei nicht nur in der Schönheit der fertigen Bilder, sondern wurde auch in der Entstehungssituation als direkter Wettbewerb inszeniert: Ziel ist eine „Qualitätssteigerung durch mehr oder weniger institutionalisierten Wettbewerb“. [^15]

![Netzwerk des Kopien-Stammbaums.](https://firebasestorage.googleapis.com/v0/b/aries-a0120.appspot.com/o/-MtYnHWt73vQzDabD1K6%2Fimages%2F-My-M75bwIcH0WJh4t6q?alt=media&token=49d2b2f3-0f2a-4ad9-ad8d-b31de9b13f4d)
_Abb.2: Ein Netzwerk einiger Cascinaschlacht-Rezeptionen. In interaktiver Form einsehbar unter https://tonimassenberg.github.io/Rezeption-Michelangelo/Stammbaum/._

### 3.2 Cascinarezeption

Schon direkt nach ihrer Entstehung begann die lange Wirkungsgeschichte der „Cascinaschlacht“. Vasari schrieb: 

> „Sicher darf man das glauben, denn als der Karton nach seiner Fertigstellung unter großem Aufsehen der Künstlerschaft und zu Michelangelos äußerstem Ruhm in die Sala del Papa gebracht wurde, sind all jene, die nach diesem Karton ihre Studien gemacht und ihn abgezeichnet haben, wie es in Florenz späterhin Fremde und Einheimische viele Jahre lang taten, zu herausragenden Persönlichkeiten dieser Kunst geworden, wie wir sehen konnten.“[^16] 

In den nur zehn Jahren seiner Existenz wurde der Karton vielfach kopiert. Dabei spielte eine Rolle, dass es sich bei dem Karton der „Casinaschlacht“ um ein Werk Michelangelos handelte, das im Vergleich beispielsweise zur Decke der Sixtinischen Kapelle sehr zugänglich war, als es in der Sala del Papa im Komplex von S. Maria Novella aufbewahrt wurde.[^17] Dies gab den nacheifernden Künstlern die Gelegenheit, den Karton zu studieren und zu kopieren, beispielsweise im Fall von Marcantonio Raimondi, dessen Kupferstiche ebenfalls zur frühen Berühmtheit der „Cascinaschlacht“ beitrugen.[^18] Die Druckgraphik als Medium erhöht dabei im Sinne der Aemulatio die Vergleichssituation, da „die besten Werke überall schnell verfügbar und als Kanon etabliert“[^19] waren.

![Marcantonios Druckgraphik.](https://firebasestorage.googleapis.com/v0/b/aries-a0120.appspot.com/o/-MtYnHWt73vQzDabD1K6%2Fimages%2F-MtYnMq_dnzqyi8PO2zB?alt=media&token=1dd01d65-97ff-49ef-8a32-efd5f3025732 )
_Abb.3: Einer von mehreren Kupferstichen auf Basis der „Cascinaschlacht“, die Marcantonio anfertigte. Raimondi, Marcantonio, Die Badenden, 1510, Kupferstich, 21,5 x 28,2 cm; British Museum. Abb. nach: https://www.britishmuseum.org/collection/object/P_1895-0915-135 (07.02.22)._

Auch Sangallo kopierte das Original in Zeichnungen, auf denen seine berühmte Kopie von 1541 basiert. Sangallo war dabei ein Teil der sehr kleinen Schülerschaft Michelangelos,[^20] womit sie unter den vielen Rezipienten der „Cascinaschlacht“ ein Beispiel der „kleinsten aemulativen Einheiten, die Meister-Schüler-Verhältnisse“[^21] darstellen.

Es spielt bei der Rezeption von Bildteilen auch eine Rolle, dass Künstler erst einmal im Feld der Imitatio von dem Vorbild und den Erfahrungen anderer Künstler profitieren, indem sie aus ihren Bildern lernen; gerade die „Cascinaschlacht“ bietet genug „Neuerungen in der affektbetonten Darstellung bewegter Akte“,[^22] um die Nutzung als Vorlage für eine Figur in einem neuen Bild zu rechtfertigen. Gewissermaßen bietet die große Auswahl körperbetonter Posen einen Katalog von Vorlagen, durch die auch andere Künstler von Michelangelos anatomischen Studien profitieren konnten.[^23] Mancher Auffassung nach war auch Michelangelos Art, in Zeichnung und Gemälden sein Verständnis der Figuren aus der Bildhauerei einfließen zu lassen, die eine besondere Faszination einer tieferen Körperlichkeit und Plastizität ausmacht und weitreichende Konsequenzen für die italienische Kunst des 16. Jahrhunderts hatte.[^24] 

Darüber hinaus eignet sich die „Cascinaschlacht“ so auffallend gut zum Kopieren, weil sich auch einzelne Figuren separat darstellen lassen. Schaut man sich in den Abbildungen die einzelnen Figuren an, merkt man schnell, dass sie nur wenig miteinander interagieren. Kaum zwei von ihnen haben Augenkontakt, berühren oder unterhalten sich. Außerdem sind einige der Figuren so im Bild platziert, dass keine Stelle ihres Körpers von etwas Anderem als sich selbst oder ihrer Kleidung verdeckt wird. Diese Figuren können völlig separat von den anderen betrachtet werden, da sie vollständig dargestellt sind und ohne ihren Kontext betrachtet werden können. Dazu gehören die Figuren, die im vorliegenden Projekt die IDs B, O und R tragen und die meist rezipierten Figuren sind (siehe unten). Figuren, die größtenteils von anderen Figuren verdeckt werden und daher nicht in sinnvoller Weise ohne diese dargestellt werden können, wie G und U, werden dagegen nur rezipiert, wenn das vollständige Ensemble kopiert wird. Die Möglichkeit, die verschiedenen Posen einzeln oder in ausgewählten kleineren Gruppen zu rezipieren, scheint also eine Rolle in der Beliebtheit der „Cascinaschlacht“ als Vorlage gespielt haben.

Ein so hoch gelobtes, berühmtes Werk bietet aber auch genug Wiedererkennungspotential, um eine Figur in einen völlig neuen Kontext einbetten zu können und somit gegebenenfalls subversiv mit den Erwartungen zu spielen, indem der Kanon unterlaufen wird.[^25] Marcantonio Raimondi fertigte mehrere Sangallos Bild ähnliche Kopien einzelner Figuren an, schuf aber auch einen Druck, in dem die Haltung der Figur B gespiegelt, also von vorn gezeigt, und von einer weiblichen Figur eingenommen wurde. Jan van Amstel malte 1535, vermutlich auf die Druckgraphik Marcantonios Bezug nehmend,[^26] dieselbe Figur ebenfalls um 180 Grad gedreht, sowohl im bildlichen Sinn (von vorne) als auch inhaltlich, da die Figur hier statt eines bald siegreichen florentinischen Kriegers und aemulativen Beispiels der Schönheit einen sündigen Pilger darstellt.[^27] So wird die Technik der Rezeption genutzt um Erwartungen zu brechen und dem neu entstandenen Bild eine Bedeutungsebene hinzuzufügen.

![Jan van Amstel, Liebespaar im Kornfeld.](https://firebasestorage.googleapis.com/v0/b/aries-a0120.appspot.com/o/-MtYnHWt73vQzDabD1K6%2Fimages%2F-MtYnMqbV476dJdzsiIx?alt=media&token=a98bf455-b759-4576-8c99-7ec6b7777b42 )
_Abb.4: Amstel, Jan van, Liebespaar im Kornfeld, 1535, Öl auf Holz, 28 x 20,5 cm; Herzog Anton Ulrich-Museum Braunschweig. Abb. nach: Müller, Jürgen, Die Welt als Bordell. Überlegungen zur Genremalerei Jan van Amstels, in: Münch, Birgit Ulrike, Müller, Jürgen (Hrsg.): Peiraikos' Erben: die Genese der Genremalerei bis 1550 (=Trierer Beiträge zu den historischen Kulturwissenschaften, Bd. 14), Wiesbaden 2015, S. 52._

Vielleicht wollten manche Künstler auch einen aemulativen Wettkampf mit Michelangelo eingehen, ohne dass die tatsächliche Ähnlichkeit oder Übertreffung der Werke durch direkten Vergleich ermittelt werden kann; schließlich ist die Grenze der Imitatio erreicht, wenn das Vorbild nicht erhalten ist.[^28] 

## 4 Die Netzwerkgraphen

### 4.1 Zur Netzwerkforschung

Die menschliche Wahrnehmung kann optische Muster schneller erkennen als Daten in anderer Form. Visualisierungen helfen daher komplexe Zusammenhänge in großen Datensätzen zu verstehen, indem sie abstrakte Informationen in räumliche Datenstrukturen überführen.[^29] An Stelle der Bilder oder zusätzlich zu ihnen werden also Metadaten visuell veranschaulicht. Der Darstellung als Netzwerke liegt dabei das Verständnis zugrunde, dass Personen und Objekte in Beziehungen zueinander dargestellt werden können; man lenkt den Fokus also vom Objekt weg auf die Zusammenhänge und Kontexte dazwischen. Die formale Repräsentation als Graph zwingt zur Präzision und Klarheit der Aussagen.[^30] Die quantitative Arbeit (das Distance Reading) legt dabei unter Umständen neue Schlüsse nahe oder belegt Thesen, die vom Einzelfall her entwickelt wurden, muss aber eben durch den Einzelfall und den näheren Blick auf die untersuchten Objekte überprüft und verfeinert werden.[^31]

### 4.2 Der Figurengraph

Im vorliegenden Projekt wurde nur mit einem vergleichsweise kleinen Datensatz gearbeitet, dennoch macht die Visualisierung in Form eines Netzwerkgraphen die systematischen Zusammenhänge zwischen den Bildern sichtbar, die in einem Text eine große Menge an Erklärung verlangt hätten. Dies betrifft insbesondere den Figurengraphen, der 27 die „Cascinaschlacht“ rezipierende Abbildungen sowie 19 erhaltene Skizzen Michelangelos mit den darauf abgebildeten Figuren in Verbindung setzt. Die Nodes repräsentieren hier die Werke sowie die Figuren der „Cascinaschlacht“. Ein weiterer Node mit dem Label „Andere Figur(en)“ und der ID X repräsentiert alle Figuren, die in einem Werk vorkommen, aber nicht in Sangallos Kopie der „Cascinaschlacht“, was hier als Maß der Ähnlichkeit mit dem Original betrachtet wird. Die Edges ziehen in diesem Graphen Verbindungen zwischen einem Werk und allen darin abgebildeten Figuren. Da die meisten Figuren mehrfach rezipiert wurden und die meisten Werke mehrere Figuren zeigen, ergibt sich daraus ein komplexes Netzwerk. In einer Informationskarte, die eingeblendet wird wenn man eine der Nodes auswählt, werden die Abbildung sowie die entsprechenden Metadaten eingeblendet. Bei den Figuren-Nodes sieht man die Figur, wie Sangallo sie dargestellt hat.

![Die einzelnen Figuren, ausgeschnitten aus Sangallos Kopie.](https://firebasestorage.googleapis.com/v0/b/aries-a0120.appspot.com/o/-MtYnHWt73vQzDabD1K6%2Fimages%2F-Mz1P7LHNuqhOKvJMEhh?alt=media&token=a5255a32-6443-4c33-994f-1f35b9ef1e91)
_Abb.5: Die einzelnen Figuren, ausgeschnitten aus Sangallos Kopie._

Durch die Darstellung als Force Atlas erkennt man ein dichtes Netz der Kanten im Bereich der Bilder, die den vollständigen Karton oder große Teile daraus rezipieren. Um diesen Kern gruppieren sich die Figuren-Nodes, weiter außen finden sich die Werke, die nur wenige Figuren darstellen. Die Größe der Nodes ergibt sich aus der Betweenness Centrality, der Relevanz des Nodes für das Zusammenhalten des Netzwerkes.[^32]  Dadurch werden die Knoten der Figuren, die am häufigsten rezipiert wurden, größer dargestellt. Die Farben der Nodes und Edges orientieren sich an der Modularity Class, also den errechneten nächsten Nachbarn, wodurch sich kleinere Netzwerke der am häufigsten zusammen vorkommenden Figuren und der daher im Bezug auf ihre Figurenkonstellationen ähnlichen Werke bilden. In dieser Visualisierung bilden die Nachbarschaften zwölf Gruppen, die in einem Drop-Down Menü sichtbar sind; wird eine Gruppe oder ein Node darin ausgewählt, werden alle nicht zu der ausgewählten Nachbarschaft gehörenden Nodes ausgeblendet.

![Der Figurengraph.](https://firebasestorage.googleapis.com/v0/b/aries-a0120.appspot.com/o/-MtYnHWt73vQzDabD1K6%2Fimages%2F-Mz1Qrc1qPl-VUb_jKbz?alt=media&token=3a209a7f-832f-4573-8ff9-1982ce26d805)

_Abb. 6: Ein Netzwerk der rezipierten Cascina-Figuren. In interaktiver Form einsehbar unter https://tonimassenberg.github.io/Rezeption-Michelangelo/Figuren/._

Zentral ist bei diesem Graphen die Frage danach, wie oft und in welchen Kombinationen die Figuren zitiert oder kopiert wurden und welche Eigenschaften die häufiger rezipierten Figuren gemeinsam haben. Dabei wurde auch geprüft, ob ein Zusammenhang zwischen der Häufigkeit der Rezeptionen einzelner Figuren und den Skizzen Michelangelos besteht, was nahegelegt hätte dass kompliziertere Darstellungen, für die mehr Vorbereitung nötig war, auch mehr direkte Nachfolger herausfordern. Letzeres kann verneint werden, da auf den erhaltenen Vorzeichnungen fast ausschließlich Figuren dargestellt sind, die nicht oder nicht unmittelbar im finalen Karton (oder zumindest in Sangallos Kopie) verwendet wurden, was im Graphen als Gruppe 1 erkennbar wird. Möglicherweise waren diese Figuren verworfene Ideen oder Vorzeichnungen für eventuell geplante weitere Figurengruppen im Fresko.[^33] 

| Figur  | Häufigkeit der Rezeption |
| ------------- | ------------- |
| B  | 12  |
| R  | 12  |
| O  | 11  |
| J  | 9  |
| L  | 9  |
| M  | 9  |
| S  | 9  |
| F  | 8  |
| I  | 8  |
| Q  | 8  |
| K  | 7  |
| P  | 7  |
| C  | 6  |
| D  | 6  |
| E  | 6  |
| G  | 5  |
| H  | 5  |
| N  | 5  |
| A  | 4  |
| T  | 4  |
| U  | 4  |
| X  | 3  |

Eine These bezüglich der Beliebtheit von Figuren für die Rezeption wurde bereits aufgestellt: Wichtig für die Auswahl ist, dass die Figur nicht verdeckt wird und so außerhalb des Kontextes der anderen Figuren dargestellt werden kann, ohne dass Körperteile ergänzt werden müssen. Dies lässt sich durch die vorliegende Forschung bestätigen: Die am häufigsten rezipierten Figuren sind  B (unter den 27 Kopien 12 mal vertreten), R (ebenfalls 12 mal rezipiert) und O (11), die an keiner Stelle von anderen Figuren verdeckt werden und dadurch auch ohne den Kontext anderer Figuren darstellbar sind. Auch auf die mit je 9 Kopien folgenden Figuren  L, M und S trifft dies zu. Ebenfalls 9 mal rezipiert wurde J, deren Beine zwar verdeckt werden, die aber die bewegteste Figur im Bild und deren Oberkörper ebenfalls vollständig zu sehen ist. Am seltensten kopiert (ausschließlich in den vier Abbildungen, die die vollständige Gruppe rezipieren) wurden U und T, von denen je nur ein Körperteil sichtbar ist, und A, die an mehreren Stellen verdeckt wird. Diese große Auswahl an klar erkennbaren Figuren erklärt auch die allgemeine Beliebtheit der „Cascinaschlacht“ für Rezeptionen.

Beliebte Kombinationen von Figuren lassen sich anhand der Gruppen bzw. der Modularity Class erkennen, in der Visualisierung also an der Farbe. Nicht alle Gruppen sind dabei besondere Figurenkonstellationen – die selten rezipierten Figuren bilden Gruppen allein (Gruppe 9/U und Gruppe 12/G) oder werden zusammengefasst, obwohl sie nicht zusammen rezipiert wurden (z.B. Gruppe 11), weil sie jeweils mit den Abbildungen verbunden sind, die alle oder die meisten Figuren rezipieren. Gruppe 3 legt als Kriterium die räumliche Nähe der sich überschneidenden Figuren im Bild nahe, wodurch es sich anbietet die Figuren zusammen abzubilden, hier die bewegte Figur J, die in der Gruppe mit R und S am meisten Sinn ergibt, was die Beliebtheit dieser drei Figuren erklärt.
Ein anderes Beispiel ist die Gruppe 4, in der Abbildungen versammelt sind, die die nicht abgeschnittenen Figuren in verschiedenen Konstellationen zusammenstellen und somit dem Rezipienten ein gewisses Maß an Freiheit erlauben, wobei dennoch hauptsächlich oder ausschließlich Michelangelos Figuren verwendet werden. Dies ist eventuell mit dem Zusammenspiel von der Imitatio der Figuren und einer Aemulatio in Form der versuchten Übertreffung in der Auswahl der Figuren und der Komposition zu erklären.

### 4.3 Der Stammbaumgraph

Der Stammbaumgraph dagegen lässt sich mit einem persönlichen Stammbaum vergleichen, bei dem sich eine „Abstammung“ durch die Verkettung von Rezeptionen konstruiert. Die 13 Nodes repräsentieren die Kunstwerke, die gerichteten Kanten beschreiben die Richtung, in der ein Künstler einen anderen Künstler und damit zunehmend indirekt Michelangelo rezipiert hat. Zusätzlich zu den Knoten, die Abbildungen repräsentieren, wurde ein Knoten „Originalkarton“ eingefügt, der das Zentrum des „Stammbaums“ bildet. Die Farbe der Nodes orientiert sich an den Künstlern, Werke desselben Künstlers haben also dieselbe Farbe und können schnell als zusammengehörig erkannt werden. Die Größe der Nodes ergibt sich auch hier aus der Betweenness Centrality. Diese ist in diesem Zusammenhang ein wichtiges Kriterium, denn wenn mehrere Bilder von der Existenz einer einzelnen früheren Kopie abhängig sind, ist diese wichtiger für die Verbreitung der „Cascinaschlacht“ und Michelangelo als Vorbild für weitere Rezeptionen. In der Visualisierung sind die entsprechenden Nodes größer dargestellt. 
Leider hat sich herausgestellt, dass bei einem so begrenzten Datensatz – der Stammbaumgraph kann bisher nur 13 Abbildungen berücksichtigen, weil für alle anderen Werke entsprechende Angaben zu den dem Künstler vorliegenden Vorbildern bisher nicht gefunden wurden – zuverlässige Aussagen schwierig sind. Die vorliegenden Informationen suggerieren aber eine hohe Relevanz der frühen Kopien Marcantonios, die wie oben erwähnt die frühe Begeisterung für die „Cascinaschlacht“ mitbegründeten, sowie von Sangallos Kopie, auf der vor allem Werke basieren die im 19. Jahrhundert in England entstanden, da die Abbildung zu dem Zeitpunkt bereits in Holkham Hall sichtbar war.

## 5 Fazit 

Im vorliegenden Projekt wurden die gegenwärtig auffindbaren Bilder, die Michelangelos „Cascinaschlacht“ rezipieren, in zwei Netzwerkgraphen sortiert, wodurch die Bildersammlung übersichtlicher und mögliche Antworten auf mehrere Forschungsfragen visuell sichtbar wurden. So wurde festgestellt, dass  für die Beliebtheit der „Cascinaschlacht“ als Vorlage neben der Entstehungssituation im Wettbewerbskontext und der Ausstellungssituation, die den Karton, so lange er bestand, zugänglicher machte als andere großformatige Bilder Michelangelos, vor allem die vielen einzeln kopierbaren Figuren ausschlaggebend waren. Würden die vorliegenden Daten durch genauere Forschung zu jeder einzelnen Abbildung ergänzt, könnte die Technik der Visualisierung wie hier präsentiert auch zum Nachvollziehen der Dynamiken zwischen den Kopien verwendet werden. So könnte man sich fragen ob es Fälle gibt in denen ein Werk von mehreren Abbildungen beeinflusst wurde, was im Netzwerkgraphen klar sichtbar wäre. Die Netzwerkforschung als Technik zur Erforschung aemulativer Zusammenhänge hat sich somit bewährt.


## 6 Literaturverzeichnis
arthistoricum.net, Michelangelos Schlacht bei Cascina, zugänglich über: https://www.arthistoricum.net/themen/portale/renaissance/lektion-xi-florenz-1500-1508-leonardo-michelangelo-und-raffael/4-michelangelos-schlacht-von-cascina (letzter Zugriff: 11.03.22).

Brinton, Christoper G., Chiang, Mung, The Power of Networks. Six Principles That Connect Our Lives, Princeton 2017.

Gould, Cecil, Michelangelo. Battle of Cascina, Newcastle upon Tyne 1966.

Glinka, Katrin, Dörk, Marian, Zwischen Repräsentation und Rezeption. Visualisierung als Facette von Analyse und Argumentation in der Kunstgeschichte, in: Kuroczyński, Piotr/Bell, Peter/Dieckmann, Lisa (Hrsg.), Computing Art Reader. Einführung in die digitale Kunstgeschichte, Heidelberg 2018, S. 234-250.

Jonietz, Fabian, Die Scuole delle arti als Orte der aemulatio. Der Fall der Cappella Brancacci,  in:  Müller, Jan Dirk/Pfisterer, Ulrich/Bleuler, Anna Kathrin/Jonietz, Fabian (Hrsg.), Aemulatio. Kulturen des Wettstreits in Text und Bild (1450-1620) (=Pluralisierung & Autorität, Bd. 27), Berlin/Boston 2011, S. 770-811.

Jonietz, Fabian, Labor omnia vincit? Fragmente einer kunsttheoretischen Kategorie, in:  Müller, Jan Dirk/Pfisterer, Ulrich/Bleuler, Anna Kathrin/Jonietz, Fabian (Hrsg.), Aemulatio. Kulturen des Wettstreits in Text und Bild (1450-1620) (=Pluralisierung & Autorität, Bd. 27), Berlin/Boston 2011, S. 573-681.

Lemercier, Claire, Formal network methods in history: why and how? In: Fertig, Georg (Hrsg.): Social Networks, Political Institutions, and Rural Societies, o.O. 2015, S. 281-310, zugänglich über: https://halshs.archives-ouvertes.fr/halshs-00521527v2 (letzter Zugriff 13.03.22). 

Müller, Jan Dirk, Pfisterer, Ulrich, Vorrede, in:  Dies./Bleuler, Anna Kathrin/Jonietz, Fabian (Hrsg.), Aemulatio. Kulturen des Wettstreits in Text und Bild (1450-1620) (=Pluralisierung & Autorität, Bd. 27), Berlin/Boston 2011, S. 1-32.

Müller, Jürgen, Die Welt als Bordell. Überlegungen zur Genremalerei Jan van Amstels, in: Münch, Birgit Ulrike, Müller, Jürgen (Hrsg.): Peiraikos' Erben: die Genese der Genremalerei bis 1550 (=Trierer Beiträge zu den historischen Kulturwissenschaften, Bd. 14), Wiesbaden 2015, S. 15-52.

Satzinger, Georg, Warum Michelangelo? In: Ders./Schütze, Sebastian (Hrsg.), Der Göttliche. Hommage an Michelangelo (Ausst.-Kat. Kunst- und Ausstellungshalle der Bundesrepublik Deutschland, Bonn 2015), München 2015,  S. 14-33.

Satzinger, Georg, Marcantonio Raimondi (Texte 74, 75 und 77), in: Ders./Schütze, Sebastian (Hrsg.), Der Göttliche. Hommage an Michelangelo (Ausst.-Kat. Kunst- und Ausstellungshalle der Bundesrepublik Deutschland, Bonn 2015), München 2015,  S. 155-156.

Satzinger, Georg, Luigi Schiavonetti (Text 73), in: Ders./Schütze, Sebastian (Hrsg.), Der Göttliche. Hommage an Michelangelo (Ausst.-Kat. Kunst- und Ausstellungshalle der Bundesrepublik Deutschland, Bonn 2015), München 2015,  S. 157.

Schütze, Sebastian: Nacktheit in großen Tableaus, in: Ders./Satzinger, Georg (Hrsg.), Der Göttliche. Hommage an Michelangelo (Ausst.-Kat. Kunst- und Ausstellungshalle der Bundesrepublik Deutschland, Bonn 2015), München 2015, S. 152.

Vasari, Giorgio, Das Leben des Michelangelo. Neu übersetzt und kommentiert, Berlin 2009.


## 7 Fußnoten

   [^1]: Vgl. zum ganzen Abschnitt Gould, Cecil, Michelangelo. Battle of Cascina. Newcastle upon Tyne 1966, S.6, sowie Satzinger, Georg, Warum Michelangelo? In: Ders./Schütze, Sebastian (Hrsg.), Der Göttliche. Hommage an Michelangelo (Ausst.-Kat. Kunst- und Ausstellungshalle der Bundesrepublik Deutschland, Bonn 2015), München 2015, S. 14-33, S. 17f.
   [^2]: Vgl. Gould 1966, S. 6, sowie Vasari, Giorgio: Das Leben des Michelangelo. Neu übersetzt und kommentiert. Berlin 2009, S. 60.
   [^3]: Schütze, Sebastian: Nacktheit in großen Tableaus, in: Ders./Satzinger, Georg (Hrsg.), Der Göttliche. Hommage an Michelangelo (Ausst.-Kat. Kunst- und Ausstellungshalle der Bundesrepublik Deutschland, Bonn 2015), München 2015, S.152.
   [^4]: Vgl. Gould 1966, S. 6.
   [^5]: Vgl. zum ganzen Abschnitt: Gould 1966, S.10f.
   [^6]: Vgl. Satzinger, Marcantonio Raimondi 2015, S. 115.
   [^7]: Vgl. Müller, Jan Dirk, Pfisterer, Ulrich, Vorrede, in:  Dies./Bleuler, Anna Kathrin/Jonietz, Fabian (Hrsg.), Aemulatio. Kulturen des Wettstreits in Text und Bild (1450-1620) (=Pluralisierung & Autorität, Bd. 27), Berlin/Boston 2011, S. 22.
   [^8]: Vgl. ebd., S. 7.
   [^9]: Vgl. ebd., S. 6.
   [^10]: Ebd., S. 2.
   [^11]: Vgl. ebd., S. 10f.
   [^12]: Ebd., S. 1.
   [^13]: Vgl. ebd., S. 4.
   [^14]: Vgl. Jonietz, Fabian, Labor omnia vincit? Fragmente einer kunsttheoretischen Kategorie, in:  Müller, Jan Dirk/Pfisterer, Ulrich/Bleuler, Anna Kathrin/Jonietz, Fabian (Hrsg.), Aemulatio. Kulturen des Wettstreits in Text und Bild (1450-1620) (=Pluralisierung & Autorität, Bd. 27), Berlin/Boston 2011, S. 573-681, S. 778.
   [^15]: Müller / Pfisterer 2011, S. 3.
   [^16]: Vasari 2009, S. 61f.
   [^17]: Vgl. Jonietz, Fabian, Die Scuole delle arti als Orte der aemulatio: Der Fall der Cappella Brancacci,  in:  Müller, Jan Dirk/Pfisterer, Ulrich/Bleuler, Anna Kathrin/Jonietz, Fabian (Hrsg.), Aemulatio. Kulturen des Wettstreits in Text und Bild (1450-1620) (=Pluralisierung & Autorität, Bd. 27), Berlin/Boston 2011, S. 770-811, S. 775.
   [^18]: Vgl. Satzinger, Marcantonio Raimondi 2015, S.155.
   [^19]: Müller / Pfisterer 2011, S. 17.
   [^20]: Vgl. Jonietz, Die Scuole delle arti 2011, S. 771.
   [^21]: Müller / Pfisterer 2011, S. 21.
   [^22]: Satzinger, Marcantonio Raimondi 2015, S. 154.
   [^23]:  Vgl. Satzinger, Warum Michelangelo? 2015, S. 17.
   [^24]: Vgl. Wilde, Johannes: Michelangelo. Six lectures by Johannes Wilde. Oxford 1978, S. 44, sowie arthistoricum.net, Michelangelos Schlacht bei Cascina, https://www.arthistoricum.net/themen/portale/renaissance/lektion-xi-florenz-1500-1508-leonardo-michelangelo-und-raffael/4-michelangelos-schlacht-von-cascina (letzter Zugriff: 11.03.22).
   [^25]:   Müller / Pfisterer 2011, S. 6.
   [^26]:   Vgl. Müller, Jürgen, Die Welt als Bordell. Überlegungen zur Genremalerei Jan van Amstels, in: Münch, Birgit Ulrike, Müller, Jürgen (Hrsg.): Peiraikos' Erben: die Genese der Genremalerei bis 1550 (=Trierer Beiträge zu den historischen Kulturwissenschaften, Bd. 14), Wiesbaden 2015, S. 40f.
   [^27]:  Ebd., S. 39.
   [^28]: Müller / Pfisterer 2011, S. 12f.
   [^29]:  Vgl. Glinka, Katrin, Dörk, Marian, Zwischen Repräsentation und Rezeption. Visualisierung als Facette von Analyse und Argumentation in der Kunstgeschichte, in: Kuroczyński, Piotr/Bell, Peter/Dieckmann, Lisa (Hrsg.), Computing Art Reader. Einführung in die digitale Kunstgeschichte, Heidelberg 2018, S. 234-250, S. 237f.
   [^30]:  Vgl. Lemercier, Claire, Formal network methods in history: why and how? In: Fertig, Georg (Hrsg.): Social Networks, Political Institutions, and Rural Societies, o.O. 2015, S. 281-310, S. 287.
   [^31]:  Vgl. ebd., S. 286.
   [^32]: Für eine ausführliche Erklärung der Relevanz von Betweenness vgl. Brinton, Christoper G., Chiang, Mung, The Power of Networks. Six Principles That Connect Our Lives, Princeton 2017, S. 198.
   [^33]: Für Überlegungen zu möglichen weiteren geplanten Figuren siehe Gould 1966, S. 5f.


