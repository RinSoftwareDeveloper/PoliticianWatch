# Politician Watch https://www.youtube.com/watch?v=HJWTDwqhpY0
April 15th-16th                                                                                      

Presented by: Ethan Yip and Kuldeep Debnath

##### Additional Reference:
Find another copy of this on our official [release paper](https://docs.google.com/document/d/1ni7cnznwXeRdt45k5rsyo_Rg0bbm-SpDlanTZhezmoA/edit).
You can view the website for yourself here (released on a small dataset): [politicianwatch.transparency.repl.co](https://politicianwatch.transparency.repl.co/)
This project is in the _Anti-Corruption/Transparency Category_ 

Check out our devpost!
[https://devpost.com/software/politicianwatch](https://devpost.com/software/politicianwatch)


## Mission:
Our goal is to allow the general public to have easily accessible information on corruption and promote political transparency globally.

## Background:
Have you ever wondered how politicians spend their money and avoid transparency? According to an article written on Politico in 2016 titled, [How politicians hide their spending from the public](https://www.politico.com/story/2016/11/how-politicians-hide-their-spending-from-the-public-230609), “It’s not a partisan trend, as both Democrats and Republicans have long been adept at exploiting transparency work-arounds to keep their activities hidden.” The public deserves to know what politicians spend their money on. 

When we started investigating this issue, we learned that many politicians use LLC’s (Limited Liability Companies) to hide their spending from the public. For example (quoted from the same article), “Hillary Clinton has paid her digital firm, Bully Pulpit Interactive, more than $55 million through payments from her campaign and joint committee with the party, and provided no specifics on the firm’s activities.” 
The money that politicians hide and impacts our economy and impacts work toward the UN 17 Sustainable Goals. The money could easily go toward the fight against poverty (SDGS #1) or help improve quality education (SDGS #4); instead, politicians use this money for their own purposes.



## How do we fight this?
A simple but effective way to stop politicians from hiding their spending is to make their spendings public (transparency). Thankfully, we have many information leaks that give us the owners of these LLC’s that are controlled by politicians. Most notably:

- Panama Papers (2016)
- Paradise Papers (2017 & 2018)
- Pandora Papers (2021)

The information leaked by these papers give us information on companies that we can use programs and organize them into databases (mostly those established by the ICIJ and some other sources) to shed light on these politicians. 

## What is hard with this?
Many NGOs provide information about these corruptions and spending. However, politicians do not simply leave their name as a beneficiary of the LLC. They are listed under a few different layers of companies. For example, KONSTANTIN ERNST is D’Zandra Holdings Limited, and also a shareholder of Haldis Corp. Funny enough, Haldis Corp suspiciously gained a lot of money after his acquisition and it was found that he received a 23% stake in a billion dollar deal. It is never known what he has done with this stake or money, but it also happens that he is in a close circle with Vladimir Putin. With just the names of the companies (provided by ICIJ and other sources), you cannot find what corruption is underneath.


## How can PoliticianWatch help?
PoliticianWatch uses an algorithm to sort through data from multiple sources and databases and cross references and checks them to create a comprehensive view on:

- Who is corrupted?
- Where is this corrupted person from?
- Which business is corrupted?

For those politicians who have a spotlight, some detail will be provided into them as well.


## Where do we find this information?
While we have many databases, we rely mostly on the information gathered from the 3 papers and others listed in this public repository: 
- https://github.com/ICIJ/offshoreleaks-data-packages

We also try to reference a few state sources as well to provide a more comprehensive database such as:
- https://www.njportal.com/dor/businessnamesearch/

However, those state sources have not been fully implemented and cross referenced into our project because of time constraints.



## Development Challenges
We faced many challenges in the development of this project. Firstly, finding various sources with these information leaks are hard to come by. Afterwards, we had to collect all the data and parse it into the same format to enter it into the database. Finally, we took a small selection and localized it, to create a small dataset for this project which can be easily expanded on as we continue development outside this hackathon.

## What’s next for PoliticianWatch
Because of the way that the PoliticianWatch software architecture was designed, it is an easy to expand product that can support a large database. This project can truly continue and become a major provider of leaked data on LLC's and put the nail in corruption's coffin, one and for all.

## Fun Facts:
The water drop logo represents clarity and transparency on political matters like you can see through a drop of water.


