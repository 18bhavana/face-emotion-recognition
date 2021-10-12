# FACE-EMOTION-RECOGNITION

INTERNSHIP REPORT ON MACHINE LEARNING AMD ARTIFICIAL INTELLIGENCE


          Supervised by :
              	Arun Rajpurohit
                 Dr Pooja

          Submitted by :
	              Bhavana.B M

Date Of Submission : 10/10/2021

# SELF INTRODUCTION

Sir/Madam Hello ,
                Thank you for giving me this opportunity to introduce myself. My name is BHAVANA M .I am from CHIKMAGALUR . I did my PU in HASSAN currently I’m pursuing BE from VTU UNIVERSITY . I did my schooling in HASSAN . I belong to a nuclear family . We are four members in my family father ,mother , elder brother and me.
	     My strengths are I’m honest , punctuate ,self-motivated , quick learner and hardworking. My short term goal is to get a job in a reputed company in which I can grow my working skills and get more and more knowledge . Which helps me  in future. My long term goal is to become a more responsible and knowledgeable personality and achieve a good position in the organization .
	     
 	       That’s all about me and thanks again for this great opportunity.
	       
# COMPANY INTRODUCTION

		Dlithe consultancy service private limited, is Edutech company, based out in Bengaluru. Since inception in the year 2018, the company is working with major academic institution and corporate providing competency development services, technical consultation and product development.
		The company is led by industry professionals with two decades of experience, leveraging their experiences towards students mentoring. The company has also developed mobile application for health care company recently.
		Dlithe consultancy service private limited is a private incorporated on 04 February 2019. It is classified as non-govt company and is registered at register of companies, Bangalore.
		The company vision is to build an agile workforce towards global industry needs. To support business entities to achieve customer experience and operational excellence goals.  
		
# INTERNSHIP JOURNEY,LEARNING FROM INTERNSHIP
		I very much enjoyed the internship program of python with machine learning . The course started with basics of python and then machine learning involves learning of different maps,chatbot and few algorithms and building a model.
		Overall this internship program was very helpful and got learn these technologies with a very profound atomosphere.I thank DLithe for providing the same.
		
# ASSIGNMENT DETAILS WITH OUTCOME

## DESCRIPTION
		What is emotion detection and recognition?
			Emotion Detection & Recognition is a technology that recognizes a human's behavior and emotion by integrating image processing techniques. The software tools applicable to cater to the purpose of detection and recognition can detect slight facial changes.

		How Python is used in face recognition?
			You first pass in the image and cascade names as command-line arguments. We'll use the ABBA image as well as the default cascade for detecting faces provided by OpenCV. Now we create the cascade and initialize it with our face cascade. This loads the face cascade into memory so it's ready for use.
			
## PROGRAM CODE		

	!pip install deepface
	import cv2
	import matplotlib.pyplot as plt
	from deepface import DeepFace
	from google.colab import drive
	drive.mount('/content/drive')
	img = cv2.imread('/content/drive/MyDrive/michael-dam-mEZ3PoFGs_k-unsplash.jpg')
	plt.imshow(img[:,:,::-1])
	plt.show()
	result = DeepFace.analyze(img, actions= ['emotion'])
	print(result) 
	
## OUTCOME

https://colab.research.google.com/drive/1mrJDjJQMN9hjfeKF37YVVSt0ShssKLGP	
	
# CONCLUSION
		In a nutshell, this internship has been an excellent and rewarding experience. I can conclude that there have been a lot I’ve learnt from my work at DLithe. Needless to say, the technical aspects of the work I’ve done are not flawless and could be improved provided enough time. 






