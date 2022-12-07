# 《Spring in Action, 6th Edition》Learning Notes



## 1. Profiles

![Redis 4.x Cookbook](assets/cover.png)

|    **Title**    | **Spring In Action 6th** [ISBN: 9781617297571] |
| :-------------: | :--------------------------------------------: |
|   **Author**    |                **Craig Walls**                 |
| **Publication** |               **Packt, 2022.2**                |
|    **Pages**    |                    **520**                     |

> **Introduction**
>
> **If you need to learn Spring, look no further than this widely beloved and comprehensive guide! Fully revised for Spring 5.3, and packed with interesting real-world examples to get your hands dirty with Spring.**
>
> In *Spring in Action, 6th Edition* you will learn:
>
> - Building reactive applications
> - Relational and NoSQL databases
> - Integrating via HTTP and REST-based services, and sand reactive RSocket services
> - Reactive programming techniques
> - Deploying applications to traditional servers and containers
> - Securing applications with Spring Security
>
> Over the years, *Spring in Action* has helped tens of thousands of developers get a major productivity boost from Spring. This new edition of the classic bestseller covers all of the new features of Spring 5.3 and Spring Boot 2.4 along with examples of reactive programming, Spring Security for REST Services, and bringing reactivity to your databases. You’ll also find the latest Spring best practices, including Spring Boot for application setup and configuration.
>
> **about the technology**
>
> Spring is required knowledge for Java developers! Why? Th is powerful framework eliminates a lot of the tedious configuration and repetitive coding tasks, making it easy to build enterprise-ready, production-quality software. The latest updates bring huge productivity boosts to microservices, reactive development, and other modern application designs. It’s no wonder over half of all Java developers use Spring.
>
> **about the book**
>
> *Spring in Action, Sixth Edition* is a comprehensive guide to Spring’s core features, all explained in Craig Walls’ famously clear style. You’ll put Spring into action as you build a complete database-backed web app step-by-step. This new edition covers both Spring fundamentals and new features such as reactive flows, Kubernetes integration, and RSocket. Whether you’re new to Spring or leveling up to Spring 5.3, make this classic bestseller your bible!
>
> **what’s inside**
>
> - Relational and NoSQL databases
> - Integrating via RSocket and REST-based services
> - Reactive programming techniques
> - Deploying applications to traditional servers and containers
>
> **about the reader**
>
> For beginning to intermediate Java developers.
>
> **about the author**
>
> **Craig Walls** is an engineer at VMware, a member of the Spring engineering team, a popular author, and a frequent conference speaker.



## 2. Outlines

Status available：:heavy_check_mark: (Completed) | :hourglass_flowing_sand: (Working) | :no_entry: (Not Started) | :orange_book: (Finish reading)

|           No.            |             Chapter Title             |          Status          |
| :----------------------: | :-----------------------------------: | :----------------------: |
|                          |    **Part I Foundational Spring**     |                          |
| [Ch01](./Ch01.md)（26P） |      Getting started with Spring      | :hourglass_flowing_sand: |
| [Ch02](./Ch02.md)（32P） |      Developing web applications      |        :no_entry:        |
| [Ch03](./Ch03.md)（33P） |           Working with data           |        :no_entry:        |
| [Ch04](./Ch04.md)（19P） |    Working with nonrelational data    |        :no_entry:        |
| [Ch05](./Ch05.md)（27P） |            Securing Spring            |        :no_entry:        |
| [Ch06](./Ch06.md)（23P） | Working with configuration properties |        :no_entry:        |
|                          |     **Part II Integrated Spring**     |                          |
| [Ch07](./Ch07.md)（23P） |        Creating REST services         |        :no_entry:        |
| [Ch08](./Ch08.md)（24P） |             Securing REST             |        :no_entry:        |
| [Ch09](./Ch09.md)（33P） |    Sending messages asynchronously    |        :no_entry:        |
| [Ch10](./Ch10.md)（36P） |          Integrating Spring           |        :no_entry:        |
|                          |     **Part III Reactive Spring**      |                          |
| [Ch11](./Ch11.md)（29P） |          Introducing Reactor          |        :no_entry:        |
| [Ch12](./Ch12.md)（29P） |       Developing reactive APIs        |        :no_entry:        |
| [Ch13](./Ch13.md)（32P） |      Persisting data reactively       |        :no_entry:        |
| [Ch14](./Ch14.md)（18P） |         Working with RSocket          |        :no_entry:        |
|                          |      **Part IV Deployed Spring**      |                          |
| [Ch15](./Ch15.md)（36P） |   Working with Spring Boot Actuator   |        :no_entry:        |
| [Ch16](./Ch16.md)（12P） |         Administering Spring          |        :no_entry:        |
| [Ch17](./Ch17.md)（08P） |      Monitoring Spring with JMX       |        :no_entry:        |
| [Ch18](./Ch18.md)（16P） |           Deploying Spring            |        :no_entry:        |



Powershell script for generating markdown files in batch:

```powershell
# Create 18 empty markdown files named Ch##.md:
for($i=1; $i -le 18; $i=$i+1){ New-Item -Name "Ch$('{0:d2}' -f $i).md"; }
```

 
