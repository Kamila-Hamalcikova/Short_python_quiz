# Python quiz

### Description

Purpose was to refresh Python coding basics by creating quiz with 3 questions while avoiding repetition of code. When user answered 3times incorrectly, quiz was shutdown.

I used nested dictionary and iterating through for loop and while loop. It was short exercise from [Jedha Fullstack course](https://en.jedha.co/programme/bootcamp-full-stack)

### Code snippet

 ```
# for loop to interate though all questions
for question in questions:

    # ask question
    part = input(quiz[questions[counter]]["Q"])

    # when answer to question is wrong, deduce 1 chance
    while part != (str(quiz[questions[counter]]["A"])).lower():
        nb_chances -= 1
        print("You have {} chances".format(nb_chances))
 ```
