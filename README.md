# Invoice finder

Final project for the Building AI course

Data and AI techniques: What data sources does your project depend on? Almost all AI solutions depend on some data. The availability and quality of the data are essential. Which AI techniques do you think will be helpful? Depending on whether you've been doing the programming exercises or not, you may choose to include a concrete demo implemented by coding, using some actual data!
How is it used: What is the context in which your solution is used, and by whom? Who are the people affected by it? It’s important to appreciate the viewpoints of all those affected.
Challenges: What does your project not solve? It’s important to understand that any technological solution will have its limitations.
What next: How could your project grow and become something even more?
Acknowledgments: If you’re using open source code or documents in your project, make sure you give credit to the creators. Mention your sources of inspiration, too.

## Summary

On July 1st, 2024 Poland introduces obligatory electronic invoice system called KSeF. Each company will have one account in KSeF. All invoices for company will be on this account. 
Currently when employee pays with company card (ex. lunch with a customer) he/she gets paper invoice and accounting can match invoice with payment. From July 1st, 2024 employee
will not receive paper invoice.

## Background

The problem is described in Summary. After introduction of KSeF companies in Poland will have accounts in KSeF, on which will be send all invoices for particular company.
In most cases it should be ease to match invoice with payment, although in case of company card payments there is no easy way to match them.

* problem 1 - matching company bank card payments with invoices in KSeF
* problem 2 - matching cash payments with invoices in KSeF

I assume that it will be very company problem in Poland after July 1st, 2024. Most of small and medium companies will have to go through each invoice and try to match it with bank card billings. As a board member of medium size company I will have to deal with this problem somehow.

## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
