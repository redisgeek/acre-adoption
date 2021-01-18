# Azure Cache for Redis Enterprise Adoption
A framework for adopting Azure Cache for Redis Enterprise that tries to align with the
[Azure Cloud Adoption Framework](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/)

## Getting Started

1.  Clone the repository
    ```
    git@github.com:redisgeek/acre-adoption.git
    ```
2.  CD into the repository
    ```
    cd acre-adoption
    ```
3.  Use docker to serve the content
    ```
    docker run --name acre-adoption -v $PWD/:/usr/share/nginx/html:ro -d -p 8089:80 nginx
    ``` 
4.  Open browser to http://localhost:8089/

## Five Milestones

This is just an example.
Originally, each milestone was a meeting lasting less than 1 hour.
Each meeting was delivered over a "lunch and learn" format.
Each organization is different, so this will not work for every organization.
Use it as a starting point, and iterate on it, over time.

## Portfolio

This framework is for starting small and building momentum.
Start with one portfolio of applications.
Identify one application that is not too complex and not too simple.
The application must also have some meaningful business value.
Make sure that the 1st application-effort can be completed within the desired timeframe.

## Transparency and Consistency

Keep the progress visible.
After each iteration, make adjustments.
Capture the outcomes of each iteration as well.
Let the framework work for you as you move on to more important efforts.

## Enablement

Consistency of enablement is important.
Keeping the entire organization informed of the latest guidance
is a great way to prevent non-compliant workloads.
This can be accomplished with periodic workshops or demonstrations.
Having regular "office hours" specific to the domain, is another
great way of enabling good consumers of the service.