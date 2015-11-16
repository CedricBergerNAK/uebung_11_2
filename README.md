# Kapitel 11 Übung 2 ("Kartenstapel mit Exceptions")

> Verwenden Sie für diese Übung bevorzugt Ihr eigenes Blackjack-Projekt. Notfalls können Sie aber auch auf die mitgelieferte ```Spielkartenstapel```-Klasse zurückgreifen.

* Ändern Sie die Methode ```getObersteKarte()``` der Klasse ```Spielkartenstapel``` derart, dass sie eine angemessene Exception wirft, wenn der Stapel leer ist.
* Ergänzen Sie das Projekt um eine Klasse ```Test``` mit einer ```main```-Methode.
* Erzeugen Sie in dieser Methode einen Spielkartenstapel und nehmen Sie solange Karten, bis die Exception ausgelöst wird.
* Erweitern Sie das Programm derart, dass die kritische Anweisung in einem ```try-catch```-Block steht und die Exception abgefangen wird. Wenn das auftritt, mischen Sie den Stapel neu.
