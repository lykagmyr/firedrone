# firedrone
Μια εργασία των μαθητών του ΓΕΛ Αγίου Μύρωνα για τη δημιουργία ενός ανιχνευτή πυρκαγιών.

Σκοπός της εργασίας μας είναι η δημιουργία ενός εργαλείου ανίχνευσης πυρκαγιών για να γίνει πιο αποτελεσματική η αντιμετώπισή τους.
Οι μαθητές έχοντας ως αφετηρία το δυσάρεστο γεγονός της καταστροφικής φωτιάς στην Αττική το καλοκαίρι του 2018, σκέφτηκαν ότι αν υπήρχε έγκαιρη προειδοποίηση προς την πυροσβεστική ίσως να μην υπήρχαν τόσα θύματα. 
Προτάθηκε λοιπόν η κατασκευή ενός αυτόματου συστήματος που θα ανιχνεύει την ύπαρξη καπνού και φωτιάς σε δασικές περιοχές και θα ενημερώνει τις αρμόδιες υπηρεσίες.
Αρχικά υπήρχε η σκέψη να δημιουργηθεί ένα στατικό σύστημα, όπως οι ανιχνευτές φωτιάς στα σπίτια. Διαπιστώθηκε ότι αυτό ίσως είναι ακριβή λύση καθώς θα απαιτούσε την εγκατάσταση πολλών τέτοιων συσκευών. 
Καταλήξαμε στο συμπέρασμα ότι θα ήταν φθινότερη η κατασκευή ενός ιπτάμενου συστήματος ανίχνευσης που θα είχε τη δυνατότητα να επιτηρεί μεγαλύτερης έκτασης περιοχή.
Η συγκεκριμένη εργασία αποτελεί ένα δύσκολο κατασκευαστικό εγχείρημα που ίσως να υπερβαίνει τις γνώσεις του Γενικού Λυκείου, όμως οι μαθητές πιστεύουν ότι είναι μια ιδιαίτερη πρόκληση.

ΣΥΝΤΟΜΗ ΠΕΡΙΓΡΑΦΗ

Το σύστημα μας θα κατασκευαστεί σύμφωνα με τα παρακάτω:

Πάνω στο drone θα εχει προσαρμοστεί το arduino που θα έχει τον έλεγχό του.
Με αυτό θα έχουν συνδεθεί με κατάλληλη διάταξη: 

    ο αισθητήρας προσανατολισμού ώστε να μπορεί να γίνει ο χειρισμός και να διατηρεί ένα συγκεκριμένο υψος πτήσης
    
    η wifi πλακέτα για να επιτευχθεί σύνδεση μέσω wifi με κινητό για το χειρισμό του
    
    αισθητήρας gps για να στέλνεται μήνυμα με τις συντεταγμένες τις φωτιάς όταν εντοπιστεί
    
    3 ανιχνευτές φωτιάς στο κάτω μέρος ώστε να καλύπτουν όσο το δυνατό μεγαλύτερη περιοχή
    
    ένας ανιχνευτής καπνού στην άνω πλευρά και ένας στην κάτω πλευρά του drone
    
    οι 4 μονάδες ESC για τον έλεγχο των κινητήρων
     


ΑΠΑΙΤΗΣΕΙΣ ΥΛΙΚΟΥ
Η εργασία μας για να υλοποιηθεί χρειάζεται τα παρακάτω:

    x1 Arduino Uno,

    x1 GY-87 αισθητήρας 3 αξόνων και υψομέτρου

    x1 GPS module για τον προσδιορισμό θέσης

    x2 αισθητήρες καπνού 

    x3 αισθητήρες φωτιάς

    x1 Esp32 module (bluetooth, wifi) για τον χειρισμό του

    x1 prototype board, για σύνδεση των εξαρτημάτων

    x2 LEDs, 

    Resistors 300Ω+1k+1,5K,

    x1 Lipo battery 2200 mah-30C, μπαταρία

    x4 brushless motors 1000KV, κινητήρας

    x4 ESCs 30A, μονάδα ελέγχου κινητήρα

    x4 1045 έλικες για drone,
    
    x1 σκελετος drone 450mm*55mm


