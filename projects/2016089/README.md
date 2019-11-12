# Τίτλος εργασίας: User Land

#### Ονοματεπώνυμο: Σακουμπέντας Χρήστος
#### Αριθμός Μητρώου: Π2016089

## Συμμετοχικό Περιεχόμενο

* [Ιστοσελίδα](https://csakou.github.io/gr/)
* [Αποθετήριο Κώδικα](https://github.com/csakou/gr)

### Παραδοτέο Α

#### Προσθήκη εικόνων με πνευματικά δικαιώματα

Όλες οι προσθήκες αρχείων:
 * SuperPaint
   * https://github.com/csakou/gr/commit/18936d1906911320352516de4605dfd8c728ad21
   * https://github.com/csakou/gr/commit/fb6121d4c262b8a3f292295bc4344d7a1dd59c39
 * Maya
   * https://github.com/csakou/gr/commit/c5c48f47b3ae9436222f49615eb63897c42f2279
   * https://github.com/csakou/gr/commit/4a1e28826b7e90982abb2cb387c453ac6024c7a4
 * IBM-5100 Portable Computer
   * https://github.com/csakou/gr/commit/2acdc7547cee9097afe4047b232a4e31a9c51e40
   * https://github.com/csakou/gr/commit/b61341cfee5ece66751f217dcf5c8ba80fbee6bc
 * Spacewar!
   * https://github.com/csakou/gr/commit/9efffcc9cb5d73949f7560ab1c4dfa47bd8cf6dd
   * https://github.com/csakou/gr/commit/76985eebae019c20b9fed998742a1f1c712a4dcc
 * ELIZA
   * https://github.com/csakou/gr/commit/461d156f38cfb371817b79dfc8f6f3eb92a41c19
   * https://github.com/csakou/gr/commit/d69cf9c333d0ee295074ebb21aefdac64aaf0b41

## Εισαγωγή

  Στην παρούσα εργασία μας ζητήθηκε να δοκιμάσουμε σε περιβάλλον UNIX και μέσω χρήσης terminal emulator να κάνουμε 6 διάφορετικές ασκήσεις από τις διαθέσιμες και να παραδοθούν μέσα σε 2 παραδοτέες "ημερομηνίες". Παρακάτω υπάρχουν αναλυτικά τα αποτελέσματα και οι ενέργειες της κάθε άσκησης καθώς και μια γενική περιγραφή της εργασίας, εργαλεία που χρησιμοποιήθηκαν, πηγές και συμπεράσματα.
  
## Σύνοψη
 
  Σε κάθε παραδοτέο έγιναν τα βασικά τα οποία απαιτούσε η κάθε άσκηση μα και κάποιες επιπλέον ενέργειες όπως η χρήση κάποιου παρόμοιου εργαλείου με αυτά τα οποία υπήρχαν στα προτεινόμενα, καθώς και τρέξιμο των προγραμμάτων με παραμέτρους ώστε να δούμε ένα κομμάτι των δυνατοτήτων της κάθε εφαρμογής. Έγιναν λήψεις των συνεδριών του terminal μέσω του προγράμματος Asciinema και παραθέτονται σύνδεσμοι για κάθε άσκηση και τα ζητούμενα της ώστε να υπάρχει και οπτικά το αποτέλεσμα. Επίσης για κάθε εργαλείο το οποίο βρήκα σε αντιστοιχία με κάποιο από τα προτεινόμενα υπάρχει η αντίστοιχη λήψη στο Asciinema και συγκρίνω την λειτουργικότητα τους με τα προτεινόμενα.

## Διαδικασία Ανάπτυξης

  Δεν υπήρξε ιδιαίτερη διαδικάσια ανάπτυξης καθώς η εργασία δεν είναι προγραμματιστική. Παρόλα αυτά όταν χρειάστηκε να ανοίξω οποιαδήποτε αρχεία χρησιμοποίησα το Vim. Για κάθε άσκηση και παραδοτέο έγινε πρώτα μια ανάλυση του τί χρειάζομαι σε εργαλεία και το πως να στήσω το περιβάλλον ώστε να γίνει η κάθε άσκηση αποδοτικά χωρίς να ψάχνω για εργαλεία που κάνουν το ζητούμενο ή παρόμοια εργαλεία και παραμέτρους αφού εμφανιστεί κάποιο πρόβλημα. Στην εύρεση και επεξήγηση των παραμέτρων βοηθήθηκα πολύ από την UNIX εντολή "man ...". Τέλος όπου χρειάστηκα έκανα αναζήτηση για χρήση εργαλείων ή όμοια στις εξής σελίδες:
  
  * [Alternative To](https://alternativeto.net)
  * [Google](https://google.com)
  * [StackOverflow](https://stackoverflow.com)

## Εργαλεία που χρησιμοποιήθηκαν

  * [Vim](https://vim.org): για την επεξεργασία αρχείων.
  * [Asciinema](https://asciinema.org): για την λήψη των συνεδριών τερματικού.
  * [Unix Commands](https://www.wikiwand.com/en/List_of_Unix_commands): για την εύρεση εντολών Unix που υλοποιούν ή βοηθούν στο ζητούενο.

## Παραδοτέο 1

Αρχικά έπρεπε να κάνουμε το περιβάλλον ανάπτυξης με όλα τα απαραίτητα πακέτα και εργαλεία που θα φανούν χρήσιμα.
Έπειτα με την χρήση του Asciinema έγινε λήψη των παρακάτω ασκήσεων.

### Assignment 1
  
  #### Βασική λειτουργικότητα και παράθεση συστήματος.

  - [Αλλαγή του ονόματος τερματικού](https://asciinema.org/a/IoIdqQ1eCcnbeEVEGh2Q5tojT)
  
  - [Χρήση εργαλείου Neofetch](https://asciinema.org/a/BQgxRBDqA6cyHLprG3hOYTzsp) χωρίς παραμέτρους:
  Βλέπουμε πως στην απλή μορφή του παραθέτει ήδη αρκετή πληροφορία για το σύστημα που το χρησιμοποιεί.
  
  - [Χρήση Neofetch με παραμέτρους](https://asciinema.org/a/DC4mlnu31hAX5p9k4m9OgMXI7):
  Με επιπλέον παραμέτρους μπορούμε να δούμε πως προσφέρει περισσότερη πληροφορία όπως:
    * --memory_percent on: για το ποσοστό μνήμης που χρησιμοποιείται.
    * --memory_display infobar: για μια μπάρα που δείχνει οπτικά την ποσότητα ram που χρησιμοποιείται.
    * --refresh_rate on: για να δείχνει την συχνότητα ανανέωσης της οθόνης του συστήματος.
    * --cpu_temp c: για εμφάνιση της θερμοκρασίας του επεξεργαστή σε βαθμούς κελσίου.
    * --gpu_temp c: αντίστοιχα για την κάρτα γραφικών.

  - [Χρήση εργαλείου Screenfetch](https://asciinema.org/a/eBbM5EY7AcKjHxTauVKwWM7XP):
  Το εργαλείο Screenfetch δείχνει περίπου την ίδια πληροφορία, μικρότερη συγκριτικά, με το Neofetch με μικρές διαφορές αλλά δεν δέχεται παραμέτρους ώστε να εμφανίσει περισσότερη πληροφορία σε αντίθεση με το Neofetch.
  
  - [Εμφάνιση όλων των αρχείων στο directory](https://asciinema.org/a/65RwKF0B5acbJ3HzZwHkOnBG4):
  Μέσω της εντολής ls εμφάνισα τα αρχεία που βρίσκονται στο Home directory του υπολογιστή μου. Στην συνέχεια προσθέτοντας μία παράμετρο εμφάνισα και τα κρυμμένα αρχεία που βρίσκονται στο συγκεκριμένο directory.
  
  - [Εμφάνιση αρχείων σε λίστα](https://asciinema.org/a/jXKOd2qWxPYz6Q89E5mNgxIMG):
  Προσθέτοντας μία ακόμα παράμετρο εμφάνισα όλα τα αρχεία στο directory με επιπλέον τα δικαιώματα πάνω στο αρχείο, το βάθος του αρχείου (πόσα πόσα ύπο directories περιέχει), τον δημιουργό αλλά και την ομάδα στην οποία ανοίκει, το μέγεθος του σε bytes, την τελευταία ημερομηνία τροποποίησης και τέλος το όνομα του αρχείου.
  
  - [Εμφάνιση του shell configuration](https://asciinema.org/a/BDYsrFcinrAwYne5ierhaIFrN):
  Αποφάσισα να δείξω το shell configuration του υπολογιστή μου απλά ανοίγοντας τα αρχεία με τον κειμενογράφο  Vim και να παραθέσω το περιεχόμενο τους.
  
  - [Εμφάνιση shell configuration με άλλον τρόπο](https://asciinema.org/a/KVCUWNnnfU0iMxumLr778EkFP):
  Ένας δεύτερος τρόπος να δεις το περιεχόμενο ενός αρχείου κειμένου είναι η Unix εντολή "cat path/to/filename".
  
### Assignment 2

  ####  Βασικές ντολές υστήματος, επεξεργασία αρχείων και ανάγνωση τεκμηρίωσης προγραμμάτων.

  - [Προσπέλαση και επεξεργασία αρχείων με το Ranger](https://asciinema.org/a/KiEAKOfqsMFPIL7Lnt1RicUiO):
  Μία αρκετά βασική προσπέλαση των αρχείων του συστήματος με την χρήση του εργαλείου [Ranger](https://ranger.github.io/) και άνοιγμα ενός αρχείου προς επεξεργασία.
  
  - [Προσπέλαση και επεξεργασία αρχείων με το Midnight Commander](https://asciinema.org/a/lYuUaUj36DDCt8liGEE6R3sKY):
  Όμοια με το Ranger το [Midnight Commander](https://midnight-commander.org/) είναι terminal file manager έχει όμως αρκετές επιπλέον δυνατότητες όπως την επιλογή του τύπου terminal emulator που θέλεις να χρησιμοποιήσεις (η παράμετρος -x επιλέγει τον τύπο xterm) αλλά και το πως εμφανίζονται χρωματικά τα αρχεία και άλλες πολλές ιδιότητες.
  
### Assignment 3
  
  #### Αύξηση αποδοτικότητας με την χρήση εργαλείων "todo"
  
  - [Χρήση του yokadi](https://asciinema.org/a/KCq7Y5spzqE2ZzfjNttseA5re):
  Το [yokadi](https://github.com/agateau/yokadi) είναι ένα ενδιαφέρον και λειτουργικό CLI todo list application το οποίο παρέχει
πληθώρα εντολών για την οργάνωση των εργασίων που πρέπει να γίνουν. Στο παραπάνω cast φαίνονται με μία πρώτη ματιά οι βασικές λειτουργίες του yokadi:
    * t_add [project_name]  [task], για την δημιουργία νέας διεργασίας σε ένα project. Αν δεν υπάρχει το project το δημιουργεί εκείνη την στιγμή.
    * t_list [project_name]\*  (-all)\*, για να δούμε είτε γενικά είτε σε συγκεκριμένο project πόσες διεργασίες έχουμε να ολοκληρώσουμε ακόμα. Με την παράμετρο "-all" μπορούμε να δούμε ακόμα και τις ολοκληρωμένες διεργασίες στο συγκεκριμένο project.
    * t_mark_done [task_id], οι διεργασίες μας όταν δημιουργούνται τους αποδίδεται αυτόματα ένα αναγνωριστικό (id). Με αυτό μπορούμε να επεξεργαστούμε την κάθε διεργασία μοναδικά και με την εντολή t_mark_done μπορούμε να την θέσουμε ως ολοκληρωμένη.
    * t_apply [task_id(s)] t_urgency [number_that_reflects_urgency], η εντολή t_apply είναι πολύ ισχυρή. Μπορούμε να θέσουμε για παράδειγμα με την υποεντολή t_urgency την κρισιμότητα μιάς διεργασίας σε μία ή και παραπάνω διεργασίες. Για παράδειγμα:
  t_apply 1-3 t_urgency 15, θέτει στις διεργασίες 1 εως 3 κρισιμότητα 15. Τα νούμερα δεν αναπαριστούν κάτι συγκεκριμένο στο πρόγραμμα αλλά καθορίζονται από τον χρήστη.
    * t_due [task_id]  [date time || +No_of_weeks/days/months/years], για να θέσουμε την ημερομηνία "λήξης" μίας διεργασίας δίνοντας απλά το αναγνωριστικό της διεργασίας και μετά είτε την ημερομηνία (συμπληρωματικά αν θέλουμε και την ώρα), είτε τον αριθμό εβδομάδων, ημερών, μηνών ή και χρόνων που επιθυμούμε.
    * t_recurs [task_id]  [period]  [starting_day(and time if we wish)]\*, η εντολή t_recurs ουσιαστικά μας δίνει την δυνατότητα να κάνουμε μία διεργασία επαναλαμβανώμενη απλά χρησιμοποιώντας το αναγνωριστικό της διεργασίας, την χρόνική περίοδο που συμβαίνει η επανάληψη π.χ. εβδομαδιαία και τέλος αν επιθμούμε την ημέρα από την οποία θα ξεκινήσει η επανάληψη ή και την ώρα.
  
  - [Χρήση του TaskWarrior](https://asciinema.org/a/tCy1zBev1Rh5nNk8eR8RrNdlD)
  Το TaskWarrior είναι ένα πολύ ισχυρό εργαλείο productivity. Περιέχει πάρα πολλές λειτουργίες που κάποιος χρειάζεται αρκετό καιρό χρήσης μόνο για να τις μάθει όλες. Πέρα από την βασική χρήση σαν "todo list" εργαλείο περιέχει ακόμη και εντολές για reports ώστε να μπορείς να δεις την απόδοση σου μηνιαία, ετήσια ή ακόμη και εβδομαδιαία. Οι εντολές του είναι πάρα πολλές για να τις παραθέσουμε εδώ αλλά μπορεί: 
    * task add [task_description], να δημιουργήσει διεργασίες. 
    * task [task_id] modify project:[project_name], να τις αποδώσει σε κάποιο project.
    * task [task_id] modify +[tag], να τους βάλει tags.
    * task [task_id] modify prio:[Low||Medium||High], να ορίσει priority (Low-Medium-High). 
    * task [task_id] modify due:[due_date || weeks || days ]  (etc.), να ορίσει ημερομηνία λήξης της διεργασίας. 
    * task [task_id] modify recur:[when_to_reocurr || how_often], όπως και recursion. 
    * task [task_id] modify depends:[task_id], να ορίσουμε πως μία διεργασία είναι εξαρτώμενη από μία άλλη που πρέπει να ολοκληρωθεί πρώτα.
    
  Το TaskWarrior έχει ένα σύστημα Urgency όπου αποδίδει αυτόματα τιμές στις διεργασίες με βάση τί πιστεύει εκείνο πως επείγει. Μπρούμε φυσικά να παρέμβουμε και να δώσουμε τις δικές μας τιμές ή ακόμη και να το απενεργοποιήσουμε εντελός. Είναι εν κατακλείδι ένα πολύ ισχυρό εργαλείο που αν κάποιος το χρησιμοποιήσει στο έπακρο έχει να προσφέρει αρκετή λειτουργικότητα. Από την άλλη αν χρειαζόμαστε απλά ένα "todo list" λογισμικό τότε ίσως να είναι καλύτερη ιδέα να καταφύγουμε σε μία πιο απλή λύση.
    
## Παραδοτέο 2

### Assignment 4

### Assignment 5

### Assignment 6

## Συμπεράσματα

## Αναφορές-Πηγές

## Τελική Αναφορά
[Αναφορά](https://csakou.github.io/HCI_REPORT)