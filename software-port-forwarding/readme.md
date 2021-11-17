# Port-Forwarding του Helium Miner

## Εισαγωγή

Ο οδηγός αφορά όλους τους Miners από όλους τους κατασκευαστές.  
Προς το παρόν, ο οδηγός αφορά miners που είναι συνδεδεμένοι με καλώδιο Ethernet.  
Το port-forwarding είναι απαραίτητο για να μπορέσει να λάβει μηνύματα ο miner απο το helium network.  

> Το μοναδικό port που πρέπει να ανοίξετε είναι το 44158. Προσοχή! Μήν ανοίξετε άλλα ports εκτός και αν γνωρίζετε τι κάνετε.

## Προαπαιτούμενα

### Admin Rights on the router

Αν παίρνετε internet ως guest, πολύ πιθανόν o admin να μην σας επιτρέψει να κάνετε port-forwarding.

### Routable public IP

Πολύ πιθανόν, ο πάροχος του internet έχει κάνει για λόγους ασφαλείας το δίκτυό σας CG-NAT.
Αυτό εμποδίζει το miner να δεχτεί μηνύματα μέσω ιντερνετ.
Επικοινωνήστε με τον πάροχό σας να απενεργοποιήσει το CG-NAT, ώστε να έχετε ένα routable public IP.
Αυτό το ζήτημα το έχουν αντιμετωπίσει όχι μόνο για mining αλλά και όσοι έχουν κάμερες στο σπίτι που θέλουν να βλέπουν απομακρυσμένα, ή και σε gaming consoles.

## Port Forwarding

- [Cosmote Speedport Plus](cosmote/speedport-plus-port-forwarding.md)


## Επιβεβαίωση

Απο ένα browser, άνοιξε το https://portchecker.co/
Κράτησε την ip που σου προτείνει και στο port number βάλε 44158.
Αγνόησε το drop down δεξιά, είναι για επιλογή port.
Κανε Κλικ στο Check
Αν δείς το παρακάτω μήνυμα είσαι ΟΚ!
`Port 44158 is open`

## Troubleshooting

1. Check τα προαπαιτούμενα!
1. Search στο #software-port-forwarding του [Helium Greece Discord](https://discord.gg/EY6cfmay)
ίσως και άλλοι έχουν το ίδιο πρόβλημα
1. Ρώτα στο #software-port-forwarding του Helium Greece Discord

## Feedback

Έχεις ιδέες για να βελτιώσουμε αυτή τη σελίδα; Σε δυσκόλεψε ή σε παραπληροφόρησε κάτι;  
Μοιράσου το στο #software-port-forwarding. Ευχαριστούμε!

## Resources

Resources used for this guide
- [Helium Greece Discord](https://discord.gg/EY6cfmay)
- [Jason's workflow](https://cdn.discordapp.com/attachments/901775195025596446/908303528148234300/relay-v6.jpg)