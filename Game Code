
#Now I Make Database For Quiestion (List) And Answer!!!

question_data=[
    {"text":"Situated in South Asia, Bangladesh is bordered by India and which country to the south-east?","answer":"B"},
    {"text":"In 1971 after a bloody resistance, Bangladesh officially gained independence from which nation?","answer":"D"},
    {"text":"Due to its high soil fertility, a large percentage of Bangladeshi people rely on agriculture to make a living. Which of these crops are you least likely to find growing in Bangladesh?","answer":"B"},
    {"text":"Bangladesh is home to a number of biodiversity hotspots. Which endangered species found in the country is also the national animal?","answer":"D"},
    {"text":"Bangladesh is a land of extreme climate. Which of these best describes the yearly climate trend of the nation?","answer":"B"},
    {"text":"As the capital city, Dhaka hosts numerous political institutions. A remnant of the British Raj, the Bangabhaban in the city is the official residence of which Bangladeshi executive?","answer":"B"},
    {"text":"A gorgeous geographic feature of Bangladesh is the largest mangrove forest of its type in the world, known as the what?","answer":"D"},
    {"text":"Bangladesh life centres on a series of major river networks, the bulk of which empty into which large body of water located south of the country?","answer":"C"},
    {"text":"Topographically, Bangladesh is quite a flat country. Which of the eight administrative districts of Bangladesh has its name derived from the hilly region it's situated in, one of the few exceptions to this rule?","answer":"B"},
    {"text":"St. Martin's Island in Bangladesh is the country's only example of what type of aquatic island?","answer":"D"}
]

#Now I Make a Datavse for Multipule Answer option (list)!!!

option= [["A.Pakistan","B.Myanmar","C.Nepal","D.Bhutan"],
         ["A.India","B.France","C.Pakistan","D. United Kingdom"],
         ["A.Rice","B.Strawberries","C.Potatoes","D.Tea"],
         ["A.Asian elephant", "B.Binturong","C.Sambar deer","D.Bengal tiger"],
         ["A.Temperate", "B.Tropical","C.Alpine","D.Arid"],
         ["A.Prime Minister", "B.President","C.King","D.Governor-General"],
         ["A.Olgas", "B.Socotra","C.Bungle Bungles","D.Sundarbans"],
         ["A.Gulf of Aden", "B.South China Sea","C.Bay of Bengal","D.Arabian Sea"],
         ["A.Lakshmipur", "B.Chittagong","C.Chandpur","D.Brahmanbaria"],
         ["A.Volcanic", "B.Continental","C.Artifical","D.Coral"],
]

#Now Here I Use Function


#inital score is 0

score = 0

def check_answer(user_guess, correct_answer):
    if user_guess == correct_answer:
        return True
    else:
        return False




#Now Here I Write My Main Code

for question_num in range(len(question_data)):
    print("*****************************************************************************************************************")
    print(question_data[question_num]["text"])
    for i in option[question_num]:
        print(i)

    guess=input("Enter the Answer(A/B/C/D):").upper()
    is_correct=check_answer(guess,question_data[question_num]["answer"])
    if is_correct:
        print("Correct Answer")
        score += 1
    else:
        print("Incorrect Answer")
        print(f"The Correct Answer is {question_data[question_num]['answer']}")
    print(f"Your Correct score is {score}/{question_num+1}")
print(f"You have given  {score} correct answers")
print(f"The score is {(score/len(question_data))*100}%")



