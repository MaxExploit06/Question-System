import random
questions1 = ['q1','q2','q3']
answers1 = ['a1','a2','a3']
def quiz():
	i = 2
	n = random.randint(0,i)
	ans = input(questions1[n])
	if ans == answers1[n]:
		print('that is correct!')
	else:
		print('that is the wrong answer, the correct answer is', answers1[n])
	i = i - 1
	questions1.remove(questions1[n])
	answers1.remove(answers1[n])
	quiz()
quiz()
