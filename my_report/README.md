# Lesson: Digital & Serious Games

### First and Last Name: Nikiforos Mavridis
### University Registration Number: dpsd17067
### GitHub Personal Profile: https://github.com/Nikf0r0s
### Digital & Serious Games Personal Repository: https://github.com/Nikf0r0s/Role-Playing-Game
### Game online: https://nikf0r0s.github.io/Role-Playing-Game/ 

# Introduction
Αρχική ιδέα: Ο παίκτης να είναι μια πανοπλία που ζωντάνεψε και προσπαθεί να ξεφύγει από
το να είναι έκθεμα και να απελευθερωθεί.
Τελικό Concept: Ο Ruby μεταμορφώνεται σε "πανοπλία" που περιφέρεται μέσα σε μια
επαυλη! Πρεπει να προσέξει να μην τον βρουν οι νοικοκυρες αλλιώς θα τον γυρίσουν πισω!

# Summary
Μετά από σύντομες αξιολογήσεις από χρήστες το τελικό αποτέλεσμα ενώ έχει γίνει κάποια
προσπάθεια δεν εμβαθύνει αρκετά τους χρήστες στο concept της ιστορίας. Το πιο κύριο
αιτήματα των χρηστών είναι για εναν κατανοητό τρόπο να νικήσουν.


# 1st Deliverable
Δημιουργία προταρχικού χάρτη. Animation και κίνηση του παίκτη στον χώρο.

# 2nd Deliverable
Χρησημοποιησα το rigidbody για την κινηση του παίχτη ώστε να μην δημιουργητε το εφε που όταν παει στον τοιχο ξαναγυρναει πισω και ξαναπαει προς το τοιχο.
Η κινηση του rigidbody καλείται μέσα απο την update καθως αποδιδει καλήτερα και όχι απο την fixedupdate που θα ήταν στανταρ το frame update σε καθε μηχανημα.
Ο "κακός" κάθε φορά που συμετέχει σε κάποια σύγκουση αλλάζει φορά στην κίνησή του και ανα ένα χρονικό διάστημα αλλάζει άξονα κίνησης.
Σε τρίτο χρόνο θέλω να διορθώσω οι ¨σφαιρες¨ να εκτοξευονται σε κατευθυνση που θα μπορεί να επιράσει ο χρήστης και θέλω να σχηματίσω λίγο καλήτερα μια ιστορία και το gameplay συνολικά σαν εμπειρία.

# 3rd Deliverable 
Αρχικά διορθώθηκαν κάποια λάθη στον κώδικα. Ο παίκτης μπορεί να “πυροβολήσει” προς
όλες τις κατευθύνσεις. Ακόμα οταν ο παίκτης μπαίνει σε κάποιο damage zone αλλάζει
χρώματα προκειμένου να καταλαβαίνει ο χρήστης ότι χάνει ζωή.
Οι πιο κύριες αλλαγές έγιναν με στόχο να συνάδουν με το concept της ιστορίας. Ο παίκτης
όταν δεν κινείται γίνεται αόρατος. Οι κακοί οταν ο παίκτης είναι αόρατος δεν μπορούν να τον
βλάψουν με το “βλέμμα” τους ωστόσο αν κάποιος κακός πέσει πάνω του τότε δέχεται
damage. Τα damage zones έγιναν τα φώτα του χώρου. Ο παίκτης πυροβολόντας μπορεί να
καταστρέψει την “ορατότητα” των κακών.
Προστέθηκε ήχος σαν γενικό background ηλεκτρονική ambient μουσική. Σαν ήχος των
κακών ένα μουρμούρισμα

# Conclusions
Μπορούν να προστεθούν κάποια πράγματα ακόμα ώστε οι χρήστες να νιώθουν πως
υπάρχει σκοπός και όχι απλά ότι περιφέρονται στον χώρο.


# Sources
###Code sources: https://www.youtube.com/watch?v=Cry7FOHZGN4 , https://www.youtube.com/watch?v=32VXj5BB7wU , https://www.youtube.com/watch?v=rycsXRO6rpI , https://www.youtube.com/watch?v=DTp5zi8_u1U
###Tileset source: https://opengameart.org/content/metroidvania-tileset-v2 
###Sprite sheet: https://opengameart.org/content/lpc-combat-armor-for-women , https://opengameart.org/content/pixel-items-1 , https://opengameart.org/content/pixel-heart-sprite

