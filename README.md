Για την εργάσια είχα μπερδευτεί για το αν την αποθηκεύουμε σε δικό μας repository ή όχι και εφτιάξα ενα repository με solutions.txt στο οποίο αποθήκευσα όλες τις λύσεις αφού τελείωσα την εργάσια. Μετά είδα την οδηγία να μην προσθέσουμε όλες τις λύσεις μαζί στο τέλος και ότι την υποβάλλουμε στο https://classroom.github.com/a/sdllo8YY, οπότε θα κάνω τα 12 διαφορετικά git commits, αλλά έχω ήδη λύσει όλη την εργάσια. 

Για τις λύσεις:

Byte0: Πολλά cd μέχρι τον τελικό φάκελο και cat για το περιεχόμενο του

Byte1: man + εντολή

Byte2: grep "will find" shakespeare.txt

Byte3: diff shakespeare.modified.txt shakespeare.txt

Byte4: cd maze και μετά find left/right για να βρούμε το path του cup.txt

Byte5: Tο αρχείο δεν γίνεται compile οπότε έφτιαξα φάκελο στο /tmp και το αντέγραψα εκεί όπου το έκανα compile. Έπειτα για να τρέξει ήθελε ./byte5 και sdi με format sdiYYNNNNN οπότε έγραψα ./byte5 sdi1234567 και έβγαλε αυτό 
το κλειδί.

Byte6: To σκέτο unzip δεν δούλευε, αλλά δούλεψε το unzip -p.

Byte7: Με δοκιμές...  tar -p -x -f byte7.tar.gz -O

Byte8: nano carriage_return.txt

Byte9: cat /home/byte9/-

Byte10: sort -d

Byte11: Μετά από δοκιμές κατέληξα σε αυτή την εντολή: uniq births.txt -d -c. Έπειτα επιβεβαίωσα με grep "Rebeka" που την έβγαλε περισσότερες φορές σχετικά με τα υπόλοιπα ονόματα που συνέκρινα πάλι με grep. 
Note: όταν έτρεχα παρόμοια εντολή με το sort έπαιρνα αυτό: sort: births.txt:2: disorder: Abbe. Όμως με το grep είδα ότι το Rebeka ήταν πιο πολλές φορές στη λίστα. 
