# Towards LLM-based semantic analysis of historical legal documents

## Experiments Pipeline

![pipeline_v2](https://github.com/AndreasSoularidis/LLM_historical_legal_documents/assets/20847732/71ed76e6-6e0a-4a50-a4c7-41220bc2c529)

## Examples

## Transcription Phase

![transcription_phase](https://github.com/AndreasSoularidis/LLM_historical_legal_documents/assets/20847732/6a04a4aa-4e4b-41c5-8c5c-b895ad393769)

### Phase 1 
**Prompt:**

### Phase 2
**Prompt:** Ποιά είναι η σχέση των συμβαλλόμενων προσώπων; 
In New York today, on the fifth (5th) day of August in the year one thousand nine hundred sixty-five (1965), Wednesday, at my nota-ry office located at 7 Warren St, on the ground floor of the building owned by me, the undersigned notary and resident of New York, the following individuals, known to me and not exempt from the law, presented themselves: 1) Mr. John Doe, a businessman born in New Jersey in 1920, residing in New York, holder of Identifica-tion Card number AK 17546 issued on 02/11/1932 by the New York Police Department, with Tax Identification Number (TIN) 111064589, 2) Mr. Robert Doe, a businessman born in New York in 1940, residing in New York, holder of Identification Card number AK 87432 issued on 22/05/1955 by the New York Police Depart-ment, with TIN 182200769. They requested that I draft this docu-ment, and they declared and affirmed the following: A) DESCRIPTION OF INHERITED REAL ESTATE AND TITLES On the fifth (5th) day of August in the year one thousand nine hundred sixty-five (1965), John Doe, retired, born in 1940 in New Jersey, with TIN 176352089, bequeaths to his son Robert Doe the following described properties, all located in New Jersey:

**ChatGPT-3.5:** Το παραπάνω κείμενο φαίνεται να αναφέρεται σε έναν νοτάριο στη Νέα Υόρκη, ο οποίος καταγράφει ένα έγγραφο που σχετίζεται με τη μεταβίβαση κτηματικής περιουσίας από τον John Doe στον γιο του Robert Doe. Το έγγραφο φαίνεται να καθορίζει λεπτομερώς την κτηματική περιουσία που μεταβιβάζεται, καθώς και τα πρόσωπα που εμπλέκονται.Πιο συγκεκριμένα, το έγγραφο παρουσιάζει τους παρακάτω ανθρώπους:
1. Ο κ. John Doe, επιχειρηματίας γεννημένος στο Νιού Τζέρσεϊ το 1920, κατοικεί στη Νέα Υόρκη. Δίνονται πληροφορίες όπως ο αριθμός της ταυτότητάς του, ο αριθμός ταυτότητας του από την αστυνομία της Νέας Υόρκης, και ο φορολογικός του αριθμός.
2. Ο κ. Robert Doe, επιχειρηματίας γεννημένος στη Νέα Υόρκη το 1940, κατοικεί επίσης στη Νέα Υόρκη. Δίνονται παρόμοιες πληροφορίες όπως ο αριθμός της ταυτότητάς του, ο αριθμός ταυτότητας από την αστυνομία της Νέας Υόρκης, και ο φορολογικός του αριθμός.

Στη συνέχεια, το έγγραφο φαίνεται να περιγράφει λεπτομερώς την κτηματική περιουσία που μεταβιβάζεται από τον John Doe στον Robert Doe στη Νιού Τζέρσεϊ στις 5 Αυγούστου 1965.
Η σχέση των συμβαλλόμενων προσώπων σε αυτήν την περίπτωση είναι η μεταβίβαση περιουσίας από τον πατέρα (John Doe) στον γιο (Robert Doe) με τη χρήση ενός νοταριακού έγγραφου. Η σχέση αυτή φαίνεται να είναι μια συμφωνία μεταξύ τους για τη μεταβίβαση της κτηματικής περιουσίας και άλλων σχετικών λεπτομερειών.

**Prompt Translation**
Traslation: What is the relationship between the parties?

***Response Translation*** 
**ChatGPT-3.5:** The above text appears to refer to a notary public in New York, who is recording a document concerning the transfer of real estate from John Doe to his son Robert Doe. The document appears to describe in detail the real property transferred and the persons involved; in particular, the document lists the following persons:
1. Mr. John Doe, a businessman born in New Jersey in 1920, residing in New York City. Information is provided such as his New York City Police Department identification number, his New York City Police Department identification number and his tax identification number.
2. Mr. Robert Doe, a businessman born in New York in 1940, also resides in New York. Similar information is provided, including his New York City Police Department identification number, his New York City Police Department registration number and his tax identification number.
The document then appears to detail the real property transferred from John Doe to Robert Doe in New Jersey on August 5, 1965.
The relationship of the parties in this case is the transfer of real property from father (John Doe) to son (Robert Doe) by the use of a deed. This relationship appears to be an agreement between them to transfer the property and other relevant details.

### Phase 3
**Prompt:** Μπορείς να κατανοήσεις το παρόν κείμενο; 
Ἐν λαρίσσῃ σήμερον την Κατην τοῦ μηνός Νοεμβρίου τοῦ χιλιοστοῦ ὀκτακοσιοστοῦ ὀγδο ηκοστοῦ πρώτου ἕτους, ἠμέραν Τετάρτην ἐνώπιον ἐμοῦ τοῦ Συμβολαιογράφου λαρίσσης ἀναστασίου Γ. Φίλιου καὶ τῶν προσυπογεγραμμένων δύο μαρτύρων γνωστῶν μου πο-
λιτῶν ἐλλήνων καὶ μη ἐξαιρετέων κου Χρήστου Α. Μπλάτσα ἔμπορον καὶ Ἀβραάμ Μ. Κοέν ἀργυραμοιβοῦ ἀμφοτέρων κατοίκων Λαρίσσῃς, ἐνεφανήσθη ὁ ἐπίσης γνωστός μου καὶ μη ἐξαιρετέος κύριος Χουσνῆ Ναρούφ ἐφφένδης κτηματίας κάτοικος λαρίσσῃς καὶ ἐδήλωσεν ὅτι εἰ ὅλοι ἐν
γένη τὸ ἐκκρεμμές ἥδη καὶ μελλούσας ἀναφορά καὶ ἀπό θέσις τοῦ περί παντός ἀντικειμένου καὶ κατά παντός ἀντιδίκου του διορίζει καὶ ἀποκαθιστά πληρεξούσιον καὶ ἀντιπρόσωπον του τὸν ἐνταυθα Δικηγόρον κ. Γεώργιον Τἐτσην ἐς ὅν παρέχει τὸ δικαίωμα να πα-
ρίσταται ἀντ΄αὐτοῦ ἐνώπιον ἀπαντων τῶν ἐνταύθα Δικασητρίων καὶ ὑπερασπίζεται καθ΄ὅλους τοὺς νόμιμους τρόπους ἐπιχειρών ὅλοι τὰ κύριας καὶ ἐν παρόδῳ πράξες τὰ προβλεπομένα ἀπό τ΄ἄρθρ. 95 καὶ 96 τὰ οἰκονομίας, ἱδίως δε να προσκαλεῖ, ἐξετάζει καὶ ἐξαιρεῖ μάρτυρας 
καὶ ἐνώπιον εἰσηγητῶν να διορίζει διαιτητάς καὶ πραγματογνώμονες πρακτικῶν εξαιρέσεις κατἀ ---- κατά δικαστῶν καὶ δικαστικῶν ὑπαλλήλων, ν΄ἐνεργεί ἀναγκαστικά καὶ συντηρητικά μέτρα κατά παντός ἀντιδίκου του πρὸς δε πείρος συμβιβασμῶν καὶ συγκαταβατικές συμφωνίες ἀνακοινώσεις δικῶν καὶ παρεμβάσεις καὶ τὸ ἔνδικον μέσον τῆς ἀνεραίσεως καὶ τῆς ἐπαναλήψεως τὶς διαδικασίες ἀποδέχηται καὶ ἐκτελεῖ ἀνακάπτη καὶ ἐκκαλεῖ παντός εἴδους ἀποφάσεις ἐν γένει καὶ ἐν μέρει, νὰ παραιχηται ἀπό τινός ἐνδίκου μέσου καὶ τῆς ὅλος δίκης καὶ τῆς ὁρκοδο-
σίας διαδίκων ἥ μαρτύρων να ἐπά γῃ δέχηται καὶ ἀντεπάγῃ ὅρκους καὶ να ἀπογράφῃ παν δικόγραφον καὶ παν ἄξιο ἕγγραφον χρῆζον ὑπογραφῆς, να διορίζῃ ἐν ἀνάγκη καὶ ἄξιους πληρεξουσίους καὶ ἐν γένει να πράττῃ πάν ὅτι ἀποτελεῖ τὸ συμφέρον τοῦ ἐντολέως τοῦ ὑποσχομένου τοῦτον τὴν πλήρη παραδοχῆν τῶν πράξεων τοῦ ὁ νομίμων καὶ ---των τῆ βεβαίωσιν συνετάχθῃ τὸ παρόν ἐντός τοῦ γραφείου μου ὅπερ ἔχω ὑπό τῶν 3η σελίδα διεγράφησαν τρεῖς λέξεις ἐν τῶν ἀποθηκῶν τοῦ Α. Χαϊμ Αλχαν τὰ κειμένων εἰς θέσιν παζάρι τῆς πόλεως ταῦτης καὶ ἀναγνωσθέν εὐκρι
νῶς καὶ μεγαλοφώνως εἰ ἐπήκοον τοῦ εντολέως καὶ τῶν μαρτύρων ὑπογραφεται παρ’αὐτῶν καὶ ἐμοῦ ὁ δὲ ἐντολεύς ὑπέγραψε τουρκιστί οἱ ἐντολεῖς οἱ μάρτυρες Ἀβραἀμ Μ. Κοέν

**ChatGPT-3.5:** Αυτό το κείμενο είναι γραμμένο στην αρχαία ελληνική γλώσσα (αρχαία ελληνική παράγωγη του κειμένου σε γράμματα). Πρόκειται για ένα νομικό έγγραφο ή ένα επίσημο κείμενο που περιγράφει μια νομική διαδικασία ή συμφωνία μεταξύ διάφορων ατόμων. Ο τρόπος γραφής και οι φράσεις που χρησιμοποιούνται αντιπροσωπεύουν τη γλώσσα που χρησιμοποιούνταν στην αρχαία Ελλάδα.

**Prompt Translation**
Can you understand this text?

**Response Translation**
**ChatGPT-3.5:** This text is written in Ancient Greek (Ancient Greek derivation of the text in letters). It is a legal document or an official text describing a legal procedure or agreement between different people. The style of writing and the phrases used represent the language used in ancient Greece.

### Phase 4
**Prompt:** Μπορείς να κατανοήσεις τον τύπο του κειμένου; 
**ChatGPT-3.5:** Το παραπάνω κείμενο είναι ένα κείμενο που αναφέρεται σε ένα συμβόλαιο ή εντολή (συμφωνία) μεταξύ τριών ατόμων, δηλαδή του Συμβολαιογράφου (λογογράφου), του Χουσνῆ Ναρούφ (εντολεύοντος), και δύο μαρτύρων (Αβραάμ Μ. Κοέν και Χρήστου Α. Μπλάτσα). Το κείμενο περιγράφει τις υποχρεώσεις και τα καθήκοντα που έχει ο εντολεύων προς τον Δικηγόρο Γεώργιον Τέτσην. Ο εντολεύων διατάσσει στον Δικηγόρο να παρασταθεί εξ ονόματός του σε δικαστικές διαδικασίες και να εκπροσωπεί τα συμφέροντά του. Επίσης, αναφέρει τις αρμοδιότητες του Δικηγόρου, όπως τη διορισμό διαιτητών, την εξεταστική διαδικασία, τη διακανονιστική διαδικασία, και άλλες νομικές διαδικασίες. Επιπλέον, το συμβόλαιο αναφέρει την υποχρέωση του εντολεύοντος να παραδίδει όλα τα έγγραφα και να υπογράφει κάθε απαραίτητο έγγραφο.
Συνοπτικά, πρόκειται για ένα νομικό κείμενο που ορίζει τις υποχρεώσεις και τα καθήκοντα ενός Δικηγόρου στο πλαίσιο συγκεκριμένης νομικής υπόθεσης.

**Prompt Translation**
Can you understand the type of text? 

**Response Translation**
**ChatGPT-3.5:** The above text is a text that refers to a contract or command (agreement) between three persons, namely the Notary (logographer), Husni Naruf (the one who commands), and two witnesses (Abraham M. Cohen and Christos A. Blatsa). The text describes the obligations and duties of the principal towards the lawyer George Tetsin. The principal instructs the Attorney to appear on his behalf in court proceedings and to represent his interests. It also states the powers of the Attorney, such as the appointment of arbitrators, the examination process, the settlement process, and other legal proceedings. In addition, the contract states the obligation of the attorney to deliver all documents and sign any necessary documents.
In summary, it is a legal document that defines the obligations and duties of an attorney in the context of a specific legal case.

## ChatGPT-3.5 vs Gemini/Bard metrics

![image](https://github.com/AndreasSoularidis/LLM_historical_legal_documents/assets/20847732/ec62e1f4-5830-466e-a508-881caf8f13ec)

![image](https://github.com/AndreasSoularidis/LLM_historical_legal_documents/assets/20847732/0ec58f46-22cd-41aa-8878-010d2b0c3ad2)

