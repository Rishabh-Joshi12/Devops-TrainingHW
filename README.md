# Devops-TrainingHW
Job1: IF developer push to master branch then jenkins will fetch from master and deploy on productionOS .


![job1](https://user-images.githubusercontent.com/64701398/81203627-c98d8800-8fe5-11ea-8029-46f8c183a020.png)




![job1 2](https://user-images.githubusercontent.com/64701398/81203649-d14d2c80-8fe5-11ea-91e1-12d0aee8cf63.png)


Job2: If developer pushes to dev branch then jenkins will fetch from dev and deploy on testingOS



![job2](https://user-images.githubusercontent.com/64701398/81203672-d7430d80-8fe5-11ea-824a-0dba51044aff.png)



![job2 1](https://user-images.githubusercontent.com/64701398/81203687-dad69480-8fe5-11ea-8191-7f444bfa26a6.png)


Job3: If in testingOS website is working fine then jenkins will merge dev branch to master branch and trigger job1 to update in productionOS.



![job3](https://user-images.githubusercontent.com/64701398/81203701-de6a1b80-8fe5-11ea-9ffd-bcb616e24943.png)



![job3 1](https://user-images.githubusercontent.com/64701398/81203711-e1650c00-8fe5-11ea-9f82-5a63db91132a.png)



![job3 2](https://user-images.githubusercontent.com/64701398/81203719-e4f89300-8fe5-11ea-957c-2a7c33baefa3.png)


As all these three jobs are working perfectly blue ball can be seen :


![jenkins](https://user-images.githubusercontent.com/64701398/81203736-eb870a80-8fe5-11ea-9eaf-71a3f1db986b.png)


Here is the output of the two systems:


![outputjob1](https://user-images.githubusercontent.com/64701398/81203756-f17ceb80-8fe5-11ea-8d07-7a13804088f7.png)


![outputjob2](https://user-images.githubusercontent.com/64701398/81203762-f477dc00-8fe5-11ea-803b-30a8f200703f.png)






