# 0x0D. Web stack debugging #0 
<details>
<summary>Let's first pull a Docker image and run a container:</summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/13tHWGzc/image.png' border='0' alt='image'/></a>
</details>

Note that `docker` command will pull the Ubuntu docker container image from the Internet and run it. I let you look at the meaning of the flags using the command `docker run --help`, the main idea is that it keeps the container up and running.

<details>
<summary>To execute a command on the Docker container, use *docker exec*:</summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/fLLDygWS/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary>If you want to connect to your Docker container and use Bash, you need to use *docker exec -ti*:</summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/433xH3B3/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary>If you want to stop a container, use *docker stop*:</summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/sxCzmf97/image.png' border='0' alt='image'/></a>
</details>


## Tasks

<details>
<summary><a href="./0-give_me_a_page">0. Give me a page!</a></summary><br>
<ul>
  <li>Advice; install docker on your local machine then pull the docker image debug the issue then proceed.</li>
<ul>
AVOID installing docker in ubuntu 14.04
</details>
