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

|              No.              |               Chapter Title                |       Status       |
| :---------------------------: | :----------------------------------------: | :----------------: |
|              P1               |       **Part I Foundational Spring**       |                    |
|  [Ch01](./Ch01.md)（P3, 26）  |        Getting started with Spring         | :heavy_check_mark: |
| [Ch02](./Ch02.md)（P29, 32）  |        Developing web applications         | :heavy_check_mark: |
| [Ch03](./Ch03.md)（P61, 33）  |             Working with data              | :heavy_check_mark: |
| [Ch04](./Ch04.md)（P94, 19）  |      Working with nonrelational data       |   :orange_book:    |
| [Ch05](./Ch05.md)（P113, 27） |              Securing Spring               |   :orange_book:    |
| [Ch06](./Ch06.md)（P140, 21） |   Working with configuration properties    |   :orange_book:    |
|             P161              |       **Part II Integrated Spring**        |                    |
| [Ch07](./Ch07.md)（P163, 23） |           Creating REST services           |   :orange_book:    |
| [Ch08](./Ch08.md)（P186, 24） |               Securing REST                |   :orange_book:    |
| [Ch09](./Ch09.md)（P210, 33） |      Sending messages asynchronously       |   :orange_book:    |
| [Ch10](./Ch10.md)（P243, 36） |             Integrating Spring             |   :orange_book:    |
|             P277              |        **Part III Reactive Spring**        |                    |
| [Ch11](./Ch11.md)（P279, 29） |            Introducing Reactor             |   :orange_book:    |
| [Ch12](./Ch12.md)（P308, 29） |          Developing reactive APIs          |   :orange_book:    |
| [Ch13](./Ch13.md)（P337, 32） |         Persisting data reactively         |   :orange_book:    |
| [Ch14](./Ch14.md)（P369, 18） |            Working with RSocket            |   :orange_book:    |
|             P285              |        **Part IV Deployed Spring**         |                    |
| [Ch15](./Ch15.md)（P387, 36） |     Working with Spring Boot Actuator      |   :orange_book:    |
| [Ch16](./Ch16.md)（P423, 12） |            Administering Spring            |   :orange_book:    |
| [Ch17](./Ch17.md)（P435, 08） |         Monitoring Spring with JMX         |   :orange_book:    |
| [Ch18](./Ch18.md)（P443, 16） |              Deploying Spring              |   :orange_book:    |
|             P459              | Appendix—Bootstrapping Spring applications |                    |



Powershell script for generating markdown files in batch:

```powershell
# Create 18 empty markdown files named Ch##.md:
for($i=1; $i -le 18; $i=$i+1){ New-Item -Name "Ch$('{0:d2}' -f $i).md"; }
```

 
