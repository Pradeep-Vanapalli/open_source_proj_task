Docker Commands:
1. docker --version - To check the version of the docker.
 ![Screenshot from 2022-10-18 20-23-15](https://user-images.githubusercontent.com/66369393/196465879-1c17d831-121b-41ee-8b3e-0ceb85a36186.png)

2. docker images - To check the all docker images and their details.
![Screenshot from 2022-10-18 20-26-47](https://user-images.githubusercontent.com/66369393/196466578-e89d9270-9f7a-465b-b076-21ee7b80e0ce.png)

3. docker pull <image_name> - To clone the image into our local.
![Screenshot from 2022-10-18 20-29-58](https://user-images.githubusercontent.com/66369393/196467325-a1f9263e-d640-49bd-a627-35918cc475f1.png)
 
4. docker run <image_name> -  To run the docker image in the container.
![Screenshot from 2022-10-18 20-33-45](https://user-images.githubusercontent.com/66369393/196469347-9b5692f2-d6ae-4ede-8707-fa2dc12da921.png)

5. docker build <image_name> . - To build the docker image.
![Screenshot from 2022-10-18 20-37-53](https://user-images.githubusercontent.com/66369393/196470246-721607cd-8b8a-449d-ba46-9c78269ee9fd.png)

6. docker ps - To check if the docker container is running or not after run.
![Screenshot from 2022-10-18 20-45-03](https://user-images.githubusercontent.com/66369393/196471545-6429c56a-5bee-4eb5-8415-f31544eccfb0.png)

7. docker ps -a - To check the details of all the docker containers.
![Screenshot from 2022-10-18 20-46-22](https://user-images.githubusercontent.com/66369393/196472053-4572cc74-35c1-4409-ad2e-41261d63449c.png)

8. docker rm -f <container_id> - To delete the docker container forcefully.
![Screenshot from 2022-10-18 20-49-36](https://user-images.githubusercontent.com/66369393/196473066-05dce39f-9511-4f3e-b5b2-88954e93f94b.png)

9. docker rmi -f <image_name> -  To delete the docker image container forcefully.
![Screenshot from 2022-10-18 20-55-41](https://user-images.githubusercontent.com/66369393/196474308-fd143da0-231e-4609-8acf-b2ad9c2cc2dd.png)

10. docker start <container_id> -  To start the container
![Screenshot from 2022-10-18 22-34-01](https://user-images.githubusercontent.com/66369393/196497796-2fd1afeb-b92a-42b1-ac18-564277259e09.png)

11. dokcer stop <container_id> - To stop the container
![Screenshot from 2022-10-18 22-36-16](https://user-images.githubusercontent.com/66369393/196498273-b2559272-2e80-4634-b87e-f58fd50ff6b7.png)

12. docker logs <container_id> - To check the container output and the complete details from strat to stop.
![Screenshot from 2022-10-18 22-38-43](https://user-images.githubusercontent.com/66369393/196498811-7ff0cd73-06fd-4fab-b5ad-fbdc1296fc72.png)

13. dokcer push <image_name:latest> - To push the dokcer image to the docker hub.
![Screenshot from 2022-10-18 22-55-26](https://user-images.githubusercontent.com/66369393/196501860-302d77b5-b814-44e5-ae1e-3a06df6f4390.png)

14. docker diff <container_id> - To preview the impact of your changes in a build
![Screenshot from 2022-10-18 23-00-43](https://user-images.githubusercontent.com/66369393/196502981-cbe8aec9-a124-4205-91eb-e57f0a6b8ed5.png)

15. docker history <image_name> - To check the image complete history.
![Screenshot from 2022-10-18 23-02-23](https://user-images.githubusercontent.com/66369393/196503436-5e332472-b512-437a-a74f-607c2a1893a7.png)
