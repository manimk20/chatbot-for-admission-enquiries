def chatbot():
    print("Hi! I'm a simple chatbot. Type 'Bye' to exit.")
    while True:
        user_input = input('You:' )
        if user_input == 'Hi' or user_input == 'Hii' or user_input == 'hi' or user_input == 'hii' or user_input == 'Hello'or user_input =='hello'or user_input =='hy'or user_input =='helo'or user_input =='Good Morning'or user_input =='Good Evening'or user_input =='Good Afterrnoon'or user_input =='good morning'or user_input =='good afternoon' or user_input == 'good evening'or user_input =='gd mrng'or user_input =='gd nonn'or user_input =='gd eve':
            print('Chatbot:Hello! How can I help you today?')
        elif user_input == 'How many departments are there in this college?' or user_input == 'Can you please give me the name of the departments?':
            print('Chatbot: In B.E, we have Nine Departments Artificial Intelligence and Data Science (AI&DS), Automobile Engineering, Civil Engineering (CE), Computer Science and Engineering (CSE), Electrical and Electronics Engineering (EEE), ELECTRONICS AND COMMUNICATION ENGINEERING(ECE), Electronics and Instrumentation Engineering (EIE), Information Technology(IT), Mechanical Engineering(Mech)')
        elif user_input == 'how to apply for admission?' or user_input == 'How to apply for admission?' or user_input == 'What is the admission contact number' or user_input == 'admission contact number' or user_input == 'Admission contact number' or user_input == 'What types of scholarships are available for incoming students?':
            print('Chatbot: For inquiries about admissions or scholarships, please contact us at 893922 1120 or 91235 47550')
        elif user_input == 'what is the counseling code?' or user_input == 'What is the counseling code for admission?' or user_input == 'What is the counseling code?' or user_input == 'TNEA code' or user_input == 'TNEA Code':
            print("Chatbot:Our College TNEA code is '1120'")
        elif user_input == 'bye' or user_input == 'Thank you' or user_input == 'Thank you!' or user_input == 'thank you' or user_input == 'Bye' or user_input == 'Good bye' or user_input == 'good bye' or user_input == 'Ok, thank you' or user_input == 'ok, thank you' or user_input == 'ok thank you':
            print('Chatbot: Thank you! Have a great day!')
            break
        else:
            print("Chatbot: Sorry, I didn't understand that. Can you please rephrase?")
if __name__ == '__main__':
