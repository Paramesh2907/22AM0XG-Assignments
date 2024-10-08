### Day 1 Assignments

> [!NOTE]
> Pls edit this table while submitting the assignments

| Status         | Questions     | 
|----------------|---------------|
| <ul><li>- [X] </li></ul> | Execute 25 Docker CLI commands, capture the output screenshots, and document each command's usage on a GitHub Wiki page. |
| <ul><li>- [X] </li></ul> | Install VSCode and Python. Check the version of Python. Document these steps in GitHub Wiki. |
| <ul><li>- [X] </li></ul> | [Python] Create a sample flask app and edit the same to showcase your college information(Name, Register_number,etc) |
| <ul><li>- [X] </li></ul> | [Docker] Create the docker image for the above-mentioned flask app and run the same view of the page in a browser |
| <ul><li>- [X] </li></ul> | [Docker] Create a docker compose file for the 2 images: nginx/httpd and run the same view of the page in a browser |
| <ul><li>- [X] </li></ul> | [Docker] Pull one of the participant’s docker images and verify whether the app is running or not  |
| <ul><li>- [X] </li></ul> | Create a GitHub account with a personal mail ID & fork this repo and rename this in the format 22AM0XG-Assignments-Register-Number  |
| <ul><li>- [X] </li></ul> | Create a LinkedIn account with personal mail ID  |

***

### Day 1 Assignments - Answers and Screenshots

> [!WARNING]
> Pls submit the correct screenshots

> [!CAUTION]
> Pls don't copy from others. Marks will be reduced for both students

#### #1 Execute 25 Docker CLI commands, capture the output screenshots, and document each command's usage on a GitHub Wiki page
1.docker version ![Screenshot (22)](https://github.com/user-attachments/assets/ac65205d-669b-4433-a0bb-a6f719d51387)
2.docker info ![Screenshot (23)](https://github.com/user-attachments/assets/c9a7c7c0-3198-4b76-ae7c-db3502639574)
3.docker system info ![Screenshot (25)](https://github.com/user-attachments/assets/e27a2dc2-d232-47d6-ac62-df68f041e664)
4.docker --help ![Screenshot (24)](https://github.com/user-attachments/assets/0aa20079-657a-42f3-875a-fead5c435581)
5.docker compose version<br>![Screenshot 2024-09-28 133511](https://github.com/user-attachments/assets/1c91425f-a567-48b7-9f53-fe6e237838b2)

6.docker login

![Screenshot 2024-09-28 133652](https://github.com/user-attachments/assets/6af040d9-4109-40f5-b239-25576f3a1abf)

7.docker logout<br> ![Screenshot 2024-09-28 133809](https://github.com/user-attachments/assets/2cd10704-a7a4-4609-af4a-0634e622c4c1)

8.docker search nginx  <br>  ![image](https://github.com/user-attachments/assets/0e068e71-7459-4270-8363-6508497406bf)

9.docker images <br> ![image](https://github.com/user-attachments/assets/bbb7031b-2945-488d-b0a9-9701f1ec0f1f)

10.docker pull nginx <br> ![Screenshot 2024-09-28 144206](https://github.com/user-attachments/assets/d1e1e9cc-0fb2-4fe8-a0e5-fa0c68b70a2c)

11.docker run -itd nginx <br>![Screenshot 2024-09-28 144713](https://github.com/user-attachments/assets/9d82eb06-c15f-4892-9465-5504bce8b262)

12.docker ps <br> ![Screenshot 2024-09-28 144454](https://github.com/user-attachments/assets/3aabc81a-0868-49c2-b70a-94903ee585f3)

13.docker stop bc329101bbd8 <br> ![Screenshot 2024-09-28 144956](https://github.com/user-attachments/assets/541a0b52-8288-4fc3-915c-c35d0c4ec170)

14.docker start 3f26a5b9344e<br> ![Screenshot 2024-09-28 145302](https://github.com/user-attachments/assets/703ab005-27c2-4f69-ab70-ff411ca8e28f)

 15.docker restart <br>![Screenshot 2024-09-28 145415](https://github.com/user-attachments/assets/997f544e-af54-4637-a5db-12379d3682f1)
 
16.docker logs 3f26a5b9344e <br> ![Screenshot 2024-09-28 145615](https://github.com/user-attachments/assets/71558805-55b0-40d7-9de4-b4487ecdba7e)

17.docker rm 3f26a5b9344e <br> ![Screenshot 2024-09-28 145742](https://github.com/user-attachments/assets/840af747-5639-4e1a-a609-e228ba14fef8)

18.docker build <br>![Screenshot 2024-09-29 101002](https://github.com/user-attachments/assets/3147adac-e502-4971-a1b4-c9f7b6422be5)

19.docker push <br>![Screenshot 2024-09-29 101520](https://github.com/user-attachments/assets/909fe3ee-60de-44b0-b4a3-795df76396af)


20.docker tag<br> ![Screenshot 2024-09-29 102434](https://github.com/user-attachments/assets/07347517-2461-4bf6-957a-d07154af31cc)

21.docker save <br> ![Screenshot 2024-09-29 102940](https://github.com/user-attachments/assets/b97d0aa0-5e10-4e4b-88b8-6c244a158db4)

22.docker load <br> ![Screenshot 2024-09-29 103130](https://github.com/user-attachments/assets/c9fd0af0-d44b-44e9-aadf-0991e07161c3)

23.docker exec <br> ![Screenshot 2024-09-29 103444](https://github.com/user-attachments/assets/3b0950d6-e4c6-429c-8cc8-a2b2e96535ba)

24.docker cp <br> ![Screenshot 2024-09-29 103821](https://github.com/user-attachments/assets/bf41f77d-433a-47cf-b374-93d432651505)

25.docker system prune <br> ![Screenshot 2024-09-29 104030](https://github.com/user-attachments/assets/d86d87a9-d4ff-4a8f-b5cd-a83959acddb5)


 ***

#### #2 Install VSCode and Python. Check the version of Python. Document these steps in GitHub Wikip
1.python version <br> -![Screenshot 2024-09-28 142805](https://github.com/user-attachments/assets/fcfc8878-9738-4434-9300-12bb677c1887)

***

#### #3 [Python] Create a sample flask app and edit the same to showcase your college information(Name, Register_number,etc)
1.python py-hello-world.py <br> ![Screenshot 2024-09-29 104308](https://github.com/user-attachments/assets/168d126b-3e71-4342-a7f8-65e3eb9333fa)

2.python app.py <br> ![Screenshot 2024-09-29 110547](https://github.com/user-attachments/assets/8887a16d-5944-41f1-9af0-f7a3197c7777)

***

#### #4 [Docker] Create the docker image for the above-mentioned flask app and run the same view of the page in a browser
1.docker build <br> ![image](https://github.com/user-attachments/assets/fb8d4aab-2b4c-4582-b5a6-8806dea0b693)

2.docker push <br> ![Screenshot 2024-09-29 114323](https://github.com/user-attachments/assets/7c3338a2-7fd2-4d37-8fec-3519a624b093)

***

#### #5 [Docker] Create a docker compose file for the 2 images: nginx/httpd and run the same view of the page in a browser
1.![Screenshot 2024-09-29 122749](https://github.com/user-attachments/assets/75a0697d-2d58-4cc0-b67a-426bddc69a9d)

2.![Screenshot 2024-09-29 122830](https://github.com/user-attachments/assets/1b0be559-f1d3-4478-adde-5f43e7e43612)

***

#### #6 [Docker] Pull one of the participant’s docker images and verify whether the app is running or not

1.![Screenshot 2024-09-29 141159](https://github.com/user-attachments/assets/a35ffb96-1a46-4878-8c23-90f4bbd19f2c)

***

#### #7 Create a GitHub account with a personal mail ID & fork this repo and rename this in the format 22AM0XG-Assignments-Register-Number
> Add your answer here!

***

#### #8 Create a LinkedIn account with personal mail ID
> Add your answer here!

***
