#Mobile Emergency
#MakeSPPrep Project
#Heart Health
print "Welcome, please insert your health information."
print "Please select one of the following conditions:"
print "1. arrhythmia"
print "2. high blood pressure"
print "3. frequent cardic arrest"
print "4. heart murmurs"
print "5. coronary hartry disease"
print "6. congestive heart failure"
print "7. periphial artery disease"
print "8. stroke"
print "9. prior heart attacks"
print "10. cogenital heart disease"
information = raw_input()
if information == 'arrhythmia':
    print "We will monitor you heart rate, in case of emergency, we will contact the paramedics."
elif information == 'high blood pressure':
    print "We will remind you what to avoid and any habits you fall victim to."
elif information == 'frequent cardiac arrest':
    print "We will constantly make sure your heart is stable."
elif information == 'heart murmurs':
    print "We recommend that you visit your doctor often"
elif information == 'coronary artery disease':
    print "We recommend that you try to lower your blood pressure to prevent any heart attacks." 
elif information == 'congestive heart failure':
    print "Go see your doctor to finalize the cause of you problem."
elif information == 'periphial artery disease':
    print "Lessen use of tobacco, get more exercise, eat healthy."
elif information == 'stroke':
    print "Go take blood thinners as well as tPa."
elif information == 'prior heart attacks':
    print "What is recommended is that you take aspirin to prevent blood clots that could lead to a heart attack."
elif information == 'cogenital heart disease':
    print "what you should do is to lower your blood pressure by any means"
else:
    print "I'm sorry, that is not an option."
