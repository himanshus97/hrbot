# HRbot- Using Rasa FrameWork

Let's Build A chatBot using Rasa Framework who will gonna take interview over any medium.

Happy Path Would Be:

User -> hello (*Confirm INTENT) </br>
Bot -> Hello, I am Heena ,From HrBot co. Are you looking for job change. </br>
User -> Yes (*affirm INTENT) </br>
Bot -> Hello, Sir Let me know Name. </br>
User -> Himanshu Saini {*NAME ENTITY} </br>
Bot -> Alright! {Himanshu Saini} ,i have a job for the role of {ANY_PROFILE} at {ANY_COMPANY_NAME} and The Job Location is {ANY_LOCATION}, IS this Suitable For You ? </br>
User -> Yes This Is Suitable For Me (*affirm INTENT) </br>
Bot -> Let me give you a breif about company {ABOUT_COMPANY} is it fine? </br>
User -> Yes (*affirm)</br>
BOT -> ALright! {Himanshu Saini}. Could You Please Tell Me Your Current CTC and Expected CTC?</br>
User -> Current CTC is 1.2 Million and Expected CTC would Be 1.5 Million (*Salary INTENT/CUR_CTC Slot/Exp_CTC Slot)</br>
BOT -> What is Your Notice Period ?</br>
User -> My Notice Period is 45 days (*Notice Period/*Value ENTITY/NOTICE Slot)</br>
Bot -> Alright!,Tell me More About Yourself.</br>
User -> {USER's ABOUT}</br>
Bot -> What is Your Overall Experience</br>
User -> 2 Years (EXPERIENCE Slot)</br>
Bot -> Thankyou, For Your Interest, Our Team Will contact You after Evaluation.Bye Have A Great Day Ahead. </br>
