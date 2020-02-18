# Strategic Domain-Driver Sesign
Domain-Driven Desing (DDD) has been around since Eric Evans publiched his book about the subject in 2003. I myself came into contact with DDD some years ago when I joined a that suffred from data consistency problems. Duplicates showed up in the database, some information was not saved at all, an you could run into optimistic locking errors anywhere and anytime. We managed to solve this by using the building blocks of tactical Domain-Driven Design.
I have learned more about Domain-Driven Design since then and also to try to use my projects wherever appropriate. However, during the past years when i have talked to other developers, many of them have heard about the term Domain-Driven Design, but the do not know what it means. In this article series, I am going to give a brief introduction to Domain-Driven Design as I see and understand it. the content is very much based on the book Domain-Driven Design: Takling Complexity in the Heart of Software be Eric Evans and Implementing Domain-Driven Design by Vaughn Vernon. However, I have tried to explain everything in my own words and also inject my own thoughts, opinions, and experiences.
You will not become an expert in Domain-Driven Design by reading me article series, but i hope it inspires you to read more about it elsewhere. I also highly encourage you to read the books by Evans and Vernon.

# What is a Domain?
If i look up the word domain in the Dictionary app on my MacBook, I get the following definition:
" [A]n area of terriroty owned or controlled by particular rules or goverment...
    * a specified sphere of activity or knowlaedge...
--- Apple Dictionary
In the case of Domain-Driven Design, it is the second part of the definition that we are interested in. In this case, activity is whatever an organization does and knowledge is how the organization does it. We are also going to add the enviroment in which organization conducts its activities to the domain concept.

# Subdomains
The domain concept is very broad and abstract. To make it more concrete and tangible, it makes sense to split it up into smaller parts called subdomains. Finding these subdomains is not always an easy things to do, and if you get them wrong, you can run into trouble down the road when the pieces in your puzzle all of a sudden do not fil well together.
Before you go looking of subdomains, you should think about the subdomain categories. All subdomains can be devided into three categories:
1. Core domains.
2. Supporting subdomains.
3. Generic subdomains.
Not only will these categories help you to find your subdomains, they will also help you to prioritize your development efforts.
A core subdomain is what makes an organization special and different from other organization. 