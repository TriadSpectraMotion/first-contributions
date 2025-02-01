# __________________ "मेरो पहिलो योगदान"_____________________

# १. फोर्क गर्नु (Fork a Repository)
GitHub मा जानुहोस् र आफ्नो इच्छित रिपोजिटरी खोल्नुहोस्।
"Fork" बटन क्लिक गर्नुहोस्, जसले रिपोजिटरीको प्रतिलिपि (copy) तपाईंको खातामा बनाउँछ।



# २. आफ्नो लोकल मेसिनमा क्लोन गर्नु (Clone the Repository)
आफ्नो GitHub प्रोफाइलमा फोर्क गरिएको रिपोजिटरी खोल्नुहोस्।

"Code" बटन क्लिक गरी SSH वा HTTPS URL प्रतिलिपि गर्नुहोस्।

टर्मिनल वा कमान्ड लाइन खोल्नुहोस् र निम्न कमान्ड चलाउनुहोस्:

sh
Copy
Edit
git clone <repo-url>
(उदाहरण: git clone https://github.com/your-username/repository-name.git)



# ३. मुख्य रिपोजिटरीलाई रिमोट एड गर्नु (Add Upstream Remote)
आफ्नो फोर्क गरिएको रिपोजिटरीलाई मुख्य (original) रिपोजिटरीसँग समायोजन गर्न:

sh
Copy
Edit
cd repository-name
git remote add upstream https://github.com/original-owner/repository-name.git
अब जाँच गर्न:

sh
Copy
Edit
git remote -v


# ४. नयाँ ब्रान्च सिर्जना गर्नु (Create a New Branch)
शाखा परिवर्तन गर्नु (main ब्रान्चमा हुनु पर्छ):

sh
Copy
Edit
git checkout main
git pull upstream main
नयाँ ब्रान्च बनाउन:

sh
Copy
Edit
git checkout -b feature-branch-name


# ५. आवश्यक परिवर्तनहरू गर्नु (Make Changes and Commit)
फाइलहरू सम्पादन गर्नुहोस् वा नयाँ फाइलहरू थप्नुहोस्।

परिवर्तन स्टेज गर्नु:

sh
Copy
Edit
git add .
परिवर्तनहरू कमिट गर्नु:

sh
Copy
Edit
git commit -m "यो परिवर्तनको बारेमा संक्षिप्त विवरण"


# ६. आफ्नो फोर्क गरिएको रिपोजिटरीमा परिवर्तन पठाउनु (Push Changes to Your Forked Repository)
नयाँ ब्रान्चलाई GitHub मा पठाउनुहोस्:

sh
Copy
Edit
git push origin feature-branch-name


# ७. पुल रिक्वेस्ट पठाउनु (Create a Pull Request - PR)
GitHub मा आफ्नो फोर्क गरिएको रिपोजिटरी खोल्नुहोस्।
"Compare & pull request" बटन क्लिक गर्नुहोस्।
PR को शीर्षक र विवरण राम्रोसँग लेख्नुहोस्।
PR सबमिट गर्न "Create pull request" बटन क्लिक गर्नुहोस्।


# ८. समीक्षा र मर्ज (Review and Merge)
कोड र PR को समीक्षा गर्नुपर्छ।
रिपोजिटरीका मालिकले स्वीकृत गरेपछि PR मर्ज गरिन्छ।


# ९. आफ्नो लोकल रिपोजिटरीलाई अपडेट गर्नु (Sync Your Local Repository)
लोकल रिपोजिटरीलाई पछिल्लो अपडेटसँग समायोजन गर्न:

sh
Copy
Edit
git checkout main
git pull upstream main
git push origin main
🎯 निष्कर्ष
यो प्रक्रिया GitHub मा ओपन-सोर्स योगदान गर्न वा अन्य परियोजनामा सहकार्य गर्न अत्यावश्यक छ। कुनै पनि भ्रम भएमा सोध्न सक्नुहुन्छ! 🚀