# Lesson: Interaction Design

### First and Last Name: Χρήστος Ντουσόπουλος Γιώργος Παχής Έκτωρ Καραβάς
### University Registration Number: dpsd14074 dpsd17084 dpsd14035
### GitHub Personal Profile: https://github.com/GeorgePachis

# Introduction

# Summary


# 1st Deliverable
### 1)Brief:
Σχεδιάζουμε ένα υφασμάτινο σύστημα (e-textile) απεικόνισης ζωτικής κατάστασης ενός αθλητή κατά την διάρκεια της σωματικής του άσκησης. Στόχος μας είναι, ο χρήστης να μπορεί να έχει τόσο μια στιγμιαία εκτίμηση της κατάστασης του, όσο και να έχει πρόσβαση σε συνολικά στατιστικά της απόδοσής του μέσω app.


### 2)Έρευνα με βάση το PACT ( People Activities Context Technology )

##### i)People:
Ως χρήστες ορίστηκαν οι αθλητές ηλικίας 25-45 ετών καθώς και άτομα τα οποία πάσχουν από Deuteranomaly(red-green colour blindness) καθώς και από κώφωση. Θέλουν να ακολουθούν ένα υγιεινό τρόπο ζωής, ασχολούνται με το τρέξιμο σαν είτε ως χόμπι είτε επαγγελματικά και επιθυμούν να βελτιώσουν την κατάσταση της υγείας τους. Τέλος, είναι εξοικειωμένοι με την τεχνολογία που χρησιμοποιείται στα σύγχρονα αθλητικά gadget.

##### ii)Activities:
Οι δρομείς τρέχουν έχοντας μαζί τους αθλητικά όργανα μέτρησης.  Εκτός από αυτό, βασικός τους εξοπλισμός είναι ισοθερμικά σορτσάκια και μπλούζες για να ανεβάσουν στην αρχή και έπειτα να διατηρήσουν την θερμοκρασία του σώματος και τσαντάκι μέσης για μεταφορα προσωπικών αντικειμένων όπως το κινητό, το πορτοφόλι και ένα μπουκαλάκι νερό. Η διάρκεια της δραστηριότητας διαφέρει εξαιτίας διαφορετικών προσωπικών παραγόντων. Με την δική μας παρέμβαση ο δρομέας θα έχει ταυτόχρονη πρόσβαση στις διαφορετικές ενδείξεις του gadget (π.χ παλμούς καρδιάς, επίπεδα οξυγόνου) ενώ τρέχει.Ταυτόχρονα το GPS θα του προτείνει πιθανές διαδρομές βάσει των προτιμήσεών του (απόσταση, χρόνο) .   Οι δρομείς οι οποίοι επιλέγουν να αθλούνται σε εξωτερικό χώρο τις περισσότερες φορές επιλέγουν να μην πάρουν μαζί τους πολλά προσωπικά αντικείμενα καθώς τα ρούχα που φορούν δεν τα κρατούν ασφαλή κατά τη διάρκεια της δραστηριότητας καθώς επίσης πολλές φορές δεν διαθέτουν και κάποιο αποθηκευτικό χώρο (τσέπες).
Παίρνουν λοιπόν μαζί τους λίγα αντικείμενα καθώς και κάποιο wearable της επιλογής τους το οποίο συνήθως είναι της μορφής κάποιου smartwatch ή κάποιας συσκευής (ipod, mp3) που με τη χρήση ειδικής θήκης που φορούν επιπλέον στηρίζουν στο μπράτσο τους. 

##### iii)Context:
Η δραστηριότητα λαμβάνει χώρα σε εξωτερικό χώρο ο οποίος έχει καλές καιρικές συνθήκες χωρίς να αποκλείουμε και κάποιες πιο ακραίες περιπτώσεις. Επίσης υπάρχει διαφορά στο φώς ανάλογα με την ώρα της μέρας.Επίσης η δραστηριότητα πραγματοποιείται αστικό περιβάλλον. 

##### iv)Technology:
Με βάση το project που επιλέξαμε και έπειτα από συζήτηση καταλήξαμε στα παρακάτω components, δίπλα από κάθε component παρατίθεται η πηγή του: 

Conductive thread:[Πατήστε εδώ](https://www.sparkfun.com/products/11791/) 

Πλακέτα LilyPad: [Πατήστε εδώ](https://www.sparkfun.com/products/13342)

Lilypad vibe board:[Πατήστε εδώ](https://www.sparkfun.com/products/11008)

Lilypad gps: [Πατήστε εδώ](https://www.hellasdigital.gr/electronics/sensors/gps/neo-6m-gps-module-aircraft-flight-controller-for-arduino-mwc-imu-apm2/?sl=en)

Rgb led: [Πατήστε εδώ](https://www.sparkfun.com/products/13735) 

Θήκη για battery:[Πατήστε εδώ](https://www.sparkfun.com/products/13883)

Heart rate oximeter sensor: Πατήστε εδώ[[1]](https://www.sparkfun.com/products/15219) ή εδώ
[[2]](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/mcu-and-components/heart-pulse/max30100-heart-rate-oximeter-pulse-sensor-module/)

NeoLed: [Πατήστε εδώ](https://www.sparkfun.com/products/12661)


Παρακάτω χωρίζουμε τα component αναλόγως τον ρόλο τους:

Input:heart rate oximeter sensor, gps, battery, vibe board

Output: rgb leds,neoled

Communication: πλακέτα Lilypad, conductive thread 

Content: Οι πληροφορίες που θα παρέχει η συσκευή στον χρήστη θα είναι σχετικά με την υγεία του και τις βασικές λειτουργίες του σώματός του.
Όπως φαίνεται και στην εικόνα στην θήκη της μπαταρίας, η οποία μπορεί να ραφτεί πάνω σε ύφασμα, έρχεται και κουμπώνει μια μπαταρία λιθίου των 3v. 
![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/Battery.png)

Πηγή εικόνας:[Εδώ](https://learn.sparkfun.com/tutorials/lilypad-basics-e-sewing/installing-your-battery-and-testing-your-finished-circuit)


# 2nd Deliverable
### 3)Information architecture

Ο εγκέφαλος αυτού του συστήματος είναι η πλακέτα Lillypad πάνω στην οποία θα συνδέονται όλοι οι αντίστοιχοι αισθητήρες που θα αναλυθούν παρακάτω. Τα διάφορα components θα συνδέονται με την πλακέτα μέσω ενός conductive thread το οποίο θα είναι ραμμένο πάνω στο ύφασμα του ρούχου.
Αρχικά στην θήκη της μπαταρίας θα τοποθετείται μπαταρία λιθίου η οποία θα έχει συγκεκριμένο χρόνο ζωής. Το vibe board δέχεται ως input κάποιες τιμές και παράγει δόνηση. Στο project μας σκοπεύουμε μέσω κώδικα να προγραμματίσουμε το lilypad ώστε όταν δέχεται μια συγκεκριμενη τιμή να δονείται ο συγκεκριμένος αισθητήρας ώστε να ενημερώνει τον χρήστη ότι έφτασε κάποιο όριο( π.χ. στους καρδιακούς του παλμούς ).
Επίσης το σύστημα θα διαθέτει gps μέσω του οποίου θα φαίνεται μέσω app απ το κινητό η τοποθεσία του αθλητή κάθε χρονική στιγμή.
Τέλος χρησιμοποιούνται rgb leds τα οποία θα ανάβουν αναλόγως με τις τιμές που θα δέχεται το lilypad απο τους αισθητήρες.

Όσον αφορά το περιβάλλον του app, αρχικά θα εμφανίζει μια σελίδα για εγγραφή ή σύνδεση στον λογαριασμό σου. Μετά θα μεταβαίνεις στην κύρια σελίδα στην οποία θα φαίνονται τα βασικά στοιχεία τα οποία θα μπορείς να ρυθμίσεις τα όριά τους, δηλαδή τoν χρόνο, την απόσταση που θες να διανύσεις και οι θερμίδες που θες να κάψεις.

### Αρχική σελίδα:

![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/Sign_in_Page.jpg)

Και τα τρια αυτά στοιχεία θα έχουν ένα συγκεκριμένο σύμβολο. 
Κάτω από αυτά τα σύμβολα θα υπάρχουν κάποιες προκαθορισμένες προτεινόμενες επιλογές αλλά θα δίνεται η επιλογή στον χρήστη να βάλει δικά του κριτήρια (επιλογή custom). Θα υπάρχει και μία επιλογή που θα σε πλοηγεί σε μία τρίτη σελίδα όπου θα φαίνονται στατιστικά που αφορούν τους καρδιακούς παλμούς και τα επίπεδα του οξυγόνου. Τέλος, θα υπάρχει και μία σελίδα που θα περιέχει το ιστορικό των προηγούμενων διαδρομών που έχεις ακολουθήσει.

![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/Choice_Page.jpg)

### Σελίδα με στατιστικά:
![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/Statistics_Page.jpg)
Ακολουθεί και ένα σχεδιάγραμμα όλων των επιλογών πλοήγησης που μπορεί να έχει ο χρήστης μέσα στην εφαρμογή:
![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/1%20(1).jpg)
### 4) User Interface
Το υπό σχεδίαση αντικείμενο θα είναι και αυτό wearable για το χέρι προκειμένου να αποφευχθούν τα προβλήματα που προαναφέρθηκαν. Παρόλα αυτά, δεν θα επιβαρύνει καθόλου τον χρήστη καθώς θα είναι κατασκευασμένο από λεπτο ύφασμα ειδικό για αθλητικό εξοπλισμό.Τα wearables τύπου smartwatch που χρησιμοποιούνται από τους χρήστες δεν έχουν “τέλεια” εφαρμογή με το χέρι του χρήστη καθώς με την κίνηση μπορεί να μην μένουν σταθερά και αν ο χρήστης τα σφίξει παραπάνω μπορεί να τραυματιστεί ή απλώς να νιώθει μια ενόχληση στο συγκεκριμένο σημείο. Ταυτόχρονα ο ιδρώτας μπορεί να λερώσει η να φθείρει τη συσκευή.

Με τη χρήση υφάσματος, το αντικείμενο θα έχει “τέλεια” εφαρμογή στο χέρι του χρήστη καθώς και θα είναι ελαφρύ ανθεκτικό και θα αναπνέει προκειμένου να μην προκαλέσει ερεθισμούς στον χρήστη. Αφού έχει κατεβάσει το app στο κινητό του, θα επιλέγει διάφορες ρυθμίσεις προσωποποίησης του αντικειμένου (π.χ χρώμα LED, LED modes). Μόλις το φορέσει ο χρήστης θα πρέπει να το ενεργοποιησει κρατώντας το κουμπί παρατεταμένα για 5 δευτερόλεπτα και αυτόματα κάνει σύζευξη με το κινητό και την εφαρμογή . 

Κατα τη διάρκεια της διαδικασίας, ο χρήστης μπορεί επίσης με το πάτημα του κουμπιού για 2 sec θα μπορεί να αλλάζει μεταξύ των ενδείξεων δηλαδή θα αλλάζουν χρώμα τα RGB και κάθε χρώμα αντιστοιχεί σε ενα mode ( θερμιδες Β , απόσταση G, χρόνος R). Με τη χρήση GPS και λαμπτήρων LED οι οποίοι θα υποδεικνύουν πότε ο χρήστης θα πρέπει να στρίψει θα έχει τη δυνατότητα να του προτείνει διαφορετικές διαδρομές τις οποίες μπορεί να ακολουθεί ανάλογα με τον χρόνο που αυτός διαθέτει ή την απόσταση που έχει προκαθοριστεί. Εναλλακτικά σε περίπτωση που ο χρήστης δεν ακολουθήσει την προτεινομενη διαδρομή, οι λαμπτήρες που υποδηλώνουν την αλλαγή πορείας ενεργοποιούνται με το στιγμιαίο πάτημα του κουμπιού που βρίσκεται στο πάνω μέρος του αντικειμένου. Ταυτόχρονα με διαφορετικούς λαμπτήρες θα μπορεί να βλέπει σε πραγματικό χρόνο την πρόοδο που έχει κάνει (πχ απόσταση,χρόνο, θερμίδες) σύμφωνα με τον στόχο που έχει θέσει από πρίν.Τέλος, η διαύγεια των λαμπτήρων θα είναι αυξομειούμενη προκειμένου να μπορούν να τον παρατηρούν οι οδηγοί οχημάτων τόσο τη μέρα όσο και τη νύχτα. Αφού τελειώσει η δραστηριότητα, ο χρήστης έχει τη δυνατότητα να δει στατιστικά σχετικά με την απόδοσή του, την πρόοδο πρός τους στόχους που έχει θέσει, καθώς και την κατάσταση του οργανισμού του από την εφαρμογή στο κινητό του. 
Το αντικείμενο στη συνέχεια μπορεί να πλυθεί στο πλυντήριο αφου αφαιρεθουν τα αποσπώμενα ηλεκτρονικά μέρη του. Μολις τελειώσουν οι μπαταρίες ο χρήστης την αφαιρεί και την αντικαθιστά.
### 5) Interface Components

#### Button

Το σύστημα διαθέτει ένα κουμπί με το οποίο ο χρήστης μπορεί να αλληλεπιδράσει με τρεις διαφορετικούς τρόπους:
Κρατώντας πατημένο το κουμπί παρατεταμένα  για 5 δευτερόλεπτα, ο χρήστης ενεργοποιεί/απενεργοποιεί τη συσκευή η οποία συγχρονίζεται αυτόματα με το κινητό.
Με το πάτημα του ίδιου κουμπιού παρατεταμένα για 2 δευτερόλεπτα θα μπορεί να αλλάζει το mode με το οποίο ανάβουν τα LED τα οποία προβάλλουν το περιβραχιόνιο, ετσι ώστε να ενημερώνεται το περιβάλλον του χρήστη για την ύπαρξή του. 
Τέλος με το απλό πάτημα του κουμπιού εναλλάσσεται η απεικόνιση μεταξύ των τριών στόχων που έχει θέσει ο χρήστης (απόσταση,χρόνος,θερμίδες) καθώς και της ένδειξης της μπαταρίας στην μπαρα LED η οποία είναι τοποθετημένη δίπλα από αυτό (κουμπί). 
Το κουμπί είναι συνδεδεμένο απευθείας με το LilyPad.

#### NeoLed 

Τα συγκεκριμένα LED είναι 8 στη σειρά και χρησιμοποιούνται για δείχνουν στον χρήστη την πρόοδο που κάνει όσον αφορά τους στόχους του σε πραγματικό χρόνο καθώς και την στάθμη της μπαταρίας. Συνδέονται με το LilyPad απευθείας αφού είναι απαραίτητο προκειμένου να παίρνει ο χρήστης αντίστοιχα τα δεδομένα.

#### RGB LED strip

Η ταινία LED θα είναι ραμμένη περιμετρικά γύρω από το περιβραχιόνιο και στόχος της είναι να ενημερώνει το περιβάλλον του χρήστη για την ύπαρξή του ( π.χ να είναι εμφανής από μακριά στους οδηγούς οχημάτων). Ο φωτισμός της ταινίας ποικίλει και ο χρήστης μπορεί να τον αλλάξει μεταξύ πολλών διαφορετικών modes με το πάτημα του κουμπιού για 2 δευτερόλεπτα. Συνδέεται με το LilyPad.


#### RGB LED 

Η συσκευή θα διαθέτει και δυο ξεχωριστά LED τοποθετημένα δεξιά και αριστερά του κουμπιού. Βy default το αριστερό αντιστοιχεί στο οξυμετρο και το δεξί στο εύρος των καρδιακών παλμών τα οποία αναπαρίστανται χρωματικά (μπλε χαμηλα , πρασινο φυσιολογικά, κοκκινο υψηλά). Όταν ο χρήστης προκαθορισει μέσω του app συγκεκριμένη διαδρομή που θα ακολουθήσει τότε αυτά τα δυο LED αποκτούν και ακόμα μια χρήση.Η ένδειξη παραμένει στο default (οξυμετρο, παλμοι) κατά τη διάρκεια κίνησης του χρήστη, ενώ όταν μέσω GPS αντιληφθεί ότι βρίσκεται 10 μέτρα πριν από τη στροφή την οποία πρέπει να ακολουθήσει η συσκευή δονείται και αναβοσβήνει το αντίστοιχο LED πορτοκαλί χρώματος (δεξί και αριστερό)έως ότου ο χρήστης ολοκληρώσει την κίνηση αλλαγής κατεύθυνσης. Είναι συνδεδεμένα απευθείας στο LilyPad.

#### App
Μέσω της εφαρμογής, ο χρήστης έχει τη δυνατότητα να θέσει 3 διαφορετικούς στόχους:
Χιλιομετρική απόσταση που θέλει να διανύσει 
Χρονικό διάστημα για το οποίο θα εκτελει τη δραστηριότητα 
Τις θερμίδες τις οποίες θέλει να κάψει
Η αναπαράσταση του στόχου καθώς και η πρόοδος αυτού θα αναπαριστώνται από ταινία led η οποία θα προσομοιώνει το effect φόρτισης. Η σύνδεση του app και της συσκευής γίνεται με bluetooth.

Επίσης, θα μπορεί να προκαθοριζει και να σώζει διαφορετικές διαδρομές προκειμένου να έχει πρόσβαση και καθοδήγηση από το GPS.Ταυτόχρονα θα μπορεί να αλλάζει τα χρώματα των ενδείξεων σύμφωνα με τις προτιμήσεις του καθώς και να βλέπει στατιστικά που αφορούν τις επιδόσεις του αλλά και την εξέλιξή του.
Η σύνδεση όλων των μερών του λογισμικού θα είναι παράλληλη.


# 3rd Deliverable 
Storyboard

![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/1.jpg)



Prototyping
Το πρωτότυπό μας: 

![This is an image]()

Ο κώδικας που χρησιμοποιήθηκε:


#include <Adafruit_NeoPixel.h>

#include <SparkFun_Bio_Sensor_Hub_Library.h>

#include <Wire.h>

 
// No other Address options.

#define DEF_ADDR 0x55

 
#define PIN 7

// How many NeoPixels are attached to the Arduino?

#define NUMPIXELS 8

Adafruit_NeoPixel pixels = Adafruit_NeoPixel(NUMPIXELS, PIN, NEO_GRB + NEO_KHZ800);

 
 
// Reset pin, MFIO pin

int resPin = 4;

int mfioPin = 5;

 
// Takes address, reset pin, and MFIO pin.

SparkFun_Bio_Sensor_Hub bioHub(resPin, mfioPin);

 
bioData body;

// ^^^^^^^^^
// What's this!? This is a type (like int, byte, long) unique to the SparkFun
// Pulse Oximeter and Heart Rate Monitor. Unlike those other types it holds
// specific information on your heartrate and blood oxygen levels. BioData is
// actually a specific kind of type, known as a "struct".
// You can choose another variable name other than "body", like "blood", or
// "readings", but I chose "body". Using this "body" varible in the
// following way gives us access to the following data:
// body.heartrate  - Heartrate
// body.confidence - Confidence in the heartrate value
// body.oxygen     - Blood oxygen level
// body.status     - Has a finger been sensed?

 
 
 
void setup() {

 
  Serial.begin(115200);
  
  
 
  Wire.begin();
  
  int result = bioHub.begin();
  
 
 
  pixels.begin();  // This initializes the NeoPixel library.
  
  for (int i = 0; i < NUMPIXELS; i++) {
  
    pixels.setPixelColor(i, pixels.Color(1, 1, 1));
    
  }
  
  pixels.show();
  
 
 
  long last_pix_upd = 0;
  
 
  int bpm = 0;
  
 
  long ms = millis();
  
  if (ms - last_pix_upd > 10)  //don't update pixels too often
  
  {
  
    int r, g, b;
    
    last_pix_upd = ms;
    
    int bpm = body.heartRate;
    
    float max_bright = 160;     //value of maximum brightness, max 255. But you don't always want it at max :)
    
    float dd = 25;              //change in BPM between color tones (blue->green->yellow->pink->red)
    
    
    float t1 = 90, t2, t3, t4;  //t1 - "base" BPM, lower than t1 would be blue
    
    
    t2 = t1 + dd;
    
    t3 = t2 + dd;
    
    t4 = t3 + dd;
    
    //code for changing color depending in which t1...t4 range we are now
    
    if (bpm < t1) {
    
      r = 0;
      
      g = 0;
      
      b = max_bright;
      
    } else if (bpm < t2) {
    
      r = 0;
      
      g = max_bright * (bpm - t1) / dd;
      
      b = max_bright - g;
      
    } else if (bpm < t3) {
    
      r = max_bright * (bpm - t2) / dd;
      
      g = max_bright - r;
      
      b = r / 4;
      
    } else if (bpm < t4) {
    
      r = max_bright;
      
      g = 0;
      
      b = max_bright / 2 - max_bright * (bpm - t3) / (2 * dd);
      
    } else {
    
      r = max_bright;
      
      g = 0;
      
      b = 0;
      
    }
    
    int on_pixels = (bpm - 80) / 8;  //since it's intended for running, I'm not
    
    //showing anything less than 80 BPM, this way it's more sensitive in
    
    //high load area
    
    for (int i = 0; i < NUMPIXELS; i++) {
    
      //pixels are set from last to first for no particular reason, would
      
      //work just as fine if set from first to last
      
      if (i < on_pixels) pixels.setPixelColor(NUMPIXELS - i - 1, pixels.Color(r, g, b));
      
      else
      
        pixels.setPixelColor(NUMPIXELS - i - 1, pixels.Color(0, 0, 0));  //turn off all other LEDs
        
    }
    
    pixels.show();
    
  }
  
}

 
 
 
void loop() {

 
  // Information from the readBpm function will be saved to our "body"
  
  // variable.
  
  
  body = bioHub.readBpm();
  
 
 
  // Slow it down or your heart rate will go up trying to keep up
  
  // with the flow of numbers
  
  delay(250);
  
}



# Conclusions
[](https://www.google.com)

# Sources
-https://learn.sparkfun.com/tutorials/lilypad-light-sensor-hookup-guide/all

-https://learn.sparkfun.com/tutorials/lilypad-development-board-hookup-guide/all 

-https://www.uxbooth.com/articles/complete-beginners-guide-to-information-architecture/?fbclid=IwAR3TKg4V9QYQ2C5VZ459DC_E2gt56sk-CyIKoCvCYtHqKQN8OIMA0ne2nuQ#what
