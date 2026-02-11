# hello_world
> This is my first project(?) on github.An easy code based on python could get basic information about hotels while gain concrete comments about specific hotel. The data comes from xiecheng.com.(Actually I forget the website)
> 
> The code I shared here are really simple and my true purpuse is learning the way of using Github to be honest. By the way, I could review markdown.
> Maybe I can learn English meanwhile(just kedding).
>
> A good beginning might be half way of success, but I don't consider this seriously,I wanna interest--The true purpuse.

## Introduction

Based on libs including **re** and **requests** etc, this project could scrape information on a wedsite.
The project devided into two parts, the concrete information are as followed.
The first project could gain information about hotel like:

- address
- price
- overall rating
- name

The second project gain information like:
- user' name&id
- check-in time
- room type
- rating
- comment information
- ...

## Guidance
We could regard the process of scraping as a series of interaction of input&output to get the data we want. The data is roughly divided into three parts: network parsing, data extraction, and data storage, which you can clearly see in the comments. \n
In the first part you can change website to gain different data of different hotels. And the way is really simple. Just change the details of URL and add the id of the purpose hotel feel free. But if you feel confused about above content, I thought some knowledge about URl structure is helpful for you.
The second part is relatively fixed while the third part aimed to save the data as CSV.
 
