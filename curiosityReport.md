Curiosity Report:
Alternatives to AWS

There are multiple aternatives to AWS. Many of them lack some of the services that AWS has, but they all provide scalable cloud hosting. 

Microsoft Azure:
    Much cheaper SQL hosting
    Stronger Microsoft server integration, but more limited linux support
    Generally cheaper than AWS with pay-as-you-go pricing
    AWS uses EC2 to balance ECS, DynamoDB capacity, and other metics
    Azure scales the instance itself. 
    Less code than AWS

Google Cloud: 
    Easier account managament than Amazon's IAM
    Access to google's BigQuery datalake service
    Lowest market share of the main 3
    Positions itself as a "low code" between Azure's no code and AWS's high code solutions

Every one of these services offer alternatives for the same services, just under different names. If you want to find a database, object storage, scalable cloud computing, or a similar service, you'll find it in any of the three. 
AWS offers the most overall services to use and you will find a way to accomplish whatever you need to do. It can be difficult to figure out where those services are located or how to use them.
Azure offers comprehensive solutions that are appealing to the average corporation. Going to one vendor for cloud services, email, networking, etc. appeals to the lazy systems architect and they're designed to interface nicer than AWS. It does have troubles withe more customized solutions sometimes(I saw a few reports of people complaining that they had issues with deploying Linux servers.) Also, many people complained about the lack of customizability along with having to work with Microsoft. How much of this can be perscibied to devops engienners hating Microsoft is an ongoing debate.
Google Cloud isn't used nearly as much in the wider market. It has the nessessary services, but there currently isn't an incentive to switch. Google has a long history of developing random projects and then killing them uncerimoniously. Many of them end up on the Google Cloud program, which results in a disjointed feel between the services. Their determination to go for a "low code" solution instead of committing to either no code or code contributes to that. It's in need of further development, and it's unclear if Google is willing to commit to that long term.

Overall, which cloud provider to use depends on what you specifically need for your deployment. Using mutiple services from different vendors is a common solution.

If you want the most services, use AWS
If you want something cheaper, use Azure
If you're doing a lot of data science, use Google Cloud.