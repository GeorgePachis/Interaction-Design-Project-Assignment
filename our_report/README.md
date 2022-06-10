# Lesson: Interaction Design

### First and Last Name: Χρήστος Ντουσόπουλος Γιώργος Παχής Έκτωρ Καραβάς
### University Registration Number: dpsd14074 dpsd17084 dpsd14035
### GitHub Personal Profile: https://github.com/GeorgePachis

# Introduction

# Summary


# 1st Deliverable

### 1)Brief: 

Σχεδιάζουμε ένα υφασμάτινο σύστημα (e-textile) απεικόνισης ζωτικής κατάστασης ενός αθλητή κατά την διάρκεια της σωματικής του άσκησης. Στόχος μας είναι, οι προπονητές τους να μπορούν να βλέπουν σε πραγματικό χρόνο τους καρδιακούς παλμούς των αθλητών τους προκειμένου να μπορούν να αναγνωρίσουν ταλέντα καθώς και πότε αυτοί φτάνουν στα “όριά τους”.


### 2)Έρευνα με βάση το PACT ( People Activities Context Technology )

i)People: Ως χρήστες ορίστηκαν οι αθλητές ηλικίας 17-35 ετών οι οποίοι αθλούνται υπο την επίβλεψη προπονητή  καθώς και οι προπονητές τους οι οποίοι θέλουν να γνωρίζουν την κατάσταση των αθλητών τους. Ταυτόχρονα, οι γιατροί των αθλητών θα μπορούν να παρακολουθούν την κατάσταση της υγείας τους.Τέλος, είναι εξοικειωμένοι με την τεχνολογία που χρησιμοποιείται στα σύγχρονα αθλητικά gadget.

ii)Activities: Οι αθλητές οι οποίοι πραγματοποιούν την άσκησή τους υπό την επίβλεψη κάποιου προπονητή/εκπαιδευτή συνήθως ακολουθούν τις οδηγίες του. 
Παρόλα αυτά, πολλές φορές τα δεδομένα που έχουν διαθέσιμα οι προπονητές δεν είναι αρκετά προκειμένου να αποφασίσουν και κατ επέκταση να εκτελέσουν την κατάλληλη άσκηση για τον εκάστοτε αθλητή.Αυτό έχει ως αποτέλεσμα πολλές φορές υπερβαίνουν τα όρια των αθλητών ή να μην τα φτάνουν. Ταυτόχρονα, οι αθλητές που ασχολούνται με πρωταθλητισμό, χρειάζονται ειδική και προσωποποιημένη μεταχείριση όταν πρόκειται για ατομικό άθλημα αλλά και όταν πρόκειται για ομάδα πρέπει ο προπονητής να μπορεί να καταλαβαίνει πως όλοι του οι αθλητές βρίσκονται σε ίδια ή κοντινά επίπεδα φυσικής κατάστασης προκειμένου να έχουν την ίδια απόδοση καθώς σε μια ομάδα το αποτέλεσμα είναι το άθροισμα των επιμέρους ατομικών προσπαθειών και ενεργειών.

iii)Context: Η δραστηριότητα λαμβάνει χώρα σε εξωτερικό ή και κλειστό  χώρο ο οποίος εάν ανήκει στην πρώτη περίπτωση έχει καλές καιρικές συνθήκες χωρίς να αποκλείουμε και κάποιες πιο ακραίες περιπτώσεις καθώς υπάρχουν φορές - και ιδιαίτερα στον πρωταθλητισμό - κατα τις οποίες πραγματοποιούνται κανονικά οι προπονήσεις παρά τις δυσμενείς καιρικές συνθήκες. Η  δραστηριότητα πραγματοποιείται σε αστικό περιβάλλον και έχει διάρκεια από 1 έως 4 ώρες

iv)Technology: Με βάση το project που επιλέξαμε και έπειτα από συζήτηση καταλήξαμε στα παρακάτω components, δίπλα από κάθε component παρατίθεται η πηγή του: 

Conductive thread (https://www.sparkfun.com/products/11791 ) 

Πλακέτα LilyPad (https://www.sparkfun.com/products/13342

Θήκη για battery:https://www.sparkfun.com/products/13883 

Heart rate oximeter sensor: https://www.sparkfun.com/products/15219

NeoLed: https://www.sparkfun.com/products/12661


Παρακάτω χωρίζουμε τα component αναλόγως τον ρόλο τους:

Input: battery, Heart rate oximeter sensor

Output: NeoLed

Communication: Πλακέτα Lilypad, conductive thread 

Content: Οι πληροφορίες που θα παρέχει η συσκευή στον χρήστη θα είναι σχετικά με τους καρδιακούς παλμούς του.
Όπως φαίνεται και στην εικόνα στην θήκη της μπαταρίας, η οποία μπορεί να ραφτεί πάνω σε ύφασμα, έρχεται και κουμπώνει μια μπαταρία λιθίου των 3v. 
 
![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/Battery.png)

Πηγή εικόνας:[Εδώ](https://learn.sparkfun.com/tutorials/lilypad-basics-e-sewing/installing-your-battery-and-testing-your-finished-circuit)


# 2nd Deliverable

### 3)Information architecture

Ο εγκέφαλος αυτού του συστήματος είναι η πλακέτα Lillypad πάνω στην οποία θα συνδέεται το οξύμετρο. Τα διάφορα components θα συνδέονται με την πλακέτα μέσω ενός conductive thread το οποίο θα είναι ραμμένο πάνω στο ύφασμα του ρούχου.
Αρχικά στην θήκη της μπαταρίας θα τοποθετείται μπαταρία λιθίου η οποία θα έχει συγκεκριμένο χρόνο ζωής. Το οξύμετρο δέχεται ως input κάποιες τιμές και παράγει πληροφορία για τους καρδιακούς παλμούς. Στο project μας σκοπεύουμε μέσω κώδικα να προγραμματίσουμε το lilypad ώστε όταν δέχεται μια συγκεκριμενη τιμή να ανάβουν τα NeoLed ώστε να ενημερώνουν τον χρήστη ότι έφτασε κάποιο όριο στους καρδιακούς του παλμούς.


Ακολουθεί και ένα σχεδιάγραμμα όλων των επιλογών πλοήγησης που μπορεί να έχει ο χρήστης:

![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/%CE%A3%CF%87%CE%B5%CE%B4%CE%B9%CE%AC%CE%B3%CF%81%CE%B1%CE%BC%CE%BC%CE%B1.jpg)

Πηγή εικόνας:https://learn.sparkfun.com/tutorials/lilypad-basics-e-sewing/installing-your-battery-and-testing-your-finished-circuit 

Πηγές για Information architecture:
-https://www.uxbooth.com/articles/complete-beginners-guide-to-information-architecture/?fbclid=IwAR3TKg4V9QYQ2C5VZ459DC_E2gt56sk-CyIKoCvCYtHqKQN8OIMA0ne2nuQ#what 

### 4) User Interaction 

 
Το υπό σχεδίαση αντικείμενο θα είναι wearable στη μορφή προπονητικής φανέλας/μπλούζας.Δεν θα επιβαρύνει καθόλου τον χρήστη καθώς θα είναι κατασκευασμένο από λεπτο ύφασμα ειδικό για αθλητικό εξοπλισμό.
Με τη χρήση υφάσματος, το αντικείμενο θα έχει καλή εφαρμογή στον χρήστη καθώς και θα είναι ελαφρύ ανθεκτικό και θα αναπνέει προκειμένου να μην του προκαλέσει ερεθισμούς. 

Κατα τη διάρκεια της διαδικασίας, ο χρήστης μπορεί να παρακολουθεί τις ενδείξεις οι οποίες αναπαριστώνται χρωματικά μέσω των NeoLed και οι οποίες θα αντιστοιχούν σε τρεις διαφορετικές καταστάσεις καρδιακών παλμών. Η πρώτη αντιστοιχεί σε καρδιακούς παλμούς από 40-100 bpm(πράσινο χρώμα), η δεύτερη από 100-135bpm (κίτρινο χρώμα) η τρίτη από 135-170 bpm(πορτοκαλί χρώμα) και η τέταρτη απο 170 και πάνω(κόκκινο χρώμα). Με αυτόν τον τρόπο, οι αθλητές αλλά και οι προπονητές τους θα λαμβάνουν ανατροφοδότηση ανα πάσα στιγμή κατά τη διάρκεια της διαδικασίας και θα μπορούν να προσαρμόζονται στις ανάγκες των αθλητών τους και κατανοούν καλύτερα τα όριά τους. Το αντικείμενο στη συνέχεια μπορεί να πλυθεί στο πλυντήριο αφου αφαιρεθούν τα αποσπώμενα ηλεκτρονικά μέρη του. Μολις τελειώσει η μπαταρία ο χρήστης την αφαιρεί και την αντικαθιστά.

### 5) Interface Components

NeoLed 

Τα συγκεκριμένα LED είναι 8 στη σειρά και χρησιμοποιούνται για δείχνουν στον αθλητή αλλά και στον προπονητή  τους καρδιακούς του παλμούς (του αθλητή) σε πραγματικό χρόνο και σε εύρος τεσσάρων σταδίων. Συνδέονται με το LilyPad απευθείας αφού είναι απαραίτητο προκειμένου να μεταφράζονται τα αντίστοιχα δεδομένα σε ενδείξεις Led.


# 3rd Deliverable 
Storyboard

![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/1.jpg)



Prototyping
Το πρωτότυπό μας: 

![This is an image](https://github.com/GeorgePachis/Interaction-Design-Project-Assignment/blob/main/2.jpg)

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
