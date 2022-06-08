## Sichern Sie Ihr Geld

Wie im vorherigen Kapitel erwähnt, ist es unser Ziel, die Stufe "Ihre Schlüssel, Ihre Bitcoin" zu erreichen.

Um Bitcoin zu kaufen, zu verwenden und aufzubewahren, benötigen Sie:

* Bitcoin-Wallet = Ihr digitales Schließfach. Eine treffendere Analogie ist ein digitaler Schlüsselbund für die einzelnen Abteilungen des Schließfaches.
* Bitcoin-Adressen = eine oder mehrere eindeutige Adressen für Ihr Geld auf der Blockchain, Ihre Empfangsadressen (genauer gesagt eine nicht ausgegebene Transaktionsausgabe UTXO)
* Seed = die Wiederherstellungsdaten für Ihre Bitcoin-Wallet.

### Bitcoin-Wallet
Stellen Sie sich eine Wallet wie ein öffentliches Schließfach mit mehreren Abteilungen vor. Jeder kann Geld in jedes der Fächer einzahlen. Nur der Besitzer der privaten Schlüssel kann ein Fach aufschließen und das darin befindliche Geld bewegen. Ihre Bitcoin-Wallet besteht aus allen Abteilungen und enthält alle privaten Schlüssel, um sie zu entsperren. Private Schlüssel und Bitcoin-Adressen werden aus dem Seed generiert. Der Seed ist die Wurzel aller Schlüssel und Adressen, er ist wie ein Eimer, in dem alle Ihre privaten Schlüssel gespeichert sind.

[Begriffsdefinitionen](resources/_seed-postbox.png) [^69]

Die Wallet ist eine App auf Ihrem Telefon oder eine Software auf Ihrem Computer, die alles im Hintergrund verwaltet - Ihre privaten Schlüssel, Ihre Adressen und das Senden und Empfangen von Bitcoin.

Bitcoin-Wallets enthalten Schlüssel, keine Coins. Jeder Benutzer hat eine Wallet mit Schlüsseln. Wallets sind eigentlich Schlüsselbunde mit Paaren von privaten/öffentlichen Schlüsseln. Ihr Geld wird in der Bitcoin-Blockchain gespeichert.

### Bitcoin-Adresse
Um Bitcoin zu erhalten, benötigen Sie eine Bitcoin-Adresse, an die Ihnen jemand Bitcoin schicken kann. Die Bitcoin-Adresse besteht aus einer langen Reihe von Ziffern und Buchstaben.

Ein Beispiel für eine Bitcoin-Adresse: 346n4apJCQPg2XAXU3bfNQTogz4PyTkrEf

Das Eintippen von 34 Ziffern ist natürlich sehr unpraktisch, daher werden häufig QR-Codes der Adressen verwendet, die automatisch von Ihrem Wallet erstellt werden.

![BTC-Adresse als QR-Code](resources/_address-book.PNG)

Bitcoin ist pseudonym, d. h. Sie müssen weder Ihre E-Mail-Adresse noch Ihre persönliche Identität mit einer Wallet verbinden. Die Bitcoin-Blockchain ist jedoch transparent, was bedeutet, dass Ihre Bitcoin-Adressen im Internet öffentlich einsehbar sind. Sie können zum Beispiel bei Blockcypher danach suchen und alle aktuellen Transaktionen und Werte einsehen. Hier ist ein Beispiellink: [https://anita.link/explorer](https://anita.link/explorer)

Geben Sie daher aus Gründen des Datenschutzes Ihre Bitcoin-Adressen nicht in Verbindung mit Ihrer Identität im Internet bekannt. Die Privatsphäre ist auch der Grund, warum Sie Adressen nicht wiederverwenden sollten. Die meisten Bitcoin-Wallets stellen Ihnen für jede Transaktion automatisch eine neue Adresse zur Verfügung.

Kommen wir nun zum wichtigsten Teil der Sicherung Ihrer Bitcoin: dem Seed.

### Seed und private Keys

Da der Seed die Wurzel aller privaten Schlüssel ist, darf niemand sonst Zugang zu ihm haben. Die Person, die den Seed kennt, hat die ultimative Kontrolle über das Geld an den Bitcoin-Adressen.

Der Seed (manchmal auch mnemonische Phrase oder Backup-Phrase genannt) ist eine Folge von 12 oder 24 Wörtern, die Ihnen Zugang zu den privaten Schlüsseln Ihrer Wallet-Adressen und damit zu Ihren Bitcoin verschafft. Das bedeutet, dass diese Wortfolge geheim bleiben muss. Jeder, der den Seed kennt, kann auf Ihre Coins zugreifen und sie übernehmen. Warum ist das so?

Ihre Coins befinden sich nicht in Ihrer digitalen Wallet, so wie sie in Ihrer normalen physischen Brieftasche sind. Stattdessen werden sie in der Blockchain verzeichnet. Vergleichen Sie dies mit einer E-Mail und einem Brief. Sie können von überall auf der Welt auf Ihr E-Mail-Konto zugreifen, weil Ihre E-Mails online gespeichert sind, während Ihr Briefkasten stationär ist. Dies gilt in ähnlicher Weise für Bitcoin.

Der weltweite Zugriff auf Ihr Vermögen ist mit dem Seed immer möglich, unabhängig vom Hersteller Ihrer Wallet. Achten Sie bei der Auswahl Ihrer Wallet auf den Begriff "HD-Wallet" (Hierarchical Deterministic). HD-Wallets ermöglichen es Ihnen, zu einem anderen Hersteller zu wechseln, den Seed zu importieren und Ihre Coins wiederherzustellen.

Angenommen, Ihr Smartphone wird beschädigt, Sie können nicht mehr auf Ihre Bitcoin-Wallet-App zugreifen und müssen auf ein neues Telefon wechseln. Sie installieren eine neue Version Ihrer Bitcoin-Wallet und importieren den Seed aus Ihrer ersten Wallet. Der Zugriff auf Ihr Geld ist wiederhergestellt.

Der Seed wird von der Wallet-App während der Ersteinrichtung generiert. Die meisten Wallets führen Sie durch die Einrichtung und weisen Sie an, die Seed-Wörter auf ein Blatt Papier zu schreiben. Wenn Ihre Wallet dies nicht sofort anbietet, suchen Sie nach der Funktion "Backup erstellen" oder "Backup" und folgen Sie den Schritten. Die Erstellung des Seed funktioniert auf die entgegengesetzte Art und Weise wie die Erstellung eines Passworts, wie Sie es üblicherweise auf Websites kennen. Nicht Sie legen das Passwort fest, sondern die Wallet selbst.

Die Reihenfolge der Wörter ist WICHTIG! Sie müssen die Wörter genau in der Reihenfolge aufschreiben, in der sie erscheinen.

> Beispiel seed: cruise item paper slim vocal power like video snap museum mirror sun

Schreiben Sie den Seed von Hand auf ein Blatt Papier und bewahren Sie ihn sicher auf. Machen Sie keinen Screenshot und speichern Sie ihn nicht auf Ihrem Telefon oder Computer, der mit dem Internet verbunden ist, da alle diese Orte gehacked werden können. Weitere Informationen zur Sicherheit finden Sie in Kapitel 5.

Da sich Ihr Guthaben nicht in Ihrer Wallet befindet, sondern auf der Blockchain verzeichnet ist, können Sie über Ihr Bitcoin-Guthaben weltweit verfügen, auch wenn Sie Ihr Land ohne elektronischen Geräte verlassen müssen. Sie merken sich die 12 oder 24 Seed-Wörter in der richtigen Reihenfolge. Nach Ankunft im Zielland installieren Sie eine neue Wallet und importieren den Seed. Magisch.

[^69]: Anita Posch, inspiriert von Andreas M. Antonopoulos
